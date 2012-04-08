<!DOCTYPE html
    PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"
    "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" lang="en" xml:lang="en">
<head>
 <title>/trunk/CANDYDOC.txt - helix - dsource.org</title>
 <meta name="description" content="Open Source Development for the D Programming Language">
 <meta name="keywords" content="dsource, d programming, d programming language, subversion, trac">
 <link rel="start" href="/projects/helix/wiki" /><link rel="search" href="/projects/helix/search" /><link rel="help" href="/projects/helix/wiki/TracGuide" /><link rel="stylesheet" href="/projects/helix/chrome/common/css/trac.css" type="text/css" /><link rel="stylesheet" href="/projects/helix/chrome/common/css/dsource.css" type="text/css" /><link rel="stylesheet" href="/projects/helix/chrome/common/css/code.css" type="text/css" /><link rel="stylesheet" href="/projects/helix/chrome/common/css/browser.css" type="text/css" /><link rel="stylesheet" href="/projects/helix/pygments/trac.css" /><link rel="icon" href="/projects/helix/chrome/common/dsource.ico" type="image/x-icon" /><link rel="shortcut icon" href="/projects/helix/chrome/common/dsource.ico" type="image/x-icon" /><link rel="up" href="/projects/helix/browser/trunk" title="Parent directory" /><link rel="alternate" href="/projects/helix/browser/trunk/CANDYDOC.txt?format=txt" title="Plain Text" type="text/plain" /><link rel="alternate" href="/projects/helix/browser/trunk/CANDYDOC.txt?format=raw" title="Original Format" type="text/plain; charset=iso-8859-15" />
 <style type="text/css">
</style>
 <script type="text/javascript" src="/projects/helix/chrome/common/js/trac.js"></script>
 <script type="text/javascript" src="/projects/helix/chrome/common/js/dsource.js"></script>
</head>
<body onload="initNav();">


<div id="container">
 
 <div id="siteheader">
  <div id="left">
   <div id="logo"><img src="/chrome/dsource/img/dsource-logo.gif" /></div>
   <div id="title">dsource.org</div>
   <div id="tag">Open Source Development for<br />
                  the D Programming Language</div>
  </div>
 
  <div id="right">
   <ul>
    <li><a href="/">Home</a></li>
    <li><a id="current" href="/projects/">Projects</a></li>
    <li><a href="/forums/"><span>Forums</span></a></li>
    <li><a href="/projects/tutorials/wiki"><span>Tutorials</span></a></li>
    <li><a href="/site/"><span>Site</span></a></li>
   </ul>
  </div>
 </div>
 
 <div id="mainpage">
 
  <div id="banner">


<div id="header"><h1><a href="http://www.dsource.org/">helix</a></h1></div>

  </div>



  <div id="nav_all">
   <div id="mainnav" class="nav"><ul><li class="first"><a accesskey="1" href="/projects/helix/wiki">Wiki</a></li><li><a accesskey="2" href="/projects/helix/timeline">Timeline</a></li><li><a accesskey="3" href="/projects/helix/roadmap">Roadmap</a></li><li class="active"><a href="/projects/helix/browser">Browse Source</a></li><li><a href="/projects/helix/report">View Tickets</a></li><li class="last"><a accesskey="4" href="/projects/helix/search">Search</a></li></ul></div>
   <div id="metanav" class="nav"><ul><li class="first"><a href="/forums/login.php?redirect=../projects/helix/browser/trunk/CANDYDOC.txt">Login</a></li><li><a accesskey="6" href="/projects/helix/wiki/TracGuide">Help/Guide</a></li><li class="last"><a href="/projects/helix/about">About Trac</a></li></ul></div>
   <div id="searchnav">
   <form id="search" action="/projects/helix/search" method="get">
    <div>
     <label for="proj-search">Search:</label>
     <input type="text" id="proj-search" name="q" size="10" accesskey="f" value="" />
     <input type="submit" value="Search" />
     <input type="hidden" name="wiki" value="on" />
     <input type="hidden" name="changeset" value="on" />
     <input type="hidden" name="ticket" value="on" />
    </div>
   </form>
   </div>
  </div>

  <div id="main">




<div id="ctxtnav" class="nav">
 <ul>
  <li class="first"><a href="/projects/helix/changeset/5/trunk/CANDYDOC.txt">
   Last Change</a></li>
  <li class="last"><a href="/projects/helix/log/trunk/CANDYDOC.txt">
   Revision Log</a></li>
 </ul>
</div>


<div id="searchable">
<div id="content" class="browser">
 <h1><a class="first" title="Go to root directory" href="/projects/helix/browser">root</a><span class="sep">/</span><a title="View trunk" href="/projects/helix/browser/trunk">trunk</a><span class="sep">/</span><a title="View CANDYDOC.txt" href="/projects/helix/browser/trunk/CANDYDOC.txt">CANDYDOC.txt</a></h1>

 <div id="jumprev">
  <form action="" method="get">
   <div>
    <label for="rev">View revision:</label>
    <input type="text" id="rev" name="rev" value="" size="4" />
   </div>
  </form>
 </div>

 

 
  <table id="info" summary="Revision info"><tr>
    <th scope="col">
     Revision <a href="/projects/helix/changeset/5">5</a>, 2.1 kB
     (checked in by nail, 6 years ago)
    </th></tr><tr>
    <td class="message"><p>
Initial import <br />
</p>
</td>
   </tr>
  </table>
  <div id="preview"><table class="code"><thead><tr><th class="lineno">Line</th><th class="content">&nbsp;</th></tr></thead><tbody><tr><th id="L1"><a href="#L1">1</a></th>
<td>CanDyDOC is fileset for creating advanced documentation of programs written</td>
</tr><tr><th id="L2"><a href="#L2">2</a></th>
<td>in D programming language. CanDyDOC adds some eye-candy and advanced navigation</td>
</tr><tr><th id="L3"><a href="#L3">3</a></th>
<td>features to .html documents that are generated by D compiler and known as DDOC.</td>
</tr><tr><th id="L4"><a href="#L4">4</a></th>
<td>Produced result is AJAX web-application that is compatible with all mainstream</td>
</tr><tr><th id="L5"><a href="#L5">5</a></th>
<td>web browsers.</td>
</tr><tr><th id="L6"><a href="#L6">6</a></th>
<td></td>
</tr><tr><th id="L7"><a href="#L7">7</a></th>
<td>This is a version 0.80. For latest release see</td>
</tr><tr><th id="L8"><a href="#L8">8</a></th>
<td>http://trac.dsource.org/projects/helix/</td>
</tr><tr><th id="L9"><a href="#L9">9</a></th>
<td></td>
</tr><tr><th id="L10"><a href="#L10">10</a></th>
<td>CanDyDOC includes following files:</td>
</tr><tr><th id="L11"><a href="#L11">11</a></th>
<td>&nbsp; &nbsp; - candy.ddoc</td>
</tr><tr><th id="L12"><a href="#L12">12</a></th>
<td>&nbsp; &nbsp; &nbsp; &nbsp; File with DDOC macro definitions. You haven&#39;t to touch it.</td>
</tr><tr><th id="L13"><a href="#L13">13</a></th>
<td></td>
</tr><tr><th id="L14"><a href="#L14">14</a></th>
<td>&nbsp; &nbsp; - modules.ddoc</td>
</tr><tr><th id="L15"><a href="#L15">15</a></th>
<td>&nbsp; &nbsp; &nbsp; &nbsp; You should enumerate all modules that would be avaible for navigation</td>
</tr><tr><th id="L16"><a href="#L16">16</a></th>
<td>&nbsp; &nbsp; &nbsp; &nbsp; here.</td>
</tr><tr><th id="L17"><a href="#L17">17</a></th>
<td></td>
</tr><tr><th id="L18"><a href="#L18">18</a></th>
<td>&nbsp; &nbsp; - style.css</td>
</tr><tr><th id="L19"><a href="#L19">19</a></th>
<td>&nbsp; &nbsp; &nbsp; &nbsp; Cascading style sheet file that defines look of produced documentation.</td>
</tr><tr><th id="L20"><a href="#L20">20</a></th>
<td>&nbsp; &nbsp; &nbsp; &nbsp; You can leave this file without changes or adjust fonts, colors, etc</td>
</tr><tr><th id="L21"><a href="#L21">21</a></th>
<td>&nbsp; &nbsp; &nbsp; &nbsp; here. See it for documentation.</td>
</tr><tr><th id="L22"><a href="#L22">22</a></th>
<td></td>
</tr><tr><th id="L23"><a href="#L23">23</a></th>
<td>&nbsp; &nbsp; - ie56hack.css</td>
</tr><tr><th id="L24"><a href="#L24">24</a></th>
<td>&nbsp; &nbsp; &nbsp; &nbsp; CSS file to force Internet Explorer 5/6 browser show documentation</td>
</tr><tr><th id="L25"><a href="#L25">25</a></th>
<td>&nbsp; &nbsp; &nbsp; &nbsp; as it looks like in standard-compliant browsers.</td>
</tr><tr><th id="L26"><a href="#L26">26</a></th>
<td></td>
</tr><tr><th id="L27"><a href="#L27">27</a></th>
<td>&nbsp; &nbsp; - tree.js</td>
</tr><tr><th id="L28"><a href="#L28">28</a></th>
<td>&nbsp; &nbsp; &nbsp; &nbsp; JavaScript implementing tree control that looks like native one.</td>
</tr><tr><th id="L29"><a href="#L29">29</a></th>
<td></td>
</tr><tr><th id="L30"><a href="#L30">30</a></th>
<td>&nbsp; &nbsp; - util.js</td>
</tr><tr><th id="L31"><a href="#L31">31</a></th>
<td>&nbsp; &nbsp; &nbsp; &nbsp; Common cross-browser routines.</td>
</tr><tr><th id="L32"><a href="#L32">32</a></th>
<td></td>
</tr><tr><th id="L33"><a href="#L33">33</a></th>
<td>&nbsp; &nbsp; - explorer.js</td>
</tr><tr><th id="L34"><a href="#L34">34</a></th>
<td>&nbsp; &nbsp; &nbsp; &nbsp; Heart of every documentation&#39;s page. Controls generation, behaviour and</td>
</tr><tr><th id="L35"><a href="#L35">35</a></th>
<td>&nbsp; &nbsp; &nbsp; &nbsp; navigation of a page.</td>
</tr><tr><th id="L36"><a href="#L36">36</a></th>
<td></td>
</tr><tr><th id="L37"><a href="#L37">37</a></th>
<td>&nbsp; &nbsp; - numerous of image files in &#39;img&#39; folder.</td>
</tr><tr><th id="L38"><a href="#L38">38</a></th>
<td></td>
</tr><tr><th id="L39"><a href="#L39">39</a></th>
<td>How to use:</td>
</tr><tr><th id="L40"><a href="#L40">40</a></th>
<td>&nbsp; &nbsp; 1) Put &#39;candydoc&#39; directory in place where documentation will be.</td>
</tr><tr><th id="L41"><a href="#L41">41</a></th>
<td>&nbsp; &nbsp; 2) Modify modules.ddoc file: enumerate all modules that should be avaible</td>
</tr><tr><th id="L42"><a href="#L42">42</a></th>
<td>&nbsp; &nbsp; &nbsp; &nbsp;for navigation.</td>
</tr><tr><th id="L43"><a href="#L43">43</a></th>
<td>&nbsp; &nbsp; 3) Modify style.css file if you want to change style of documentation. Or</td>
</tr><tr><th id="L44"><a href="#L44">44</a></th>
<td>&nbsp; &nbsp; &nbsp; &nbsp;leave it unmodified to apply defaul theme.</td>
</tr><tr><th id="L45"><a href="#L45">45</a></th>
<td>&nbsp; &nbsp; 4) Run documentation compilation with candy.ddoc and modules.ddoc specified</td>
</tr><tr><th id="L46"><a href="#L46">46</a></th>
<td>&nbsp; &nbsp; &nbsp; &nbsp;on command line.</td>
</tr><tr><th id="L47"><a href="#L47">47</a></th>
<td>&nbsp; &nbsp; 5) Enjoy a result :)</td>
</tr><tr><th id="L48"><a href="#L48">48</a></th>
<td></td>
</tr><tr><th id="L49"><a href="#L49">49</a></th>
<td>Known bugs:</td>
</tr><tr><th id="L50"><a href="#L50">50</a></th>
<td>&nbsp; &nbsp; - Explorer window doesn&#39;t work on Safari browser.</td>
</tr><tr><th id="L51"><a href="#L51">51</a></th>
<td>&nbsp; &nbsp; - Scroll bar positions are not adjusted after explorer&#39;s tab change in Opera</td>
</tr><tr><th id="L52"><a href="#L52">52</a></th>
<td>&nbsp; &nbsp; &nbsp; browser. So it is posible to see nothing on some tab: solution is to</td>
</tr><tr><th id="L53"><a href="#L53">53</a></th>
<td>&nbsp; &nbsp; &nbsp; return to a previous tab, scroll it to top and then return back.</td>
</tr><tr><th id="L54"><a href="#L54">54</a></th>
<td>&nbsp; &nbsp; - Overlapping of some elements when too few horizontal place avaible.</td>
</tr></tbody></table>
  </div>

 <div id="help">
  <strong>Note:</strong> See <a href="/projects/helix/wiki/TracBrowser">TracBrowser</a> for help on using the browser.
 </div>

  <div id="anydiff">
   <form action="/projects/helix/anydiff" method="get">
    <div class="buttons">
     <input type="hidden" name="new_path" value="/trunk/CANDYDOC.txt" />
     <input type="hidden" name="old_path" value="/trunk/CANDYDOC.txt" />
     <input type="hidden" name="new_rev" value="" />
     <input type="hidden" name="old_rev" value="" />
     <input type="submit" value="View changes..." title="Prepare an Arbitrary Diff" />
    </div>
   </form>
  </div>

</div>
</div>
<script type="text/javascript">searchHighlight()</script>
<div id="altlinks"><h3>Download in other formats:</h3><ul><li class="first"><a href="/projects/helix/browser/trunk/CANDYDOC.txt?format=txt">Plain Text</a></li><li class="last"><a href="/projects/helix/browser/trunk/CANDYDOC.txt?format=raw">Original Format</a></li></ul></div>

  </div>
 </div>
 
 <div id="sitefooter">
  <p class="left">&copy; Copyright 2004-2012 - The Sankaty Group, Inc.
   All rights reserved.</p>
  <p class="right">
   <a href="/site/donate">Make a Donation</a><br /><br />
   <a id="priv" href="/site/privacy">Privacy Statement</a>&nbsp;&nbsp;
   <a id="tos" href="/site/terms">Terms of Service</a>
  </p>
 </div>
</div>

 </body>
</html>

