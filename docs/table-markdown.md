---
layout: default
title: Markdown Table
datatable: true
---
<style>
  tr:nth-child(even) {
    background-color: #D6EEE;
  }
</style>

# Markdown Table Page

| Priority apples | Second priority | Third priority |
|-------|--------|---------|
| ambrosia | gala | red delicious |
| pink lady | jazz | macintosh |
| honeycrisp | granny smith | fuji |

<p></p>
<p></p>
<h2>An HTML Table</h2>

<table>
<colgroup>
<col width="30%" />
<col width="70%" />
</colgroup>
<thead>
<tr class="header">
<th>Field</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td markdown="span">First column **fields**</td>
<td markdown="span">Some descriptive text. This is a markdown link to [Google](http://google.com). Or see [some link][mydoc_tags].</td>
</tr>
<tr>
<td markdown="span">Second column **fields**</td>
<td markdown="span">Some more descriptive text.
</td>
</tr>
</tbody>
</table>

<h2>A Simple Invoice</h2>

<table style="width:50%">
  <tr>
    <th>Invoice</th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
  </tr>
  <tr>
    <td>Invoice Number</td>
    <td>20240923-1</td>
    <td></td>
    <td></td>
    <td>Vendor:Vendor Inc.</td>
  </tr>
  <tr>
    <td>Invoice Date:</td>
    <td>09/23/2023</td>
    <td></td>
    <td></td>
    <td>Buyer: Library</td>
  </tr>
  <tr>
    <td>Line Number</td>
    <td>Title</td>
    <td>Order Number</td>
    <td>Quantity</td>
    <td>Price</td>
  </tr>
  <tr>
    <td>1</td>
    <td>Washington D. C.</td>
    <td>POL-178651</td>
    <td>1</td>
    <td>$20.00</td>
  </tr>
  <tr>
    <td>2</td>
    <td>The judgment of Paris</td>
    <td>POL-178652</td>
    <td>1</td>
    <td>$20.00</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td></td>
    <td>Shipping:</td>
    <td>$5.00</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td></td>
    <td>Total:</td>
    <td>$35.00</td>
  </tr>
</table>

<h2>This is markdown with liquid styling</h2>

<table>
  <thead>
    <tr>
      <th>Column 1</th>
      <th>Column 2</th>
    </tr>
  </thead>
  <tbody>

      <tr style="background-color: 'white';">
        <td>Value 1</td>
        <td>Value 2</td>
      </tr>

      <tr style="background-color: '#f0f0f0';">
        <td>Value 3</td>
        <td>Value 4</td>
      </tr>

      <tr style="background-color: 'white';">
        <td>Value 5</td>
        <td>Value 6</td>
      </tr>
      
      <tr style="background-color: '#f0f0f0';">
        <td>Value 7</td>
        <td>Value 8</td>
      </tr>

  </tbody>
</table>

