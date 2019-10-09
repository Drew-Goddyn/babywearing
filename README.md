# README

[![Build Status](https://travis-ci.org/rubyforgood/babywearing.svg?branch=master)](https://travis-ci.org/rubyforgood/babywearing)

# Babywearing

The [Mid-Atlantic Babywearing](https://midatlanticbabywearing.org) organization
is dedicated to supporting the wearing of babies and toddlers for all
caregivers. The MAB Volunteers love holding their babies, toddlers and older
children close with baby carriers and work to spread that joy throughout the
south-eastern and south-central areas of Pennsylvania.

## What is Babywearing?

Babywearing is a method of carrying a baby, toddler or older child close against
one’s body using any of a variety of types of carriers. Babywearing is a tool
that has been utilized all over the world for many centuries, allowing
caretakers to engage in daily activities while staying connected with the child
and enjoying additional bonding time.

Check out the
[many benefits](https://midatlanticbabywearing.org/benefits-of-babywearing/) of
babywearing.

## About this Project

MAB has a lending library so that their members can try different types of
carriers and find what works best for their family. They currently have software
that works pretty well, but is a strain on their budget. The new software will keep
track of members & dues as well as the lending library items and their due
dates.

This project aims to provide MAB with a new Lending Library that is more cost
effective and provides the same capabilities as their existing system with an
emphasis on tailoring the experience to better suit the needs of this
organization. The primary set of features this project will focus on includes:

- Managing inventory of hundreds of carriers across multiple locations

- Allowing Members to create or update their account information

- Using volunteers to check in and check out carriers from inventory

- Recording (not processing) financial transactions such as late fees and
  membership dues

  - Simplifying the process to waive late fees

- Improved notification of activities to members including:

  - Due date reminders for checked out items

  - Updates or changes to events and item due dates

- Signing agreements and waivers to participate in the organization

Some additional stretch goals include:

- Transferring inventory between locations (and tracking that history)

- Event attendance sign in

  - Fast sign in for existing Members

  - Easy transition to create new accounts for new Members

- Assign location preferences to Members

- Opt-in text message for meeting and check out reminders using Twilio

### Technical considerations

The volunteers in this group are very mobile and are using their personal phones
or tablets (mostly iPad minis) to capture event attendance, register users, and
process transactions. This project needs to consider a mobile-first design to
continue to provide the users the flexibility of working remote without having
to carry a laptop. Some events are also more of an ad-hoc popup so a phone could be the only
device available in those moments.

## Development

### Ruby Version
<<<<<<< HEAD
This app uses Ruby version 2.6.3, Rails version 5.2.3 and PostgreSQL 11.4

### Setup
* Clone the repo
* run `bundle install`
* run `rails db:create db:migrate`
=======

This app uses Ruby version 2.6.3 and Rails version 5.2.3

### Setup

- Clone the repo
- run `bundle install`
- run `rails db:create`
- run `rake db:migrate`
>>>>>>> bc2dd1266d00a2689249ba37471c6c5d3ed97123

### Seed the database

From the root of the app, run `bundle exec rails db:seed`. This will create some initial data to use while testing the app and developing new features.

### Install ImageMagick

ImageMagick is needed for the pages with images of carriers
run`brew install imagemagick`

### Start the app

Run `rails s` and browse to http://localhost:3000/

## How to Contribute

_We ♥ contributors!_

By participating in this project, you agree to abide by the
Ruby for Good [Code of Conduct](code-of-conduct.md).

We welcome all types of contributions, but any pull requests that address open
issues, have test coverage, or are tagged with the next milestone will be
prioritized. Please read our [How to Contribute](CONTRIBUTING.md) guide for more
information.
