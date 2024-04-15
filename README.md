# visit

https://fyle-internship-challenge-23-sand.vercel.app/

# Submission for Fyle Frontend Challenge

## Assumptions

No extra assumptions were made. The challenge is completed according to the instructions.

## Methods Implemented in API service

There are two methods that are implemented in API service.

### 1. getUser()

This methods takes one string argument i.e. github username, and returns all the public data about user such as name, bio, location, twitter handle etc.

### 2. getRepos()

This methods takes one string argument i.e. github username and one number argument i.e. perpage (repositories to display per page. By default: 10) , and returns an array of objects in which each object contains specified number of repositories data.

## Testing

All the test cases can be run using "ng test" command.

Test can also be run using following steps:

> Step 1: Clone the repository (`https://github.com/Gajmain2020/fyle-internship-challenge-23.git`).

> Step 2: Install all dependencies using `npm install` command.

> Step 2: Run `npm test` command to test all the tests.
