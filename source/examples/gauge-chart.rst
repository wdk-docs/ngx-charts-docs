Gauge Chart
===========

Gauge
-----

{% embed
data=“{"url":"https://stackblitz.com/edit/swimlane-gauge-chart?embed=1&file=app/app.component.ts","type":"link","title":"gauge-chart
- StackBlitz","description":"Gauge Chart demo for
ngx-charts","icon":{"type":"icon","url":"https://c.staticblitz.com/assets/icon-664493542621427cc8adae5e8f50d632f87aaa6ea1ce5b01e9a3d05b57940a9f.png","aspectRatio":0},"thumbnail":{"type":"thumbnail","url":"https://c.staticblitz.com/assets/icon-664493542621427cc8adae5e8f50d632f87aaa6ea1ce5b01e9a3d05b57940a9f.png","aspectRatio":0}}”
%}

Inputs
------

+----------+-------+-----+-------------------------------------------------+
| Property | Type  | De  |                   Description                   |
|          |       | fa  |                                                 |
|          |       | ul  |                                                 |
|          |       |  t  |                                                 |
|          |       | Va  |                                                 |
|          |       | lu  |                                                 |
|          |       |  e  |                                                 |
+==========+=======+=====+=================================================+
| view     | numbe |     | the dimensions of the chart [width, height]. If |
|          | r[]   |     | left undefined, the chart will fit to the       |
|          |       |     | parent container size                           |
+----------+-------+-----+-------------------------------------------------+
| resul    | objec |     | the chart data                                  |
| ts       | t[]   |     |                                                 |
+----------+-------+-----+-------------------------------------------------+
| schem    | objec |     | the color scheme of the chart                   |
| e        | t     |     |                                                 |
+----------+-------+-----+-------------------------------------------------+
| custo    | funct |     | custom colors for the chart. Used to override a |
| mColo    | ion   |     | color for a specific value                      |
| rs       | or    |     |                                                 |
|          | objec |     |                                                 |
|          | t     |     |                                                 |
+----------+-------+-----+-------------------------------------------------+
| anima    | boole | tr  | enable animations                               |
| tions    | an    | ue  |                                                 |
+----------+-------+-----+-------------------------------------------------+
| legen    | boole | fa  | show or hide the legend                         |
| d        | an    | ls  |                                                 |
|          |       | e   |                                                 |
+----------+-------+-----+-------------------------------------------------+
| legen    | strin | ‘L  | the legend title                                |
| dTitl    | g     | eg  |                                                 |
| e        |       | en  |                                                 |
|          |       | d’  |                                                 |
+----------+-------+-----+-------------------------------------------------+
| min      | numbe | 0   | starting point of the scale                     |
|          | r     |     |                                                 |
+----------+-------+-----+-------------------------------------------------+
| max      | numbe | 10  | ending point of the scale                       |
|          | r     | 0   |                                                 |
+----------+-------+-----+-------------------------------------------------+
| units    | strin |     | text to display under the value                 |
|          | g     |     |                                                 |
+----------+-------+-----+-------------------------------------------------+
| bigSe    | numbe | 10  | number of big segments on the axis              |
| gment    | r     |     |                                                 |
| s        |       |     |                                                 |
+----------+-------+-----+-------------------------------------------------+
| small    | numbe | 5   | number of small segments between every big      |
| Segme    | r     |     | segment                                         |
| nts      |       |     |                                                 |
+----------+-------+-----+-------------------------------------------------+
| showA    | boole | tr  | show or hide the axis                           |
| xis      | an    | ue  |                                                 |
+----------+-------+-----+-------------------------------------------------+
| axisT    | funct |     | the axis tick formatting                        |
| ickFo    | ion   |     |                                                 |
| rmatt    |       |     |                                                 |
| ing      |       |     |                                                 |
+----------+-------+-----+-------------------------------------------------+
| value    | funct |     | function that formats the value in the middle   |
| Forma    | ion   |     | of the chart                                    |
| tting    |       |     |                                                 |
+----------+-------+-----+-------------------------------------------------+
| angle    | numbe | 24  | the angle that the chart spans (in degrees)     |
| Span     | r     | 0   |                                                 |
+----------+-------+-----+-------------------------------------------------+
| start    | numbe | -1  | the angle that the chart is rotated by. Use     |
| Angle    | r     | 20  | negative half of the spanning angle to          |
|          |       |     | centralize                                      |
+----------+-------+-----+-------------------------------------------------+
| toolt    | boole | fa  | show or hide the tooltip                        |
| ipDis    | an    | ls  |                                                 |
| abled    |       | e   |                                                 |
+----------+-------+-----+-------------------------------------------------+
| toolt    | Templ |     | a custom ng-template to be displayed inside the |
| ipTem    | ateRe |     | tooltip                                         |
| plate    | f     |     |                                                 |
+----------+-------+-----+-------------------------------------------------+
| showT    | boole | tr  | show or hide the inner text                     |
| ext      | an    | ue  |                                                 |
+----------+-------+-----+-------------------------------------------------+

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
