# nrs-training-alpha-test-one

In this experiment we're testing 2 types of support model;

1. A-Syncronous support (responses that have a delay. e.g. forum, email)
2. Real-time support (instant responses e.g. live-chat, phone call)


## Set up for development
1. `npm install`
2. `npm start`


## A-sync support
We are using [Muut](https://muut.com/learning-fractions/#!/general). An online forum. At a glance it's more usable than other forums and it only requires a simple username and password to post questions, we'll use this to generate an account for our participants.

The prototype is available at the `/async` endpoint.

## Real-time support
We are using [Crisp Chat](https://crisp.chat) for our live support. It is free and allows multiple tutors to respond in sync.

The prototype is available at the `/live` endpoint.
