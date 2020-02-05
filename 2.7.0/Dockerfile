FROM ruby:2.7.0

RUN apt-get update -qq && apt-get install -y build-essential

# for postgres
RUN apt-get install -y libpq-dev

# for nokogiri
RUN apt-get install -y libxml2-dev libxslt1-dev

# for capybara-webkit
RUN apt-get install -y libqtwebkit4 libqt4-dev xvfb

# for a JS runtime
RUN apt-get install -y nodejs

# install firefox
RUN apt-get install -y libffi-dev firefox

#RUN wget "https://github.com/mozilla/geckodriver/archive/v0.26.0.tar.gz"

#RUN tar -zxvf v0.26.0.tar.gz

#RUN chmod +x geckodriver

#RUN mv geckodriver /usr/local/bin

#RUN rm v0.26.0.tar.gz

