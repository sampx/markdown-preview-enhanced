
<!-- toc orderedList:0 depthFrom:1 depthTo:6 -->

* [Table of Contents](#table-of-contents)
	* [[TOC]](#toc)
	* [Configuration](#configuration)
	* [Demo](#demo)

<!-- tocstop -->

# Table of Contents
**Markdown Preview Enhanced** can create `TOC` for your markdown file.   
You can press <kbd>cmd+shift+p</kbd> then choose `Markdown Preview Enhanced: Create Toc` to create `TOC`.  
Multiple TOCs can be created.  
To exclude a heading from the `TOC`, insert `<!-- untoc -->` **above** your heading.  

## [TOC]  
You can also create `TOC` by inserting `[TOC]` to your markdown file.  
For example:  
```markdown  

[TOC]  

# Heading 1
```
However, this way will only display TOC in preview, while leaving editor content unchanged.  

## Configuration  
* **orderedList**  
Use orderedList or not.  
* **depthFrom**, **depthTo**  
`[1~6]` inclusive.   

## Demo  
![toc](http://i.imgur.com/z1to5jy.gif)
