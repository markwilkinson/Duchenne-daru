FROM rubydata/minimal-notebook:94284f1ddacc
RUN whoami
USER root
ENV TAG=94284f1ddacc
COPY ./binder .
#RUN rm /var/lib/apt/lists/* -vf
RUN cat /etc/apt/sources.list
RUN cat /etc/apt/sources.list | grep arrow

RUN APT_KEY_DONT_WARN_ON_DANGEROUS_USAGE=1 apt-key adv --no-tty --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys 9CBA4EF977CA20B8
RUN apt-get -y update 
RUN apt-get -y upgrade 
RUN apt-get install -y libtool-bin autotools-dev autoconf
RUN bundle config   && bundle install --verbose 


