# Fone Dynamics Backend Development Coding Challenge

## Introduction

Thank you for your interest in working with us at Fone Dynamics!
We all love working with talented co-workers.  This challenge is intended to help us evaluate where you are in your programming career so we can determine how you might fit within our company.

## The Challenge

### Background

In order to assess your ability to develop backend applications, we ask that you develop a RESTful API in C# .Net Core.

### Setup

1. You must first fork this repo. If you do not have a GitHub account, you will need to first sign up in order to fork it.
2. Clone your forked repo and develop the application according to the requirements below.
3. Once you think you have completed the exercise to a satisfactory level, ensure all of your code has been committed to your forked repo and issue a Pull Request back to the FoneDynamics repo.

### Requirements

You have been tasked to build a HTTP RESTful API using C# .Net Core.

#### Backend

You will need to set up a database of your choice, containing two tables:
- users; containing usernames and passwords
- customers; containing customer data such as id, name, number of employees, tags

The API will connect to the database and serve data. You will need to generate a token to be returned by the Authorization endpoint.

This API will incorporate two endpoints:

1. Authorization endpoint
2. Customer record endpoint - to be secured by the token generated by the authorization endpoint.

The url/path of these endpoints is at your discretion.

The customer record endpoint should also provide a filter on the querystring to filter by at least 1 tag, and/or the following for number of employees:
- 1-10
- 11-50
- &gt;50

Please include the data in your database in your git repository with a plaintext database dump.

## Questions?

If you have any questions around the implementation of this exercise, please open an Issue on the parent repository at https://github.com/fonedynamics
