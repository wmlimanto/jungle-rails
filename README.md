# Jungle

A mini e-commerce application built with Rails 6.1 for purposes of teaching Rails by example.

## Product Overview

### Homepage

![navbar](https://user-images.githubusercontent.com/100328767/191619156-2bd43158-2207-4bf6-a4be-c545710798ce.png)

![homepage](https://user-images.githubusercontent.com/100328767/191619172-c2e80aaa-1953-45e3-9f76-f643bb155e26.png)

### Product Details Page

![product details](https://user-images.githubusercontent.com/100328767/191619185-b76b2742-32f8-4c4d-acc0-730ee713445a.png)

### My Cart Page

![my cart](https://user-images.githubusercontent.com/100328767/191619199-9f9d7fae-9f97-4742-af9e-38453a3fdb12.png)

### Empty Cart

![empty cart](https://user-images.githubusercontent.com/100328767/191619208-7f5abca2-e860-4524-93db-a67d8fc972c6.png)

### Sign Up

![sign up](https://user-images.githubusercontent.com/100328767/191619217-e4edc847-6b14-4e2d-b209-99320286d4af.png)

### Login

![login](https://user-images.githubusercontent.com/100328767/191619234-d816f8b5-2467-4527-9ee1-cbcff2446f38.png)


## Setup

1. Run `bundle install` to install dependencies
2. Create `config/database.yml` by copying `config/database.example.yml`
3. Create `config/secrets.yml` by copying `config/secrets.example.yml`
4. Run `bin/rails db:reset` to create, load and seed db
5. Create .env file based on .env.example
6. Sign up for a Stripe account
7. Put Stripe (test) keys into appropriate .env vars
8. Run `bin/rails s -b 0.0.0.0` to start the server

## Database

If Rails is complaining about authentication to the database, uncomment the user and password fields from `config/database.yml` in the development and test sections, and replace if necessary the user and password `development` to an existing database user.

## Stripe Testing

Use Credit Card # 4111 1111 1111 1111 for testing success scenarios.

More information in their docs: <https://stripe.com/docs/testing#cards>

## Dependencies

- Rails 6.1 [Rails Guide](http://guides.rubyonrails.org/v6.1/)
- Bootstrap 5
- PostgreSQL 9.x
- Stripe
