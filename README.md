# my-github-based-json-server
> ### _Repo Base For Typicode's MyJSON Server Project_

## Overview

### Web-UI / Frontend URL:
### https://my-json-server.typicode.com/matt-d-brown/my-github-based-json-server
served from the source at https://github.com/matt-d-brown/my-github-based-json-server/blob/master/db.json

## Current File Contents

**_db.json:_**
```json
{
  "posts": [
    { "id": 1, "title": "Post 1" },
    { "id": 2, "title": "Post 2" },
    { "id": 3, "title": "Post 3" }
  ],
  "comments": [
    { "id": 1, "body": "some comment", "postId": 1 },
    { "id": 2, "body": "some comment", "postId": 1 }
  ],
  "profile": {
    "name": "typicode"
  }
}
```

## Endpoints

#### Endpoint:
##### https://my-json-server.typicode.com/matt-d-brown/my-github-based-json-server/comments

#### Result:
```json
[
  {
    "id": 1,
    "body": "some comment",
    "postId": 1
  },
  {
    "id": 2,
    "body": "some comment",
    "postId": 1
  }
]
```
