# solaris-training-products-management

## What do we want?

The goal is to create a Rails API and an Emberjs frontend app for basic product management. Both apps should be TDD.

## Specs

### Rails API

**Details**
*Resources*
* Product: CRUD, pagination
* Item: CRUD, pagination
* Status: stocked, sold, dispatched

**Hints**
* **Test Framework:** [RSpec](http://rspec.info/)
* **JSON format:** [JSON API](http://jsonapi.org/) ([gem](https://github.com/cerebris/jsonapi-resources))
* Products have many items, items belong to a product
* Items should not be creatable without an assigned product
* gem stateful_enum - A very simple state machine plugin built on top of ActiveRecord::Enum

### Ember

**Details**

*Pages*
* Products Index
* Product Show
* Product Edit
* Product New
* Items Index
* Item Show
* Item New

## Rails API to Ember
### Things to remember

*Rails*
*CORS
*In config/application.rb ('Access-Control=Allow-Origin => *')
*Do not leave as wildcard for deployment

*Ember*
*Custom host 'adapters/application.js' (http://localhost:3000)


