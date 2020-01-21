
# How to launch the project

To start the test:

```bash

git clone https://github.com/lumapps/data-interview.git

cd data-interview

python -m venv venv

source venv/bin/activate

```

# Technical test

## Introduction

In this test, we will ask you to perform a regular job performed by the Data Team at Lumapps.

You will find a set of mock data in this test, called `test_data.csv`. Its content reflects the usage of your platform by users.

Each of your customer is asking you to provide them the amount of participating users on the platform using the provided data.

## Task

The expected task should not take you longer than 1 hour to complete.

Using **SQL**, you are asked to provide the percentage of participating users by customer by day between the 1/15/2020 and the 1/22/2020. A participating user is a user who either write, like or comment a content.

You are expected to:

- use Python 3.x and follow the good practices of this language;

- provide a short explanation of each non-native Python library you decided to use;

- use PostgreSQL to store your data. If you need a Docker image to help you solve this test, you can find one on [dockerhub](https://hub.docker.com/_/postgres).

- use only not nullable column in your table;

- not to modify the test data.

You will provide:

- a script to integrate the relevant data into a PostgreSQL database;

- the schema of the SQL table(s) you plan to use. No nullable value is allowed in this test;

- the SQL query(ies) which will provide you the answer;

- the expected values of the amount of participating users.
