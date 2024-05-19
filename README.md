# laravel-docs-latest-10.x

# How to save the hidden token
```
You can solve it by creating a new github token to authenticate your composer requests.
You can do this two ways:

By defining your token globally:

composer config --global github-oauth.github.com <TOKEN>
Or by defining your token in a project composer.json:

{  
  "config": {
    "github-oauth": {
      "github.com": "<TOKEN>"
      }
    }
}

```
