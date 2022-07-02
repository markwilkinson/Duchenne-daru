FROM rubydata/minimal-notebook:94284f1ddacc
ENV TAG=94284f1ddacc
COPY . .
RUN whoami
USER root
RUN apt-get -y update && apt-get -y dist-upgrade && apt-get install -y libtool-bin autotools-dev autoconf
USER jovyan
RUN bundle install --verbose

