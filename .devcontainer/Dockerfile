# Make sure RUBY_VERSION matches the Ruby version in .ruby-version
ARG RUBY_VERSION=3.1.0
FROM ghcr.io/rails/devcontainer/images/ruby:$RUBY_VERSION

RUN set -xe \ 
    && curl -fsSL https://deb.nodesource.com/setup_20.x | bash - \
    && apt -y install --no-install-recommends nodejs

