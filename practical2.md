# Practical 2: Introduction to CSS
1. All tags has specific in-built style. However they can be further applied custom styles.  
__**Header 1**__
```
<h1 style="font-weight:bold;text-decoration:underline"> Header 1 </h1>
```

2. Note that CSS declaration comes in pairs of (properties: values1 [value2])  
Some properties (like border) can be declared via shorthand, where several values (border-width border-style border-color) are combined on value.
```
font-weight: bold  
border: 1px solid black  
```

3. CSS can also be grouped to from a specific style  
Here, all h1 tags will be assume a specific style.
```
h1 {
  font-weight: bold  
  border: 1px solid black  
}
```

4. Block elements and non-block elements  
Block item occupies a whole line because they break into new line, whereas inline item doesnt.  
span displayed inline  
div displayed block   
p displayed block   

5. Document flow  
By default, document flow from left to right. Cultures that write from other way round will need to be styled differently. 

6. These styles can also be stored away in a .css file, ready to be referenced by different other html pages.

file content of *style.css*
```
h1 {
  font-weight: bold  
  border: 1px solid black  
}
```

*style.css* referenced by other .html files, head section
```
<link rel="stylesheet" type="text/css" href="style.css">
```

7. Note that a regular .html file has structure of  
html>   
&nbsp; &nbsp; head (this is where imports of CSS, javascript lives)  
&nbsp; &nbsp; body  

8. Examples of CSS use at [CSS Zen Garden](http://www.csszengarden.com/).


### Activity 1
Get familiar with some common CSS properties. You can visit any webpage and by pressing F12, launch chrome developer to manipulate the styles.
- background-color
- color
- width
- height
- margin
- padding
- font-family
- list-style-type


### Activity 2
Setup localhost using Internet Information System (IIS) on windows.  
Serve page on local network.

### Setting up IIS
1. Go to your programs and features  
windows key + r  
type in appwiz.cpl  
2. Go turn windows features on/ off  
Internet Information Services, check it
3. Press OK

### Checking own IP.
Using cmd, run ipconfig to identify.
By providing your IP address to peers, they'll be able to surf your website
