# Bootstrap Htmg fallback
A Twitter Bootstrap based Html5 input fallback. It adds Bootstrap widgets to the 
[mvcct-enhancer](https://github.com/MvcControlsToolkit/mvcct-enhancer) basic Html5 input fallback module. 
Thus it depends on both the mvcct.enhancer.js, and mvcct.enhancer.input.basic.js [mvcct-enhancer](https://github.com/MvcControlsToolkit/mvcct-enhancer) modules.
It is enough to load the bootstrap.html5.fallback.js, and the selected bootstrap widgets (listed below) to enrich mvcct-enhancer html5 fallback with botsstrap modules.
More specifically, date-picker, date-time-picker, numeric-range, and color-picker 
widgets are added as needed to the falled back Html5 inputs.

Widget options are added to the overall mvcct-enhancer options object. 
Please refer to the [mvcct-enhancer](https://github.com/MvcControlsToolkit/mvcct-enhancer) 
for the usage of the mvcct-enhancer module. Below, all selected bootstrap widgets, and the loacation theyr options are placed.
All widgets(as well as mvcct-enhancer) are registered as dependencies, so if you use either nmp, or bower you will them have 
automatically installed when you install bootstrap-html5-fallback:

1. Date-picker: [smalot-bootstrap-datetimepicker](https://github.com/smalot/bootstrap-datetimepicker). Options placed in options property: html5FallbackWidgets.date
2. Time-picker: [smalot-bootstrap-datetimepicker](https://github.com/smalot/bootstrap-datetimepicker). Options placed in options property: html5FallbackWidgets.time
3. Date-time-picker: [smalot-bootstrap-datetimepicker](https://github.com/smalot/bootstrap-datetimepicker). Options placed in options property: html5FallbackWidgets.datetime
4. Color-picker: [mjolnic-bootstrap-colorpicker](https://github.com/mjolnic/bootstrap-colorpicker).Options placed in options property: html5FallbackWidgets.color
5. Numeric-range [seiyria-bootstrap-slider](https://github.com/seiyria/bootstrap-slider).Options placed in options property: html5FallbackWidgets.range