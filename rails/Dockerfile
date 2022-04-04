FROM ruby:2.7

WORKDIR /app
COPY Gemfile /app/Gemfile
RUN bundle install

CMD [ "rails", "server", "-b", "0.0.0.0" ]
