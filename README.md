
## Installation

```bash
$ npm install
```

## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Testing APIs
Let's start our development server using ``` npm run start:dev ```

## Get all posts
Let's make a GET request to http://localhost:3000/posts. The result should be a 200 OK success code with an empty array.

## Create a post
Let's make a POST request to http://localhost:3000/posts using the following as our JSON body.
```bash
{
  "date": "2021-08-16",
  "title": "Intro to NestJS",
  "body": "This blog post is about NestJS",
  "category": "NestJS"
}
```
## Get a post
Let's make a GET request to http://localhost:3000/posts/1. The result should be a successful 200 OK response code, along with the data for the post with an id of 1.

## Update a post
Let's make a PUT request to http://localhost:3000/posts/1 using the following as our JSON body.
```bash
{
  "date": "2021-08-16",
  "title": "Intro to TypeScript",
  "body": "An intro to TypeScript",
  "category": "TypeScript"
}
```
The result should be a successful 200 OK response code, along with a JSON representation of the post that was updated.

## Delete a post
Let's make a DELETE request to http://localhost:3000/posts/1. The result should be a successful 200 OK response code with no JSON object returned.
