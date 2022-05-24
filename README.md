# codecademy-learning
My Codecademy Learning Diary

## Useful resources
* Practice interview technical interview questions [Leetcode link](https://leetcode.com/)
* Textbook in javascript [Eloquent JavaScript - 3rd edition (2018)](https://eloquentjavascript.net/)
* Textbook in HTML/CSS [Learn to Code HTML & CSS](https://learn.shayhowe.com/)
* Textbook in HTML/CSS [HTML & CSS IS HARD](https://www.internetingishard.com/)
* HTML/CSS/Javascript reference documentation [Mozilla Developer Network](https://developer.mozilla.org/en-US/)
* HTML Code validator tool [HTML validation](https://validator.w3.org/)
* HTML Elements Documentation [MDN HTML Docs](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
* Learn CSS [Jen Kramer's Courses](https://frontendmasters.com/teachers/jen-kramer/)

## Fundamental of HTML
### Important tags to pay attention to
* The ```<em>``` tag will generally render as italic emphasis, it is used to emphasize text
* The  ```<strong>``` will generally render as bold emphasis, it is use to highlight important text
* The ```<video src="myVideo.mp4" width="320" height="240" controls>Video not supported</video>``` is a used to render video content on the screen with play control
* The ```<audio src="myAudio.mp4" type="audio/mp3" controls>Audio not supported</audio>``` is a used to render audio content on the screen with play control
* But for multiple audio sources, you can use the following code
  ```<audio controls><source src="url.mp3" type="audio/mp3"></audio>```
* The use of anchor tag can be seen as ```<a href="URL" target="_blank">Desired content to anchor</a>``` the ```target``` attribute with value ```"_blank"``` opens a new window/tab whenever the anchor tag content is clicked on in the browser
* The use of ```<!-- add your comment here -->``` to introduce comments into html file
* ```<div>``` vs ```<section>``` if we are introducing container for sole purpose of styling one, the use ```<div>``` is sufficient, else,  ```<section>``` should be use.

### Standard HTML Structure
* The html document starts with a document declaration ```<!DOCTYPE html>``` to indicate the file is an HTML 5 documents
* The ```<html></html>```is initiated to house the full html structure 
* ```./``` in the sample code ```<a href="./contact.html">Contact</a>``` tells the browser to look for the ```contact.html``` file in the current directory/folder

### Understanding HTML Table

* The ```<table>``` element creates a table.
* The ```<tr>``` element adds rows to a table.
* To add data to a row, you can use the ```<td>``` element.
* Table headings clarify the meaning of data. Headings are added with the ```<th>``` element.
* Table data can span columns using the ```colspan``` attribute.
* Table data can span rows using the ```rowspan``` attribute.
* Tables can be split into three main sections: a head, a body, and a footer.
* A table’s head is created with the ```<thead>``` element.
* A table’s body is created with the ```<tbody>``` element.
* A table’s footer is created with the ```<tfoot>``` element.
Sample code snippet below:
```html
<table>
  <!--Below code create the table header (thead) section that houses Column's title-->
  <thead>
    <!--belw code create the table header row (tr) that houses each Column's title as shown with (th) tags-->
    <tr>
      <th>Quarter</th>
      <th>Revenue</th>
      <th>Costs</th>
    </tr>
    <!--End of header row-->
  </thead>
  <!--End of table header section row-->
  
  <!--Below code create the table body section that housses the table data-->
  <tbody>
    <!-- each (tr) tag creates a row of data with td/th represent a cell in a row-->
    <tr>
      <!--
        a colspan/rowsppanattribute can be added to the th/td/tr to marge 2 or more cells together
        either vertically in the case of (tr) or horizontally in the case of td/th see example below:
        <tr rowspan="2"></tr> will merge to cells together vertically with  <tr colspan="2"></tr> will
        merge 2 cells together horizonatally
       -->
      <th>Q1</th>
      <td>$10M</td>
      <td>$7.5M</td>
    </tr>
    <!--End of first row of data-->
    <!--Start of a new row-->
    <tr>
      <th>Q2</h>
      <td>$12M</td>
      <td>$5M</td>
    </tr>
    <!--End of another row-->
  </tbody>
  <!--End of table body section-->
  <!--Table footer to show table summary like some or count or other summary statistics-->
  <tfoot>
    <tr>
      <th>Total</th>
      <td>$22M</td>
      <td>$12.5M</td>
    </tr>
  </tfoot>
<!--End of footer-->
</table>

```

### HTML Sematics Summary
* Semantic HTML introduces meaning to a page through specific elements that provide context as to what is in between the tags.
* Semantic HTML is a modern standard and makes a website accessible for people who use screen readers to translate the webpage and improves your website’s SEO.
* ```<header>, <nav> , <main> and <footer>``` create the basic structure of the webpage.
* ```<section>```< defines elements in a document, such as chapters, headings, or any other area of the document with the same theme.
* ```<article>```< holds content that makes sense on its own such as articles, blogs, comments, etc.
* ```<aside>```< contains information that is related to the main content, but not required in order to understand the dominant information.
* ```<figure>```< encapsulates all types of media.
* ```<figcaption>``` is used to describe the media in ```<figure>```.
* ```<video>, <embed>, and <audio>``` elements are used for media files.


