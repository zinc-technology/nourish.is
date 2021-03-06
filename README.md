# Nourish

Community-centric organization platform

## Developing

### Requirements

1. Ruby, version specified in [.ruby-version](./.ruby-version)
1. Postgresql v11

### Getting Started

1. Clone the repository: `git clone git@github.com:zinc-technology/nourish.is.git`
1. Install dependencies: `bundle install`
1. Setup the database: `rake db:create db:migrate db:seed`
1. Start Rails server: `rails s`

## Testing

- Developer testing is done via unit tests and feature tests in the `spec/` folder.
- Exploratory and usability testing is done on https://nourish-core-sandbox.herokuapp.com/
- Run `brew install geckodriver` to run system test
