Pie Grid Chart
==============

.. _pie-grid-chart-1:

Pie Grid Chart
--------------

{% embed
data=“{"url":"https://stackblitz.com/edit/swimlane-pie-chart-grid?embed=1&file=app/app.component.ts","type":"link","title":"pie-grid-chart
- StackBlitz","description":"Pie Grid Chart demo for
ngx-charts","icon":{"type":"icon","url":"https://c.staticblitz.com/assets/icon-664493542621427cc8adae5e8f50d632f87aaa6ea1ce5b01e9a3d05b57940a9f.png","aspectRatio":0},"thumbnail":{"type":"thumbnail","url":"https://c.staticblitz.com/assets/icon-664493542621427cc8adae5e8f50d632f87aaa6ea1ce5b01e9a3d05b57940a9f.png","aspectRatio":0}}”
%}

Inputs
------

+---+----+---+----------------------------------------------------------+
| P | Ty | D | Description                                              |
| r | pe | e |                                                          |
| o |    | f |                                                          |
| p |    | a |                                                          |
| e |    | u |                                                          |
| r |    | l |                                                          |
| t |    | t |                                                          |
| y |    | V |                                                          |
|   |    | a |                                                          |
|   |    | l |                                                          |
|   |    | u |                                                          |
|   |    | e |                                                          |
+===+====+===+==========================================================+
| v | nu |   | the dimensions of the chart [width, height]. If left     |
| i | mb |   | undefined, the chart will fit to the parent container    |
| e | er |   | size                                                     |
| w | [] |   |                                                          |
+---+----+---+----------------------------------------------------------+
| r | ob |   | the chart data                                           |
| e | je |   |                                                          |
| s | ct |   |                                                          |
| u | [] |   |                                                          |
| l |    |   |                                                          |
| t |    |   |                                                          |
| s |    |   |                                                          |
+---+----+---+----------------------------------------------------------+
| s | ob |   | the color scheme of the chart                            |
| c | je |   |                                                          |
| h | ct |   |                                                          |
| e |    |   |                                                          |
| m |    |   |                                                          |
| e |    |   |                                                          |
+---+----+---+----------------------------------------------------------+
| c | fu |   | custom colors for the chart. Used to override a color    |
| u | nc |   | for a specific value                                     |
| s | ti |   |                                                          |
| t | on |   |                                                          |
| o | or |   |                                                          |
| m | ob |   |                                                          |
| C | je |   |                                                          |
| o | ct |   |                                                          |
| l |    |   |                                                          |
| o |    |   |                                                          |
| r |    |   |                                                          |
| s |    |   |                                                          |
+---+----+---+----------------------------------------------------------+
| a | bo | t | enable animations                                        |
| n | ol | r |                                                          |
| i | ea | u |                                                          |
| m | n  | e |                                                          |
| a |    |   |                                                          |
| t |    |   |                                                          |
| i |    |   |                                                          |
| o |    |   |                                                          |
| n |    |   |                                                          |
| s |    |   |                                                          |
+---+----+---+----------------------------------------------------------+
| l | st | ‘ | the text to show under the total value                   |
| a | ri | T |                                                          |
| b | ng | o |                                                          |
| e |    | t |                                                          |
| l |    | a |                                                          |
|   |    | l |                                                          |
|   |    | ’ |                                                          |
+---+----+---+----------------------------------------------------------+
| t | bo | f | show or hide the tooltip                                 |
| o | ol | a |                                                          |
| o | ea | l |                                                          |
| l | n  | s |                                                          |
| t |    | e |                                                          |
| i |    |   |                                                          |
| p |    |   |                                                          |
| D |    |   |                                                          |
| i |    |   |                                                          |
| s |    |   |                                                          |
| a |    |   |                                                          |
| b |    |   |                                                          |
| l |    |   |                                                          |
| e |    |   |                                                          |
| d |    |   |                                                          |
+---+----+---+----------------------------------------------------------+
| t | Te |   | a custom ng-template to be displayed inside the tooltip  |
| o | mp |   |                                                          |
| o | la |   |                                                          |
| l | te |   |                                                          |
| t | Re |   |                                                          |
| i | f  |   |                                                          |
| p |    |   |                                                          |
| T |    |   |                                                          |
| e |    |   |                                                          |
| m |    |   |                                                          |
| p |    |   |                                                          |
| l |    |   |                                                          |
| a |    |   |                                                          |
| t |    |   |                                                          |
| e |    |   |                                                          |
+---+----+---+----------------------------------------------------------+
| d | nu |   | total number that the value of each object in the        |
| e | mb |   | results array will be compared to. If left undefined,    |
| s | er |   | the value of each object will automatically be compared  |
| i |    |   | to the total of all the values in the results array.     |
| g |    |   |                                                          |
| n |    |   |                                                          |
| a |    |   |                                                          |
| t |    |   |                                                          |
| e |    |   |                                                          |
| d |    |   |                                                          |
| T |    |   |                                                          |
| o |    |   |                                                          |
| t |    |   |                                                          |
| a |    |   |                                                          |
| l |    |   |                                                          |
+---+----+---+----------------------------------------------------------+
| m | nu | 1 | minimum width of each graph in grid                      |
| i | mb | 5 |                                                          |
| n | er | 0 |                                                          |
| W |    |   |                                                          |
| i |    |   |                                                          |
| d |    |   |                                                          |
| t |    |   |                                                          |
| h |    |   |                                                          |
+---+----+---+----------------------------------------------------------+

Outputs
-------

======== ===========
Property Description
======== ===========
select   click event
======== ===========

Data Format
-----------

The data format is single series:

.. code:: text

   [
     {
       "name": "Germany",
       "value": 8940000
     },
     {
       "name": "USA",
       "value": 5000000
     }
   ]
