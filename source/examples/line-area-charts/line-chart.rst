Line Chart
==========

.. _line-chart-1:

Line Chart
----------

{% embed
data=“{"url":"https://stackblitz.com/edit/swimlane-line-chart?embed=1&file=app/app.component.ts","type":"link","title":"line-chart
- StackBlitz","description":"Line Chart demo for
ngx-charts","icon":{"type":"icon","url":"https://c.staticblitz.com/assets/icon-664493542621427cc8adae5e8f50d632f87aaa6ea1ce5b01e9a3d05b57940a9f.png","aspectRatio":0},"thumbnail":{"type":"thumbnail","url":"https://c.staticblitz.com/assets/icon-664493542621427cc8adae5e8f50d632f87aaa6ea1ce5b01e9a3d05b57940a9f.png","aspectRatio":0}}”
%}

Inputs
------

+----------+------+---------------+---------------------------------------------------------+
| Property | Type | Default Value |                       Description                       |
+==========+======+===============+=========================================================+
| vi       | n    |               | the dimensions of the chart [width, height]. If left    |
| ew       | u    |               | undefined, the chart will fit to the parent container   |
|          | m    |               | size                                                    |
|          | b    |               |                                                         |
|          | e    |               |                                                         |
|          | r    |               |                                                         |
|          | [    |               |                                                         |
|          | ]    |               |                                                         |
+----------+------+---------------+---------------------------------------------------------+
| re       | o    |               | the chart data                                          |
| su       | b    |               |                                                         |
| lt       | j    |               |                                                         |
| s        | e    |               |                                                         |
|          | c    |               |                                                         |
|          | t    |               |                                                         |
|          | [    |               |                                                         |
|          | ]    |               |                                                         |
+----------+------+---------------+---------------------------------------------------------+
| sc       | o    |               | the color scheme of the chart                           |
| he       | b    |               |                                                         |
| me       | j    |               |                                                         |
|          | e    |               |                                                         |
|          | c    |               |                                                         |
|          | t    |               |                                                         |
+----------+------+---------------+---------------------------------------------------------+
| sc       | s    | ‘             | the color scale type. Can be either ‘ordinal’ or        |
| he       | t    | o             | ‘linear’                                                |
| me       | r    | r             |                                                         |
| Ty       | i    | d             |                                                         |
| pe       | n    | i             |                                                         |
|          | g    | n             |                                                         |
|          |      | a             |                                                         |
|          |      | l             |                                                         |
|          |      | ’             |                                                         |
+----------+------+---------------+---------------------------------------------------------+
| cu       | f    |               | custom colors for the chart. Used to override a color   |
| st       | u    |               | for a specific value                                    |
| om       | n    |               |                                                         |
| Co       | c    |               |                                                         |
| lo       | t    |               |                                                         |
| rs       | i    |               |                                                         |
|          | o    |               |                                                         |
|          | n    |               |                                                         |
|          | o    |               |                                                         |
|          | r    |               |                                                         |
|          | o    |               |                                                         |
|          | b    |               |                                                         |
|          | j    |               |                                                         |
|          | e    |               |                                                         |
|          | c    |               |                                                         |
|          | t    |               |                                                         |
+----------+------+---------------+---------------------------------------------------------+
| an       | b    | t             | enable animations                                       |
| im       | o    | r             |                                                         |
| at       | o    | u             |                                                         |
| io       | l    | e             |                                                         |
| ns       | e    |               |                                                         |
|          | a    |               |                                                         |
|          | n    |               |                                                         |
+----------+------+---------------+---------------------------------------------------------+
| ra       | n    | 0             | opacity of the shadow around the line indication the    |
| ng       | u    | .             | (optional) min and max values. The range shadow is only |
| eF       | m    | 1             | displayed if min and max values are provided with the   |
| il       | b    | 5             | data. The color of the shadow is alwas the color of the |
| lO       | e    |               | central line.                                           |
| pa       | r    |               |                                                         |
| ci       |      |               |                                                         |
| ty       |      |               |                                                         |
+----------+------+---------------+---------------------------------------------------------+
| le       | b    | f             | show or hide the legend                                 |
| ge       | o    | a             |                                                         |
| nd       | o    | l             |                                                         |
|          | l    | s             |                                                         |
|          | e    | e             |                                                         |
|          | a    |               |                                                         |
|          | n    |               |                                                         |
+----------+------+---------------+---------------------------------------------------------+
| le       | s    | ‘             | the legend title                                        |
| ge       | t    | L             |                                                         |
| nd       | r    | e             |                                                         |
| Ti       | i    | g             |                                                         |
| tl       | n    | e             |                                                         |
| e        | g    | n             |                                                         |
|          |      | d             |                                                         |
|          |      | ’             |                                                         |
+----------+------+---------------+---------------------------------------------------------+
| le       | s    | ‘             | the legend position [‘right’, ‘below’]                  |
| ge       | t    | r             |                                                         |
| nd       | r    | i             |                                                         |
| Po       | i    | g             |                                                         |
| si       | n    | h             |                                                         |
| ti       | g    | t             |                                                         |
| on       |      | ’             |                                                         |
+----------+------+---------------+---------------------------------------------------------+
| xA       | b    | f             | show or hide the x axis                                 |
| xi       | o    | a             |                                                         |
| s        | o    | l             |                                                         |
|          | l    | s             |                                                         |
|          | e    | e             |                                                         |
|          | a    |               |                                                         |
|          | n    |               |                                                         |
+----------+------+---------------+---------------------------------------------------------+
| yA       | b    | f             | show or hide the y axis                                 |
| xi       | o    | a             |                                                         |
| s        | o    | l             |                                                         |
|          | l    | s             |                                                         |
|          | e    | e             |                                                         |
|          | a    |               |                                                         |
|          | n    |               |                                                         |
+----------+------+---------------+---------------------------------------------------------+
| sh       | b    | t             | show or hide the grid lines                             |
| ow       | o    | r             |                                                         |
| Gr       | o    | u             |                                                         |
| id       | l    | e             |                                                         |
| Li       | e    |               |                                                         |
| ne       | a    |               |                                                         |
| s        | n    |               |                                                         |
+----------+------+---------------+---------------------------------------------------------+
| ro       | b    | f             | round domains for aligned gridlines                     |
| un       | o    | a             |                                                         |
| dD       | o    | l             |                                                         |
| om       | l    | s             |                                                         |
| ai       | e    | e             |                                                         |
| ns       | a    |               |                                                         |
|          | n    |               |                                                         |
+----------+------+---------------+---------------------------------------------------------+
| sh       | b    | f             | show or hide the x axis label                           |
| ow       | o    | a             |                                                         |
| XA       | o    | l             |                                                         |
| xi       | l    | s             |                                                         |
| sL       | e    | e             |                                                         |
| ab       | a    |               |                                                         |
| el       | n    |               |                                                         |
+----------+------+---------------+---------------------------------------------------------+
| sh       | b    | f             | show or hide the y axis label                           |
| ow       | o    | a             |                                                         |
| YA       | o    | l             |                                                         |
| xi       | l    | s             |                                                         |
| sL       | e    | e             |                                                         |
| ab       | a    |               |                                                         |
| el       | n    |               |                                                         |
+----------+------+---------------+---------------------------------------------------------+
| xA       | s    |               | the x axis label text                                   |
| xi       | t    |               |                                                         |
| sL       | r    |               |                                                         |
| ab       | i    |               |                                                         |
| el       | n    |               |                                                         |
|          | g    |               |                                                         |
+----------+------+---------------+---------------------------------------------------------+
| yA       | s    |               | the y axis label text                                   |
| xi       | t    |               |                                                         |
| sL       | r    |               |                                                         |
| ab       | i    |               |                                                         |
| el       | n    |               |                                                         |
|          | g    |               |                                                         |
+----------+------+---------------+---------------------------------------------------------+
| tr       | b    | t             | trim or not ticks on the x axis                         |
| im       | o    | r             |                                                         |
| XA       | o    | u             |                                                         |
| xi       | l    | e             |                                                         |
| sT       | e    |               |                                                         |
| ic       | a    |               |                                                         |
| ks       | n    |               |                                                         |
+----------+------+---------------+---------------------------------------------------------+
| tr       | b    | t             | trim or not ticks on the Y axis                         |
| im       | o    | r             |                                                         |
| YA       | o    | u             |                                                         |
| xi       | l    | e             |                                                         |
| sT       | e    |               |                                                         |
| ic       | a    |               |                                                         |
| ks       | n    |               |                                                         |
+----------+------+---------------+---------------------------------------------------------+
| ro       | b    | t             | enable automic rotation of x-axis ticks to prevent      |
| ta       | o    | r             | overlaps                                                |
| te       | o    | u             |                                                         |
| XA       | l    | e             |                                                         |
| xi       | e    |               |                                                         |
| sT       | a    |               |                                                         |
| ic       | n    |               |                                                         |
| ks       |      |               |                                                         |
+----------+------+---------------+---------------------------------------------------------+
| ma       | n    | 1             | max length of the ticks. If ``trimXAxisTicks`` is       |
| xX       | u    | 6             | ``true``, ticks over this length will be trimmed        |
| Ax       | m    |               |                                                         |
| is       | b    |               |                                                         |
| Ti       | e    |               |                                                         |
| ck       | r    |               |                                                         |
| Le       |      |               |                                                         |
| ng       |      |               |                                                         |
| th       |      |               |                                                         |
+----------+------+---------------+---------------------------------------------------------+
| ma       | n    | 1             | max length of the ticks. If ``trimYAxisTicks`` is       |
| xY       | u    | 6             | ``true``, ticks over this length will be trimmed        |
| Ax       | m    |               |                                                         |
| is       | b    |               |                                                         |
| Ti       | e    |               |                                                         |
| ck       | r    |               |                                                         |
| Le       |      |               |                                                         |
| ng       |      |               |                                                         |
| th       |      |               |                                                         |
+----------+------+---------------+---------------------------------------------------------+
| xA       | f    |               | the x axis tick formatting                              |
| xi       | u    |               |                                                         |
| sT       | n    |               |                                                         |
| ic       | c    |               |                                                         |
| kF       | t    |               |                                                         |
| or       | i    |               |                                                         |
| ma       | o    |               |                                                         |
| tt       | n    |               |                                                         |
| in       |      |               |                                                         |
| g        |      |               |                                                         |
+----------+------+---------------+---------------------------------------------------------+
| yA       | f    |               | the y axis tick formatting                              |
| xi       | u    |               |                                                         |
| sT       | n    |               |                                                         |
| ic       | c    |               |                                                         |
| kF       | t    |               |                                                         |
| or       | i    |               |                                                         |
| ma       | o    |               |                                                         |
| tt       | n    |               |                                                         |
| in       |      |               |                                                         |
| g        |      |               |                                                         |
+----------+------+---------------+---------------------------------------------------------+
| xA       | a    |               | predefined list of x axis tick values                   |
| xi       | n    |               |                                                         |
| sT       | y    |               |                                                         |
| ic       | [    |               |                                                         |
| ks       | ]    |               |                                                         |
+----------+------+---------------+---------------------------------------------------------+
| yA       | a    |               | predefined list of y axis tick values                   |
| xi       | n    |               |                                                         |
| sT       | y    |               |                                                         |
| ic       | [    |               |                                                         |
| ks       | ]    |               |                                                         |
+----------+------+---------------+---------------------------------------------------------+
| ti       | b    | f             | display a timeline control under the chart. Only        |
| me       | o    | a             | available if a the x scale is linear or time            |
| li       | o    | l             |                                                         |
| ne       | l    | s             |                                                         |
|          | e    | e             |                                                         |
|          | a    |               |                                                         |
|          | n    |               |                                                         |
+----------+------+---------------+---------------------------------------------------------+
| au       | b    | f             | set the minimum value of the y axis to the minimum      |
| to       | o    | a             | value in the data, instead of 0 (ignored if yScaleMin   |
| Sc       | o    | l             | is defined)                                             |
| al       | l    | s             |                                                         |
| e        | e    | e             |                                                         |
|          | a    |               |                                                         |
|          | n    |               |                                                         |
+----------+------+---------------+---------------------------------------------------------+
| cu       | f    |               | the interpolation function used to generate the curve.  |
| rv       | u    |               | It accepts any                                          |
| e        | n    |               | `d3.curve <https://github.com/d3/d3-shape#curves>`__    |
|          | c    |               | function                                                |
|          | t    |               |                                                         |
|          | i    |               |                                                         |
|          | o    |               |                                                         |
|          | n    |               |                                                         |
+----------+------+---------------+---------------------------------------------------------+
| gr       | b    | f             | fill elements with a gradient instead of a solid color  |
| ad       | o    | a             |                                                         |
| ie       | o    | l             |                                                         |
| nt       | l    | s             |                                                         |
|          | e    | e             |                                                         |
|          | a    |               |                                                         |
|          | n    |               |                                                         |
+----------+------+---------------+---------------------------------------------------------+
| ac       | o    | [             | elements to highlight                                   |
| ti       | b    | ]             |                                                         |
| ve       | j    |               |                                                         |
| En       | e    |               |                                                         |
| tr       | c    |               |                                                         |
| ie       | t    |               |                                                         |
| s        | [    |               |                                                         |
|          | ]    |               |                                                         |
+----------+------+---------------+---------------------------------------------------------+
| to       | b    | f             | show or hide the tooltip                                |
| ol       | o    | a             |                                                         |
| ti       | o    | l             |                                                         |
| pD       | l    | s             |                                                         |
| is       | e    | e             |                                                         |
| ab       | a    |               |                                                         |
| le       | n    |               |                                                         |
| d        |      |               |                                                         |
+----------+------+---------------+---------------------------------------------------------+
| to       | T    |               | a custom ng-template to be displayed inside the tooltip |
| ol       | e    |               | when hovering a single point                            |
| ti       | m    |               |                                                         |
| pT       | p    |               |                                                         |
| em       | l    |               |                                                         |
| pl       | a    |               |                                                         |
| at       | t    |               |                                                         |
| e        | e    |               |                                                         |
|          | R    |               |                                                         |
|          | e    |               |                                                         |
|          | f    |               |                                                         |
+----------+------+---------------+---------------------------------------------------------+
| se       | T    |               | a custom ng-template to be displayed inside the tooltip |
| ri       | e    |               | when hovering series                                    |
| es       | m    |               |                                                         |
| To       | p    |               |                                                         |
| ol       | l    |               |                                                         |
| ti       | a    |               |                                                         |
| pT       | t    |               |                                                         |
| em       | e    |               |                                                         |
| pl       | R    |               |                                                         |
| at       | e    |               |                                                         |
| e        | f    |               |                                                         |
+----------+------+---------------+---------------------------------------------------------+
| re       | o    |               | an array of reference lines to be shown behind the      |
| fe       | b    |               | chart. Every reference line should be of format {name,  |
| re       | j    |               | value}                                                  |
| nc       | e    |               |                                                         |
| eL       | c    |               |                                                         |
| in       | t    |               |                                                         |
| es       | [    |               |                                                         |
|          | ]    |               |                                                         |
+----------+------+---------------+---------------------------------------------------------+
| sh       | b    | f             | show or hide the reference lines                        |
| ow       | o    | a             |                                                         |
| Re       | o    | l             |                                                         |
| fL       | l    | s             |                                                         |
| in       | e    | e             |                                                         |
| es       | a    |               |                                                         |
|          | n    |               |                                                         |
+----------+------+---------------+---------------------------------------------------------+
| sh       | b    | t             | show or hide the reference line labels                  |
| ow       | o    | r             |                                                         |
| Re       | o    | u             |                                                         |
| fL       | l    | e             |                                                         |
| ab       | e    |               |                                                         |
| el       | a    |               |                                                         |
| s        | n    |               |                                                         |
+----------+------+---------------+---------------------------------------------------------+
| xS       | a    |               | the minimum value of the x axis (if the x scale is      |
| ca       | n    |               | linear or time)                                         |
| le       | y    |               |                                                         |
| Mi       |      |               |                                                         |
| n        |      |               |                                                         |
+----------+------+---------------+---------------------------------------------------------+
| xS       | a    |               | the maximum value of the x axis (if the x scale is      |
| ca       | n    |               | linear or time)                                         |
| le       | y    |               |                                                         |
| Ma       |      |               |                                                         |
| x        |      |               |                                                         |
+----------+------+---------------+---------------------------------------------------------+
| yS       | n    |               | the minimum value of the y axis                         |
| ca       | u    |               |                                                         |
| le       | m    |               |                                                         |
| Mi       | b    |               |                                                         |
| n        | e    |               |                                                         |
|          | r    |               |                                                         |
+----------+------+---------------+---------------------------------------------------------+
| yS       | n    |               | the maximum value of the y axis                         |
| ca       | u    |               |                                                         |
| le       | m    |               |                                                         |
| Ma       | b    |               |                                                         |
| x        | e    |               |                                                         |
|          | r    |               |                                                         |
+----------+------+---------------+---------------------------------------------------------+

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

Regular line charts
~~~~~~~~~~~~~~~~~~~

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

Line charts indicating the range of the data
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

The data format is multi series. Plus, the minimum and the maximum value
of each data point are provided. For instance, you can use these values
to show the error margin of your data. Another use case are cumulated
data. The central line show the average values. The range shows
indicates the distribution of the data.

.. code:: text

   [
     {
       "name": "Germany",
       "series": [
         {
           "name": "2010",
           "value": 7300000,
           "min": 7000000,
           "max": 7600000
         },
         {
           "name": "2011",
           "value": 8940000,
           "min": 8840000,
           "max": 9300000
         }
       ]
     },

     {
       "name": "USA",
       "series": [
         {
           "name": "2010",
           "value": 7870000,
           "min": 7800000,
           "max": 7950000
         },
         {
           "name": "2011",
           "value": 8270000,
           "min": 8170000,
           "max": 8300000
         }
       ]
     }
   ]
