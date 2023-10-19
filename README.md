# Events API JSON DB

This is a simple JSON database file that can be used with the JSON server package to create a RESTful API for events.

## Schema

```
{
  "type": "object",
  "properties": {
    "name": { "type": "string" },
    "location": { "type": "string" },
    "dateAndTime": { "type": "string" },
    "duration": { "type": "integer" },
    "description": { "type": "string" },
    "customUrl": { "type": "string" },
    "id": { "type": "integer" }
  }
}
```

## Usage

This file serves as a stateless "database" that is used for the service [My JSON Server](https://my-json-server.typicode.com/)
