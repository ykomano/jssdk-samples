# JS SDK with D3.js (Line Chart)

http://ykomano.github.io/jssdk-samples/d3js-linechart/

Please refer original sample http://bl.ocks.org/mbostock/3883245

This sample loads data from KiiCloud.

```
<date> = 20150803 (2015/08/03)
<time> = 131700 (13:17:00)

https://<site>.kii.com/api/apps/<appid>/buckets/line/objects/<date>

{
  "data": {
    "<time>": {
      "temperature": 28
    },
    "<time>": {
      "temperature": 29
    },
    "<time>": {
      "temperature": 25
    }
  }
}
```
