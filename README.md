# Jungle

A mini e-commerce application built with Rails 4.2.

![""](https://github.com/belalelmi/jungle-rails/blob/master/lib/assets/Screen%20Shot%202022-01-11%20at%2012.09.33%20AM.png?raw=true)

### Additional Steps for Apple M1 Machines

1. Make sure that you are runnning Ruby 2.6.6 (`ruby -v`)
1. Install ImageMagick `brew install imagemagick imagemagick@6 --build-from-source`

### Setup

1. Run `bundle install` to install dependencies
2. Create `config/database.yml` by copying `config/database.example.yml`
3. Create `config/secrets.yml` by copying `config/secrets.example.yml`
4. Run `bin/rake db:reset` to create, load and seed db
5. Create .env file based on .env.example
6. Sign up for a Stripe account
7. Put Stripe (test) keys into appropriate .env vars
8. Run `bin/rails s` or `rails s` to start the server

### Dependencies

- Rails 4.2 [Rails Guide](http://guides.rubyonrails.org/v4.2/)
- PostgreSQL 9.x
- Stripe

## Tech Stack

- Ruby 2.6.6
- Rails 4.2.11
- Stripe
- jQuery
- Gem:
  - [pg](https://github.com/ged/ruby-pg) | PostgreSQL library for Ruby

### Stripe Testing

Use Credit Card # 4111 1111 1111 1111 for testing success scenarios.

More information in their docs: <https://stripe.com/docs/testing#cards>
