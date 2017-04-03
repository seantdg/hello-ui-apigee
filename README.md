# hello-ui-apigee

This is a Hello World UI that uses the Express JS server library and Jade for templating. You can deploy to Apige using the following command:

apigeetool deploynodeapp -n (api name) -b (basepath) -e (environment) -o (org name)

For example:
``` bash
apigeetool deploynodeapp -n helloweb -b /helloweb/v1 -e test -o seandavis
```


You will need to have installed *apigeetool*

``` bash
npm install -g apigeetool
```
