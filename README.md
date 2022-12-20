Readme
================

## Purpose

Collect soil quality data and aggregate up to NUTS2 level to join to
Rosés-Wolf database on regional GDP

## Download data

You can download the data in excel format at [this
link](data/soil_suitability.xlsx)

It looks like this:

<div id="qbasgzimwk" style="overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
  <style>html {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Helvetica Neue', 'Fira Sans', 'Droid Sans', Arial, sans-serif;
}

#qbasgzimwk .gt_table {
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

#qbasgzimwk .gt_heading {
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

#qbasgzimwk .gt_title {
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

#qbasgzimwk .gt_subtitle {
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

#qbasgzimwk .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#qbasgzimwk .gt_col_headings {
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

#qbasgzimwk .gt_col_heading {
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

#qbasgzimwk .gt_column_spanner_outer {
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

#qbasgzimwk .gt_column_spanner_outer:first-child {
  padding-left: 0;
}

#qbasgzimwk .gt_column_spanner_outer:last-child {
  padding-right: 0;
}

#qbasgzimwk .gt_column_spanner {
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

#qbasgzimwk .gt_group_heading {
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
}

#qbasgzimwk .gt_empty_group_heading {
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

#qbasgzimwk .gt_from_md > :first-child {
  margin-top: 0;
}

#qbasgzimwk .gt_from_md > :last-child {
  margin-bottom: 0;
}

#qbasgzimwk .gt_row {
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

#qbasgzimwk .gt_stub {
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

#qbasgzimwk .gt_stub_row_group {
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

#qbasgzimwk .gt_row_group_first td {
  border-top-width: 2px;
}

#qbasgzimwk .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#qbasgzimwk .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #D3D3D3;
}

#qbasgzimwk .gt_first_summary_row.thick {
  border-top-width: 2px;
}

#qbasgzimwk .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#qbasgzimwk .gt_grand_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#qbasgzimwk .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #D3D3D3;
}

#qbasgzimwk .gt_striped {
  background-color: rgba(128, 128, 128, 0.05);
}

#qbasgzimwk .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#qbasgzimwk .gt_footnotes {
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

#qbasgzimwk .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-left: 4px;
  padding-right: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#qbasgzimwk .gt_sourcenotes {
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

#qbasgzimwk .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#qbasgzimwk .gt_left {
  text-align: left;
}

#qbasgzimwk .gt_center {
  text-align: center;
}

#qbasgzimwk .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}

#qbasgzimwk .gt_font_normal {
  font-weight: normal;
}

#qbasgzimwk .gt_font_bold {
  font-weight: bold;
}

#qbasgzimwk .gt_font_italic {
  font-style: italic;
}

#qbasgzimwk .gt_super {
  font-size: 65%;
}

#qbasgzimwk .gt_footnote_marks {
  font-style: italic;
  font-weight: normal;
  font-size: 75%;
  vertical-align: 0.4em;
}

#qbasgzimwk .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}

#qbasgzimwk .gt_indent_1 {
  text-indent: 5px;
}

#qbasgzimwk .gt_indent_2 {
  text-indent: 10px;
}

#qbasgzimwk .gt_indent_3 {
  text-indent: 15px;
}

#qbasgzimwk .gt_indent_4 {
  text-indent: 20px;
}

#qbasgzimwk .gt_indent_5 {
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
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col">id</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_left" rowspan="1" colspan="1" scope="col">nuts</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_left" rowspan="1" colspan="1" scope="col">region</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_left" rowspan="1" colspan="1" scope="col">country</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col">suitability_class_mean</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col">suitability_class_max</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" scope="col">suitability_class_min</th>
    </tr>
  </thead>
  <tbody class="gt_table_body">
    <tr><td class="gt_row gt_right">1</td>
<td class="gt_row gt_left">AT11</td>
<td class="gt_row gt_left">Burgenland</td>
<td class="gt_row gt_left">Austria</td>
<td class="gt_row gt_center">3.957746</td>
<td class="gt_row gt_center">10</td>
<td class="gt_row gt_center">2</td></tr>
    <tr><td class="gt_row gt_right">2</td>
<td class="gt_row gt_left">AT12+AT13</td>
<td class="gt_row gt_left">Lower Austria</td>
<td class="gt_row gt_left">Austria</td>
<td class="gt_row gt_center">4.123167</td>
<td class="gt_row gt_center">8</td>
<td class="gt_row gt_center">2</td></tr>
    <tr><td class="gt_row gt_right">3</td>
<td class="gt_row gt_left">AT21</td>
<td class="gt_row gt_left">Carinthia</td>
<td class="gt_row gt_left">Austria</td>
<td class="gt_row gt_center">6.762500</td>
<td class="gt_row gt_center">9</td>
<td class="gt_row gt_center">2</td></tr>
    <tr><td class="gt_row gt_right">4</td>
<td class="gt_row gt_left">AT22</td>
<td class="gt_row gt_left">Styria</td>
<td class="gt_row gt_left">Austria</td>
<td class="gt_row gt_center">6.494774</td>
<td class="gt_row gt_center">9</td>
<td class="gt_row gt_center">2</td></tr>
    <tr><td class="gt_row gt_right">5</td>
<td class="gt_row gt_left">AT31</td>
<td class="gt_row gt_left">Upper Austria</td>
<td class="gt_row gt_left">Austria</td>
<td class="gt_row gt_center">4.587379</td>
<td class="gt_row gt_center">9</td>
<td class="gt_row gt_center">2</td></tr>
    <tr><td class="gt_row gt_right">6</td>
<td class="gt_row gt_left">AT32</td>
<td class="gt_row gt_left">Salzburg</td>
<td class="gt_row gt_left">Austria</td>
<td class="gt_row gt_center">7.786885</td>
<td class="gt_row gt_center">9</td>
<td class="gt_row gt_center">2</td></tr>
    <tr><td class="gt_row gt_right">7</td>
<td class="gt_row gt_left">AT33</td>
<td class="gt_row gt_left">Tyrol</td>
<td class="gt_row gt_left">Austria</td>
<td class="gt_row gt_center">8.324074</td>
<td class="gt_row gt_center">9</td>
<td class="gt_row gt_center">5</td></tr>
    <tr><td class="gt_row gt_right">8</td>
<td class="gt_row gt_left">AT34</td>
<td class="gt_row gt_left">Vorarlberg</td>
<td class="gt_row gt_left">Austria</td>
<td class="gt_row gt_center">7.837209</td>
<td class="gt_row gt_center">9</td>
<td class="gt_row gt_center">5</td></tr>
    <tr><td class="gt_row gt_right">9</td>
<td class="gt_row gt_left">BE10+BE24+BE31</td>
<td class="gt_row gt_left">Brabant</td>
<td class="gt_row gt_left">Belgium</td>
<td class="gt_row gt_center">3.586207</td>
<td class="gt_row gt_center">6</td>
<td class="gt_row gt_center">2</td></tr>
    <tr><td class="gt_row gt_right">10</td>
<td class="gt_row gt_left">BE21</td>
<td class="gt_row gt_left">Antwerp</td>
<td class="gt_row gt_left">Belgium</td>
<td class="gt_row gt_center">5.074074</td>
<td class="gt_row gt_center">8</td>
<td class="gt_row gt_center">4</td></tr>
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

<div id="jknymxclgl" style="overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
  <style>html {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Helvetica Neue', 'Fira Sans', 'Droid Sans', Arial, sans-serif;
}

#jknymxclgl .gt_table {
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

#jknymxclgl .gt_heading {
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

#jknymxclgl .gt_title {
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

#jknymxclgl .gt_subtitle {
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

#jknymxclgl .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#jknymxclgl .gt_col_headings {
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

#jknymxclgl .gt_col_heading {
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

#jknymxclgl .gt_column_spanner_outer {
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

#jknymxclgl .gt_column_spanner_outer:first-child {
  padding-left: 0;
}

#jknymxclgl .gt_column_spanner_outer:last-child {
  padding-right: 0;
}

#jknymxclgl .gt_column_spanner {
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

#jknymxclgl .gt_group_heading {
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
}

#jknymxclgl .gt_empty_group_heading {
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

#jknymxclgl .gt_from_md > :first-child {
  margin-top: 0;
}

#jknymxclgl .gt_from_md > :last-child {
  margin-bottom: 0;
}

#jknymxclgl .gt_row {
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

#jknymxclgl .gt_stub {
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

#jknymxclgl .gt_stub_row_group {
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

#jknymxclgl .gt_row_group_first td {
  border-top-width: 2px;
}

#jknymxclgl .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#jknymxclgl .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #D3D3D3;
}

#jknymxclgl .gt_first_summary_row.thick {
  border-top-width: 2px;
}

#jknymxclgl .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#jknymxclgl .gt_grand_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#jknymxclgl .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #D3D3D3;
}

#jknymxclgl .gt_striped {
  background-color: rgba(128, 128, 128, 0.05);
}

#jknymxclgl .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#jknymxclgl .gt_footnotes {
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

#jknymxclgl .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-left: 4px;
  padding-right: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#jknymxclgl .gt_sourcenotes {
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

#jknymxclgl .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#jknymxclgl .gt_left {
  text-align: left;
}

#jknymxclgl .gt_center {
  text-align: center;
}

#jknymxclgl .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}

#jknymxclgl .gt_font_normal {
  font-weight: normal;
}

#jknymxclgl .gt_font_bold {
  font-weight: bold;
}

#jknymxclgl .gt_font_italic {
  font-style: italic;
}

#jknymxclgl .gt_super {
  font-size: 65%;
}

#jknymxclgl .gt_footnote_marks {
  font-style: italic;
  font-weight: normal;
  font-size: 75%;
  vertical-align: 0.4em;
}

#jknymxclgl .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}

#jknymxclgl .gt_indent_1 {
  text-indent: 5px;
}

#jknymxclgl .gt_indent_2 {
  text-indent: 10px;
}

#jknymxclgl .gt_indent_3 {
  text-indent: 15px;
}

#jknymxclgl .gt_indent_4 {
  text-indent: 20px;
}

#jknymxclgl .gt_indent_5 {
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
      <th class="gt_col_heading gt_columns_bottom_border gt_left" rowspan="1" colspan="1" scope="col">Field</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_left" rowspan="1" colspan="1" scope="col">Value</th>
    </tr>
  </thead>
  <tbody class="gt_table_body">
    <tr><td class="gt_row gt_left">Theme</td>
<td class="gt_row gt_left">Suitability and Attainable Yield</td></tr>
    <tr><td class="gt_row gt_left">Sub-theme</td>
<td class="gt_row gt_left">Suitability Class</td></tr>
    <tr><td class="gt_row gt_left">Variable name</td>
<td class="gt_row gt_left">Crop suitability index in classes</td></tr>
    <tr><td class="gt_row gt_left">Time period</td>
<td class="gt_row gt_left">1981-2010</td></tr>
    <tr><td class="gt_row gt_left">Climate data source</td>
<td class="gt_row gt_left">CRUTS32</td></tr>
    <tr><td class="gt_row gt_left">Crop</td>
<td class="gt_row gt_left">Wheat</td></tr>
    <tr><td class="gt_row gt_left">Water supply</td>
<td class="gt_row gt_left">Rainfed</td></tr>
    <tr><td class="gt_row gt_left">Input level</td>
<td class="gt_row gt_left">Low</td></tr>
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

<div id="bbrjwslbzz" style="overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>html {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Helvetica Neue', 'Fira Sans', 'Droid Sans', Arial, sans-serif;
}

#bbrjwslbzz .gt_table {
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

#bbrjwslbzz .gt_heading {
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

#bbrjwslbzz .gt_title {
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

#bbrjwslbzz .gt_subtitle {
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

#bbrjwslbzz .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#bbrjwslbzz .gt_col_headings {
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

#bbrjwslbzz .gt_col_heading {
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

#bbrjwslbzz .gt_column_spanner_outer {
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

#bbrjwslbzz .gt_column_spanner_outer:first-child {
  padding-left: 0;
}

#bbrjwslbzz .gt_column_spanner_outer:last-child {
  padding-right: 0;
}

#bbrjwslbzz .gt_column_spanner {
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

#bbrjwslbzz .gt_group_heading {
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
}

#bbrjwslbzz .gt_empty_group_heading {
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

#bbrjwslbzz .gt_from_md > :first-child {
  margin-top: 0;
}

#bbrjwslbzz .gt_from_md > :last-child {
  margin-bottom: 0;
}

#bbrjwslbzz .gt_row {
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

#bbrjwslbzz .gt_stub {
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

#bbrjwslbzz .gt_stub_row_group {
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

#bbrjwslbzz .gt_row_group_first td {
  border-top-width: 2px;
}

#bbrjwslbzz .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#bbrjwslbzz .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #D3D3D3;
}

#bbrjwslbzz .gt_first_summary_row.thick {
  border-top-width: 2px;
}

#bbrjwslbzz .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#bbrjwslbzz .gt_grand_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#bbrjwslbzz .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #D3D3D3;
}

#bbrjwslbzz .gt_striped {
  background-color: rgba(128, 128, 128, 0.05);
}

#bbrjwslbzz .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#bbrjwslbzz .gt_footnotes {
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

#bbrjwslbzz .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-left: 4px;
  padding-right: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#bbrjwslbzz .gt_sourcenotes {
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

#bbrjwslbzz .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#bbrjwslbzz .gt_left {
  text-align: left;
}

#bbrjwslbzz .gt_center {
  text-align: center;
}

#bbrjwslbzz .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}

#bbrjwslbzz .gt_font_normal {
  font-weight: normal;
}

#bbrjwslbzz .gt_font_bold {
  font-weight: bold;
}

#bbrjwslbzz .gt_font_italic {
  font-style: italic;
}

#bbrjwslbzz .gt_super {
  font-size: 65%;
}

#bbrjwslbzz .gt_footnote_marks {
  font-style: italic;
  font-weight: normal;
  font-size: 75%;
  vertical-align: 0.4em;
}

#bbrjwslbzz .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}

#bbrjwslbzz .gt_indent_1 {
  text-indent: 5px;
}

#bbrjwslbzz .gt_indent_2 {
  text-indent: 10px;
}

#bbrjwslbzz .gt_indent_3 {
  text-indent: 15px;
}

#bbrjwslbzz .gt_indent_4 {
  text-indent: 20px;
}

#bbrjwslbzz .gt_indent_5 {
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
      <th class="gt_col_heading gt_columns_bottom_border gt_left" rowspan="1" colspan="1" scope="col">NUTS2_regions</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_left" rowspan="1" colspan="1" scope="col">Aggregation</th>
    </tr>
  </thead>
  <tbody class="gt_table_body">
    <tr><td class="gt_row gt_left">AT12+AT13</td>
<td class="gt_row gt_left">AT123</td></tr>
    <tr><td class="gt_row gt_left">DE71+DE72</td>
<td class="gt_row gt_left">DE712</td></tr>
    <tr><td class="gt_row gt_left">DE91+DE92</td>
<td class="gt_row gt_left">DE912</td></tr>
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
| HU32      |               4.222222 |                     6 |                     2 |
| PL43      |               4.927757 |                     6 |                     3 |
| DEB3      |               4.390244 |                     6 |                     2 |
| PL62      |               3.974359 |                    10 |                     2 |
| SK03      |               4.871528 |                     9 |                     2 |
| FR82      |               5.393411 |                    10 |                     2 |
| FR24      |               3.678414 |                     6 |                     2 |
| FR83      |               5.773723 |                     8 |                     2 |
| SE33      |               8.569377 |                    10 |                     6 |
| ES70      |               6.765306 |                     9 |                     4 |

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
