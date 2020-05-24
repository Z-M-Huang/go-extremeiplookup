# go-extremeiplookup
Unofficial lib for https://extreme-ip-lookup.com. Thank you for the awesome api

[![Build Status](https://travis-ci.com/Z-M-Huang/go-extremeiplookup.svg?branch=master)](https://travis-ci.com/Z-M-Huang/go-extremeiplookup)

# Example usage
```
  import "github.com/Z-M-Huang/go-extremeiplookup"

  resp, err := extremeiplookup.Get(host)
  if err != nil {
    panic(err)
  }
  fmt.Println(resp.Query)
```