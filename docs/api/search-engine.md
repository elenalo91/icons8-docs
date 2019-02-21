---
# Page settings
layout: default
keywords:
comments: false

# Hero section
title: Search Engine
description: Learn about our searching api capabilities
icon: 'search-more'

# Micro navigation
micro_nav: false

# Page navigation
page_nav:
  next:
      content: Retrieval Engine
      url: '/api/retrieval-engine'
---
<ul>
    <li>
   <details>
     <summary>
       <h2> How it Works? </h2>
     </summary> 
<p>The engine is a dedicated service. It accepts search queries and returns responses. A response is a JSON containing metadata items for the most relevant icons. You can use the metadata to further filter, group, and retrieve icons. This section explains the searching parameters used for the service. You embed these parameters one after another in your query. The order of the parameters is up to you.</p>
   </details>
   </li>
   <li>
   <details>
     <summary>
       <h2> API Key / Token </h2>
     </summary>
<p>Personal <b>API key</b> or <b>token</b> is a shortcode in text format. This token grants you permission to send requests to searching and retrieval engines. After we receive a payment from a client, we issue an API key. You may proceed with the payment on <a href="https://icons8.recurly.com/subscribe/api_access" rel="nofollow">this page</a>.</p>
   </details>
   </li>
    <li>
   <details>
     <summary>
       <h2> Endpoint </h2>
     </summary>
<p>The endpoint is the URL where our service can be accessed by a client application. The v4 search engine endpoint is: <a href="https://api.icons8.com/api/iconsets/v4/search" rel="nofollow">https://api.icons8.com/api/iconsets/v4/search</a></p>
   </details>
   </li>
   <li>
   <details>
     <summary>
       <h2> Platform  </h2>
     </summary>
<p>There is a set of parameters or attributes with a name  <code>platform</code> or a <code>platform_api_code</code> or a <code>platform_code.</code>  All these names mean the same thing, the style of the icons.</p>
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
   </li>
   <li>
   <details>
     <summary>
       <h2> Language  </h2>
     </summary>
<p>Icon names, categories, and tags are localized. Here's the list of supported languages:</p>
 <p align="center">
</p><table>
<thead>
<tr>
<th>Language</th>
<th>Language name</th>
</tr>
</thead>
<tbody>
<tr>
<td>en-US</td>
<td>English</td>
</tr>
<tr>
<td>fr-FR</td>
<td>French</td>
</tr>
<tr>
<td>de-DE</td>
<td>German</td>
</tr>
<tr>
<td>it-IT</td>
<td>Italian</td>
</tr>
<tr>
<td>pt-BR</td>
<td>Portuguese</td>
</tr>
<tr>
<td>pl-PL</td>
<td>Polish</td>
</tr>
<tr>
<td>ru-RU</td>
<td>Russian</td>
</tr>
<tr>
<td>es-ES</td>
<td>Spanish</td>
</tr>
<tr>
<td>zh-CN</td>
<td>Chinese</td>
</tr>
<tr>
<td>ja-JP</td>
<td>Japanese</td>
</tr>
</tbody>
</table>
<p></p>
<p>The primary language is English. If we do not internationalize something, it will be in English.</p>
   </details>
   </li>
   <li>
   <details>
     <summary>
       <h2> Amount  </h2>
     </summary>
<p>This field is the largest number of icons which you'd like to receive. The default value is 25.</p>
   </details>
   </li>
   <li>
   <details>
     <summary>
       <h2>  Offset  </h2>
     </summary>
<p>This field is the offset from the first received result. The default value is 0.</p>
   </details>
   </li>
   <li>
   <details>
     <summary>
       <h2> Sample Request </h2>
     </summary>
<p><a href="https://api.icons8.com/api/iconsets/v4/search?term=home&amp;amount=50&amp;offset=0&amp;platform=all&amp;language=en-US&amp;token=al05i21yfatb4s5eac20c4wr4394b1z2" rel="nofollow">https://api.icons8.com/api/iconsets/v4/search?term=home&amp;amount=50&amp;offset=0&amp;platform=all&amp;language=en-US&amp;token=al05i21yfatb4s5eac20c4wr4394b1z2</a>.</p>
<ul>
<li>search query: "home"</li>
<li>amount: "50"</li>
<li>platform (style): "all"</li>
<li>language: "US"</li>
<li>token: "al05i21yfatb4s5eac20c4wr4394b1z2"</li>
</ul>
   <br>
<p>You may use the platform as a filter in your requests.</p>
   </details>
   </li>
   <li>
   <details>
     <summary>
       <h2> Sample Response </h2>
     </summary>
 <p align="center">
</p><table>
<thead>
<tr>
<th><a target="_blank" rel="noopener noreferrer" href="/icons8-docs/public/icons/v4_Search_JSON_1.png"><img src="/icons8-docs/public/icons/v4_Search_JSON_1.png" style="max-width:100%;"></a></th>
<th><a target="_blank" rel="noopener noreferrer" href="/icons8-docs/public/icons/v4_Search_JSON_2.png"><img src="/icons8-docs/public/icons/v4_Search_JSON_2.png" style="max-width:100%;"></a></th>
</tr>
</thead>
</table>
   <p></p>
<p>You may use category attribute to group the results. Pay attention that the service will not return the categories which have less than ten icons.</p>
   </details>
   </li>
   </ul>
