Tree Map Chart
==============

.. _tree-map-chart-1:

Tree Map Chart
--------------

{% embed
data=“{"url":"https://stackblitz.com/edit/swimlane-tree-map-chart?embed=1&file=app/app.component.ts","type":"link","title":"tree-map-chart
- StackBlitz","description":"Tree Map Chart demo for
ngx-charts","icon":{"type":"icon","url":"https://c.staticblitz.com/assets/icon-664493542621427cc8adae5e8f50d632f87aaa6ea1ce5b01e9a3d05b57940a9f.png","aspectRatio":0},"thumbnail":{"type":"thumbnail","url":"https://c.staticblitz.com/assets/icon-664493542621427cc8adae5e8f50d632f87aaa6ea1ce5b01e9a3d05b57940a9f.png","aspectRatio":0}}”
%}

Inputs
------

+----------+-------+-----+--------------------------------------------------+
| Property | Type  | De  |                   Description                    |
|          |       | fa  |                                                  |
|          |       | ul  |                                                  |
|          |       |  t  |                                                  |
|          |       | Va  |                                                  |
|          |       | lu  |                                                  |
|          |       |  e  |                                                  |
+==========+=======+=====+==================================================+
| vie      | numbe |     | the dimensions of the chart [width, height]. If  |
| w        | r[]   |     | left undefined, the chart will fit to the parent |
|          |       |     | container size                                   |
+----------+-------+-----+--------------------------------------------------+
| res      | objec |     | the chart data                                   |
| ult      | t[]   |     |                                                  |
| s        |       |     |                                                  |
+----------+-------+-----+--------------------------------------------------+
| sch      | objec |     | the color scheme of the chart                    |
| eme      | t     |     |                                                  |
+----------+-------+-----+--------------------------------------------------+
| cus      | funct |     | custom colors for the chart. Used to override a  |
| tom      | ion   |     | color for a specific value                       |
| Col      | or    |     |                                                  |
| ors      | objec |     |                                                  |
|          | t     |     |                                                  |
+----------+-------+-----+--------------------------------------------------+
| ani      | boole | tr  | enable animations                                |
| mat      | an    | ue  |                                                  |
| ion      |       |     |                                                  |
| s        |       |     |                                                  |
+----------+-------+-----+--------------------------------------------------+
| too      | boole | fa  | show or hide the tooltip                         |
| lti      | an    | ls  |                                                  |
| pDi      |       | e   |                                                  |
| sab      |       |     |                                                  |
| led      |       |     |                                                  |
+----------+-------+-----+--------------------------------------------------+
| val      | funct |     | function that formats the cell value             |
| ueF      | ion   |     |                                                  |
| orm      |       |     |                                                  |
| att      |       |     |                                                  |
| ing      |       |     |                                                  |
+----------+-------+-----+--------------------------------------------------+
| lab      | funct |     | function that formats the cell label             |
| elF      | ion   |     |                                                  |
| orm      |       |     |                                                  |
| att      |       |     |                                                  |
| ing      |       |     |                                                  |
+----------+-------+-----+--------------------------------------------------+
| gra      | boole | fa  | fill elements with a gradient instead of a solid |
| die      | an    | ls  | color                                            |
| nt       |       | e   |                                                  |
+----------+-------+-----+--------------------------------------------------+
| too      | Templ |     | a custom ng-template to be displayed inside the  |
| lti      | ateRe |     | tooltip                                          |
| pTe      | f     |     |                                                  |
| mpl      |       |     |                                                  |
| ate      |       |     |                                                  |
+----------+-------+-----+--------------------------------------------------+

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
