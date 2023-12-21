# Ex-06-Book-Cover-Design
# Aim:
To create a book cover design using Html and Css code's
## Step1:
Select an image from online and make it as background image
## Step2:
Using vs code create a html and css files
## Step3:
Try some designs and some font over the image
## Step4:
Give the author name and photo down below the book cover
## Step5:
Run the Html Program to see the results
# Program:

book.html::
```
<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="book.css">
</head>
<body>
   

<h1>Expert insight</h1>
<hr>
<p align="center"><b>Responsive Web Design with HTML5 and CSS</b></p>
<div class="direct">
  Develop future-proof responsive websites using latest html and css techniques
</div>


<div class="edit">
  Third Edition
  <img src="MyPic.jpg" alt="">
  <hr>
  
</div>
<div class="name">
  PYNAM VINODH
</div>


</body>
</html>


```
book.css:
```
body {
    background-image: url("background.jpg");
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
    margin-left: 100px;
    color:  white;
  }
  
  .edit {
    position: sticky;
    left: 0;
    font-size: 50px;
    color: orange;
      }
  
  h1 {
    color: white;
    font-size: 50px;
  }
  p {
     
     font-size: 100px;
  }
  
  .direct {
    font-size: 50px;
  }
  img {
    bottom: 200px;
    margin-bottom: 100px;
    margin-right: 100px;
    float: right;
  }
  .create {
    position: fixed;
    right: 0;
    margin-bottom: 20px;
    margin-right: 100px;
    bottom: 100px; 
    color: white; 
  }
 .name {
  position: fixed;
  left: 0;
  margin-bottom: 200px;
  margin-left: 100px;
  bottom: 20px; 
  color: white; 
  font-size: 50px;

 }
```
 }
# Output:
  ![BookCover](https://github.com/PYNAMVINODH/Ex-06-Book-Cover-Design/assets/145742678/c72723ef-859e-44fe-b454-0bf84cf4cfdf)





 
