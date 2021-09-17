Generated from middleware.py on 2021-09-17 13:22:42.251452

# peeringdb_server.middleware

Custom django middleware

# Classes
---

## CurrentRequestContext

```
CurrentRequestContext(builtins.object)
```

Middleware that sets the current request context

This allows us to access the current request from anywhere we need to


### Methods

#### \__call__
`def __call__(self, request)`

Call self as a function.

---
#### \__init__
`def __init__(self, get_response)`

Initialize self.  See help(type(self)) for accurate signature.

---