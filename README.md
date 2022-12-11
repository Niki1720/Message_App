# Message Me - chat app

Message Me is an application that allows the user to chat with other people.
The chat function uses `Action Cable`, which seamlessly integrates `WebSockets` with the rest of my Rails application.

Rails version `6.1`.
Ruby version `2.5`


# Getting started

To get the Rails server running locally:

* Clone this repo
* `bundle install` to install all req'd dependencies
* `rake db:migrate` to make all database migrations
* `rails s` to start the local server

### Important controllers:
* `chatroom_controller`
* `messages_controller`
* `sessions_controller`


##### Resource

Table creation and model with validation:
* Users
* Messages

#### Associations
* One-to-many between users and messages



#### Authentication

* Login using secure password

#### Restriction of actions

* Based on logged in/logged out state
