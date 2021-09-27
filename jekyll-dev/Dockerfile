FROM ubuntu

RUN apt update
RUN apt -y install ruby
RUN apt -y install gcc
RUN apt -y install g++
RUN apt -y install make
RUN apt -y install ruby-dev
RUN apt -y install ruby-etc
RUN gem install json
RUN gem install bigdecimal
RUN gem install jekyll -v 3.9
RUN gem install bundler
RUN gem install webrick
RUN jekyll new my blog

EXPOSE 4000
