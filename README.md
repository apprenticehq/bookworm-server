# README

This repo is maintained by apprentice members

* Ruby version

  We use the ruby version `2.3.1`

  ```sh
  $ ruby -v
  ruby 2.3.1p112 (2016-04-26 revision 54768) [x86_64-darwin15]
  ```

* System dependencies

  It dependents on PostgreSQL. You should install PostgreSQL.
  If you use Homebrew, invoke below.
  ```sh
  $ brew install postgresql
  ```
  Or install Postgres.app .

* Configuration

  ```sh
  $ git clone [this repo]
  $ cd bookworm-server
  $ bundle install --path=vendor/bundle
  $ bundle exec rails s
  ```

* Database creation

  ```sh
  $ bundle exec rails db:create
  $ bundle exec rails db:migrate
  ```

* Database initialization

  tbd

* How to run the test suite

  tbd
