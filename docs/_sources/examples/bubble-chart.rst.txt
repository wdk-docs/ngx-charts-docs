Bubble Chart
============

{% embed
data=“{"url":"https://stackblitz.com/edit/swimlane-bubble-chart?embed=1&file=app/app.component.ts","type":"link","title":"bubble-chart
- StackBlitz","description":"Bubble Chart demo for
ngx-charts","icon":{"type":"icon","url":"https://c.staticblitz.com/assets/icon-664493542621427cc8adae5e8f50d632f87aaa6ea1ce5b01e9a3d05b57940a9f.png","aspectRatio":0},"thumbnail":{"type":"thumbnail","url":"https://c.staticblitz.com/assets/icon-664493542621427cc8adae5e8f50d632f87aaa6ea1ce5b01e9a3d05b57940a9f.png","aspectRatio":0}}”
%}

Inputs
======

+-------+-------+----+------------------------------------------------+
| Prope | Type  | De | Description                                    |
| rty   |       | fa |                                                |
|       |       | ul |                                                |
|       |       | t  |                                                |
|       |       | Va |                                                |
|       |       | lu |                                                |
|       |       | e  |                                                |
+=======+=======+====+================================================+
| view  | numbe |    | the dimensions of the chart [width, height].   |
|       | r[]   |    | If left undefined, the chart will fit to the   |
|       |       |    | parent container size                          |
+-------+-------+----+------------------------------------------------+
| resul | objec |    | the chart data                                 |
| ts    | t[]   |    |                                                |
+-------+-------+----+------------------------------------------------+
| schem | objec |    | the color scheme of the chart                  |
| e     | t     |    |                                                |
+-------+-------+----+------------------------------------------------+
| schem | strin | ‘o | the color scale type. Can be either ‘ordinal’  |
| eType | g     | rd | or ‘linear’                                    |
|       |       | in |                                                |
|       |       | al |                                                |
|       |       | ’  |                                                |
+-------+-------+----+------------------------------------------------+
| custo | funct |    | custom colors for the chart. Used to override  |
| mColo | ion   |    | a color for a specific value                   |
| rs    | or    |    |                                                |
|       | objec |    |                                                |
|       | t     |    |                                                |
+-------+-------+----+------------------------------------------------+
| anima | boole | tr | enable animations                              |
| tions | an    | ue |                                                |
+-------+-------+----+------------------------------------------------+
| legen | boole | fa | show or hide the legend                        |
| d     | an    | ls |                                                |
|       |       | e  |                                                |
+-------+-------+----+------------------------------------------------+
| legen | strin | ‘L | the legend title                               |
| dTitl | g     | eg |                                                |
| e     |       | en |                                                |
|       |       | d’ |                                                |
+-------+-------+----+------------------------------------------------+
| legen | strin | ‘r | the legend position [‘right’, ‘below’]         |
| dPosi | g     | ig |                                                |
| tion  |       | ht |                                                |
|       |       | ’  |                                                |
+-------+-------+----+------------------------------------------------+
| xAxis | boole | fa | show or hide the x axis                        |
|       | an    | ls |                                                |
|       |       | e  |                                                |
+-------+-------+----+------------------------------------------------+
| yAxis | boole | fa | show or hide the y axis                        |
|       | an    | ls |                                                |
|       |       | e  |                                                |
+-------+-------+----+------------------------------------------------+
| showG | boole | tr | show or hide the grid lines                    |
| ridLi | an    | ue |                                                |
| nes   |       |    |                                                |
+-------+-------+----+------------------------------------------------+
| round | boole | fa | round domains for aligned gridlines            |
| Domai | an    | ls |                                                |
| ns    |       | e  |                                                |
+-------+-------+----+------------------------------------------------+
| showX | boole | fa | show or hide the x axis label                  |
| AxisL | an    | ls |                                                |
| abel  |       | e  |                                                |
+-------+-------+----+------------------------------------------------+
| showY | boole | fa | show or hide the y axis label                  |
| AxisL | an    | ls |                                                |
| abel  |       | e  |                                                |
+-------+-------+----+------------------------------------------------+
| xAxis | strin |    | the x axis label text                          |
| Label | g     |    |                                                |
+-------+-------+----+------------------------------------------------+
| yAxis | strin |    | the y axis label text                          |
| Label | g     |    |                                                |
+-------+-------+----+------------------------------------------------+
| rotat | boole | tr | enable automic rotation of x-axis ticks to     |
| eXAxi | an    | ue | prevent overlaps                               |
| sTick |       |    |                                                |
| s     |       |    |                                                |
+-------+-------+----+------------------------------------------------+
| xAxis | funct |    | the x axis tick formatting                     |
| TickF | ion   |    |                                                |
| ormat |       |    |                                                |
| ting  |       |    |                                                |
+-------+-------+----+------------------------------------------------+
| yAxis | funct |    | the y axis tick formatting                     |
| TickF | ion   |    |                                                |
| ormat |       |    |                                                |
| ting  |       |    |                                                |
+-------+-------+----+------------------------------------------------+
| xAxis | any[] |    | predefined list of x axis tick values          |
| Ticks |       |    |                                                |
+-------+-------+----+------------------------------------------------+
| yAxis | any[] |    | predefined list of y axis tick values          |
| Ticks |       |    |                                                |
+-------+-------+----+------------------------------------------------+
| activ | objec | [] | elements to highlight                          |
| eEntr | t[]   |    |                                                |
| ies   |       |    |                                                |
+-------+-------+----+------------------------------------------------+
| minRa | numbe | 3  | minimum bubble radius in px                    |
| dius  | r     |    |                                                |
+-------+-------+----+------------------------------------------------+
| maxRa | numbe | 10 | maximum bubble radius in px                    |
| dius  | r     |    |                                                |
+-------+-------+----+------------------------------------------------+
| toolt | boole | fa | show or hide the tooltip                       |
| ipDis | an    | ls |                                                |
| abled |       | e  |                                                |
+-------+-------+----+------------------------------------------------+
| toolt | Templ |    | a custom ng-template to be displayed inside    |
| ipTem | ateRe |    | the tooltip                                    |
| plate | f     |    |                                                |
+-------+-------+----+------------------------------------------------+
| xScal | any   |    | the minimum value of the x axis (if the x      |
| eMin  |       |    | scale is linear or time)                       |
+-------+-------+----+------------------------------------------------+
| xScal | any   |    | the maximum value of the x axis (if the x      |
| eMax  |       |    | scale is linear or time)                       |
+-------+-------+----+------------------------------------------------+
| yScal | any   |    | the minimum value of the y axis (if the y      |
| eMin  |       |    | scale is linear or time)                       |
+-------+-------+----+------------------------------------------------+
| yScal | any   |    | the maximum value of the y axis (if the y      |
| eMax  |       |    | scale is linear or time)                       |
+-------+-------+----+------------------------------------------------+

Outputs
=======

========== ========================================
Property   Description
========== ========================================
select     click event
activate   element activation event (mouse enter)
deactivate element deactivation event (mouse leave)
========== ========================================

Data Format
===========

Regular bubble charts
---------------------

The data format is multi series:

::

   [
     {
       "name": "Germany",
       "series": [
         {
           "name": "2010",
           "x": 40632,
           "y": 80.3,
           "r": 80.4
         },
         {
           "name": "2000",
           "x": 36953,
           "y": 80.3,
           "r": 78
         },
         {
           "name": "1990",
           "x": 31476,
           "y": 75.4,
           "r": 79
         }
       ]
     },
     {
       "name": "USA",
       "series": [
         {
           "name": "2010",
           "x": 49737,
           "y": 78.8,
           "r": 310
         },
         {
           "name": "2000",
           "x": 45986,
           "y": 76.9,
           "r": 283
         },
         {
           "name": "1990",
           "x": 3706,
           "y": 75.4,
           "r": 253
         }
       ]
     },
     {
       "name": "France",
       "series": [
         {
           "name": "2010",
           "x": 36745,
           "y": 81.4,
           "r": 63
         },
         {
           "name": "2000",
           "x": 34774,
           "y": 79.1,
           "r": 59.4
         },
         {
           "name": "1990",
           "x": 29476,
           "y": 77.2,
           "r": 56.9
         }
       ]
     },
     {
       "name": "United Kingdom",
       "series": [
         {
           "name": "2010",
           "x": 36240,
           "y": 80.2,
           "r": 62.7
         },
         {
           "name": "2000",
           "x": 32543,
           "y": 77.8,
           "r": 58.9
         },
         {
           "name": "1990",
           "x": 26424,
           "y": 75.7,
           "r": 57.1
         }
       ]
     }
   ]
