# EXP 01 - PORTFOLIO

## AIM:

To create a portfolio using HTML and CSS

## ALGORITHM:

1. Set up the basic structure of your HTML document.

2. Create a CSS file named "styles.css" and link it to your HTML document. This file will contain the CSS rules for styling your portfolio.

3. Design the layout of your portfolio using HTML elements such as < header >, < nav >, < section >, < article >, and < footer >. Use appropriate classes or IDs to style these elements later with CSS.

4. Add a header section to display your name or the title of your portfolio.

5. Add images or media to enhance your portfolio. You can use the <img> tag to display images and embed videos or other media using appropriate HTML tags.

6. Apply responsive design techniques to ensure your portfolio looks good on different devices and screen sizes. Use CSS media queries to adjust the layout and styling as needed.

7. Apply CSS styling to your portfolio elements by targeting their respective classes or IDs in the "styles.css" file. Customize the colors, fonts, spacing, and other visual properties to match your desired design.

## CODE:
### HTML CODE:
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>Portfolio</title>
        <link rel="stylesheet" href="main.css">
    </head>
    <body style="background-color: rgb(255, 255, 255);font-size:0px;">
        <center>
            <img src="pic1.png" alt="pic1" style="height:800px; width:1400px">
            <div class="A">
                <p>PORTFOLIO</p>
            </div>
            <div class="B">
                <p>_______________________________________</p>
            </div>
            <div>
                <img src="pic2.png" alt="pic2" style="height:800px; width:1400px">
                <div class="C">
                    <p>About me</p>
                </div>
                <div class="D">
                    <p>Student in Artificial Intelligence & Machine Learning.<br/>
                    I consider myself responsible and hardworking person.I am a <br/>mature team
                     worker and adaptive to the working environment.<br/>
                  Looking forward to take part in AI related projects. </p>
                </div>
                <div class="E">
                    <p>Carrier Objective</p>
                </div>
                <div class="F">
                    <p>To work in a challenging environment that provides ground to<br/>
                         implement my expertise and creativity to attain a high rank in the company<br/>
                          as well as in the society.</p>
                </div>
            </div> 
            <div>
                <img src="pic3.png" alt="pic2" style="height:800px; width:1400px">
                <div class="G">
                    <p>Education<br/> Background</p>
                </div>
                <div class="H">
                    <p><b>2021-2025</b></p>
                </div>
                <div class="h1">
                    <p><b>~SAVEETHA ENGINEERING COLLEGE</b></p>
                </div>
                <div class="h2">
                    <p><li>Bachelor of Technology</li></p>
                </div>
                <div class="h3">
                    <p>(Artificial Intelligence and Machine<br>Learning, in progress)</p>
                </div>
                <div class="I">
                    <p><b>2019-2021</b></p>
                </div>
                <div class="i1">
                    <p><b>~DEVI ACADEMY<br> SENIOR SECONDARY SCHOOL</b></p>
                </div>
                <div class="i2">
                    <p><li>Secondary School</li></p>
                    <p><li>Higher Secondary Schools</li></p>
                </div> 
            </div>  
            <div >
                <img src="pic4.png" alt="pic4" style="height:800px; width:1400px">
                <div class="J">
                    <p><b>WORK EXPERIENCE</b></p>
                </div>
                <div class="j1">
                    <p><u>Monolith Technologies</u></p>
                </div>
                <div class="j2">
                    <ol>- I had the chance to work with a team of<br/> four people during my internship under
                        the<br/> direction of Mr.Dheepan.</ol>
                    <ol>- We concentrated on learning about AR/VR<br/> gadgets and their application.</ol>
                    <ol>- Our primary endeavour involves making a<br/> contribution to a study whether
                        or not<br/> dopamine levels rise after engaging in<br/> virtual reality.</ol>
                </div>
            </div>
            <div >
                <img src="pic5.png" alt="pic5" style="height:800px; width:1400px">
                <div class="K">
                    <p><b>Technical skills</b></p>
                </div>
                <div class="k1">
                    <li>C Programming</li><br/>
                    <li>Python</li><br/>
                    <li>Web Designing</li><br/>
                    <li>Product Development</li><br/>
                    <li>3D Printing</li><br/>
                    <li>Excel Sheet</li><br/>
                </div>
                <div class="L">
                    <p><b>Soft skills</b></p>
                </div>
                <div class="l1">
                    <li>Adaptivity</li><br/>
                    <li>Time Management</li><br/>
                    <li>Creative</li><br/>
                    <li>Problem Solving Skills</li><br/>
                    <li>Critical Thinking</li><br/>
                    <li>Self-motivated</li><br/>
                </div>
            </div>
            <div>
                <img src="last.jpg" alt="last" style="height:400px; width:1400px">
                <div class="M">
                    <p><b>Contact Information</b></p>
                </div>
                <div class="m1">
                    <p><b>Address :</b></p>
                    <p><b>Phone :</b></p>
                    <p><b>Email :</b></p>
                </div>
                
                <div class="m2">
                    <p>No.23/114c,Bharathidasan Street,Valasaravakkam,ch-87</p>
                    <p>7338993846</p>
                    <p>swethamohanraj63@gmail.com</p>
                </div>
            </div>
        </center>
    </body>
</html>
```



### CSS CODE:
```
.A
{
    position: absolute;
    font-size:100px;
    top: 190px;
    color: #000000;
    padding-left:630px;
    line-height: 0.4px;
}
.B
{
    position:absolute;
    font-size:30px;
    top:280px;
    color: black;
    padding-left:600px;

}
.C
{
    position:absolute;
    font-size:70px;
    top:800px;
    color: #f38282;
    padding-left:180px; 
    font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}
.D
{
    position:absolute;
    font-size:30px;
    top:940px;
    color: #000000;
    padding-left:280px;
    text-align-last: left;
}
.E
{
    position:absolute;
    font-size:70px;
    top:1150px;
    color: #f38282;
    padding-left:180px; 
    font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif
}
.F
{
    position:absolute;
    font-size:30px;
    top:1300px;
    color: #000000;
    padding-left:280px;
    text-align-last: left;
}
.G
{
    position:absolute;
    font-size:70px;
    top:1650px;
    color: #d78585;
    padding-left:550px; 
}
.H
{
    position:absolute;
    font-size:35px;
    top:1990px;
    color: #574b4b;
    padding-left:370px;
    text-align-last: left; 
}
.h1
{
    position:absolute;
    font-size:26px;
    top:2070px;
    color: #000000;
    padding-left:220px;
      
}
.h2
{
    position:absolute;
    font-size:28px; 
    top:2110px;
    color: #000000;
    padding-left:310px;
}
.h3
{
    position:absolute;
    font-size:25px;
    top:2157px;
    color: #000000;
    padding-left:255px;
}
.I
{
    position:absolute;
    font-size:35px;
    top:1990px;
    color: #574b4b;
    padding-left:910px;
    text-align-last: left; 
}
.i1
{
    position:absolute;
    font-size:26px;
    top:2066px;
    color: #000000;
    padding-left:800px;
      
}
.i2
{
    position:absolute;
    font-size:28px; 
    top:2145px;
    color: #000000;
    padding-left:850px;
    line-height: 0.5;
    text-align: left;
}
.J
{
    position:absolute;
    font-size:40px; 
    top:2530px;
    color: #000000;
    padding-left:850px;
    line-height: 0.5;
}
.j1
{
    position:absolute;
    font-size:30px; 
    top:2620px;
    color: #d78585;
    padding-left:910px;
    line-height: 0.5; 
}
.j2
{
    position:absolute;
    font-size:25px; 
    top:2690px;
    color: #000000;
    padding-left:800px;
    text-align-last: left; 
}
.K
{
    position:absolute;
    font-size:40px; 
    top:3350px;
    color: #000000;
    padding-left:800px;
    
}
.k1
{
    position:absolute;
    font-size:25px; 
    top:3450px;
    color: #000000;
    padding-left:820px;
    text-align: left;
    line-height:15px;
    
}
.L
{
    position:absolute;
    font-size:40px; 
    top:3620px;
    color: #000000;
    padding-left:800px;
    
}
.l1
{
    position:absolute;
    font-size:25px; 
    top:3720px;
    color: #000000;
    padding-left:820px;
    text-align: left;
    line-height:15px;   
}
.M
{
    position:absolute;
    font-size:45px;
    top:4000px;
    color: #000000;
    padding-left:220px;
    text-align: left;   
}
.m1
{
    position:absolute;
    font-size:25px; 
    top:4100px;
    color: #000000;
    padding-left:320px;
}
.m2
{
    position:absolute;
    font-size:25px; 
    top:4100px;
    color: #000000;
    padding-left:430px;
    text-align: left;
}
```



## OUTPUT:
![image](https://github.com/swethamohanraj/Portfolio/assets/94228215/5c5be064-bec0-448f-a5df-071cb57ebb58)
![image](https://github.com/swethamohanraj/Portfolio/assets/94228215/65ea870a-8dba-433d-95c5-bad79d87e04c)
![image](https://github.com/swethamohanraj/Portfolio/assets/94228215/7fad88b6-67a3-49a8-b18c-589a9d20876e)
![image](https://github.com/swethamohanraj/Portfolio/assets/94228215/52aad6e7-0c27-4372-a016-1366d09a3e67)
![image](https://github.com/swethamohanraj/Portfolio/assets/94228215/1374e017-d971-47dd-8591-ad8f92cc819a)



## RESULT:

Thus, a Portfolio is created using HTML and CSS.
