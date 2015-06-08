[![Build Status](https://travis-ci.org/DanBlakeman/lend_and_tend.svg)](https://travis-ci.org/DanBlakeman/lend_and_tend)
[![Coverage Status](https://coveralls.io/repos/DanBlakeman/lend_and_tend/badge.svg)](https://coveralls.io/r/DanBlakeman/lend_and_tend)

# Lend and Tend

## The airbnb for gardens!

Created within 10 days by a team of four as a [Makers Academy](http://www.makersacademy.com/) final project.

The idea was pitched to us by a social enterprise entrepeneur looking to turn their idea into a business fast, four of us then had 10 days to work with the client to create a MVP suiting their needs.

Lend and Tend lets Londoners with gardens and little time/interest in them, list their gardens; and those with no outdoor space to securely get in touch to rent/use them!

![Screenshot](public/screenshot.png)

## Approach

From the clients brief and we extracted key user stories, and put these into an ordered backlog on a kanban service called Trello.

With twice daily standups we then paired upon working our way through each user story.

We celebrated MVP milestones and presented to the client each time we had enough new functionality to warrant a new release.

All work was BDD test driven from the below user stories using rspec and capybara, each time tests passed new code was automatically deployed to our heroku staging server for the client and ourselves to try.


### User Stories

#### 1st priority (Main User Priorities)

As a lender
So I can get my garden tended
I want to advertise my garden on this service

As a tender
So I can find a garden to tend
I want to view a list of gardens

As a lender
So I can protect my personal details
I want anyone who views my garden to be logged in

As a tender
So I can tend gardens that actually exist (i.e. not spam)
I want lenders to have to sign up

As a lender
So I can advertise my garden on this service
I want to sign up

As a tender
So I can view potential gardens to tend
I want to sign up


#### 2nd priority (Main Business Priorities)

As the administrator of Lend and Tend
So I can encourage people to sign up
I want to promote nice pictures and copy

As a lender
So I can be convinced to share my garden
I want to get some information about Lend and Tend

As a tender
So I can be convinced to share my personal info
I want to get some information about Lend and Tend

As a user
So that i can stay in touch with this new business
I would like to be added to the mailing list on signup


#### 3rd priority (Secondary User Priorities)

As a decisive tender
So I can find just the garden for me
I want to filter the list of gardens by garden features

As a tired tender
So I can see gardens nearby
I want to order the list of gardens by proximity

As a user
So that i don't need to check back daily
I would like messages from interested users to be sent to my email address


#### 4th priority (Secondary Business Priorities)

As the administrator of Lend and Tend
So I can build a buzz around my product
I want an instagram like interactive photo wall on the homepage

As a cautious admin
So I can avoid nasty mishaps
I want to manually filter the images that go on my homepage

## How to use?

### Try now!

Visit [the Lend and Tend staging server](http://pacific-tundra-1942.herokuapp.com) to try the latest iteration of the service for yourself.

### Run locally

clone and download this repo.
```
cd lend_and_tend
rails db:setup
rails s
```
open http://localhost:3000 in your favourite browser.

### Run tests

clone and download this repo.
```
cd lend_and_tend
rspec
```

## Technologies Used

- Ruby on Rails - Framework
- JS - Interactive photowall
- PostgreSQL - DB
- RSpec, Capybara, Shoulda - Testing
- Geocoder gem - Distances
- HAML/Bootstrap/Sass - Markup and styling
- Devise/Omniauth - User management
- AWS - Photo hosting
- Gibbon - Intergration with mailchimp
- Will Paginate - Paginating results
- Heroku, Git - Version control, auto deployment and hosting

## How to contribute?

We're looking to keep working with the client to keep growing and developing the project as part of her team in our spare time.

If you're interested in joining us, for some weekend pair programming, or just have some feedback/advice or ideas, simply send an email or leave a pull request.

We love to hear feedback!

Thanks for reading,

Dan


