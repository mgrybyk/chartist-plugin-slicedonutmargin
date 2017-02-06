# chartist-plugin-slicedonutmargin


Simply published jeromeWeb's https://github.com/jeromeWeb/chartist-plugin-slicedonutmargin to npm


Implements a legend for [Chartist](https://github.com/gionkunz/chartist-js) charts.


## Install

```
$ npm install chartist-plugin-slicedonutmargin --save


## Usage

In an example chart:

```javascript
var chart = new Chartist.Pie('.ct-chart', {
  labels: [1, 2, 3, 4, 5, 6, 7],
  series: [
    [2, 4, 2, 5, 4, 3, 6]
  ]
}, {
  plugins: [
    Chartist.plugins.ctSliceDonutMargin({
      sliceMargin: 6
    })
  ]
});
```

or if you like


```javascript
import ChartistSliceDonutMargin from 'chartist-plugin-slicedonutmargin'

...
  plugins: [
    ChartistSliceDonutMargin({
      sliceMargin: 2
    })
  ]
...
```