# ruby-buildpack

``` shell
> brew install buildpacks/tap/pack

> pack build test-ruby-app --path ./sample-app --buildpack ./ruby-buildpack

> docker run --rm -p 8080:8080 test-ruby-app

> curl localhost:8080
```
