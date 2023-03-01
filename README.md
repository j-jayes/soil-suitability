Readme
================

## Purpose

Collect soil quality data and aggregate up to NUTS2 level to join to
Rosés-Wolf database on regional GDP. We do this both for NUTS2 and NUTS3
(for Sweden and Spain).

## Download data

You can download the NUTS2 data in excel format at [this
link](data/soil_suitability.xlsx)

You can download the NUTS3 data in excel format at [this
link](data/soil_suitability_nuts_3.csv)

You can download the NUTS3 data for Spain and Sweden in excel format at
[this link](data/soil_suitability_nuts_3_SE_ES.csv)

It looks like this:

<div id="rnpqpmnhzk" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
  <style>html {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Helvetica Neue', 'Fira Sans', 'Droid Sans', Arial, sans-serif;
}

#rnpqpmnhzk .gt_table {
  display: table;
  border-collapse: collapse;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #A8A8A8;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #A8A8A8;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}

#rnpqpmnhzk .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#rnpqpmnhzk .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}

#rnpqpmnhzk .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}

#rnpqpmnhzk .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 0;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}

#rnpqpmnhzk .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#rnpqpmnhzk .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#rnpqpmnhzk .gt_col_heading {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}

#rnpqpmnhzk .gt_column_spanner_outer {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}

#rnpqpmnhzk .gt_column_spanner_outer:first-child {
  padding-left: 0;
}

#rnpqpmnhzk .gt_column_spanner_outer:last-child {
  padding-right: 0;
}

#rnpqpmnhzk .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}

#rnpqpmnhzk .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}

#rnpqpmnhzk .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: middle;
}

#rnpqpmnhzk .gt_from_md > :first-child {
  margin-top: 0;
}

#rnpqpmnhzk .gt_from_md > :last-child {
  margin-bottom: 0;
}

#rnpqpmnhzk .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  overflow-x: hidden;
}

#rnpqpmnhzk .gt_stub {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
}

#rnpqpmnhzk .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}

#rnpqpmnhzk .gt_row_group_first td {
  border-top-width: 2px;
}

#rnpqpmnhzk .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#rnpqpmnhzk .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #D3D3D3;
}

#rnpqpmnhzk .gt_first_summary_row.thick {
  border-top-width: 2px;
}

#rnpqpmnhzk .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#rnpqpmnhzk .gt_grand_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#rnpqpmnhzk .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #D3D3D3;
}

#rnpqpmnhzk .gt_striped {
  background-color: rgba(128, 128, 128, 0.05);
}

#rnpqpmnhzk .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#rnpqpmnhzk .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#rnpqpmnhzk .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-left: 4px;
  padding-right: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#rnpqpmnhzk .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#rnpqpmnhzk .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#rnpqpmnhzk .gt_left {
  text-align: left;
}

#rnpqpmnhzk .gt_center {
  text-align: center;
}

#rnpqpmnhzk .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}

#rnpqpmnhzk .gt_font_normal {
  font-weight: normal;
}

#rnpqpmnhzk .gt_font_bold {
  font-weight: bold;
}

#rnpqpmnhzk .gt_font_italic {
  font-style: italic;
}

#rnpqpmnhzk .gt_super {
  font-size: 65%;
}

#rnpqpmnhzk .gt_footnote_marks {
  font-style: italic;
  font-weight: normal;
  font-size: 75%;
  vertical-align: 0.4em;
}

#rnpqpmnhzk .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}

#rnpqpmnhzk .gt_indent_1 {
  text-indent: 5px;
}

#rnpqpmnhzk .gt_indent_2 {
  text-indent: 10px;
}

#rnpqpmnhzk .gt_indent_3 {
  text-indent: 15px;
}

#rnpqpmnhzk .gt_indent_4 {
  text-indent: 20px;
}

#rnpqpmnhzk .gt_indent_5 {
  text-indent: 25px;
}
</style>
  <table class="gt_table">
  <thead class="gt_header">
    <tr>
      <td colspan="7" class="gt_heading gt_title gt_font_normal gt_bottom_border" style>Extract of soil quality data</td>
    </tr>
    
  </thead>
  <thead class="gt_col_headings">
    <tr>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="id">id</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_left" rowspan="1" colspan="1" scope="col" id="nuts">nuts</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_left" rowspan="1" colspan="1" scope="col" id="region">region</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_left" rowspan="1" colspan="1" scope="col" id="country">country</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="suitability_class_mean">suitability_class_mean</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="suitability_class_max">suitability_class_max</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col" id="suitability_class_min">suitability_class_min</th>
    </tr>
  </thead>
  <tbody class="gt_table_body">
    <tr><td headers="id" class="gt_row gt_right">1</td>
<td headers="nuts" class="gt_row gt_left">AT11</td>
<td headers="region" class="gt_row gt_left">Burgenland</td>
<td headers="country" class="gt_row gt_left">Austria</td>
<td headers="suitability_class_mean" class="gt_row gt_center">3.957746</td>
<td headers="suitability_class_max" class="gt_row gt_center">10</td>
<td headers="suitability_class_min" class="gt_row gt_center">2</td></tr>
    <tr><td headers="id" class="gt_row gt_right">2</td>
<td headers="nuts" class="gt_row gt_left">AT12+AT13</td>
<td headers="region" class="gt_row gt_left">Lower Austria</td>
<td headers="country" class="gt_row gt_left">Austria</td>
<td headers="suitability_class_mean" class="gt_row gt_center">4.123167</td>
<td headers="suitability_class_max" class="gt_row gt_center">8</td>
<td headers="suitability_class_min" class="gt_row gt_center">2</td></tr>
    <tr><td headers="id" class="gt_row gt_right">3</td>
<td headers="nuts" class="gt_row gt_left">AT21</td>
<td headers="region" class="gt_row gt_left">Carinthia</td>
<td headers="country" class="gt_row gt_left">Austria</td>
<td headers="suitability_class_mean" class="gt_row gt_center">6.762500</td>
<td headers="suitability_class_max" class="gt_row gt_center">9</td>
<td headers="suitability_class_min" class="gt_row gt_center">2</td></tr>
    <tr><td headers="id" class="gt_row gt_right">4</td>
<td headers="nuts" class="gt_row gt_left">AT22</td>
<td headers="region" class="gt_row gt_left">Styria</td>
<td headers="country" class="gt_row gt_left">Austria</td>
<td headers="suitability_class_mean" class="gt_row gt_center">6.494774</td>
<td headers="suitability_class_max" class="gt_row gt_center">9</td>
<td headers="suitability_class_min" class="gt_row gt_center">2</td></tr>
    <tr><td headers="id" class="gt_row gt_right">5</td>
<td headers="nuts" class="gt_row gt_left">AT31</td>
<td headers="region" class="gt_row gt_left">Upper Austria</td>
<td headers="country" class="gt_row gt_left">Austria</td>
<td headers="suitability_class_mean" class="gt_row gt_center">4.587379</td>
<td headers="suitability_class_max" class="gt_row gt_center">9</td>
<td headers="suitability_class_min" class="gt_row gt_center">2</td></tr>
    <tr><td headers="id" class="gt_row gt_right">6</td>
<td headers="nuts" class="gt_row gt_left">AT32</td>
<td headers="region" class="gt_row gt_left">Salzburg</td>
<td headers="country" class="gt_row gt_left">Austria</td>
<td headers="suitability_class_mean" class="gt_row gt_center">7.786885</td>
<td headers="suitability_class_max" class="gt_row gt_center">9</td>
<td headers="suitability_class_min" class="gt_row gt_center">2</td></tr>
    <tr><td headers="id" class="gt_row gt_right">7</td>
<td headers="nuts" class="gt_row gt_left">AT33</td>
<td headers="region" class="gt_row gt_left">Tyrol</td>
<td headers="country" class="gt_row gt_left">Austria</td>
<td headers="suitability_class_mean" class="gt_row gt_center">8.324074</td>
<td headers="suitability_class_max" class="gt_row gt_center">9</td>
<td headers="suitability_class_min" class="gt_row gt_center">5</td></tr>
    <tr><td headers="id" class="gt_row gt_right">8</td>
<td headers="nuts" class="gt_row gt_left">AT34</td>
<td headers="region" class="gt_row gt_left">Vorarlberg</td>
<td headers="country" class="gt_row gt_left">Austria</td>
<td headers="suitability_class_mean" class="gt_row gt_center">7.837209</td>
<td headers="suitability_class_max" class="gt_row gt_center">9</td>
<td headers="suitability_class_min" class="gt_row gt_center">5</td></tr>
    <tr><td headers="id" class="gt_row gt_right">9</td>
<td headers="nuts" class="gt_row gt_left">BE10+BE24+BE31</td>
<td headers="region" class="gt_row gt_left">Brabant</td>
<td headers="country" class="gt_row gt_left">Belgium</td>
<td headers="suitability_class_mean" class="gt_row gt_center">3.586207</td>
<td headers="suitability_class_max" class="gt_row gt_center">6</td>
<td headers="suitability_class_min" class="gt_row gt_center">2</td></tr>
    <tr><td headers="id" class="gt_row gt_right">10</td>
<td headers="nuts" class="gt_row gt_left">BE21</td>
<td headers="region" class="gt_row gt_left">Antwerp</td>
<td headers="country" class="gt_row gt_left">Belgium</td>
<td headers="suitability_class_mean" class="gt_row gt_center">5.074074</td>
<td headers="suitability_class_max" class="gt_row gt_center">8</td>
<td headers="suitability_class_min" class="gt_row gt_center">4</td></tr>
  </tbody>
  
  
</table>
</div>

### Data

Data on wheat suitability from FAO-GAEZ 4, available at the [following
link](https://gaez-data-portal-hqfao.hub.arcgis.com/pages/data-viewer).

The data viewer presents the data like so:

``` r
knitr::include_graphics("images/fao_interface.PNG")
```

![](images/fao_interface.PNG)

The specific extract information is:

<div id="trygzssuei" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
  <style>html {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Helvetica Neue', 'Fira Sans', 'Droid Sans', Arial, sans-serif;
}

#trygzssuei .gt_table {
  display: table;
  border-collapse: collapse;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #A8A8A8;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #A8A8A8;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}

#trygzssuei .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#trygzssuei .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}

#trygzssuei .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}

#trygzssuei .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 0;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}

#trygzssuei .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#trygzssuei .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#trygzssuei .gt_col_heading {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}

#trygzssuei .gt_column_spanner_outer {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}

#trygzssuei .gt_column_spanner_outer:first-child {
  padding-left: 0;
}

#trygzssuei .gt_column_spanner_outer:last-child {
  padding-right: 0;
}

#trygzssuei .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}

#trygzssuei .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}

#trygzssuei .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: middle;
}

#trygzssuei .gt_from_md > :first-child {
  margin-top: 0;
}

#trygzssuei .gt_from_md > :last-child {
  margin-bottom: 0;
}

#trygzssuei .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  overflow-x: hidden;
}

#trygzssuei .gt_stub {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
}

#trygzssuei .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}

#trygzssuei .gt_row_group_first td {
  border-top-width: 2px;
}

#trygzssuei .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#trygzssuei .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #D3D3D3;
}

#trygzssuei .gt_first_summary_row.thick {
  border-top-width: 2px;
}

#trygzssuei .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#trygzssuei .gt_grand_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#trygzssuei .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #D3D3D3;
}

#trygzssuei .gt_striped {
  background-color: rgba(128, 128, 128, 0.05);
}

#trygzssuei .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#trygzssuei .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#trygzssuei .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-left: 4px;
  padding-right: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#trygzssuei .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#trygzssuei .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#trygzssuei .gt_left {
  text-align: left;
}

#trygzssuei .gt_center {
  text-align: center;
}

#trygzssuei .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}

#trygzssuei .gt_font_normal {
  font-weight: normal;
}

#trygzssuei .gt_font_bold {
  font-weight: bold;
}

#trygzssuei .gt_font_italic {
  font-style: italic;
}

#trygzssuei .gt_super {
  font-size: 65%;
}

#trygzssuei .gt_footnote_marks {
  font-style: italic;
  font-weight: normal;
  font-size: 75%;
  vertical-align: 0.4em;
}

#trygzssuei .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}

#trygzssuei .gt_indent_1 {
  text-indent: 5px;
}

#trygzssuei .gt_indent_2 {
  text-indent: 10px;
}

#trygzssuei .gt_indent_3 {
  text-indent: 15px;
}

#trygzssuei .gt_indent_4 {
  text-indent: 20px;
}

#trygzssuei .gt_indent_5 {
  text-indent: 25px;
}
</style>
  <table class="gt_table">
  <thead class="gt_header">
    <tr>
      <td colspan="2" class="gt_heading gt_title gt_font_normal gt_bottom_border" style>FAO-GAEZ 4 metadata</td>
    </tr>
    
  </thead>
  <thead class="gt_col_headings">
    <tr>
      <th class="gt_col_heading gt_columns_bottom_border gt_left" rowspan="1" colspan="1" scope="col" id="Field">Field</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_left" rowspan="1" colspan="1" scope="col" id="Value">Value</th>
    </tr>
  </thead>
  <tbody class="gt_table_body">
    <tr><td headers="Field" class="gt_row gt_left">Theme</td>
<td headers="Value" class="gt_row gt_left">Suitability and Attainable Yield</td></tr>
    <tr><td headers="Field" class="gt_row gt_left">Sub-theme</td>
<td headers="Value" class="gt_row gt_left">Suitability Class</td></tr>
    <tr><td headers="Field" class="gt_row gt_left">Variable name</td>
<td headers="Value" class="gt_row gt_left">Crop suitability index in classes</td></tr>
    <tr><td headers="Field" class="gt_row gt_left">Time period</td>
<td headers="Value" class="gt_row gt_left">1981-2010</td></tr>
    <tr><td headers="Field" class="gt_row gt_left">Climate data source</td>
<td headers="Value" class="gt_row gt_left">CRUTS32</td></tr>
    <tr><td headers="Field" class="gt_row gt_left">Crop</td>
<td headers="Value" class="gt_row gt_left">Wheat</td></tr>
    <tr><td headers="Field" class="gt_row gt_left">Water supply</td>
<td headers="Value" class="gt_row gt_left">Rainfed</td></tr>
    <tr><td headers="Field" class="gt_row gt_left">Input level</td>
<td headers="Value" class="gt_row gt_left">Low</td></tr>
  </tbody>
  
  
</table>
</div>

It is in a raster format - where the earth is broken into tiles.

This is what it looks like on a map:

``` r
library(stars)

tif <- read_stars(here::here("data", "siLr_whe_class.tif"))

ggplot() +
  geom_stars(data = tif)
```

![](README_files/figure-commonmark/unnamed-chunk-4-1.png)

We want to aggregate this to the nuts2 levels used in the Rosés-Wolf
database on regional GDP.

### NUTS2 shapefile

The NUTS2 shapefiles are from
[Eurostat](https://ec.europa.eu/eurostat/web/gisco/geodata/reference-data/administrative-units-statistical-units/nuts)

We’re going to work in WGS84 for convenience (EPSG: 4326).

We now need to aggregate up the NUTS2 regions which are joined together
in the Rosés-Wolf database on regional GDP.

They are:

<div id="auoytwqjyv" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>html {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Helvetica Neue', 'Fira Sans', 'Droid Sans', Arial, sans-serif;
}

#auoytwqjyv .gt_table {
  display: table;
  border-collapse: collapse;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #A8A8A8;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #A8A8A8;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}

#auoytwqjyv .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#auoytwqjyv .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}

#auoytwqjyv .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}

#auoytwqjyv .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 0;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}

#auoytwqjyv .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#auoytwqjyv .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#auoytwqjyv .gt_col_heading {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}

#auoytwqjyv .gt_column_spanner_outer {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}

#auoytwqjyv .gt_column_spanner_outer:first-child {
  padding-left: 0;
}

#auoytwqjyv .gt_column_spanner_outer:last-child {
  padding-right: 0;
}

#auoytwqjyv .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}

#auoytwqjyv .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}

#auoytwqjyv .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: middle;
}

#auoytwqjyv .gt_from_md > :first-child {
  margin-top: 0;
}

#auoytwqjyv .gt_from_md > :last-child {
  margin-bottom: 0;
}

#auoytwqjyv .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  overflow-x: hidden;
}

#auoytwqjyv .gt_stub {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
}

#auoytwqjyv .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}

#auoytwqjyv .gt_row_group_first td {
  border-top-width: 2px;
}

#auoytwqjyv .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#auoytwqjyv .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #D3D3D3;
}

#auoytwqjyv .gt_first_summary_row.thick {
  border-top-width: 2px;
}

#auoytwqjyv .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#auoytwqjyv .gt_grand_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#auoytwqjyv .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #D3D3D3;
}

#auoytwqjyv .gt_striped {
  background-color: rgba(128, 128, 128, 0.05);
}

#auoytwqjyv .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#auoytwqjyv .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#auoytwqjyv .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-left: 4px;
  padding-right: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#auoytwqjyv .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#auoytwqjyv .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#auoytwqjyv .gt_left {
  text-align: left;
}

#auoytwqjyv .gt_center {
  text-align: center;
}

#auoytwqjyv .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}

#auoytwqjyv .gt_font_normal {
  font-weight: normal;
}

#auoytwqjyv .gt_font_bold {
  font-weight: bold;
}

#auoytwqjyv .gt_font_italic {
  font-style: italic;
}

#auoytwqjyv .gt_super {
  font-size: 65%;
}

#auoytwqjyv .gt_footnote_marks {
  font-style: italic;
  font-weight: normal;
  font-size: 75%;
  vertical-align: 0.4em;
}

#auoytwqjyv .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}

#auoytwqjyv .gt_indent_1 {
  text-indent: 5px;
}

#auoytwqjyv .gt_indent_2 {
  text-indent: 10px;
}

#auoytwqjyv .gt_indent_3 {
  text-indent: 15px;
}

#auoytwqjyv .gt_indent_4 {
  text-indent: 20px;
}

#auoytwqjyv .gt_indent_5 {
  text-indent: 25px;
}
</style>
<table class="gt_table">
  <thead class="gt_header">
    <tr>
      <td colspan="2" class="gt_heading gt_title gt_font_normal gt_bottom_border" style>Aggregations of NUTS2 regions</td>
    </tr>
    
  </thead>
  <thead class="gt_col_headings">
    <tr>
      <th class="gt_col_heading gt_columns_bottom_border gt_left" rowspan="1" colspan="1" scope="col" id="NUTS2_regions">NUTS2_regions</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_left" rowspan="1" colspan="1" scope="col" id="Aggregation">Aggregation</th>
    </tr>
  </thead>
  <tbody class="gt_table_body">
    <tr><td headers="NUTS2_regions" class="gt_row gt_left">AT12+AT13</td>
<td headers="Aggregation" class="gt_row gt_left">AT123</td></tr>
    <tr><td headers="NUTS2_regions" class="gt_row gt_left">DE71+DE72</td>
<td headers="Aggregation" class="gt_row gt_left">DE712</td></tr>
    <tr><td headers="NUTS2_regions" class="gt_row gt_left">DE91+DE92</td>
<td headers="Aggregation" class="gt_row gt_left">DE912</td></tr>
  </tbody>
  
  
</table>
</div>

The following chunk manipulates the shapefile to make it easier to work
with in a WGS84 projection.

``` r
library(sf)

# map <- read_sf(here::here("maps", "regions_nuts2.shp")) %>% janitor::clean_names()

# map_tbl <- map %>% as_tibble()

# map_tbl %>%
#   ggplot(aes(geometry = geometry)) +
#   geom_sf() +
#   coord_sf()

## Making the map files smaller
# library(rmapshaper)
# map_simple <- ms_simplify(map, keep = 0.1,
#                                 keep_shapes = FALSE)
# 
# map_tbl_simple <- map_simple %>% as_tibble()
# 
# map_tbl_simple %>% write_rds(here::here("maps", "NUTS2_simple.rds"))

map_simple <- read_rds(here::here("maps", "NUTS2_simple.rds")) %>% 
  st_as_sf()

map_simple <- map_simple %>% 
  st_transform(crs = 4326)
```

We want to crop to only Europe: this is what the raster file looks like
now.

``` r
# st_crop removes the raster region outside of europe
tif_bbox <- st_crop(tif, map_simple %>% st_bbox())

ggplot() +
  geom_stars(data = tif_bbox)
```

![](README_files/figure-commonmark/unnamed-chunk-7-1.png)

Now we want to calculate the averages within each polygon, along with
the min and max values within each polygon.

``` r
# devtools::install_github("michaeldorman/geobgu")
library(geobgu)

map_simple_avgs <-
  map_simple %>% mutate(
    suitability_class_mean = raster_extract(tif_bbox, map_simple, fun = mean, na.rm = TRUE),
    suitability_class_max = raster_extract(tif_bbox, map_simple, fun = max, na.rm = TRUE),
    suitability_class_min = raster_extract(tif_bbox, map_simple, fun = min, na.rm = TRUE)
  )
```

This is what the averaging procedure produces:

![](README_files/figure-commonmark/unnamed-chunk-9-1.png)

The distribution of minimum and maximum values is quite erratic. The
plot below arranges the NUTS2 regions from lowest mean of suitability
class to largest. The ribbon shows the

![](README_files/figure-commonmark/unnamed-chunk-10-1.png)

Here is an example of 10 random regions.

| nuts_code | suitability_class_mean | suitability_class_max | suitability_class_min |
|:----------|-----------------------:|----------------------:|----------------------:|
| DE22      |               3.648352 |                     6 |                     2 |
| FR43      |               3.652174 |                     7 |                     2 |
| ITF3      |               6.098592 |                     8 |                     3 |
| ITG2      |               6.119777 |                     8 |                     3 |
| DE23      |               4.765714 |                     6 |                     2 |
| LT00      |               3.755118 |                     6 |                     2 |
| TRC1      |               4.744493 |                    10 |                     2 |
| RO12      |               4.469565 |                     9 |                     2 |
| DE12      |               4.271186 |                     7 |                     2 |
| ES13      |               6.640449 |                     9 |                     2 |

### Join to Rosés-Wolf database on regional GDP

``` r
# read in data file
df <- haven::read_dta(here::here("data", "RosesWolf_Regional_Fahad.dta"))

# keep unique nuts codes
df <- df %>%
  distinct(id, nuts, region, country)

# change label of joined regions
map_simple_avgs <- map_simple_avgs %>%
  st_set_geometry(NULL) %>%
  mutate(nuts = case_when(
    nuts_code == "AT123" ~ "AT12+AT13",
    nuts_code == "DE712" ~ "DE71+DE72",
    nuts_code == "DE912" ~ "DE91+DE92",
    TRUE ~ nuts_code
  ))

# join together
df_out <- df %>%
  left_join(map_simple_avgs) %>%
  select(-nuts_code)

# df_out %>% 
#   write_rds(here::here("data", "soil_suitability.rds"))

# df_out %>% 
#   write.csv(here::here("data", "soil_suitability.csv"))
```

## NUTS3 shapefile

The NUTS3 shapefiles are from
[Eurostat](https://ec.europa.eu/eurostat/web/gisco/geodata/reference-data/administrative-units-statistical-units/nuts)

We’re going to work in WGS84 for convenience (EPSG: 4326).

We now need to aggregate up the NUTS3 regions which are joined together
in the Rosés-Wolf database on regional GDP for Sweden and Spain.

They are:

<div id="chhyauileu" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>html {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Helvetica Neue', 'Fira Sans', 'Droid Sans', Arial, sans-serif;
}

#chhyauileu .gt_table {
  display: table;
  border-collapse: collapse;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #A8A8A8;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #A8A8A8;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}

#chhyauileu .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#chhyauileu .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}

#chhyauileu .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}

#chhyauileu .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 0;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}

#chhyauileu .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#chhyauileu .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#chhyauileu .gt_col_heading {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}

#chhyauileu .gt_column_spanner_outer {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}

#chhyauileu .gt_column_spanner_outer:first-child {
  padding-left: 0;
}

#chhyauileu .gt_column_spanner_outer:last-child {
  padding-right: 0;
}

#chhyauileu .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}

#chhyauileu .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}

#chhyauileu .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: middle;
}

#chhyauileu .gt_from_md > :first-child {
  margin-top: 0;
}

#chhyauileu .gt_from_md > :last-child {
  margin-bottom: 0;
}

#chhyauileu .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  overflow-x: hidden;
}

#chhyauileu .gt_stub {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
}

#chhyauileu .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}

#chhyauileu .gt_row_group_first td {
  border-top-width: 2px;
}

#chhyauileu .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#chhyauileu .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #D3D3D3;
}

#chhyauileu .gt_first_summary_row.thick {
  border-top-width: 2px;
}

#chhyauileu .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#chhyauileu .gt_grand_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#chhyauileu .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #D3D3D3;
}

#chhyauileu .gt_striped {
  background-color: rgba(128, 128, 128, 0.05);
}

#chhyauileu .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#chhyauileu .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#chhyauileu .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-left: 4px;
  padding-right: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#chhyauileu .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#chhyauileu .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#chhyauileu .gt_left {
  text-align: left;
}

#chhyauileu .gt_center {
  text-align: center;
}

#chhyauileu .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}

#chhyauileu .gt_font_normal {
  font-weight: normal;
}

#chhyauileu .gt_font_bold {
  font-weight: bold;
}

#chhyauileu .gt_font_italic {
  font-style: italic;
}

#chhyauileu .gt_super {
  font-size: 65%;
}

#chhyauileu .gt_footnote_marks {
  font-style: italic;
  font-weight: normal;
  font-size: 75%;
  vertical-align: 0.4em;
}

#chhyauileu .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}

#chhyauileu .gt_indent_1 {
  text-indent: 5px;
}

#chhyauileu .gt_indent_2 {
  text-indent: 10px;
}

#chhyauileu .gt_indent_3 {
  text-indent: 15px;
}

#chhyauileu .gt_indent_4 {
  text-indent: 20px;
}

#chhyauileu .gt_indent_5 {
  text-indent: 25px;
}
</style>
<table class="gt_table">
  <thead class="gt_header">
    <tr>
      <td colspan="2" class="gt_heading gt_title gt_font_normal gt_bottom_border" style>Aggregations of NUTS2 regions</td>
    </tr>
    
  </thead>
  <thead class="gt_col_headings">
    <tr>
      <th class="gt_col_heading gt_columns_bottom_border gt_left" rowspan="1" colspan="1" scope="col" id="NUTS2_regions">NUTS2_regions</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_left" rowspan="1" colspan="1" scope="col" id="Aggregation">Aggregation</th>
    </tr>
  </thead>
  <tbody class="gt_table_body">
    <tr><td headers="NUTS2_regions" class="gt_row gt_left">AT12+AT13</td>
<td headers="Aggregation" class="gt_row gt_left">AT123</td></tr>
    <tr><td headers="NUTS2_regions" class="gt_row gt_left">DE71+DE72</td>
<td headers="Aggregation" class="gt_row gt_left">DE712</td></tr>
    <tr><td headers="NUTS2_regions" class="gt_row gt_left">DE91+DE92</td>
<td headers="Aggregation" class="gt_row gt_left">DE912</td></tr>
  </tbody>
  
  
</table>
</div>

The following chunk manipulates the shapefile to make it easier to work
with in a WGS84 projection.

``` r
library(sf)

map <- read_sf(here::here("maps", "NUTS_RG_01M_2021_4326.shp")) %>% janitor::clean_names()

map_tbl <- map %>% as_tibble()

map_tbl %>%
  ggplot(aes(geometry = geometry)) +
  geom_sf() +
  coord_sf()
```

![](README_files/figure-commonmark/unnamed-chunk-14-1.png)

``` r
# Making the map files smaller
library(rmapshaper)
map_simple <- ms_simplify(map, keep = 0.1,
                                keep_shapes = FALSE)

map_tbl_simple <- map_simple %>% as_tibble()

map_tbl_simple %>% write_rds(here::here("maps", "NUTS3_simple.rds"))

map_simple <- read_rds(here::here("maps", "NUTS3_simple.rds")) %>% 
  st_as_sf() %>% 
  filter(levl_code == 3)

map_simple <- map_simple %>% 
  st_transform(crs = 4326)
```

We want to crop to only Europe: this is what the raster file looks like
now.

``` r
# st_crop removes the raster region outside of europe
tif_bbox <- st_crop(tif, map_simple %>% st_bbox())

ggplot() +
  geom_stars(data = tif_bbox)
```

![](README_files/figure-commonmark/unnamed-chunk-15-1.png)

Now we want to calculate the averages within each polygon, along with
the min and max values within each polygon.

``` r
# devtools::install_github("michaeldorman/geobgu")
library(geobgu)

map_simple_avgs <-
  map_simple %>% mutate(
    suitability_class_mean = raster_extract(tif_bbox, map_simple, fun = mean, na.rm = TRUE),
    suitability_class_max = raster_extract(tif_bbox, map_simple, fun = max, na.rm = TRUE),
    suitability_class_min = raster_extract(tif_bbox, map_simple, fun = min, na.rm = TRUE)
  )

map_simple_avgs <- map_simple %>% 
  bind_cols(map_simple_avgs$suitability_class_mean %>% as_tibble() %>% rename(suitability_class_mean = V1)) %>% 
  bind_cols(map_simple_avgs$suitability_class_max %>% as_tibble() %>% rename(suitability_class_max = V1)) %>%
  bind_cols(map_simple_avgs$suitability_class_min %>% as_tibble() %>% rename(suitability_class_min = V1))
```

This is what the averaging procedure produces:

![](README_files/figure-commonmark/unnamed-chunk-17-1.png)

The distribution of minimum and maximum values is quite erratic. The
plot below arranges the NUTS2 regions from lowest mean of suitability
class to largest. The ribbon shows the

![](README_files/figure-commonmark/unnamed-chunk-18-1.png)

Here is an example of 10 random regions.

| nuts_id | levl_code | cntr_code | name_latn                           | nuts_name                           | mount_type | urbn_type | coast_type | fid   | suitability_class_mean | suitability_class_max | suitability_class_min |
|:--------|----------:|:----------|:------------------------------------|:------------------------------------|-----------:|----------:|-----------:|:------|-----------------------:|----------------------:|----------------------:|
| DE21A   |         3 | DE        | Erding                              | Erding                              |          4 |         3 |          3 | DE21A |               3.571429 |                     4 |                     3 |
| CH053   |         3 | CH        | Appenzell Ausserrhoden              | Appenzell Ausserrhoden              |          3 |         2 |          3 | CH053 |               5.250000 |                     6 |                     5 |
| DE146   |         3 | DE        | Biberach                            | Biberach                            |          4 |         3 |          3 | DE146 |               3.904762 |                     5 |                     3 |
| DEB3J   |         3 | DE        | Mainz-Bingen                        | Mainz-Bingen                        |          4 |         2 |          3 | DEB3J |               4.000000 |                     6 |                     2 |
| NL337   |         3 | NL        | Agglomeratie Leiden en Bollenstreek | Agglomeratie Leiden en Bollenstreek |          4 |         1 |          1 | NL337 |               5.666667 |                     6 |                     5 |
| DE946   |         3 | DE        | Ammerland                           | Ammerland                           |          4 |         2 |          2 | DE946 |               5.312500 |                     6 |                     4 |
| DEA52   |         3 | DE        | Dortmund, Kreisfreie Stadt          | Dortmund, Kreisfreie Stadt          |          4 |         1 |          3 | DEA52 |               5.800000 |                     7 |                     5 |
| NO0B1   |         3 | NO        | Jan Mayen                           | Jan Mayen                           |          3 |         3 |          1 | NO0B1 |               9.000000 |                     9 |                     9 |
| UKJ32   |         3 | UK        | Southampton                         | Southampton                         |          4 |         1 |          1 | UKJ32 |               5.800000 |                     7 |                     5 |
| UKE11   |         3 | UK        | Kingston upon Hull, City of         | Kingston upon Hull, City of         |          4 |         1 |          1 | UKE11 |               7.000000 |                     7 |                     7 |

``` r
map_simple_avgs %>%
  as_tibble() %>% 
  select(-geometry) %>% 
  janitor::clean_names() %>% 
  # filter(cntr_code %in% c("SE", "ES")) %>% 
  write_excel_csv2(here::here("data", "soil_suitability_nuts_3.csv"))

map_simple_avgs %>%
  as_tibble() %>% 
  select(-geometry) %>% 
  janitor::clean_names() %>% 
  filter(cntr_code %in% c("SE", "ES")) %>%
  write_excel_csv2(here::here("data", "soil_suitability_nuts_3_SE_ES.csv"))
```
