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

+--------------+--------------------+---------------+------------------------------------------------+
|   Property   |        Type        | Default Value |                  Description                   |
+==============+====================+===============+================================================+
| view         | number[]           |               | the dimensions of the chart [width, height].   |
|              |                    |               | If left undefined, the chart will fit to the   |
|              |                    |               | parent container size                          |
+--------------+--------------------+---------------+------------------------------------------------+
| results      | object[]           |               | the chart data                                 |
|              |                    |               |                                                |
+--------------+--------------------+---------------+------------------------------------------------+
| scheme       | object             |               | the color scheme of the chart                  |
|              |                    |               |                                                |
+--------------+--------------------+---------------+------------------------------------------------+
| animations   | boolean            | true          | enable animations                              |
|              |                    |               |                                                |
+--------------+--------------------+---------------+------------------------------------------------+
| legen        | boolean            | false         | show or hide the legend                        |
| d            |                    |               |                                                |
+--------------+--------------------+---------------+------------------------------------------------+
| legen        | string             | ‘Legend’      | the legend title                               |
| dTitl        |                    |               |                                                |
| e            |                    |               |                                                |
+--------------+--------------------+---------------+------------------------------------------------+
| legen        | string             | ‘right’       | the legend position [‘right’, ‘below’]         |
| dPosi        |                    |               |                                                |
| tion         |                    |               |                                                |
+--------------+--------------------+---------------+------------------------------------------------+
| xAxis        | boolean            | false         | show or hide the x axis                        |
|              |                    |               |                                                |
+--------------+--------------------+---------------+------------------------------------------------+
| yAxis        | boolean            | false         | show or hide the y axis                        |
|              |                    |               |                                                |
+--------------+--------------------+---------------+------------------------------------------------+
| showX        | boolean            | false         | show or hide the x axis label                  |
| AxisL        |                    |               |                                                |
| abel         |                    |               |                                                |
+--------------+--------------------+---------------+------------------------------------------------+
| showY        | boolean            | false         | show or hide the y axis label                  |
| AxisL        |                    |               |                                                |
| abel         |                    |               |                                                |
+--------------+--------------------+---------------+------------------------------------------------+
| xAxis        | string             |               | the x axis label text                          |
| Label        |                    |               |                                                |
+--------------+--------------------+---------------+------------------------------------------------+
| yAxis        | string             |               | the y axis label text                          |
| Label        |                    |               |                                                |
+--------------+--------------------+---------------+------------------------------------------------+
| trimX        | boolean            | tru           | trim or not ticks on the x axis                |
| AxisT        |                    | e             |                                                |
| icks         |                    |               |                                                |
+--------------+--------------------+---------------+------------------------------------------------+
| trimY        | boolean            | tru           | trim or not ticks on the Y axis                |
| AxisT        |                    | e             |                                                |
| icks         |                    |               |                                                |
+--------------+--------------------+---------------+------------------------------------------------+
| rotat        | boolean            | tru           | enable automic rotation of x-axis ticks to     |
| eXAxi        |                    | e             | prevent overlaps                               |
| sTick        |                    |               |                                                |
| s            |                    |               |                                                |
+--------------+--------------------+---------------+------------------------------------------------+
| maxXA        | number             | 16            | max length of the ticks. If ``trimXAxisTicks`` |
| xisTi        |                    |               | is ``true``, ticks over this length will be    |
| ckLen        |                    |               | trimmed                                        |
| gth          |                    |               |                                                |
+--------------+--------------------+---------------+------------------------------------------------+
| maxYA        | number             | 16            | max length of the ticks. If ``trimYAxisTicks`` |
| xisTi        |                    |               | is ``true``, ticks over this length will be    |
| ckLen        |                    |               | trimmed                                        |
| gth          |                    |               |                                                |
+--------------+--------------------+---------------+------------------------------------------------+
| xAxis        | function           |               | the x axis tick formatting                     |
| TickF        |                    |               |                                                |
| ormat        |                    |               |                                                |
| ting         |                    |               |                                                |
+--------------+--------------------+---------------+------------------------------------------------+
| yAxis        | function           |               | the y axis tick formatting                     |
| TickF        |                    |               |                                                |
| ormat        |                    |               |                                                |
| ting         |                    |               |                                                |
+--------------+--------------------+---------------+------------------------------------------------+
| xAxis        | any[]              |               | predefined list of x axis tick values          |
| Ticks        |                    |               |                                                |
+--------------+--------------------+---------------+------------------------------------------------+
| yAxis        | any[]              |               | predefined list of y axis tick values          |
| Ticks        |                    |               |                                                |
+--------------+--------------------+---------------+------------------------------------------------+
| gradi        | boolean            | false         | fill elements with a gradient instead of a     |
| ent          |                    |               | solid color                                    |
+--------------+--------------------+---------------+------------------------------------------------+
| innerPadding | number or number[] | 8             | the inner padding in px                        |
+--------------+--------------------+---------------+------------------------------------------------+
| toolt        | boolean            | false         | show or hide the tooltip                       |
| ipDis        |                    |               |                                                |
| abled        |                    |               |                                                |
+--------------+--------------------+---------------+------------------------------------------------+
| toolt        | function           | (see source)  | the HTML text to display in the tooltip        |
| ipTex        |                    |               |                                                |
| t            |                    |               |                                                |
|              |                    |               |                                                |
|              |                    |               |                                                |
+--------------+--------------------+---------------+------------------------------------------------+
| toolt        | TemplateRef        |               | a custom ng-template to be displayed inside    |
| ipTem        |                    |               | the tooltip                                    |
| plate        |                    |               |                                                |
+--------------+--------------------+---------------+------------------------------------------------+

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
