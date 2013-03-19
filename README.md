jquery.line
===========

Draw a line between two given points in the passed container.

Usage:

//Assuming that #example have position:relative or absolute.

$('#example').line(0, 0, 20, 20);

You can pass some options like color, stroke width or zindex, and a callback function:

Defaults are:
  { zindex : -1,
    color : '#000000',
    stroke: '1px'
  }

Example: 

$('#example').line(0, 0, 20, 20, {color:"#CCC", stroke:'5px', zindex:1000}, function(){alert('Hello new line!')});

