FROM jekyll/jekyll:stable


COPY Gemfile .

RUN gem install bundler:1.16.1 && bundle && bundle update --bundler

WORKDIR /srv/jekyll
EXPOSE 4000