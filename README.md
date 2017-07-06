# Power-BI-Integer-Error-Demonstration
This is the source code and .pbiviz that demonstrates an error with Power BI's handling of the `integer type` in the `requireTypes` property of `capabilities.json`. 

The current `requireTypes` of the only field is:
```
 "requiredTypes": [

        {

            "integer": true

        } ]
```

And yet, decimals can be put into the field.


![A schreenshot of the visualization](https://github.com/ABKimmel/Power-BI-Integer-Error-Demonstration/blob/master/Demo.png)
