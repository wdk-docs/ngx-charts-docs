Heat Map Chart
==============

Heat Map
--------

{% embed
data=“{"url":"https://stackblitz.com/edit/swimlane-heat-map-chart?embed=1&file=app/app.component.ts","type":"link","title":"heat-map-chart
- StackBlitz","description":"Heat Map Chart demo for
ngx-charts","icon":{"type":"icon","url":"https://c.staticblitz.com/assets/icon-664493542621427cc8adae5e8f50d632f87aaa6ea1ce5b01e9a3d05b57940a9f.png","aspectRatio":0},"thumbnail":{"type":"thumbnail","url":"https://c.staticblitz.com/assets/icon-664493542621427cc8adae5e8f50d632f87aaa6ea1ce5b01e9a3d05b57940a9f.png","aspectRatio":0}}”
%}

Inputs
------

+-------+-------+-----+------------------------------------------------+
| Prope | Type  | Def | Description                                    |
| rty   |       | aul |                                                |
|       |       | t   |                                                |
|       |       | Val |                                                |
|       |       | ue  |                                                |
+=======+=======+=====+================================================+
| view  | numbe |     | the dimensions of the chart [width, height].   |
|       | r[]   |     | If left undefined, the chart will fit to the   |
|       |       |     | parent container size                          |
+-------+-------+-----+------------------------------------------------+
| resul | objec |     | the chart data                                 |
| ts    | t[]   |     |                                                |
+-------+-------+-----+------------------------------------------------+
| schem | objec |     | the color scheme of the chart                  |
| e     | t     |     |                                                |
+-------+-------+-----+------------------------------------------------+
| anima | boole | tru | enable animations                              |
| tions | an    | e   |                                                |
+-------+-------+-----+------------------------------------------------+
| legen | boole | fal | show or hide the legend                        |
| d     | an    | se  |                                                |
+-------+-------+-----+------------------------------------------------+
| legen | strin | ‘Le | the legend title                               |
| dTitl | g     | gen |                                                |
| e     |       | d’  |                                                |
+-------+-------+-----+------------------------------------------------+
| legen | strin | ‘ri | the legend position [‘right’, ‘below’]         |
| dPosi | g     | ght |                                                |
| tion  |       | ’   |                                                |
+-------+-------+-----+------------------------------------------------+
| xAxis | boole | fal | show or hide the x axis                        |
|       | an    | se  |                                                |
+-------+-------+-----+------------------------------------------------+
| yAxis | boole | fal | show or hide the y axis                        |
|       | an    | se  |                                                |
+-------+-------+-----+------------------------------------------------+
| showX | boole | fal | show or hide the x axis label                  |
| AxisL | an    | se  |                                                |
| abel  |       |     |                                                |
+-------+-------+-----+------------------------------------------------+
| showY | boole | fal | show or hide the y axis label                  |
| AxisL | an    | se  |                                                |
| abel  |       |     |                                                |
+-------+-------+-----+------------------------------------------------+
| xAxis | strin |     | the x axis label text                          |
| Label | g     |     |                                                |
+-------+-------+-----+------------------------------------------------+
| yAxis | strin |     | the y axis label text                          |
| Label | g     |     |                                                |
+-------+-------+-----+------------------------------------------------+
| trimX | boole | tru | trim or not ticks on the x axis                |
| AxisT | an    | e   |                                                |
| icks  |       |     |                                                |
+-------+-------+-----+------------------------------------------------+
| trimY | boole | tru | trim or not ticks on the Y axis                |
| AxisT | an    | e   |                                                |
| icks  |       |     |                                                |
+-------+-------+-----+------------------------------------------------+
| rotat | boole | tru | enable automic rotation of x-axis ticks to     |
| eXAxi | an    | e   | prevent overlaps                               |
| sTick |       |     |                                                |
| s     |       |     |                                                |
+-------+-------+-----+------------------------------------------------+
| maxXA | numbe | 16  | max length of the ticks. If ``trimXAxisTicks`` |
| xisTi | r     |     | is ``true``, ticks over this length will be    |
| ckLen |       |     | trimmed                                        |
| gth   |       |     |                                                |
+-------+-------+-----+------------------------------------------------+
| maxYA | numbe | 16  | max length of the ticks. If ``trimYAxisTicks`` |
| xisTi | r     |     | is ``true``, ticks over this length will be    |
| ckLen |       |     | trimmed                                        |
| gth   |       |     |                                                |
+-------+-------+-----+------------------------------------------------+
| xAxis | funct |     | the x axis tick formatting                     |
| TickF | ion   |     |                                                |
| ormat |       |     |                                                |
| ting  |       |     |                                                |
+-------+-------+-----+------------------------------------------------+
| yAxis | funct |     | the y axis tick formatting                     |
| TickF | ion   |     |                                                |
| ormat |       |     |                                                |
| ting  |       |     |                                                |
+-------+-------+-----+------------------------------------------------+
| xAxis | any[] |     | predefined list of x axis tick values          |
| Ticks |       |     |                                                |
+-------+-------+-----+------------------------------------------------+
| yAxis | any[] |     | predefined list of y axis tick values          |
| Ticks |       |     |                                                |
+-------+-------+-----+------------------------------------------------+
| gradi | boole | fal | fill elements with a gradient instead of a     |
| ent   | an    | se  | solid color                                    |
+-------+-------+-----+------------------------------------------------+
| inner | numbe | 8   | the inner padding in px                        |
| Paddi | r     |     |                                                |
| ng    | or    |     |                                                |
|       | numbe |     |                                                |
|       | r[]   |     |                                                |
+-------+-------+-----+------------------------------------------------+
| toolt | boole | fal | show or hide the tooltip                       |
| ipDis | an    | se  |                                                |
| abled |       |     |                                                |
+-------+-------+-----+------------------------------------------------+
| toolt | funct | (se | the HTML text to display in the tooltip        |
| ipTex | ion   | e   |                                                |
| t     |       | sou |                                                |
|       |       | rce |                                                |
|       |       | )   |                                                |
+-------+-------+-----+------------------------------------------------+
| toolt | Templ |     | a custom ng-template to be displayed inside    |
| ipTem | ateRe |     | the tooltip                                    |
| plate | f     |     |                                                |
+-------+-------+-----+------------------------------------------------+

Outputs
-------

======== ===========
Property Description
======== ===========
select   click event
======== ===========

Data Format
-----------

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
