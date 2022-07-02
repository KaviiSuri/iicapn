# IICAPN

IICAPN (pronounced "eye eye cap'n") is supposed to be a simple tool to run databases and other infra locally on your dev environment without any hastle.

## Motiviation

As a developer, I have to run a lot of software locally for my personal and work projects. Dealing with the hastle of installing everything and managing permissions 😪 led me to create this.

## How It Works

- IICAPN works on top of **docker** and runs pre-defined (but configurable) containers locally. These configurations are called **Orders**.
- This removes the hastle of installing / configuring databases, message queues and other infra locally.

## RoadMap

- [ ] Basic Hard Coded "Orders" and running single instance of each order.
- [ ] Exposing basic parameters for each "Order" like `USERNAME`, `PASSWORD`, `DBNAME` etc.
- [ ] Add ability to attach and detach the docker containers running to the terminal.
- [ ] Multiple instances of the same orders.
- [ ] Creating an api to make 3rd party Orders possible.
- [ ] Convert hardcoded orders to into plugins.
