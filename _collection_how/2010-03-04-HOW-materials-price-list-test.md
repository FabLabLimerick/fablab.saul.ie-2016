---
published: false
title: "Material Price List TEST"
category: materials
slug: material-price-list-test
description: "This is a list of the materials we generally stock. You should check with us if you are unsure, but this should help you to make your own calculations based on your material expenses."
---

This is a list of the materials we generally stock. You should check with us if you are unsure, but this should help you to make your own calculations based on your material expenses.

 Material| Material             | Thickness (mm)| Size (mm)     | Total €  | Source
 --------| -----------          | ------------  | ------------- | -------- | ------
TIMBER | Birch Ply | 1.5 | 1.5x1500x1500 | 40.59 | IWP
 |  | 3 | 3x1500x1500 | 20.30 | IWP
 |  | 4 | 4x1220x2440 | 42.21 | IWP
 |  | 6 | 6x1220x2440 | 46.002 | IWP
 |  | 9 | 9x1220x2440 | 51.1434 | IWP
 |  | 12 | 12x1220x2440 | 55.47 | IWP
 |  | 18 | 18x1220x2440 | 60.89 | IWP
 | Marine Ply | 12 | 12x1220x2440 | 48.71 | IWP
 |  | 18 | 18x1220x2440 | 62.24 | IWP
 | Hardwood Faced Ply | 4 | 4.0x1220x2440 | 11.84 | IWP
 |  | 5.5 | 5.5x1220x2440 | 13.19 | IWP

<script type='text/javascript'>
  var myList = [
    { "name": "abc", "age": 50 },
    { "age": "25", "hobby": "swimming" },
    { "name": "xyz", "hobby": "programming" }
    ];

 // Builds the HTML Table out of myList.
 function buildHtmlTable(selector) {
   var columns = addAllColumnHeaders(myList, selector);

   for (var i = 0; i < myList.length; i++) {
     var row$ = $('<tr/>');
     for (var colIndex = 0; colIndex < columns.length; colIndex++) {
       var cellValue = myList[i][columns[colIndex]];
       if (cellValue == null) cellValue = "";
       row$.append($('<td/>').html(cellValue));
     }
     $(selector).append(row$);
   }
 }
</script>
