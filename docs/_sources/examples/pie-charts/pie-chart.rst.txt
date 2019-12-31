Pie Chart
=========

.. _pie-chart-1:

Pie Chart
---------

{% embed
data=“{"url":"https://stackblitz.com/edit/swimlane-pie-chart?embed=1&file=app/app.component.ts","type":"link","title":"pie-chart
- StackBlitz","description":"Pie Chart demo for
ngx-charts","icon":{"type":"icon","url":"https://c.staticblitz.com/assets/icon-664493542621427cc8adae5e8f50d632f87aaa6ea1ce5b01e9a3d05b57940a9f.png","aspectRatio":0},"thumbnail":{"type":"thumbnail","url":"https://c.staticblitz.com/assets/icon-664493542621427cc8adae5e8f50d632f87aaa6ea1ce5b01e9a3d05b57940a9f.png","aspectRatio":0}}”
%}

Inputs
------

+----------+-----+-----+----------------------------------------------------+
| Property | Ty  | Def |                    Description                     |
|          | pe  | aul |                                                    |
|          |     |  t  |                                                    |
|          |     | Val |                                                    |
|          |     | ue  |                                                    |
+==========+=====+=====+====================================================+
| view     | nu  |     | the dimensions of the chart [width, height]. If    |
|          | mb  |     | left undefined, the chart will fit to the parent   |
|          | er  |     | container size                                     |
|          | []  |     |                                                    |
+----------+-----+-----+----------------------------------------------------+
| resu     | ob  |     | the chart data                                     |
| lts      | je  |     |                                                    |
|          | ct  |     |                                                    |
|          | []  |     |                                                    |
+----------+-----+-----+----------------------------------------------------+
| sche     | ob  |     | the color scheme of the chart                      |
| me       | je  |     |                                                    |
|          | ct  |     |                                                    |
+----------+-----+-----+----------------------------------------------------+
| cust     | ob  |     | custom colors for the chart. Used to override a    |
| omCo     | je  |     | color for a specific value                         |
| lors     | ct  |     |                                                    |
+----------+-----+-----+----------------------------------------------------+
| anim     | bo  | tru | enable animations                                  |
| atio     | ol  | e   |                                                    |
| ns       | ea  |     |                                                    |
|          | n   |     |                                                    |
+----------+-----+-----+----------------------------------------------------+
| labe     | bo  | fal | show or hide the labels                            |
| ls       | ol  | se  |                                                    |
|          | ea  |     |                                                    |
|          | n   |     |                                                    |
+----------+-----+-----+----------------------------------------------------+
| labe     | fu  |     | function that formats the label text               |
| lFor     | nc  |     |                                                    |
| matt     | ti  |     |                                                    |
| ing      | on  |     |                                                    |
+----------+-----+-----+----------------------------------------------------+
| trim     | bo  | tru | trim the labels beyond a certain maximum length    |
| Labe     | ol  | e   |                                                    |
| ls       | ea  |     |                                                    |
|          | n   |     |                                                    |
+----------+-----+-----+----------------------------------------------------+
| maxL     | nu  | 10  | maximum length of the labels. If ``trimLabels`` is |
| abel     | mb  |     | ``true``, labels over this length will be trimmed  |
| Leng     | er  |     |                                                    |
| th       |     |     |                                                    |
+----------+-----+-----+----------------------------------------------------+
| lege     | bo  | fal | show or hide the legend                            |
| nd       | ol  | se  |                                                    |
|          | ea  |     |                                                    |
|          | n   |     |                                                    |
+----------+-----+-----+----------------------------------------------------+
| lege     | st  | ‘Le | the legend title                                   |
| ndTi     | ri  | gen |                                                    |
| tle      | ng  | d’  |                                                    |
+----------+-----+-----+----------------------------------------------------+
| lege     | st  | ‘ri | the legend position [‘right’, ‘below’]             |
| ndPo     | ri  | ght |                                                    |
| siti     | ng  | ’   |                                                    |
| on       |     |     |                                                    |
+----------+-----+-----+----------------------------------------------------+
| expl     | bo  | fal | make the radius of each slice proportional to it’s |
| odeS     | ol  | se  | value                                              |
| lice     | ea  |     |                                                    |
| s        | n   |     |                                                    |
+----------+-----+-----+----------------------------------------------------+
| doug     | bo  | fal | should doughnut instead of pie slices              |
| hnut     | ol  | se  |                                                    |
|          | ea  |     |                                                    |
|          | n   |     |                                                    |
+----------+-----+-----+----------------------------------------------------+
| arcW     | nu  | 0.2 | arc width, expressed as a fraction of outer radius |
| idth     | mb  | 5   |                                                    |
|          | er  |     |                                                    |
+----------+-----+-----+----------------------------------------------------+
| grad     | bo  | fal | fill elements with a gradient instead of a solid   |
| ient     | ol  | se  | color                                              |
|          | ea  |     |                                                    |
|          | n   |     |                                                    |
+----------+-----+-----+----------------------------------------------------+
| acti     | ob  | []  | elements to highlight                              |
| veEn     | je  |     |                                                    |
| trie     | ct  |     |                                                    |
| s        | []  |     |                                                    |
+----------+-----+-----+----------------------------------------------------+
| tool     | bo  | fal | show or hide the tooltip                           |
| tipD     | ol  | se  |                                                    |
| isab     | ea  |     |                                                    |
| led      | n   |     |                                                    |
+----------+-----+-----+----------------------------------------------------+
| tool     | fu  |     | a function that formats the tooltip                |
| tipT     | nc  |     |                                                    |
| ext      | ti  |     |                                                    |
|          | on  |     |                                                    |
+----------+-----+-----+----------------------------------------------------+
| tool     | Te  |     | a custom ng-template to be displayed inside the    |
| tipT     | mp  |     | tooltip                                            |
| empl     | la  |     |                                                    |
| ate      | te  |     |                                                    |
|          | Re  |     |                                                    |
|          | f   |     |                                                    |
+----------+-----+-----+----------------------------------------------------+

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
