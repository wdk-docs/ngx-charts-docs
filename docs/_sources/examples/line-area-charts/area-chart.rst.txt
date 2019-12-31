Area Chart
==========

.. _area-chart-1:

Area Chart
----------

.. code::

  {% embed
    data=“{
      "url":"https://stackblitz.com/edit/swimlane-area-chart?embed=1&file=app/app.component.ts",
      "type":"link",
      "title":"area-chart- StackBlitz",
      "description":"Area Chart demo forngx-charts",
      "icon":{
        "type":"icon",
        "url":"https://c.staticblitz.com/assets/icon-664493542621427cc8adae5e8f50d632f87aaa6ea1ce5b01e9a3d05b57940a9f.png",
        "aspectRatio":0
      },
      "thumbnail":{
        "type":"thumbnail",
        "url":"https://c.staticblitz.com/assets/icon-664493542621427cc8adae5e8f50d632f87aaa6ea1ce5b01e9a3d05b57940a9f.png",
        "aspectRatio":0
      }
    }”
  %}

Inputs
------

+----------+------+---------------+--------------------------------------------------+
| Property | Type | Default Value |                   Description                    |
+==========+======+===============+==================================================+
| view     | numb |               | the dimensions of the chart [width, height]. If  |
|          | er[] |               | left undefined, the chart will fit to the parent |
|          |      |               | container size                                   |
+----------+------+---------------+--------------------------------------------------+
| resul    | obje |               | the chart data                                   |
| ts       | ct[] |               |                                                  |
+----------+------+---------------+--------------------------------------------------+
| schem    | obje |               | the color scheme of the chart                    |
| e        | ct   |               |                                                  |
+----------+------+---------------+--------------------------------------------------+
| schem    | stri | ‘o            | the color scale type. Can be either ‘ordinal’ or |
| eType    | ng   | rd            | ‘linear’                                         |
|          |      | in            |                                                  |
|          |      | al            |                                                  |
|          |      | ’             |                                                  |
+----------+------+---------------+--------------------------------------------------+
| custo    | func |               | custom colors for the chart. Used to override a  |
| mColo    | tion |               | color for a specific value                       |
| rs       | or   |               |                                                  |
|          | obje |               |                                                  |
|          | ct   |               |                                                  |
+----------+------+---------------+--------------------------------------------------+
| anima    | bool | tr            | enable animations                                |
| tions    | ean  | ue            |                                                  |
+----------+------+---------------+--------------------------------------------------+
| legen    | bool | fa            | show or hide the legend                          |
| d        | ean  | ls            |                                                  |
|          |      | e             |                                                  |
+----------+------+---------------+--------------------------------------------------+
| legen    | stri | ‘L            | the legend title                                 |
| dTitl    | ng   | eg            |                                                  |
| e        |      | en            |                                                  |
|          |      | d’            |                                                  |
+----------+------+---------------+--------------------------------------------------+
| legen    | stri | ‘r            | the legend position [‘right’, ‘below’]           |
| dPosi    | ng   | ig            |                                                  |
| tion     |      | ht            |                                                  |
|          |      | ’             |                                                  |
+----------+------+---------------+--------------------------------------------------+
| xAxis    | bool | fa            | show or hide the x axis                          |
|          | ean  | ls            |                                                  |
|          |      | e             |                                                  |
+----------+------+---------------+--------------------------------------------------+
| yAxis    | bool | fa            | show or hide the y axis                          |
|          | ean  | ls            |                                                  |
|          |      | e             |                                                  |
+----------+------+---------------+--------------------------------------------------+
| showG    | bool | tr            | show or hide the grid lines                      |
| ridLi    | ean  | ue            |                                                  |
| nes      |      |               |                                                  |
+----------+------+---------------+--------------------------------------------------+
| round    | bool | fa            | round domains for aligned gridlines              |
| Domai    | ean  | ls            |                                                  |
| ns       |      | e             |                                                  |
+----------+------+---------------+--------------------------------------------------+
| showX    | bool | fa            | show or hide the x axis label                    |
| AxisL    | ean  | ls            |                                                  |
| abel     |      | e             |                                                  |
+----------+------+---------------+--------------------------------------------------+
| showY    | bool | fa            | show or hide the y axis label                    |
| AxisL    | ean  | ls            |                                                  |
| abel     |      | e             |                                                  |
+----------+------+---------------+--------------------------------------------------+
| xAxis    | stri |               | the x axis label text                            |
| Label    | ng   |               |                                                  |
+----------+------+---------------+--------------------------------------------------+
| yAxis    | stri |               | the y axis label text                            |
| Label    | ng   |               |                                                  |
+----------+------+---------------+--------------------------------------------------+
| trimX    | bool | tr            | trim or not ticks on the x axis                  |
| AxisT    | ean  | ue            |                                                  |
| icks     |      |               |                                                  |
+----------+------+---------------+--------------------------------------------------+
| trimY    | bool | tr            | trim or not ticks on the Y axis                  |
| AxisT    | ean  | ue            |                                                  |
| icks     |      |               |                                                  |
+----------+------+---------------+--------------------------------------------------+
| rotat    | bool | tr            | enable automic rotation of x-axis ticks to       |
| eXAxi    | ean  | ue            | prevent overlaps                                 |
| sTick    |      |               |                                                  |
| s        |      |               |                                                  |
+----------+------+---------------+--------------------------------------------------+
| maxXA    | numb | 16            | max length of the ticks. If ``trimXAxisTicks``   |
| xisTi    | er   |               | is ``true``, ticks over this length will be      |
| ckLen    |      |               | trimmed                                          |
| gth      |      |               |                                                  |
+----------+------+---------------+--------------------------------------------------+
| maxYA    | numb | 16            | max length of the ticks. If ``trimYAxisTicks``   |
| xisTi    | er   |               | is ``true``, ticks over this length will be      |
| ckLen    |      |               | trimmed                                          |
| gth      |      |               |                                                  |
+----------+------+---------------+--------------------------------------------------+
| xAxis    | func |               | the x axis tick formatting                       |
| TickF    | tion |               |                                                  |
| ormat    |      |               |                                                  |
| ting     |      |               |                                                  |
+----------+------+---------------+--------------------------------------------------+
| yAxis    | func |               | the y axis tick formatting                       |
| TickF    | tion |               |                                                  |
| ormat    |      |               |                                                  |
| ting     |      |               |                                                  |
+----------+------+---------------+--------------------------------------------------+
| xAxis    | any[ |               | predefined list of x axis tick values            |
| Ticks    | ]    |               |                                                  |
+----------+------+---------------+--------------------------------------------------+
| yAxis    | any[ |               | predefined list of y axis tick values            |
| Ticks    | ]    |               |                                                  |
+----------+------+---------------+--------------------------------------------------+
| timel    | bool | fa            | display a timeline control under the chart. Only |
| ine      | ean  | ls            | available if x scale is date                     |
|          |      | e             |                                                  |
+----------+------+---------------+--------------------------------------------------+
| autoS    | bool | fa            | set the minimum value of the y axis to the       |
| cale     | ean  | ls            | minimum value in the data, instead of 0 (ignored |
|          |      | e             | if yScaleMin is defined)                         |
+----------+------+---------------+--------------------------------------------------+
| curve    | func |               | the interpolation function used to generate the  |
|          | tion |               | curve. It accepts any                            |
|          |      |               | `d3.curve <https://github.com/d3/d3-shape#curves |
|          |      |               | >`__                                             |
|          |      |               | function                                         |
+----------+------+---------------+--------------------------------------------------+
| gradi    | bool | fa            | fill elements with a gradient instead of a solid |
| ent      | ean  | ls            | color                                            |
|          |      | e             |                                                  |
+----------+------+---------------+--------------------------------------------------+
| activ    | obje | []            | elements to highlight                            |
| eEntr    | ct[] |               |                                                  |
| ies      |      |               |                                                  |
+----------+------+---------------+--------------------------------------------------+
| toolt    | bool | fa            | show or hide the tooltip                         |
| ipDis    | ean  | ls            |                                                  |
| abled    |      | e             |                                                  |
+----------+------+---------------+--------------------------------------------------+
| toolt    | Temp |               | a custom ng-template to be displayed inside the  |
| ipTem    | late |               | tooltip when hovering a single point             |
| plate    | Ref  |               |                                                  |
+----------+------+---------------+--------------------------------------------------+
| serie    | Temp |               | a custom ng-template to be displayed inside the  |
| sTool    | late |               | tooltip when hovering series                     |
| tipTe    | Ref  |               |                                                  |
| mplat    |      |               |                                                  |
| e        |      |               |                                                  |
+----------+------+---------------+--------------------------------------------------+
| xScal    | any  |               | the minimum value of the x axis (if the x scale  |
| eMin     |      |               | is linear or time)                               |
+----------+------+---------------+--------------------------------------------------+
| xScal    | any  |               | the maximum value of the x axis (if the x scale  |
| eMax     |      |               | is linear or time)                               |
+----------+------+---------------+--------------------------------------------------+
| yScal    | numb |               | the minimum value of the y axis                  |
| eMin     | er   |               |                                                  |
+----------+------+---------------+--------------------------------------------------+
| yScal    | numb |               | the maximum value of the y axis                  |
| eMax     | er   |               |                                                  |
+----------+------+---------------+--------------------------------------------------+

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
