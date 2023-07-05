FROM rubydata/minimal-notebook:94284f1ddacc
RUN whoami
USER root
ENV TAG=94284f1ddacc
COPY ./binder .
RUN apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys 9CBA4EF977CA20B8
RUN apt-get -y update && apt-get -y dist-upgrade 
RUN apt-get install -y libtool-bin autotools-dev autoconf
RUN bundle config   && bundle install --verbose 


