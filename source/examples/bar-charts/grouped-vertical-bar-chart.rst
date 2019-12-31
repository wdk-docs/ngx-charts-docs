Grouped Vertical Bar Chart
==========================

.. _grouped-vertical-bar-chart-1:

Grouped Vertical Bar Chart
--------------------------

{% embed
data=“{"url":"https://stackblitz.com/edit/swimlane-grouped-vertical-bar-chart?embed=1&file=app/app.component.ts","type":"link","title":"grouped-vertical-bar-chart
- StackBlitz","description":"Grouped Vertical Bar Chart demo for
ngx-charts","icon":{"type":"icon","url":"https://c.staticblitz.com/assets/icon-664493542621427cc8adae5e8f50d632f87aaa6ea1ce5b01e9a3d05b57940a9f.png","aspectRatio":0},"thumbnail":{"type":"thumbnail","url":"https://c.staticblitz.com/assets/icon-664493542621427cc8adae5e8f50d632f87aaa6ea1ce5b01e9a3d05b57940a9f.png","aspectRatio":0}}”
%}

Inputs
------

+----------+------+---------------+------------------------------------------------+
| Property | Type | Default Value |                  Description                   |
+==========+======+===============+================================================+
| view     | numb |               | the dimensions of the chart [width, height].   |
|          | er[] |               | If left undefined, the chart will fit to the   |
|          |      |               | parent container size                          |
+----------+------+---------------+------------------------------------------------+
| resul    | obje |               | the chart data                                 |
| ts       | ct[] |               |                                                |
+----------+------+---------------+------------------------------------------------+
| schem    | obje |               | the color scheme of the chart                  |
| e        | ct   |               |                                                |
+----------+------+---------------+------------------------------------------------+
| schem    | stri | ‘o            | the color scale type. Can be either ‘ordinal’  |
| eType    | ng   | rd            | or ‘linear’                                    |
|          |      | in            |                                                |
|          |      | al            |                                                |
|          |      | ’             |                                                |
+----------+------+---------------+------------------------------------------------+
| custo    | func |               | custom colors for the chart. Used to override  |
| mColo    | tion |               | a color for a specific value                   |
| rs       | or   |               |                                                |
|          | obje |               |                                                |
|          | ct   |               |                                                |
+----------+------+---------------+------------------------------------------------+
| anima    | bool | tr            | enable animations                              |
| tions    | ean  | ue            |                                                |
+----------+------+---------------+------------------------------------------------+
| legen    | bool | fa            | show or hide the legend                        |
| d        | ean  | ls            |                                                |
|          |      | e             |                                                |
+----------+------+---------------+------------------------------------------------+
| legen    | stri | ‘L            | the legend title                               |
| dTitl    | ng   | eg            |                                                |
| e        |      | en            |                                                |
|          |      | d’            |                                                |
+----------+------+---------------+------------------------------------------------+
| legen    | stri | ‘r            | the legend position [‘right’, ‘below’]         |
| dPosi    | ng   | ig            |                                                |
| tion     |      | ht            |                                                |
|          |      | ’             |                                                |
+----------+------+---------------+------------------------------------------------+
| xAxis    | bool | fa            | show or hide the x axis                        |
|          | ean  | ls            |                                                |
|          |      | e             |                                                |
+----------+------+---------------+------------------------------------------------+
| yAxis    | bool | fa            | show or hide the y axis                        |
|          | ean  | ls            |                                                |
|          |      | e             |                                                |
+----------+------+---------------+------------------------------------------------+
| showG    | bool | tr            | show or hide the grid lines                    |
| ridLi    | ean  | ue            |                                                |
| nes      |      |               |                                                |
+----------+------+---------------+------------------------------------------------+
| round    | bool | fa            | round domains for aligned gridlines            |
| Domai    | ean  | ls            |                                                |
| ns       |      | e             |                                                |
+----------+------+---------------+------------------------------------------------+
| showX    | bool | fa            | show or hide the x axis label                  |
| AxisL    | ean  | ls            |                                                |
| abel     |      | e             |                                                |
+----------+------+---------------+------------------------------------------------+
| showY    | bool | fa            | show or hide the y axis label                  |
| AxisL    | ean  | ls            |                                                |
| abel     |      | e             |                                                |
+----------+------+---------------+------------------------------------------------+
| xAxis    | stri |               | the x axis label text                          |
| Label    | ng   |               |                                                |
+----------+------+---------------+------------------------------------------------+
| yAxis    | stri |               | the y axis label text                          |
| Label    | ng   |               |                                                |
+----------+------+---------------+------------------------------------------------+
| trimX    | bool | tr            | trim or not ticks on the x axis                |
| AxisT    | ean  | ue            |                                                |
| icks     |      |               |                                                |
+----------+------+---------------+------------------------------------------------+
| trimY    | bool | tr            | trim or not ticks on the Y axis                |
| AxisT    | ean  | ue            |                                                |
| icks     |      |               |                                                |
+----------+------+---------------+------------------------------------------------+
| maxXA    | numb | 16            | max length of the ticks. If ``trimXAxisTicks`` |
| xisTi    | er   |               | is ``true``, ticks over this length will be    |
| ckLen    |      |               | trimmed                                        |
| gth      |      |               |                                                |
+----------+------+---------------+------------------------------------------------+
| maxYA    | numb | 16            | max length of the ticks. If ``trimYAxisTicks`` |
| xisTi    | er   |               | is ``true``, ticks over this length will be    |
| ckLen    |      |               | trimmed                                        |
| gth      |      |               |                                                |
+----------+------+---------------+------------------------------------------------+
| xAxis    | func |               | the x axis tick formatting                     |
| TickF    | tion |               |                                                |
| ormat    |      |               |                                                |
| ting     |      |               |                                                |
+----------+------+---------------+------------------------------------------------+
| yAxis    | func |               | the y axis tick formatting                     |
| TickF    | tion |               |                                                |
| ormat    |      |               |                                                |
| ting     |      |               |                                                |
+----------+------+---------------+------------------------------------------------+
| xAxis    | any[ |               | predefined list of x axis tick values          |
| Ticks    | ]    |               |                                                |
+----------+------+---------------+------------------------------------------------+
| yAxis    | any[ |               | predefined list of y axis tick values          |
| Ticks    | ]    |               |                                                |
+----------+------+---------------+------------------------------------------------+
| showD    | bool | fa            | displays the value number next to the bar      |
| ataLa    | ean  | ls            |                                                |
| bel      |      | e             |                                                |
+----------+------+---------------+------------------------------------------------+
| noBar    | bool | tr            | hide bar if value is 0 and setting is true     |
| WhenZ    | ean  | ue            |                                                |
| ero      |      |               |                                                |
+----------+------+---------------+------------------------------------------------+
| gradi    | bool | fa            | fill elements with a gradient instead of a     |
| ent      | ean  | ls            | solid color                                    |
|          |      | e             |                                                |
+----------+------+---------------+------------------------------------------------+
| activ    | obje | []            | elements to highlight                          |
| eEntr    | ct[] |               |                                                |
| ies      |      |               |                                                |
+----------+------+---------------+------------------------------------------------+
| barPa    | numb | 8             | padding between bars in px                     |
| dding    | er   |               |                                                |
+----------+------+---------------+------------------------------------------------+
| group    | numb | 16            | padding between groups in px                   |
| Paddi    | er   |               |                                                |
| ng       |      |               |                                                |
+----------+------+---------------+------------------------------------------------+
| toolt    | bool | fa            | show or hide the tooltip                       |
| ipDis    | ean  | ls            |                                                |
| abled    |      | e             |                                                |
+----------+------+---------------+------------------------------------------------+
| toolt    | Temp |               | a custom ng-template to be displayed inside    |
| ipTem    | late |               | the tooltip                                    |
| plate    | Ref  |               |                                                |
+----------+------+---------------+------------------------------------------------+
| yScal    | numb |               | the maximum value of the y axis (ignored if    |
| eMax     | er   |               | chart data contains a higher value)            |
+----------+------+---------------+------------------------------------------------+

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
