# Practical 1: Introduction to HTML
1. Tags has **start** tag and **end** tag.  
   Enclose text with start tag and end tag
- <h2> my sample text </h2> 
```
<h2> my sample text </h2> 
```
- <p> my sample text </p> 
```
<p>... </p>
```
- <i> my sample text </i>
```
<i>... </i>
```
- <b> my sample text </b>
```
<b>... </b>
```
- <quote> my sample text </quote>
```
<quote>... </quote>
```
2. Tags come sets. Tag hierarchy applies to sets  
Observer the hierarchy:  
- unordered list
   - item1
   - item2
```
<ul>
   <li> item1 </li>
   <li> item2 </li>
</ul>
```
- ordered list
   1. item1
   2. item2
```
<ol>
   <li> ordered1 </li>
   <li> ordered2 </li>
</ol>
```
- table tag  
table>  
&nbsp; &nbsp; thead> tr> th  
&nbsp; &nbsp; tbody> tr> td  

| No | r | s | t |
| --- | --- | --- | --- |
| 1 | 2 | 3 | 4 |
| 5 | 6 | 7 | 8 |

```
<table>
   <thead>
      <tr>
         <th>No </th>
         <th>r </th>
         <th>s </th>
         <th>t </th>
      </tr>
   </thead>
   <tbody>
      <tr>
         <td>1 </td>
         <td>2 </td>
         <td>3 </td>
         <td>4 </td>
      </tr>
   </tbody>
</table>
```
2. Some tags come with attributes, giving it extra behaviours  
- Merged cells horizontally
<table>
   <tr>
      <td>1 </td>
      <td>2 </td>
      <td>3 </td>
   </tr>
   <tr>
      <td colspan=2>1 </td>
      <td>3 </td>
   </tr>
   <tr>
      <td>1 </td>
      <td>2 </td>
      <td>3 </td>
   </tr>
</table>

```
<table>
   <tr>
      <td>1 </td>
      <td>2 </td>
      <td>3 </td>
   </tr>
   <tr>
      <td colspan=2>1 </td>
      <td>3 </td>
   </tr>
   <tr>
      <td>1 </td>
      <td>2 </td>
      <td>3 </td>
   </tr>
</table>
```

- Merged cells vertically 
<table>
   <tr>
      <td>1 </td>
      <td>2 </td>
   </tr>
   <tr>
      <td rowspan=2>1 </td>
      <td>2 </td>
   </tr>
   <tr>
      <td>2 </td>
   </tr>
</table>

```
<table>
   <tr>
      <td>1 </td>
      <td>2 </td>
   </tr>
   <tr>
      <td rowspan=2>1 </td>
      <td>2 </td>
   </tr>
   <tr>
      <td>2 </td>
   </tr>
</table>
```

- setting source of image
<image src="beach.jpg">
```
<image src="beach.jpg">
```

- setting hyperlink reference
<link href="practical2.html" width=250 height=250>
```
<link href="practical2.html">
```

3. Some tags are singular   
```
<br> line break
<hr> horizontal line
```

###Activity
To include the use of HTML into dummy page. Students can use online application to get immediate visual feedback of their work. 

**Resources**
* [Dummy text generator](https://www.lipsum.com/feed/html)
* Web application ([Jsbin](https://jsbin.com/?html,js,output)) to write page
* Use [Github](https://github.com/) to save work.
* HTML [basic tags](https://www.w3schools.com/html/)
* HTML [symbols](https://www.toptal.com/designers/htmlarrows/symbols/)
