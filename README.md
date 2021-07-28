# What is this
OpenFaaS golang template that uses [modified classic-watchdog](https://github.com/borodun/of-watchdog). See [go classic template](https://docs.openfaas.com/cli/templates/#go-go-classic-template)


#### Adding templates
```bash
faas template pull https://github.com/borodun/of-templates
faas new --list

Languages available as templates:
- cpu-go
```
#### Creating new function
````bash
faas new --lang cpu-go <function-name>
````

