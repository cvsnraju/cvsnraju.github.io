---
layout: post
title:  "Visualizations based on D3.js"
author: venkatc
date:   2018-01-28
tags:  [Blogging, Test, Post, Checking]
time: 2 Min
---


<!doc
<html>
<head>
   <script src="scripts/d3/d3.v4.min.js"></script>
</head>
<body>


    
<script>
d3.csv("", function(data) {
    for (var i = 0; i < data.length; i++) {
        console.log(data[i].Name);
        console.log(data[i].Age);
    }
});
</script>


</body>
</html>
