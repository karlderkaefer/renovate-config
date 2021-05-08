# cdk-renovate-config
you can use this shared renovate config for your projects
```
{
  "extends": [
    "github>karlderkaefer/cdk-renovate-config:golang"
  ]
}
```
if you want to add more configuration create a new json e.g. `hourly.json` then your config would look like 
```
  "extends": ["github>karlderkaefer/cdk-renovate-config:hourly"]
```
