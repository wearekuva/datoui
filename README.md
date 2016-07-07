# dat.oui
For all you functional haters out there. A stateful wrapper around [Oui](https://www.github.com/wearekuva/oui) that gives you a near match of [dat.gui's](https://workshop.chromeexperiments.com/examples/gui/#1--Basic-Usage) api

### How to?
```
npm install wearekuva/datoui
```

```
var gui = datoui()
gui.add( obj, 'num', {min, max} )
var folder = gui.addFolder( obj, 'num', {min, max} )
folder.add( obj, 'someOtherProp' )
```
