Number Card Chart
=================

.. _number-card-chart-1:

Number Card Chart
-----------------

{% embed
data=“{"url":"https://stackblitz.com/edit/swimlane-number-card-chart?embed=1&file=app/app.component.ts","type":"link","title":"number-card-chart
- StackBlitz","description":"Number Card Chart demo for
ngx-charts","icon":{"type":"icon","url":"https://c.staticblitz.com/assets/icon-664493542621427cc8adae5e8f50d632f87aaa6ea1ce5b01e9a3d05b57940a9f.png","aspectRatio":0},"thumbnail":{"type":"thumbnail","url":"https://c.staticblitz.com/assets/icon-664493542621427cc8adae5e8f50d632f87aaa6ea1ce5b01e9a3d05b57940a9f.png","aspectRatio":0}}”
%}

Inputs
------

+-----+------+-------+------------------------------------------------+
| Pro | Type | Defau | Description                                    |
| per |      | lt    |                                                |
| ty  |      | Value |                                                |
+=====+======+=======+================================================+
| vie | numb |       | the dimensions of the chart [width, height].   |
| w   | er[] |       | If left undefined, the chart will fit to the   |
|     |      |       | parent container size                          |
+-----+------+-------+------------------------------------------------+
| res | obje |       | the chart data                                 |
| ult | ct[] |       |                                                |
| s   |      |       |                                                |
+-----+------+-------+------------------------------------------------+
| sch | obje |       | the color scheme of the chart                  |
| eme | ct   |       |                                                |
+-----+------+-------+------------------------------------------------+
| cus | func |       | custom colors for the chart. Used to override  |
| tom | tion |       | a color for a specific value                   |
| Col | or   |       |                                                |
| ors | obje |       |                                                |
|     | ct   |       |                                                |
+-----+------+-------+------------------------------------------------+
| ani | bool | true  | enable animations                              |
| mat | ean  |       |                                                |
| ion |      |       |                                                |
| s   |      |       |                                                |
+-----+------+-------+------------------------------------------------+
| car | stri |       | color of the card background, defaults to      |
| dCo | ng   |       | color based on value and scheme                |
| lor |      |       |                                                |
+-----+------+-------+------------------------------------------------+
| ban | stri |       | color of the card color-bar, defaults to color |
| dCo | ng   |       | based on value and scheme                      |
| lor |      |       |                                                |
+-----+------+-------+------------------------------------------------+
| tex | stri |       | color of the card text, defaults to the        |
| tCo | ng   |       | inverse of the card color                      |
| lor |      |       |                                                |
+-----+------+-------+------------------------------------------------+
| emp | stri | ‘rgba | color of empty card slots                      |
| tyC | ng   | (0,   |                                                |
| olo |      | 0, 0, |                                                |
| r   |      | 0)’   |                                                |
+-----+------+-------+------------------------------------------------+
| inn | numb | 15    | padding around each card in px                 |
| erP | er   |       |                                                |
| add | numb |       |                                                |
| ing | er[] |       |                                                |
+-----+------+-------+------------------------------------------------+
| val | func |       | function that formats the card value           |
| ueF | tion |       |                                                |
| orm |      |       |                                                |
| att |      |       |                                                |
| ing |      |       |                                                |
+-----+------+-------+------------------------------------------------+
| lab | func |       | function that formats the card label           |
| elF | tion |       |                                                |
| orm |      |       |                                                |
| att |      |       |                                                |
| ing |      |       |                                                |
+-----+------+-------+------------------------------------------------+

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
