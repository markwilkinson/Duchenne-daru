FROM rubydata/minimal-notebook:94284f1ddacc
RUN whoami
USER root
ENV TAG=94284f1ddacc
COPY ./binder .
RUN apt-get -y update && apt-get -y dist-upgrade && apt-get install -y libtool-bin autotools-dev autoconf
RUN bundle config  --global silence_root_warning 1 && bundle install --verbose --global silence_root_warning 1


