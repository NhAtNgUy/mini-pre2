
<html>
<head>
<title>mini-presentation</title>
<meta name="viewport" content="initial-scale:1.0;width=device-width">
<style>
.bangtrencung {
    width: 97.7%;
    text-align: center;
    padding: 15px;
    font-family: Bernard MT Condensed;
    font-size: 30px;
    opacity: initial;
}
.img {
    box-shadow: 0px 10px 12px 0px black;
    width: 100%;
}
table , tr , td {
    border: 2px solid black;
    text-align: center;
    font-family:Bernard MT Condensed ;
    font-size: larger;
    text-align: center;
    margin: 40px auto;
    border-collapse: collapse;

}
td {
    transition: all 0.3s ease-out;
}
td:hover {background-color:chartreuse;transform: scale(1.1);}
h1 {
    border: 1px solid black;
    padding: 20px;
    text-align: center;
    width: 200px;
    background-color: rgb(64, 163, 163);
}

.div1 {
    animation-name:nguyen1 ;
    animation-duration: 2s;
    animation-iteration-count: infinite;
}
@keyframes nguyen1 {
    from {background-color:aquamarine}
    to {background-color:rgb(212, 51, 83)}
}

#Grad {
    background-image:linear-gradient(to right ,rgba(9, 214, 170, 0.938) , rgb(255, 248, 238));
}

.bangp2 {
    margin: 0 auto;
    border: 2px solid black;
    text-align: center;
    width: 650px;
    height: 150px;
    overflow: auto;
    background-color:antiquewhite ;
    font-family:Bernard MT Condensed ;
    font-size:larger;
    z-index: 1;
}
.body1 {
    display: flex;
    justify-content: center;
    align-items: center;
  }
  
  .iloveyou{
    font-family: "Arial", sans-serif;
    font-size: 50px;
    font-weight: bold;
    text-transform: uppercase;
    color:#f2f2f2;
  }
 
  .iloveyou span {
    display: inline;
    margin: 10px;
    transition: 0.3s ease-out;
  }
 
.div2 {
    animation-name:nhatnguyen1 ;
    animation-duration: 2s;
    animation-iteration-count: infinite;
}
@keyframes nhatnguyen1 {
    from {color: white;}
    to {color: #cf5123;}
}

#div3 {
    animation-name: nguyen2;
    animation: nguyen2 3s infinite;
    transition: all 0.3s ease-out;
}
@keyframes nguyen2 {
    30% {margin-left: 30px;}
}
.img1 {
    transition : all 0.3s ease-out ; 
}
.img1:hover {transform: scale(1.1);}

.layout_card { 
    max-width: 960px;  
    padding: 40px;
    margin: 0 auto;
}
.Column_card {
    display: grid;
    grid-template-columns: repeat(2,1fr);
    gap: 40px;
}
.Card { 
    background-color:#f2f2f2;
    border-radius: 6px;
    padding: 40px;
    box-shadow: 0px 8px 8px 0px rgb(49, 49, 49) ;
    transition: all 0.3s ease-out;
}
.img_end {
    transition: all 0.3s ease-out;
}
.Card:hover {transform:scale(1.2) ;}
.img_end:hover {transform: scale(1.25);}

.button { 
    text-align: center;
    border-radius: 10px;
    padding: 20px;
    background-color:rgba(255, 127, 80, 0.651) ;
    font-family:Bernard MT Condensed ;
    font-size: larger;
    transition:all 0.3s ease-out ;
    box-shadow: 0px 7px 7px 0px rgb(37, 37, 37) ;
    margin-left: 40%;
}
.preButton {
    text-align: center;
    border-radius: 10px;
    padding: 20px;
    background-color:rgba(255, 127, 80, 0.651) ;
    font-family:Bernard MT Condensed ;
    font-size: larger;
    transition:all 0.3s ease-out ;
    box-shadow: 0px 7px 7px 0px rgb(37, 37, 37) ;
}

.button:hover {transform: scale(1.1);}
.preButton:hover {transform: scale(1.1);}

.div4 {
    animation-name: nn;
    animation-duration:3s ;
    animation-iteration-count:infinite;
}
@keyframes nn { 
    from {background-color:darkorchid;}
    to {background-color:chartreuse;}
}
ul {
    top:0;
    position: sticky;
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow:hidden ;
    background-color: rgba(9, 214, 170, 0.938) ;
    border: 2px solid black;
    z-index: 2;
}
li {
    float: left;
}
li a {
    display: inline-block;
    text-align: center;
    text-decoration: none;
    padding: 20px;
    color: aliceblue;
    transition: all 0.3s ease-out;
    font-size: larger;
    font-family: Bernard MT Condensed;
}
li a:hover {background-color: rgb(142, 101, 180)}

.img_giua {
    margin: 40px auto;
}
</style>
</head>

 
    <ul >
        <li><a href="#Home">Introduction</a></li>
        <li><a href="#Overview">Bar Chart</a></li>
        <li><a href="#Hoc_van">Pie Chart</a></li>
        <li><a href="#4">Bubble Chart</a></li>
        <li><a href="#5">Logistic Regression</a></li>
        
    </ul>


<div><h1 id="div3" style="font-family:Bernard MT Condensed;border-radius: 12px;width:fit-content;box-shadow: 2px 7px 7px 0px black">1.Introduction </h1></div>
<p style="font-family:sans-serif;font-size: 30px ;" id="animation">     After having the discussion about the topic for the mini-presentation, 
    group 2 decide to choose the topic as “Can we predict school performance based on English capability? Can we guess English skills from school performance?”. What is more, this images below show our progress of the survey. </p>

    <div class="layout_card">
        <div class="Column_card">
            <img src="9d71a1349bb44fea16a5.jpg" class="img_end" alt="me" width=500px height=450px>

            <img src="fc83abdc915c45021c4d.jpg" class="img_end" alt="ME" width=500px height=450px>
        </div>
    </div>


<h id="Overview"></h>
<br>
<br>
<br>
<br>
<div id="div3"><h1 style="font-family:Bernard MT Condensed;border-radius: 16px;box-shadow: 2px 12px 10px 0px black;">2.Bar Chart </h1></div>
<p style="font-family:sans-serif;font-size: 30px ;">Because the number of students filling in each major is not the same, my group has divided the average GPA and English certificates. Here, it's the bar charts illustrate the AVG of 2 columns as GPA_point and CEFR_point.</p>
<center><img src="12e3b261c8e11cbf45f0.jpg" class="img_end" alt="me" width=800px height=450px></center>

<br>
<br>
<br>

<div class="body1">
    <div class="iloveyou div2" style="width:fit-content">
        <span>M</span>
        <span>I</span>
        <span>N</span>
        <span>I</span>
        <span>-</span>
        <span>P</span>
        <span>R</span>
        <span>E</span>
        <span>S</span>
        <span>E</span>
        <span>N</span>
        <span>T</span>
        <span>A</span>
        <span>T</span>
        <span>I</span>
        <span>O</span>
        <span>N</span>
    </div>
</div>
<h id="Hoc_van"></h>
<br>
<br>
<br>
<br>
<div id="div3"><h1 id="Hoc_van" style="font-family:Bernard MT Condensed;width:fit-content;border-radius: 16px;box-shadow: 2px 12px 10px 0px black;">3.Pie chart </h1></div>
<p style="font-family:sans-serif;font-size: 30px ;">The pie chart illustrates the average performance rate per classes in HSB. Moreover, we can obviously see that from the chart there are 4 main classes.</p>
<center><img src="384e96ccec4c3812615d.jpg" class="img_end" alt="me" width=600px height=550px></center>
<h id="4"></h>
<br>
<br>
<br>
<br>
<div id="div3"><h1 style="font-family:Bernard MT Condensed;border-radius: 16px;width:fit-content;box-shadow: 2px 12px 10px 0px black;">4.Bubble chart </h1></div>
<p style="font-family:sans-serif;font-size: 30px ;">The provided data allows us to create a bubble chart that compares the CEFR points (X-axis) and GPA points (Y-axis) based on the "Program" column. Additionally, we will utilize the "OVR_Performance" column to determine the size of each bubble. </p>
<center><img src="9421ddbda73d73632a2c.jpg" class="img_end" alt="me" width=800px height=450px></center>
<h id="5"></h>
<br>
<br>
<br>
<br>
<div id="div3"><h1 id="Hoc_van" style="font-family:Bernard MT Condensed;border-radius: 16px;width:fit-content;box-shadow: 2px 12px 10px 0px black;">5.Logistic Regression </h1></div>
<p style="font-family:sans-serif;font-size: 30px ;">Particularly, we only apply the machine learning of the Logistic Regression to predict 2 kinds of students as good and not bad. As you can see in my screen here, this is our model and we use the data based on our survey.</p>
<div class="layout_card">
    <div class="Column_card">
        <img src="d9db6c4316c3c29d9bd2.jpg" class="img_end" alt="me" width=600px height=450px>

        <img src="70d2ca4ab0ca64943ddb.jpg" class="img_end" alt="ME" width=500px height=450px>
    </div>
</div>
</body>
</html>
