# Why some APIs suck

And yours might too.

## Chatty APIs

Everything you want to do requires multiple requests

## Performance



## Bad error messages



## Pet peeve: properties as arrays

```
{
  "name": "John",
  "properties": [
    {
      "name": "age",
      "value": "30"
    }
  ]
}
```

Why not just

```
{
  "name": "John",
  "age": 30,
}

```
