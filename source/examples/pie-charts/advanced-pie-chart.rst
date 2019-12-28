Advanced Pie Chart
==================

.. _advanced-pie-chart-1:

Advanced Pie Chart
------------------

{% embed
data=“{"url":"https://stackblitz.com/edit/swimlane-pie-chart-advanced?embed=1&file=app/app.component.ts","type":"link","title":"advanced-pie-chart
- StackBlitz","description":"Advanced Pie Chart demo for
ngx-charts","icon":{"type":"icon","url":"https://c.staticblitz.com/assets/icon-664493542621427cc8adae5e8f50d632f87aaa6ea1ce5b01e9a3d05b57940a9f.png","aspectRatio":0},"thumbnail":{"type":"thumbnail","url":"https://c.staticblitz.com/assets/icon-664493542621427cc8adae5e8f50d632f87aaa6ea1ce5b01e9a3d05b57940a9f.png","aspectRatio":0}}”
%}

Inputs
------

+-------+------+----+------------------------------------------------+
| Prope | Type | De | Description                                    |
| rty   |      | fa |                                                |
|       |      | ul |                                                |
|       |      | t  |                                                |
|       |      | Va |                                                |
|       |      | lu |                                                |
|       |      | e  |                                                |
+=======+======+====+================================================+
| view  | numb |    | the dimensions of the chart [width, height].   |
|       | er[] |    | If left undefined, the chart will fit to the   |
|       |      |    | parent container size                          |
+-------+------+----+------------------------------------------------+
| resul | obje |    | the chart data                                 |
| ts    | ct[] |    |                                                |
+-------+------+----+------------------------------------------------+
| schem | obje |    | the color scheme of the chart                  |
| e     | ct   |    |                                                |
+-------+------+----+------------------------------------------------+
| custo | func |    | custom colors for the chart. Used to override  |
| mColo | tion |    | a color for a specific value                   |
| rs    | or   |    |                                                |
|       | obje |    |                                                |
|       | ct   |    |                                                |
+-------+------+----+------------------------------------------------+
| anima | bool | tr | enable animations                              |
| tions | ean  | ue |                                                |
+-------+------+----+------------------------------------------------+
| gradi | bool | fa | fill elements with a gradient instead of a     |
| ent   | ean  | ls | solid color                                    |
|       |      | e  |                                                |
+-------+------+----+------------------------------------------------+
| activ | obje | [] | elements to highlight                          |
| eEntr | ct[] |    |                                                |
| ies   |      |    |                                                |
+-------+------+----+------------------------------------------------+
| label | stri | ‘T | the text to show under the total value         |
|       | ng   | ot |                                                |
|       |      | al |                                                |
|       |      | ’  |                                                |
+-------+------+----+------------------------------------------------+
| toolt | bool | fa | show or hide the tooltip                       |
| ipDis | ean  | ls |                                                |
| abled |      | e  |                                                |
+-------+------+----+------------------------------------------------+
| toolt | Temp |    | a custom ng-template to be displayed inside    |
| ipTem | late |    | the tooltip                                    |
| plate | Ref  |    |                                                |
+-------+------+----+------------------------------------------------+
| value | func |    | function that formats the numerical value in   |
| Forma | tion |    | the chart legend                               |
| tting |      |    |                                                |
+-------+------+----+------------------------------------------------+
| nameF | func |    | function that formats name in the chart legend |
| ormat | tion |    |                                                |
| ting  |      |    |                                                |
+-------+------+----+------------------------------------------------+
| perce | func |    | function that formats the percentage number in |
| ntage | tion |    | the chart legend                               |
| Forma |      |    |                                                |
| tting |      |    |                                                |
+-------+------+----+------------------------------------------------+

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
