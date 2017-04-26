Title: 2017Springcd課程 第八週
Date: 2017-01-08 11:00
Category: Course
Tags: syllabus, week8
Slug: 2017 Week8
Author: 40423115

<!-- PELICAN_END_SUMMARY -->

1.Fossil Server 實習查驗

2.四連桿機構協同 Trace Point 查驗

3.Fourbar Walker OnShape 零件協同繪圖與組立查驗

4.分組協同零件展示

<!-- PELICAN_END_SUMMARY -->

##(一) Fossil Server 實習查驗

<a href="https://mde2a2.kmol.info/midterm/ag4/index">AG4期中考報告 fossil </a>

##(二) 四連桿機構協同 Trace Point 查驗
<a href="https://40423106.github.io/2016fallcadp_hw/blog/qi-zhong-bao-gao.html">40423106_四連桿機構協同 Trace Point 查驗</a>

<a href="https://40423107.github.io/2016fallcadp_hw/blog/40423107W9.html">40423107_四連桿機構協同 Trace Point 查驗</a>

<a href="https://40423108.github.io/2017springcd_hw/blog/xie-tong-chan-pin-she-ji-shi-xi-qi-zhong-si-lian-gan-ji-gou-xie-tong-trace-point-cha-yan.html">40423108_四連桿機構協同 Trace Point 查驗</a>
 

<a href="https://40423125.github.io/2016fallcadp_hw/blog/40423125_si-lian-gan-ji-gou-xie-tong-trace-point-cha-yan.html">40423125_四連桿機構協同 Trace Point 查驗</a>


<a href="https://40423139.github.io/2016fallcadp_hw/blog/40423139_si-lian-gan-ji-gou-xie-tong-trace-point-cha-yan.html">40423139_四連桿機構協同 Trace Point 查驗</a>


<a href="https://40423140.github.io/2016fallcadp_hw/blog/40423140_si-lian-gan-ji-gou-xie-tong-trace-point-cha-yan.html">40423140_四連桿機構協同 Trace Point 查驗</a>



##(三) Fourbar Walker OnShape 零件協同繪圖與組立查驗

利用SolveSpace畫Fourbar Walker影片

<iframe width="560" height="315" src="https://www.youtube.com/embed/d-Y2jmny8po" frameborder="0" allowfullscreen></iframe>

利用SolveSpace畫Fourbar Walker圖片

<a href="http://imgur.com/TTQqLPs"><img src="http://i.imgur.com/TTQqLPs.png" title="source: imgur.com" /></a>

利用OnShape組立Fourbar Walker影片

<iframe width="560" height="315" src="https://www.youtube.com/embed/8--yiyBAFHs" frameborder="0" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/1cA8xZVvv_0" frameborder="0" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/Cv6Anh-ri1Y" frameborder="0" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/t8nVrVXbA6Y" frameborder="0" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/ISpzreFlxv0" frameborder="0" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/NFv_6XOkOZE" frameborder="0" allowfullscreen></iframe>
##(四) 分組協同零件展示

<link href="./../work/madeleine/src/css/Madeleine.css" rel="stylesheet">
<script src="./../work/madeleine/src/stats.js"></script>
<script src="./../work/madeleine/src/detector.js"></script>
<script src="./../work/madeleine/src/three.min.js"></script>
<script src="./../work/madeleine/src/Madeleine.js"></script>

<div id="target" class="madeleine"></div>

<script>
window.onload = function(){
    var madeleine = new Madeleine({
      target: 'target', // target div id
      data: './../data/40423125.stl', // data path
      path: './../work/madeleine/src/' // path to source directory from current html file
    });
}; 
</script>

<script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r68/three.min.js"
></script>
<script src="https://rawgit.com/mrdoob/three.js/master/examples/js/controls/TrackballControls.js"
></script>
<script src="./../w9/loader.js"></script>
<script src="./../w9/stl.js"></script>
<div>
select stl file: <input type="file" id="file" /> or drop stl file
</div>
<div id="view"></div>
