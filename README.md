# 21cs3053website
This repository contains website for learning different languages by calling to random users.

HTML 

<!DOCTYPE html>
<html>
<head>
<title>TalkLingo</title>
</head>
<body>
<div class="top-background">
    <div class="title">
  <h1><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT4hSgMh8CuiGpfePKdBBWgqseYekIWid1k_brJbYsDIRWt3X4DYPpEKW2J4ZANJ-NlanE&usqp=CAU" height=60 width=60>&emsp;&emsp;&emsp;&emsp;TALKLINGO </h1>
  
  </div> 
  
<div class="home">
    <p>Home    About     Contact     FAQ</p>
</div>
<!--<div class="quote">
      <h1>Practice makes perfect</h1>
  </div>-->
<div class="container">
      <form action="/" method="GET" class="form">
        <input type="search" placeholder="Search" class="search-field" />
        <button type="submit" class="search-button">
          <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ-rEOtukLmpjM4iXN_ARqpE3iSvwyrlAkTfw&usqp=CAU" height=20 width=20>
        </button>
      </form>
    </div>
</div>
<div class="selection">
    
    <h3><strong>PRACTICE NOW</strong></h3>
    </br>
    </br>
    <label>Language</label>
    <select name="Language">
        <option value="select">select</option>
        <option value="English">English</option>
        <option value="Hindi">Hindi</option>
        <option value="German">German</option>
        <option value="Telugu">Telugu</option>
        <option value="Punjabi">Punjabi</option>
    </select>
    </br>
    </br>
    <label>Level of user</label>
    <select name="level of user">
        <option value="select">select</option>
        <option value="1">1</option>
        <option value="2">2</option>
        <option value="3">3</option>
        <option value="4">4</option>
        <option value="5">5</option>
    </select>
    </br>
    </br>
    <label>Gender</label>
    <select name="Gender">
        <option value="select">select</option>
        <option value="male">male</option>
        <option value="female">female</option>
        <option value="any">any</option>
    </select>
    </br>
    </br>
    </br><div class="button">
    
    <input type="submit" name="submit" 
    value="Start"></div>
</div>
</div>
<!-- <div class="images">
<img src="https://www.shutterstock.com/image-vector/communication-smartphone-vector-illustration-260nw-524876680.jpg"width=75%>
</div>-->
</br>
<div class="intro">
    <p>a system of communication by speaking, writing, or making signs in a way that can be understood, or any of the different systems of communication used in particular regions: [ C ] the English language. [ C ] American Sign Language. [ C ] He speaks six foreign languages.a system of communication by speaking, writing, or making signs in a way that can be understood, or any of the different systems of communication used in particular regions: [ C ] the English language. [ C ] American Sign Language. [ C ] He speaks six foreign languages.</p>
</br></br>
<div class="copyright"><p>Copyright &#169 2023 TalkLingo</p></div>
</div>

    


</body>
</html>

------------------------------CSS-----------------------

*{
    margin:0;
}
.top-background{
    /*background-image:url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ0ezHVtLdcr14Hc0_MXyTNCUV6_7oR_UAaCA&usqp=CAU');
    */
    word-spacing:0.5em;
    padding:10px;
    width:100%;
    background:#22A39F;
    
    
    
}
.title{
    color:brown;
    font-family:Brush Script MT,Comic Sans MS;
    font-size:35px;
    
}
/*
.quote{
    color:red;
    font-family:Comic Sans MS;
    font-size:20px;
    float:right;
    width:25%;
    background-image:url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ0ezHVtLdcr14Hc0_MXyTNCUV6_7oR_UAaCA&usqp=CAU');
   
}*/
.home{
    font-size:20px;
    color:#ffffff;
    background:black;
    height:45px;
    padding:0.6em 3rem;
    font-family:sans-serif;
    
}
.intro{
    /*background-image:url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTrQYE2YnmbnLb-uvroHW95VBhv9zRyxk2bcQ&usqp=CAU');
    */
    width:100%;
    background:#F3EFE0;
    padding:20px;
    position:relative;
    margin-top:240px;
    
}
.selection{
    color:red;
    background:white;
    border:5px solid green;
    width:50%;
    margin:8px;
    height:250px;
    margin-left:10px;
    float:right;
    margin-right:25%;
    text-align:center;
    letter-spacing:4px;
    font-weight:bold;
    font-family:sans-serif;
    
  /*  background-image:url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS64RLKg148fT6kUl1KF2wVAvlfb0yP02l_Gg&usqp=CAU');
  */
  background:#434242;
  font-weight:bolder;
}
.button{
    color:blue;
}
.images{
    
    
}

.copyright{
    text-align:center;
    border:2px solid green;
    
}
* {
  /* Reset browser's padding and margin */
  margin: 0;
  padding: 0;
  box-sizing: border-box; 
}

body {
  
   /*background-image:url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTrQYE2YnmbnLb-uvroHW95VBhv9zRyxk2bcQ&usqp=CAU');
*/
background:#ADDDD0;
}

.container {
  margin: 10px auto;
  width: 500px;
  height: 25px
}

/* The point of this tutorial is here */
.form {
  display: flex;
  flex-direction: row;
}
.search-field {
  width: 100%;
  padding: 10px 50px 10px 15px;
  border: none;
  border-radius: 10px;
  outline: none;
}

.search-button {
  background: transparent;
  border: none;
  outline: none;
  margin-left: -30px;
}

.search-button img {
  width: 20px;
  height: 20px;
  object-fit: cover;
}
