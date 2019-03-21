# Overview

We are building a peer-to-peer car rental service. Let's call it Drivly :)

Here is our plan:

- Let any car owner list her car on our platform.
- Let any person (let's call him 'driver') book a car for a given period and an approximate distance.

## Tasks

Your task is to develop one (or more, feel free) RESTful service(s) to:

The car owner chooses a price per day and price per km for her car. The driver then books the car for a given period and an approximate distance.

The rental price is the sum of:

- A time component: the number of rental days multiplied by the car's price per day.
- A distance component: the number of km multiplied by the car's price per km.

Download the sample data (input.json and output.json) to make your task easier.

## Non-functional requirements

Your service(s) must be resilient, fault tolerant, and responsive. You should prepare it/them to be highly scalable as possible.

## Deliverables

The following deliverables are mandatory for the test acceptance:

- Source code in a public git repository.
- Instructions for configuring and running the application.

If you think something is really necessary, but you don’t have enough time to implement, please explain how you would implement it.

Good luck!
