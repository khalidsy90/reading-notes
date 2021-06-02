# CSS : stands for Cascading Style Sheets

### CSS brings style to your web pages by interacting with HTML elements

3 ways to use css :

* **External**

html files need to include a header section that links to the external style sheet and looks something like this:

```html
<head>
<link rel=”stylesheet”  type=”text/css”  href=mysitestyle.css”>
</head>
```


* **Internal**
 Internal style sheets are CSS instructions written directly into the header of a specific .html page. (This is especially useful if you have a single page on a site that has a unique look.) An internal style sheet looks something like this. . .

 ```html
    <head>
    <style>
    Body  {  background-color:thistle;  }
    P  {  font-size:20px;  color:mediumblue;  }
    </style>
    </head>
```

* **Inline**

inline styles are snippets of CSS written directly into HTML code, and applicable only to a single coding instance. For example:
```html
<h1 style=”font-size:40px;color:violet;”>Check out this headline!</h1>
```
