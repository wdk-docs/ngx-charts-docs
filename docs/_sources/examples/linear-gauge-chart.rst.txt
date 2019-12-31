Linear Gauge Chart
==================

Linear Gauge
------------

{% embed
data=“{"url":"https://stackblitz.com/edit/swimlane-linear-gauge-chart?embed=1&file=app/app.component.ts","type":"link","title":"linear-gauge-chart
- StackBlitz","description":"Linear Gauge Chart demo for
ngx-charts","icon":{"type":"icon","url":"https://c.staticblitz.com/assets/icon-664493542621427cc8adae5e8f50d632f87aaa6ea1ce5b01e9a3d05b57940a9f.png","aspectRatio":0},"thumbnail":{"type":"thumbnail","url":"https://c.staticblitz.com/assets/icon-664493542621427cc8adae5e8f50d632f87aaa6ea1ce5b01e9a3d05b57940a9f.png","aspectRatio":0}}”
%}

Inputs
------

+----------+------+-----+---------------------------------------------------+
| Property | Type | De  |                    Description                    |
|          |      | fa  |                                                   |
|          |      | ul  |                                                   |
|          |      |  t  |                                                   |
|          |      | Va  |                                                   |
|          |      | lu  |                                                   |
|          |      |  e  |                                                   |
+==========+======+=====+===================================================+
| vie      | numb |     | the dimensions of the chart [width, height]. If   |
| w        | er[] |     | left undefined, the chart will fit to the parent  |
|          |      |     | container size                                    |
+----------+------+-----+---------------------------------------------------+
| sch      | obje |     | the color scheme of the chart                     |
| eme      | ct   |     |                                                   |
+----------+------+-----+---------------------------------------------------+
| cus      | func |     | custom colors for the chart. Used to override a   |
| tom      | tion |     | color for a specific value                        |
| Col      | or   |     |                                                   |
| ors      | obje |     |                                                   |
|          | ct   |     |                                                   |
+----------+------+-----+---------------------------------------------------+
| ani      | bool | tr  | enable animations                                 |
| mat      | ean  | ue  |                                                   |
| ion      |      |     |                                                   |
| s        |      |     |                                                   |
+----------+------+-----+---------------------------------------------------+
| min      | numb | 0   | starting point of the scale                       |
|          | er   |     |                                                   |
+----------+------+-----+---------------------------------------------------+
| max      | numb | 10  | ending point of the scale                         |
|          | er   | 0   |                                                   |
+----------+------+-----+---------------------------------------------------+
| val      | numb | 0   | the value represented on the gauge                |
| ue       | er   |     |                                                   |
+----------+------+-----+---------------------------------------------------+
| pre      | numb |     | the value represented by the vertical line on the |
| vio      | er   |     | gauge. Use this if you want to compare the        |
| usV      |      |     | current value to a previous one                   |
| alu      |      |     |                                                   |
| e        |      |     |                                                   |
+----------+------+-----+---------------------------------------------------+
| uni      | stri |     | text to display under the value                   |
| ts       | ng   |     |                                                   |
+----------+------+-----+---------------------------------------------------+
| val      | func |     | function that formats the value in the middle of  |
| ueF      | tion |     | the chart                                         |
| orm      |      |     |                                                   |
| att      |      |     |                                                   |
| ing      |      |     |                                                   |
+----------+------+-----+---------------------------------------------------+

Outputs
-------

======== ===========
Property Description
======== ===========
select   click event
======== ===========
