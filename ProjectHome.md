however, it's a simple slider but powerful.<br />
it can be used as a slider, progressbar and so on...<br />

API:<br />
//content holder(Object || css Selector)<br />
<b>renderTo</b>: $(document.body),<br />
//whether the slider can be dragged<br />
<b>enable</b>: true,<br />
//'max' or 'min'<br />
<b>initPosition</b>: 'max',<br />
//width of bar and slider<br />
<b>size</b>: { barWidth: 200, sliderWidth: 5 },<br />
//class name of bar<br />
<b>barCssName</b>: 'defaultbar',<br />
//class name of completed bar<br />
<b>completedCssName</b>: 'jquery-completed',<br />
//class name of slider<br />
<b>sliderCssName</b>: 'jquery-jslider',<br />
//class name of slider when mouse over<br />
<b>sliderHover</b>: 'jquery-jslider-hover',<br />
//fired when the users are dragging the slider<br />
<b>onChanging</b>: function() { },<br />
//fired when the users doppped the slider<br />
<b>onChanged</b>: function() { }<br />

usage as:<br />
var slider = $.fn.jSlider({...});<br />

update value:<br />
slider.setSliderValue(value,callback);<br />

<a href='http://www.ajaxplaza.net/slider/slider.htm'>live demo</a>