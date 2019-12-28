Polar/radar Chart
=================

.. _polarradar-chart-1:

Polar/radar Chart
-----------------

{% embed
data=“{"url":"https://stackblitz.com/edit/swimlane-polar-chart?embed=1&file=app/app.component.ts","type":"link","title":"polar-chart
- StackBlitz","description":"Polar / Radar Chart demo for
ngx-charts","icon":{"type":"icon","url":"https://c.staticblitz.com/assets/icon-664493542621427cc8adae5e8f50d632f87aaa6ea1ce5b01e9a3d05b57940a9f.png","aspectRatio":0},"thumbnail":{"type":"thumbnail","url":"https://c.staticblitz.com/assets/icon-664493542621427cc8adae5e8f50d632f87aaa6ea1ce5b01e9a3d05b57940a9f.png","aspectRatio":0}}”
%}

Inputs
------

+---+---+---+----------------------------------------------------------+
| P | T | D | Description                                              |
| r | y | e |                                                          |
| o | p | f |                                                          |
| p | e | a |                                                          |
| e |   | u |                                                          |
| r |   | l |                                                          |
| t |   | t |                                                          |
| y |   | V |                                                          |
|   |   | a |                                                          |
|   |   | l |                                                          |
|   |   | u |                                                          |
|   |   | e |                                                          |
+===+===+===+==========================================================+
| v | n |   | the dimensions of the chart [width, height]. If left     |
| i | u |   | undefined, the chart will fit to the parent container    |
| e | m |   | size                                                     |
| w | b |   |                                                          |
|   | e |   |                                                          |
|   | r |   |                                                          |
|   | [ |   |                                                          |
|   | ] |   |                                                          |
+---+---+---+----------------------------------------------------------+
| r | o |   | the chart data                                           |
| e | b |   |                                                          |
| s | j |   |                                                          |
| u | e |   |                                                          |
| l | c |   |                                                          |
| t | t |   |                                                          |
| s | [ |   |                                                          |
|   | ] |   |                                                          |
+---+---+---+----------------------------------------------------------+
| s | o |   | the color scheme of the chart                            |
| c | b |   |                                                          |
| h | j |   |                                                          |
| e | e |   |                                                          |
| m | c |   |                                                          |
| e | t |   |                                                          |
+---+---+---+----------------------------------------------------------+
| s | s | ‘ | the color scale type. Can be either ‘ordinal’ or         |
| c | t | o | ‘linear’                                                 |
| h | r | r |                                                          |
| e | i | d |                                                          |
| m | n | i |                                                          |
| e | g | n |                                                          |
| T |   | a |                                                          |
| y |   | l |                                                          |
| p |   | ’ |                                                          |
| e |   |   |                                                          |
+---+---+---+----------------------------------------------------------+
| c | f |   | custom colors for the chart. Used to override a color    |
| u | u |   | for a specific value                                     |
| s | n |   |                                                          |
| t | c |   |                                                          |
| o | t |   |                                                          |
| m | i |   |                                                          |
| C | o |   |                                                          |
| o | n |   |                                                          |
| l | o |   |                                                          |
| o | r |   |                                                          |
| r | o |   |                                                          |
| s | b |   |                                                          |
|   | j |   |                                                          |
|   | e |   |                                                          |
|   | c |   |                                                          |
|   | t |   |                                                          |
+---+---+---+----------------------------------------------------------+
| a | b | t | enable animations                                        |
| n | o | r |                                                          |
| i | o | u |                                                          |
| m | l | e |                                                          |
| a | e |   |                                                          |
| t | a |   |                                                          |
| i | n |   |                                                          |
| o |   |   |                                                          |
| n |   |   |                                                          |
| s |   |   |                                                          |
+---+---+---+----------------------------------------------------------+
| r | n | 0 | opacity of the shadow around the line indication the     |
| a | u | . | (optional) min and max values. The range shadow is only  |
| n | m | 1 | displayed if min and max values are provided with the    |
| g | b | 5 | data. The color of the shadow is always the color of the |
| e | e |   | central line.                                            |
| F | r |   |                                                          |
| i |   |   |                                                          |
| l |   |   |                                                          |
| l |   |   |                                                          |
| O |   |   |                                                          |
| p |   |   |                                                          |
| a |   |   |                                                          |
| c |   |   |                                                          |
| i |   |   |                                                          |
| t |   |   |                                                          |
| y |   |   |                                                          |
+---+---+---+----------------------------------------------------------+
| l | b | f | show or hide the legend                                  |
| e | o | a |                                                          |
| g | o | l |                                                          |
| e | l | s |                                                          |
| n | e | e |                                                          |
| d | a |   |                                                          |
|   | n |   |                                                          |
+---+---+---+----------------------------------------------------------+
| l | s | ‘ | the legend title                                         |
| e | t | L |                                                          |
| g | r | e |                                                          |
| e | i | g |                                                          |
| n | n | e |                                                          |
| d | g | n |                                                          |
| T |   | d |                                                          |
| i |   | ’ |                                                          |
| t |   |   |                                                          |
| l |   |   |                                                          |
| e |   |   |                                                          |
+---+---+---+----------------------------------------------------------+
| l | s | ‘ | the legend position [‘right’, ‘below’]                   |
| e | t | r |                                                          |
| g | r | i |                                                          |
| e | i | g |                                                          |
| n | n | h |                                                          |
| d | g | t |                                                          |
| P |   | ’ |                                                          |
| o |   |   |                                                          |
| s |   |   |                                                          |
| i |   |   |                                                          |
| t |   |   |                                                          |
| i |   |   |                                                          |
| o |   |   |                                                          |
| n |   |   |                                                          |
+---+---+---+----------------------------------------------------------+
| x | b | f | show or hide the x axis                                  |
| A | o | a |                                                          |
| x | o | l |                                                          |
| i | l | s |                                                          |
| s | e | e |                                                          |
|   | a |   |                                                          |
|   | n |   |                                                          |
+---+---+---+----------------------------------------------------------+
| y | b | f | show or hide the y axis                                  |
| A | o | a |                                                          |
| x | o | l |                                                          |
| i | l | s |                                                          |
| s | e | e |                                                          |
|   | a |   |                                                          |
|   | n |   |                                                          |
+---+---+---+----------------------------------------------------------+
| s | b | t | show or hide the grid lines                              |
| h | o | r |                                                          |
| o | o | u |                                                          |
| w | l | e |                                                          |
| G | e |   |                                                          |
| r | a |   |                                                          |
| i | n |   |                                                          |
| d |   |   |                                                          |
| L |   |   |                                                          |
| i |   |   |                                                          |
| n |   |   |                                                          |
| e |   |   |                                                          |
| s |   |   |                                                          |
+---+---+---+----------------------------------------------------------+
| r | b | f | round domains for aligned gridlines                      |
| o | o | a |                                                          |
| u | o | l |                                                          |
| n | l | s |                                                          |
| d | e | e |                                                          |
| D | a |   |                                                          |
| o | n |   |                                                          |
| m |   |   |                                                          |
| a |   |   |                                                          |
| i |   |   |                                                          |
| n |   |   |                                                          |
| s |   |   |                                                          |
+---+---+---+----------------------------------------------------------+
| s | b | f | show or hide the x axis label                            |
| h | o | a |                                                          |
| o | o | l |                                                          |
| w | l | s |                                                          |
| X | e | e |                                                          |
| A | a |   |                                                          |
| x | n |   |                                                          |
| i |   |   |                                                          |
| s |   |   |                                                          |
| L |   |   |                                                          |
| a |   |   |                                                          |
| b |   |   |                                                          |
| e |   |   |                                                          |
| l |   |   |                                                          |
+---+---+---+----------------------------------------------------------+
| s | b | f | show or hide the y axis label                            |
| h | o | a |                                                          |
| o | o | l |                                                          |
| w | l | s |                                                          |
| Y | e | e |                                                          |
| A | a |   |                                                          |
| x | n |   |                                                          |
| i |   |   |                                                          |
| s |   |   |                                                          |
| L |   |   |                                                          |
| a |   |   |                                                          |
| b |   |   |                                                          |
| e |   |   |                                                          |
| l |   |   |                                                          |
+---+---+---+----------------------------------------------------------+
| x | s |   | the x axis label text                                    |
| A | t |   |                                                          |
| x | r |   |                                                          |
| i | i |   |                                                          |
| s | n |   |                                                          |
| L | g |   |                                                          |
| a |   |   |                                                          |
| b |   |   |                                                          |
| e |   |   |                                                          |
| l |   |   |                                                          |
+---+---+---+----------------------------------------------------------+
| y | s |   | the y axis label text                                    |
| A | t |   |                                                          |
| x | r |   |                                                          |
| i | i |   |                                                          |
| s | n |   |                                                          |
| L | g |   |                                                          |
| a |   |   |                                                          |
| b |   |   |                                                          |
| e |   |   |                                                          |
| l |   |   |                                                          |
+---+---+---+----------------------------------------------------------+
| l | b | t | trim the labels beyond a certain maximum length          |
| a | o | r |                                                          |
| b | o | u |                                                          |
| e | l | e |                                                          |
| l | e |   |                                                          |
| T | a |   |                                                          |
| r | n |   |                                                          |
| i |   |   |                                                          |
| m |   |   |                                                          |
+---+---+---+----------------------------------------------------------+
| l | n | 1 | maximum length of the labels. If ``labelTrim`` is        |
| a | u | 0 | ``true``, labels over this length will be trimmed        |
| b | m |   |                                                          |
| e | b |   |                                                          |
| l | e |   |                                                          |
| T | r |   |                                                          |
| r |   |   |                                                          |
| i |   |   |                                                          |
| m |   |   |                                                          |
| S |   |   |                                                          |
| i |   |   |                                                          |
| z |   |   |                                                          |
| e |   |   |                                                          |
+---+---+---+----------------------------------------------------------+
| t | b | t | trim or not ticks on the Y axis                          |
| r | o | r |                                                          |
| i | o | u |                                                          |
| m | l | e |                                                          |
| Y | e |   |                                                          |
| A | a |   |                                                          |
| x | n |   |                                                          |
| i |   |   |                                                          |
| s |   |   |                                                          |
| T |   |   |                                                          |
| i |   |   |                                                          |
| c |   |   |                                                          |
| k |   |   |                                                          |
| s |   |   |                                                          |
+---+---+---+----------------------------------------------------------+
| m | n | 1 | max length of the ticks. If ``trimYAxisTicks`` is        |
| a | u | 6 | ``true``, ticks over this length will be trimmed         |
| x | m |   |                                                          |
| Y | b |   |                                                          |
| A | e |   |                                                          |
| x | r |   |                                                          |
| i |   |   |                                                          |
| s |   |   |                                                          |
| T |   |   |                                                          |
| i |   |   |                                                          |
| c |   |   |                                                          |
| k |   |   |                                                          |
| L |   |   |                                                          |
| e |   |   |                                                          |
| n |   |   |                                                          |
| g |   |   |                                                          |
| t |   |   |                                                          |
| h |   |   |                                                          |
+---+---+---+----------------------------------------------------------+
| x | f |   | the x axis tick formatting                               |
| A | u |   |                                                          |
| x | n |   |                                                          |
| i | c |   |                                                          |
| s | t |   |                                                          |
| T | i |   |                                                          |
| i | o |   |                                                          |
| c | n |   |                                                          |
| k |   |   |                                                          |
| F |   |   |                                                          |
| o |   |   |                                                          |
| r |   |   |                                                          |
| m |   |   |                                                          |
| a |   |   |                                                          |
| t |   |   |                                                          |
| t |   |   |                                                          |
| i |   |   |                                                          |
| n |   |   |                                                          |
| g |   |   |                                                          |
+---+---+---+----------------------------------------------------------+
| y | f |   | the y axis tick formatting                               |
| A | u |   |                                                          |
| x | n |   |                                                          |
| i | c |   |                                                          |
| s | t |   |                                                          |
| T | i |   |                                                          |
| i | o |   |                                                          |
| c | n |   |                                                          |
| k |   |   |                                                          |
| F |   |   |                                                          |
| o |   |   |                                                          |
| r |   |   |                                                          |
| m |   |   |                                                          |
| a |   |   |                                                          |
| t |   |   |                                                          |
| t |   |   |                                                          |
| i |   |   |                                                          |
| n |   |   |                                                          |
| g |   |   |                                                          |
+---+---+---+----------------------------------------------------------+
| a | b | f | set the minimum value of the y axis to the minimum value |
| u | o | a | in the data, instead of 0                                |
| t | o | l |                                                          |
| o | l | s |                                                          |
| S | e | e |                                                          |
| c | a |   |                                                          |
| a | n |   |                                                          |
| l |   |   |                                                          |
| e |   |   |                                                          |
+---+---+---+----------------------------------------------------------+
| c | f |   | the interpolation function used to generate the curve.   |
| u | u |   | It accepts any                                           |
| r | n |   | `d3.curve <https://github.com/d3/d3-shape#curves>`__     |
| v | c |   | function                                                 |
| e | t |   |                                                          |
|   | i |   |                                                          |
|   | o |   |                                                          |
|   | n |   |                                                          |
+---+---+---+----------------------------------------------------------+
| a | o | [ | elements to highlight                                    |
| c | b | ] |                                                          |
| t | j |   |                                                          |
| i | e |   |                                                          |
| v | c |   |                                                          |
| e | t |   |                                                          |
| E | [ |   |                                                          |
| n | ] |   |                                                          |
| t |   |   |                                                          |
| r |   |   |                                                          |
| i |   |   |                                                          |
| e |   |   |                                                          |
| s |   |   |                                                          |
+---+---+---+----------------------------------------------------------+
| t | b | f | show or hide the tooltip                                 |
| o | o | a |                                                          |
| o | o | l |                                                          |
| l | l | s |                                                          |
| t | e | e |                                                          |
| i | a |   |                                                          |
| p | n |   |                                                          |
| D |   |   |                                                          |
| i |   |   |                                                          |
| s |   |   |                                                          |
| a |   |   |                                                          |
| b |   |   |                                                          |
| l |   |   |                                                          |
| e |   |   |                                                          |
| d |   |   |                                                          |
+---+---+---+----------------------------------------------------------+
| s | b | t | show or hide all points on the line on hover             |
| h | o | r |                                                          |
| o | o | u |                                                          |
| w | l | e |                                                          |
| S | e |   |                                                          |
| e | a |   |                                                          |
| r | n |   |                                                          |
| i |   |   |                                                          |
| e |   |   |                                                          |
| s |   |   |                                                          |
| O |   |   |                                                          |
| n |   |   |                                                          |
| H |   |   |                                                          |
| o |   |   |                                                          |
| v |   |   |                                                          |
| e |   |   |                                                          |
| r |   |   |                                                          |
+---+---+---+----------------------------------------------------------+
| t | T |   | a custom ng-template to be displayed inside the tooltip  |
| o | e |   |                                                          |
| o | m |   |                                                          |
| l | p |   |                                                          |
| t | l |   |                                                          |
| i | a |   |                                                          |
| p | t |   |                                                          |
| T | e |   |                                                          |
| e | R |   |                                                          |
| m | e |   |                                                          |
| p | f |   |                                                          |
| l |   |   |                                                          |
| a |   |   |                                                          |
| t |   |   |                                                          |
| e |   |   |                                                          |
+---+---+---+----------------------------------------------------------+
| y | n |   | force y axis scaling to the provided value (ignored if   |
| A | u |   | chart data contains a higher value)                      |
| x | m |   |                                                          |
| i | b |   |                                                          |
| s | e |   |                                                          |
| M | r |   |                                                          |
| i |   |   |                                                          |
| n |   |   |                                                          |
| S |   |   |                                                          |
| c |   |   |                                                          |
| a |   |   |                                                          |
| l |   |   |                                                          |
| e |   |   |                                                          |
+---+---+---+----------------------------------------------------------+

Outputs
-------

========== ========================================
Property   Description
========== ========================================
select     click event
activate   element activation event (mouse enter)
deactivate element deactivation event (mouse leave)
========== ========================================

Data Format
-----------

Regular polar charts
~~~~~~~~~~~~~~~~~~~~

The data format is multi series:

.. code:: text

   [
     {
       "name": "Germany",
       "series": [
         {
           "name": "2010",
           "value": 7300000
         },
         {
           "name": "2011",
           "value": 8940000
         }
       ]
     },

     {
       "name": "USA",
       "series": [
         {
           "name": "2010",
           "value": 7870000
         },
         {
           "name": "2011",
           "value": 8270000
         }
       ]
     }
   ]
