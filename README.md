**PLEASE CREATE ISSUES AT https://github.com/strongloop/loopback/issues**

---

#loopback-getting-started

This is the example application that accompanies the [Getting started with LoopBack](http://docs.strongloop.com/display/LB/Getting+started+with+LoopBack) tutorial. Follow the steps in the tutorial to create this application from scratch.

NOTE: This repository has commits for each step of the tutorial, so you can pick up the tutorial at any point along the way:

See [Getting started with LoopBack](http://docs.strongloop.com/display/LB/Getting+started+with+LoopBack) for step-by-step instructions to create this application.

---

[More LoopBack examples](https://github.com/strongloop/loopback-example)


# Prerequisites -

## Install LoopBack CLI tool
To install the LoopBack command-line interface (CLI) tool, enter the command:

`npm install -g loopback-cli`

This installs the lb command-line tool for scaffolding and modifying LoopBack applications. For more information, see Command-line tools as below...

https://loopback.io/doc/en/lb3/Command-line-tools.html

## Datasource (Installation)
    - MongoDB (brew install mongo & brew services start mongodb)
      - lsof -i | grep mongo
      - mongo mongodb://127.0.0.1:27017
    - SQL SERVER
    - REST Datasource.

# Add a data source
Now we’re going to define a data source using the Data source generator:

`$ lb datasource`

The generator will prompt you for the config properties of data source.

# Demo -
    - Mongo DB
    - REST Datasource.
