---
# Page settings
layout: default
keywords:
comments: false

# Hero section
title: Retrieval Engine
description: Learn about a fancier way of retrieving icons
icon: 'search-folder'

# Micro navigation
micro_nav: false

# Page navigation
page_nav:
  prev:
      content: Web App
      url: '/web-app/'
---

<ul>

 <li>
 <details>
  <summary>
   <h2>Free VS Paid </h2>
 </summary>
<p><a href="http://img.icons8.com/" rel="nofollow">Omg-img</a> service provides free and paid options. Yes, you can search and retrieve icons with omg-img for free. The <b>free</b> option works great for small and simple projects. The <b>paid</b> option lets you craft cutting-edge apps. You may use exactly the same paid token to access both searching and retrieval engines.</p>
<p>Lots of the <a href="http://img.icons8.com/" rel="nofollow">omg-img</a> features are available to our clients for free. Premium options are available only to paying clients. The major difference is that <b>paid license</b> provides extra features which are:</p>
<ul>
<li>Access to generate PNG icons larger than 550 px</li>
<li>Access to vector-format icons (SVG, EPS, PDF). Popular SVG icons are available for <b>free</b>.</li>
<li>Access to more <a href="#service-integration-framework">'advanced search engine'</a></li>
</ul>
 </details>
 </li>

 <li>
 <details>
  <summary>
   <h2> How to Retrieve an Icon on a Paid Basis? </h2>
 </summary>
<p>The format for retrieving icons via paid requests is as follows:</p>
<ul>
<li><a href="http://img.icons8.com/%5Bplatform%5D/%5Bsize%5D/%5BcommonName%5D.%5Bformat%5D?token=YOURTOKEN" rel="nofollow">http://img.icons8.com/[platform]/[size]/[commonName].[format]?token=YOURTOKEN</a></li>
</ul>
<br>
<p>In the above request, parameters commonName, platform, token - are mandatory. Size - is optional. Assume we call v4 search engine with 'house' searching phrase and receive a JSON response as follows:</p>
 <p align="center">
   <a target="_blank" rel="noopener noreferrer" href="https://github.com/visualpharm/icons-docs/blob/master/docs/Images/Icons/JSON_RETRIEVE_1.png"><img src="https://github.com/visualpharm/icons-docs/raw/master/docs/Images/Icons/JSON_RETRIEVE_1.png" style="max-width:100%;"></a>
 </p>
<p>Take a look onto parameters in the JSON. Platform parameter attains the value "ultroviolet". The commonName attains the value "Link-company-child". That's all we need to get the icon in the SVG / EPS / PDF / PNG formats by sending the following requests to the <a href="http://img.icons8.com/" rel="nofollow">omg-img</a> service:</p>
 <p align="center">
</p><ul>
<li>'<a href="http://img.icons8.com/ultraviolet/link-company-child.svg?token=YOURTOKEN" rel="nofollow">http://img.icons8.com/ultraviolet/link-company-child.svg?token=YOURTOKEN</a>'</li>
<li>'<a href="http://img.icons8.com/ultraviolet/link-company-child.eps?token=YOURTOKEN" rel="nofollow">http://img.icons8.com/ultraviolet/link-company-child.eps?token=YOURTOKEN</a>'</li>
<li>'<a href="http://img.icons8.com/ultraviolet/link-company-child.png?token=YOURTOKEN" rel="nofollow">http://img.icons8.com/ultraviolet/link-company-child.png?token=YOURTOKEN</a>'</li>
<li>'<a href="http://img.icons8.com/ultraviolet/link-company-child.pdf?token=YOURTOKEN" rel="nofollow">http://img.icons8.com/ultraviolet/link-company-child.pdf?token=YOURTOKEN</a>'</li>
</ul>
 <p></p>
<p>Note that the 'name' parameter is not used at all in building a retrieving URL for the icon.</p>
 </details>
 </li>

 <li>
 <details>
  <summary>
   <h2> How to Retrieve an Icon for Free? </h2>
 </summary>
<p>It takes a line of code to insert an icon in SVG or PNG format from the CDN to your application of any scale:</p>
<ul>
<li><code>&lt;img src=’https://img.icons8.com/search.svg’/&gt;</code></li>
<li><code>&lt;img src=’https://img.icons8.com/search.png’/&gt;</code></li>
</ul>
 <br>
<p>Also please note that:</p>
<ul>
<li>PNG icons are available in limited size (less than 550px)</li>
<li>only popular SVG icons are available for free</li>
</ul>
 </details>
 </li>

 <li>
 <details>
  <summary>
   <h2> Icon’s Search From the Address Bar </h2>
 </summary>
<p><a href="http://img.icons8.com/" rel="nofollow">Omg-img</a> allows browsing for new icons from a browser’s address bar. This feature available for both paying and free customers:</p>
<ul>
<li><a href="https://img.icons8.com/home" rel="nofollow">https://img.icons8.com/home</a></li>
<li><a href="https://img.icons8.com/house" rel="nofollow">https://img.icons8.com/house</a></li>
<li><a href="https://img.icons8.com/bungalow" rel="nofollow">https://img.icons8.com/bungalow</a></li>
<li><a href="https://img.icons8.com/targaryen-house" rel="nofollow">https://img.icons8.com/targaryen-house</a></li>
</ul>
 </details>
 </li>

 <li>
 <details>
  <summary>
   <h2> Free Icon’s Search From Web App </h2>
 </summary>
<br>
<p>Free customers may use our web app as a free tool to search and full paths to the icons they like. Type-in a query in the app and click on the search icon to get a list of the most relevant icons.</p>
 <p align="center">
  <a target="_blank" rel="noopener noreferrer" href="https://github.com/visualpharm/icons-docs/blob/master/docs/Images/Icons/search_with_query_3.png"><img src="https://github.com/visualpharm/icons-docs/raw/master/docs/Images/Icons/search_with_query_3.png" style="max-width:100%;"></a>
</p> 
<br>
Then click on the icon you'd like to use. When the editor shows up click on the "HTML" button:
  <p align="center">
   <a target="_blank" rel="noopener noreferrer" href="https://github.com/visualpharm/icons-docs/blob/master/docs/Images/Icons/editor_main_start_html_1.png"><img src="https://github.com/visualpharm/icons-docs/raw/master/docs/Images/Icons/editor_main_start_html_1.png" style="max-width:100%;"></a>
 </p>
 <br>
 Copy the full path to the icon and paste it into your app:
 <p align="center">
   <a target="_blank" rel="noopener noreferrer" href="https://github.com/visualpharm/icons-docs/blob/master/docs/Images/Icons/html_cdn_2.png"><img src="https://github.com/visualpharm/icons-docs/raw/master/docs/Images/Icons/html_cdn_2.png" style="max-width:100%;"></a>
 </p>
 </details>
</li>
 <li>
 <details>
  <summary>
   <h2>  How to Retrieve Icons in a Particular Style? </h2>
 </summary>
<p>Retrieving an icon in particular style is easy. To do this, you embed the desired style as a parameter in your retrieval request:</p>
 <p align="center">
</p><table>
<thead>
<tr>
<th>monochrome</th>
<th>coloured</th>
</tr>
</thead>
<tbody>
<tr>
<td>iOS: <a href="http://img.icons8.com/ios/car" rel="nofollow">http://img.icons8.com/ios/car</a> <a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/b39de09cf9429fea699d507affa3c25aabd624dd/687474703a2f2f696d672e69636f6e73382e636f6d2f696f732f636172"><img src="https://camo.githubusercontent.com/b39de09cf9429fea699d507affa3c25aabd624dd/687474703a2f2f696d672e69636f6e73382e636f6d2f696f732f636172" data-canonical-src="http://img.icons8.com/ios/car" style="max-width:100%;"></a></td>
<td>Color: <a href="http://img.icons8.com/color/car" rel="nofollow">http://img.icons8.com/color/car</a> <a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/319b8a4a215245c25ed2e3ee52adaf994260b531/687474703a2f2f696d672e69636f6e73382e636f6d2f636f6c6f722f636172"><img src="https://camo.githubusercontent.com/319b8a4a215245c25ed2e3ee52adaf994260b531/687474703a2f2f696d672e69636f6e73382e636f6d2f636f6c6f722f636172" data-canonical-src="http://img.icons8.com/color/car" style="max-width:100%;"></a></td>
</tr>
<tr>
<td>Windows: <a href="http://img.icons8.com/windows/car" rel="nofollow">http://img.icons8.com/windows/car</a> <a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/5c76696861cd80f42c741f18d24fbd99df58fb1a/687474703a2f2f696d672e69636f6e73382e636f6d2f77696e646f77732f636172"><img src="https://camo.githubusercontent.com/5c76696861cd80f42c741f18d24fbd99df58fb1a/687474703a2f2f696d672e69636f6e73382e636f6d2f77696e646f77732f636172" data-canonical-src="http://img.icons8.com/windows/car" style="max-width:100%;"></a></td>
<td>Office: <a href="http://img.icons8.com/office/car" rel="nofollow">http://img.icons8.com/office/car</a> <a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/666d33ef0c7a8eb279ed5db33b3ada4b01a652fc/687474703a2f2f696d672e69636f6e73382e636f6d2f6f66666963652f636172"><img src="https://camo.githubusercontent.com/666d33ef0c7a8eb279ed5db33b3ada4b01a652fc/687474703a2f2f696d672e69636f6e73382e636f6d2f6f66666963652f636172" data-canonical-src="http://img.icons8.com/office/car" style="max-width:100%;"></a></td>
</tr>
<tr>
<td>Material: <a href="http://img.icons8.com/material/car" rel="nofollow">http://img.icons8.com/material/car</a> <a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/e7e0ad7590153c9fd378adf07558de3549c9d270/687474703a2f2f696d672e69636f6e73382e636f6d2f6d6174657269616c2f636172"><img src="https://camo.githubusercontent.com/e7e0ad7590153c9fd378adf07558de3549c9d270/687474703a2f2f696d672e69636f6e73382e636f6d2f6d6174657269616c2f636172" data-canonical-src="http://img.icons8.com/material/car" style="max-width:100%;"></a></td>
<td>Dusk: <a href="http://img.icons8.com/dusk/car" rel="nofollow">http://img.icons8.com/dusk/car</a> <a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/8e69c811f8431fbf0da5e60ac6375877174c38c6/687474703a2f2f696d672e69636f6e73382e636f6d2f6475736b2f636172"><img src="https://camo.githubusercontent.com/8e69c811f8431fbf0da5e60ac6375877174c38c6/687474703a2f2f696d672e69636f6e73382e636f6d2f6475736b2f636172" data-canonical-src="http://img.icons8.com/dusk/car" style="max-width:100%;"></a></td>
</tr>
</tbody>
</table>
<p></p>
<details>
  <summary>
   <h2>  See the List of More Than 20 Various Styles That You May Use to Retrieve Icons  </h2>
 </summary>
 <p align="center">
</p><table>
<thead>
<tr>
<th>Platform</th>
<th>Icon style</th>
</tr>
</thead>
<tbody>
<tr>
<td>win8</td>
<td>icons in the Microsoft Windows 8/Metro style</td>
</tr>
<tr>
<td>win10</td>
<td>icons in the Microsoft Windows 10/Threshold</td>
</tr>
<tr>
<td>ios7</td>
<td>icons in the Apple iOS 7/8/9/10 style</td>
</tr>
<tr>
<td>android</td>
<td>icons in the Google Android 4 Kitkat style</td>
</tr>
<tr>
<td>androidL</td>
<td>icons in the Google Android 5 Lollipop (Material) style</td>
</tr>
<tr>
<td>color</td>
<td>flat color icons</td>
</tr>
<tr>
<td>office</td>
<td>Icons for Microsoft Office</td>
</tr>
<tr>
<td>ultraviolet</td>
<td>Blue UI</td>
</tr>
<tr>
<td>nolan</td>
<td>Gradient Line</td>
</tr>
<tr>
<td>p1em</td>
<td>Simple Small</td>
</tr>
<tr>
<td>dotty</td>
<td>Dotted</td>
</tr>
<tr>
<td>dusk</td>
<td>Cute Color</td>
</tr>
<tr>
<td>Dusk_Wired</td>
<td>Cute Outline</td>
</tr>
<tr>
<td>cotton</td>
<td>Pastel</td>
</tr>
<tr>
<td>ios11</td>
<td>iOS Glyph</td>
</tr>
<tr>
<td>clouds</td>
<td>Clouds</td>
</tr>
<tr>
<td>bubbles</td>
<td>Circle Bubbles</td>
</tr>
<tr>
<td>plasticine</td>
<td>Color Hand Drawn</td>
</tr>
<tr>
<td>carbon_copy</td>
<td>Hand Drawn</td>
</tr>
<tr>
<td>doodle</td>
<td>Doodle</td>
</tr>
<tr>
<td>fineline</td>
<td>Fune Line</td>
</tr>
<tr>
<td>isometric</td>
<td>Isometric</td>
</tr>
<tr>
<td>flat_round</td>
<td>Round Infographic</td>
</tr>
<tr>
<td>m_outlined</td>
<td>Material Design Outlined</td>
</tr>
<tr>
<td>m_rounded</td>
<td>Material Design Rounded</td>
</tr>
<tr>
<td>m_two_tone</td>
<td>Material Design Two Tone</td>
</tr>
<tr>
<td>m_sharp</td>
<td>Material Design Sharp</td>
</tr>
</tbody>
</table>
<p></p>
</details>
 </details>
</li>
 <li>
 <details>
  <summary>
   <h2> How to Recolor Monochrome Icons? </h2>
 </summary>
<p>To change the color of an icon it's enough to insert an appropriate color code within an icon link:</p>
<ul>
<li><a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/253740ac91901591f66422e6e9949f3a123226de/687474703a2f2f696d672e69636f6e73382e636f6d2f696f732f4646303030302f636172"><img src="https://camo.githubusercontent.com/253740ac91901591f66422e6e9949f3a123226de/687474703a2f2f696d672e69636f6e73382e636f6d2f696f732f4646303030302f636172" data-canonical-src="http://img.icons8.com/ios/FF0000/car" style="max-width:100%;"></a> <code>http://img.icons8.com/ios/FF0000/car</code></li>
<li><a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/127a6c5d258d06d13ab98f6543230ea20f657b9a/687474703a2f2f696d672e69636f6e73382e636f6d2f696f732f3030464630302f636172"><img src="https://camo.githubusercontent.com/127a6c5d258d06d13ab98f6543230ea20f657b9a/687474703a2f2f696d672e69636f6e73382e636f6d2f696f732f3030464630302f636172" data-canonical-src="http://img.icons8.com/ios/00FF00/car" style="max-width:100%;"></a> <code>http://img.icons8.com/ios/00FF00/car</code></li>
<li><a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/bf843bf5cc690b24408ceef780edf08277bf0dbd/687474703a2f2f696d672e69636f6e73382e636f6d2f696f732f3030303046462f636172"><img src="https://camo.githubusercontent.com/bf843bf5cc690b24408ceef780edf08277bf0dbd/687474703a2f2f696d672e69636f6e73382e636f6d2f696f732f3030303046462f636172" data-canonical-src="http://img.icons8.com/ios/0000FF/car" style="max-width:100%;"></a> <code>http://img.icons8.com/ios/0000FF/car</code></li>
</ul>
 </details>
</li>
<li>
 <details>
  <summary>
   <h2> How Can I Resize an Icon? </h2>
 </summary>
<p>To change icon size, it’s just enough to embed an icon size within its link:</p>
<ul>
<li>'<a href="http://img.icons8.com/color/30px/car" rel="nofollow">http://img.icons8.com/color/30px/car</a>' <a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/bfd5be92d4edba64f144464b826e3c148e06bf39/687474703a2f2f696d672e69636f6e73382e636f6d2f636f6c6f722f333070782f636172"><img src="https://camo.githubusercontent.com/bfd5be92d4edba64f144464b826e3c148e06bf39/687474703a2f2f696d672e69636f6e73382e636f6d2f636f6c6f722f333070782f636172" data-canonical-src="http://img.icons8.com/color/30px/car" style="max-width:100%;"></a></li>
<li>'<a href="http://img.icons8.com/color/40px/car" rel="nofollow">http://img.icons8.com/color/40px/car</a>' <a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/bd0df5765ba6ee5cb3e1185dc419d6d57d412b81/687474703a2f2f696d672e69636f6e73382e636f6d2f636f6c6f722f343070782f636172"><img src="https://camo.githubusercontent.com/bd0df5765ba6ee5cb3e1185dc419d6d57d412b81/687474703a2f2f696d672e69636f6e73382e636f6d2f636f6c6f722f343070782f636172" data-canonical-src="http://img.icons8.com/color/40px/car" style="max-width:100%;"></a></li>
<li>'<a href="http://img.icons8.com/color/50px/car" rel="nofollow">http://img.icons8.com/color/50px/car</a>' <a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/f907bc264479b4f5e3e2e6b79ca5eebb1de1abf9/687474703a2f2f696d672e69636f6e73382e636f6d2f636f6c6f722f353070782f636172"><img src="https://camo.githubusercontent.com/f907bc264479b4f5e3e2e6b79ca5eebb1de1abf9/687474703a2f2f696d672e69636f6e73382e636f6d2f636f6c6f722f353070782f636172" data-canonical-src="http://img.icons8.com/color/50px/car" style="max-width:100%;"></a></li>
<li>'<a href="http://img.icons8.com/color/60px/car" rel="nofollow">http://img.icons8.com/color/60px/car</a>' <a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/3be71656851c84f019891a5e624163302017328b/687474703a2f2f696d672e69636f6e73382e636f6d2f636f6c6f722f363070782f636172"><img src="https://camo.githubusercontent.com/3be71656851c84f019891a5e624163302017328b/687474703a2f2f696d672e69636f6e73382e636f6d2f636f6c6f722f363070782f636172" data-canonical-src="http://img.icons8.com/color/60px/car" style="max-width:100%;"></a></li>
</ul>
<p>Icon's size can be written in two different formats: <code>100x100</code> or <code>100px</code>.</p>
 </details>
</li>
<li>
 <details>
  <summary>
   <h2> How to Retrieve Sharp Pixel Perfect Icons? </h2>
 </summary>
<p>Each icon style is drawn for a specific pixel grid. Look at these few examples of various pixel grids:</p>
<ul>
<li>iOS: <code>50x50</code></li>
<li>Metro: <code>26x26</code></li>
<li>Windows: <code>32x32</code></li>
<li>Material: <code>24x24</code></li>
<li>Color: <code>48x48</code></li>
<li>Office: <code>16x16</code>, <code>30x30</code>, <code>40x40</code>, <code>80x80</code></li>
</ul>
<p>We recommend you to use multiples of original icon size. This will help to avoid all sorts of artifacts (blurring edges, washed out, etc.) associated with changing an icon size. For example, for the iOS style, the multiples would be 50x50, 100x100, 150x150 and so forth. You can set an icon size either by specifying the size in pixels 100x100 / 100px or with the use of factors: 2x or x2 (the number can vary):</p>
<ul>
<li>'<a href="https://img.icons8.com/color/1x/brazilian-carnival.png" rel="nofollow">https://img.icons8.com/color/1x/brazilian-carnival.png</a>' <a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/e325889232737216a3416e11046f09208f2062c0/68747470733a2f2f696d672e69636f6e73382e636f6d2f636f6c6f722f31782f6272617a696c69616e2d6361726e6976616c2e706e67"><img src="https://camo.githubusercontent.com/e325889232737216a3416e11046f09208f2062c0/68747470733a2f2f696d672e69636f6e73382e636f6d2f636f6c6f722f31782f6272617a696c69616e2d6361726e6976616c2e706e67" data-canonical-src="https://img.icons8.com/color/1x/brazilian-carnival.png" style="max-width:100%;"></a></li>
<li>'<a href="https://img.icons8.com/color/2x/brazilian-carnival.png" rel="nofollow">https://img.icons8.com/color/2x/brazilian-carnival.png</a>' <a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/0388d586eb732bf7576a354f377690192a9f7ace/68747470733a2f2f696d672e69636f6e73382e636f6d2f636f6c6f722f32782f6272617a696c69616e2d6361726e6976616c2e706e67"><img src="https://camo.githubusercontent.com/0388d586eb732bf7576a354f377690192a9f7ace/68747470733a2f2f696d672e69636f6e73382e636f6d2f636f6c6f722f32782f6272617a696c69616e2d6361726e6976616c2e706e67" data-canonical-src="https://img.icons8.com/color/2x/brazilian-carnival.png" style="max-width:100%;"></a></li>
</ul>
 </details>
</li>
<li>
 <details>
  <summary>
   <h2> What is the Greatest Size of an Icon I Can Retrieve? </h2>
 </summary>
<p>The restriction applied to free png icons is 550 px. Paying clients may retrieve icons in any size up to 2048 px.</p>
 </details>
</li>
<li>
 <details>
  <summary>
   <h2> What Should I Do if I Can not Find an Icon That I Need? </h2>
 </summary>
<p>You may send us a <a href="https://icons8.com/request-icon/" rel="nofollow">request</a> to draw an icon you need. <a href="https://icons8.com/request-icon/free/hot" rel="nofollow">It’s completely free</a>. We try to do our the best to make our service comprehensive. However, we do prioritize the requests which have the highest demand. Be creative, ask your friends, relatives, and any community members to vote for your requested icon to put your request higher on the queue.</p>
<p>Alternatively, there is a paid fast option too, <a href="https://icons8.com/request-icon/custom/" rel="nofollow">$50 per icon, up to 20 icons a day</a>.</p>
 </details>
</li>
<li>
 <details>
  <summary>
   <h2> Can an Icon Used in my App Change Over Time? </h2>
 </summary>
<p>In short, it’s very unlikely, but it's possible. The most updated version of an icon is accessible by a given icon’s link. Let take a look at the following example. Imaging we have a link <strong><code>https://img.icons8.com/water-molecule</code></strong>. For this URL we keep showing an icon with an illustration of a water drop or an abstract molecule. But what happens if we begin to receive more and more requests to change the icon’s appearance to say a water molecule like this H<sub>2</sub>O. Most probably we will alternate its look somehow to represent the structure of two atoms of hydrogen and one atom of oxygen bonded together.</p>
<p>In case <b>if you are planning to use an icon longterm</b>, the best solution would be to use the full canonical path to the icon. For that, type in a query in the app and click on the search icon to get a list of the most relevant icons.</p>
 <p align="center">
  <a target="_blank" rel="noopener noreferrer" href="https://github.com/visualpharm/icons-docs/blob/master/docs/Images/Icons/search_with_query_3.png"><img src="https://github.com/visualpharm/icons-docs/raw/master/docs/Images/Icons/search_with_query_3.png" style="max-width:100%;"></a>
</p> 
<br>
Then click on the icon you'd like to use. When the editor shows up click on the "HTML" button:
  <p align="center">
   <a target="_blank" rel="noopener noreferrer" href="https://github.com/visualpharm/icons-docs/blob/master/docs/Images/Icons/editor_main_start_html_1.png"><img src="https://github.com/visualpharm/icons-docs/raw/master/docs/Images/Icons/editor_main_start_html_1.png" style="max-width:100%;"></a>
 </p>
 <br>
 Copy the full path to the icon and paste it in your own app:
 <p align="center">
   <a target="_blank" rel="noopener noreferrer" href="https://github.com/visualpharm/icons-docs/blob/master/docs/Images/Icons/html_cdn_2.png"><img src="https://github.com/visualpharm/icons-docs/raw/master/docs/Images/Icons/html_cdn_2.png" style="max-width:100%;"></a>
 </p>
 </details>
</li>

<li>
 <details>
  <summary>
   <h2>How to Use Responsive Size for Style? </h2>
 </summary>
<p>It’s quite simple. Just add a parameter <code>office</code> to your request. For example:</p>
<ul>
<li><a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/c035ec2470fd87927711ac8bdf760030511ba4ec/687474703a2f2f696d672e69636f6e73382e636f6d2f6f66666963652f353070782f6361722e706e673f6f66666963653d3136"><img src="https://camo.githubusercontent.com/c035ec2470fd87927711ac8bdf760030511ba4ec/687474703a2f2f696d672e69636f6e73382e636f6d2f6f66666963652f353070782f6361722e706e673f6f66666963653d3136" data-canonical-src="http://img.icons8.com/office/50px/car.png?office=16" style="max-width:100%;"></a> <code>http://img.icons8.com/office/50px/car.png?office=16</code></li>
<li><a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/3a60711bef60473768b4f7161e8f7de3d846b98f/687474703a2f2f696d672e69636f6e73382e636f6d2f6f66666963652f353070782f6361722e706e673f6f66666963653d3330"><img src="https://camo.githubusercontent.com/3a60711bef60473768b4f7161e8f7de3d846b98f/687474703a2f2f696d672e69636f6e73382e636f6d2f6f66666963652f353070782f6361722e706e673f6f66666963653d3330" data-canonical-src="http://img.icons8.com/office/50px/car.png?office=30" style="max-width:100%;"></a> <code>http://img.icons8.com/office/50px/car.png?office=30</code></li>
<li><a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/e15c3326a91dd246f5695d6b3a5316d0c6d1e5f9/687474703a2f2f696d672e69636f6e73382e636f6d2f6f66666963652f353070782f6361722e706e673f6f66666963653d3430"><img src="https://camo.githubusercontent.com/e15c3326a91dd246f5695d6b3a5316d0c6d1e5f9/687474703a2f2f696d672e69636f6e73382e636f6d2f6f66666963652f353070782f6361722e706e673f6f66666963653d3430" data-canonical-src="http://img.icons8.com/office/50px/car.png?office=40" style="max-width:100%;"></a> <code>http://img.icons8.com/office/50px/car.png?office=40</code></li>
<li><a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/d68df9dfb8e0291a7e94910c887bb0b12befad73/687474703a2f2f696d672e69636f6e73382e636f6d2f6f66666963652f353070782f6361722e706e673f6f66666963653d3830"><img src="https://camo.githubusercontent.com/d68df9dfb8e0291a7e94910c887bb0b12befad73/687474703a2f2f696d672e69636f6e73382e636f6d2f6f66666963652f353070782f6361722e706e673f6f66666963653d3830" data-canonical-src="http://img.icons8.com/office/50px/car.png?office=80" style="max-width:100%;"></a> <code>http://img.icons8.com/office/50px/car.png?office=80</code></li>
</ul>
 </details>
</li>
 
</ul>