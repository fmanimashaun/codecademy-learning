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

## Fundamental of HTML
### Important tags to pay attention to
* The ```<em>``` tag will generally render as italic emphasis, it is used to emphasize text
* The  ```<strong>``` will generally render as bold emphasis, it is use to highlight important text
* The ```<video src="myVideo.mp4" width="320" height="240" controls>Video not supported</video>``` is a used to render video content on the screen with play control
* The use of anchor tag can be seen as ```<a href="URL" target="_blank">Desired content to anchor</a>``` the ```target``` attribute with value ```"_blank"``` opens a new window/tab whenever the anchor tag content is clicked on in the browser
* The use of ```<!-- add your comment here -->``` to introduce comments into html file
* ```<div>``` vs ```<section>``` if we are introducing container for sole purpose of styling one, the use ```<div>``` is sufficient, else,  ```<section>``` should be use.

### Standard HTML Structure
* The html document starts with a document declaration ```<!DOCTYPE html>``` to indicate the file is an HTML 5 documents
* The ```<html></html>```is initiated to house the full html structure 
* ```./``` in the sample code ```<a href="./contact.html">Contact</a>``` tells the browser to look for the ```contact.html``` file in the current directory/folder

### Understanding HTML Table
Sample code snippet below:
```
<table>
  <thead>
    <tr>
      <th>Quarter</th>
      <th>Revenue</th>
      <th>Costs</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Q1</th>
      <td>$10M</td>
      <td>$7.5M</td>
    </tr>
    <tr>
      <th>Q2</th>
      <td>$12M</td>
      <td>$5M</td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <th>Total</th>
      <td>$22M</td>
      <td>$12.5M</td>
    </tr>
  </tfoot>
</table>
```


