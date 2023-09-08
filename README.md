# Node Rest API Example

This is a REST API example setup with Node, Express and mongodb

## Usage

```bash
npm start

```

## Examples

Write to db
http://localhost:3000/api/post
body: {
    "name": "TestName",
      "age": 30
}

Update
http://localhost:3000/api/update/<id>
body {
        "name": "Cody Q",
        "age": 28
}
