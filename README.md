# Web Design for a Software Product Company

# AIM:

To design a static website for a software product company company.

# DESIGN STEPS:

## Step 1:

Requirement collection.

## Step 2:

Creating the layout using HTML and CSS.

## Step 3:

Updating the sample content.

## Step 4:

Choose the appropriate style and color scheme.

## Step 5:

Validate the layout in various browsers.

## Step 6:

Validate the HTML code.

## Step 6:

Publish the website in the given URL.

# PROGRAM :
## home-site.html:

```
<html>
    <head>
        <title>Gymania</title>
        <style type="text/css">
            body{background-color: black;}
           
            .box{background-color: rgb(0, 0, 0);
            display: flex;
            height:100px;
            width:1520px;
            position: relative;
            margin-left: auto;
            margin-right: auto;
            margin-bottom: 10px;
            opacity: 0.8;
            }
            footer{
                background-color: rgb(0, 0, 0);
            color: aliceblue;
            font-size:medium;
            text-align: center;
            margin-left: -750px;
           margin-right: 245px;
            margin-top: 698px;
            
            height:27px;
            width:1000px;
            

            }
            .b-img{
            background-image: url(home-img.jpg);
            background-repeat: no-repeat;
            background-size: contain;
            background-color: rgb(0, 0, 0);
            background-position: center;
            position:absolute;
            height:725px;
            width:1520px;
            display: flex;
            object-fit: cover;
           
           
            background-size:cover;}
            .home{
                font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
                color: red;
                font-weight: bolder;
                font-size: larger;   
            }
            .contact{
            height:20px;
            width:35%;
            position:relative;
        
            top:10px;
            left:850px;
            border:4px solid rgb(255, 0, 0);
            text-align:center;
            padding:15px;
            font-family:'Gill Sans MT';
            font-size: large;  
        }
        .contact:hover{
            background-color:rgb(84, 84, 84);
        }

        .home1{
            height:20px;
            width:10%;
            position:relative;
            background-color: rgb(54, 50, 50);
            top:10px;
            left:100px;
            border:4px solid rgb(255, 0, 0);
            text-align:center;
            padding:15px;
            font-family:'Gill Sans MT';
            font-size: large;  
        }
        .home1:hover{
            background-color:rgb(84, 84, 84);
        }

        .product{
            height:20px;
            width:10%;
            position:relative;
        
            top:10px;
            left:350px;
            border:4px solid rgb(255, 0, 0);
            text-align: center;
            padding:15px;
            font-family:'Gill Sans MT';
            font-size: large;  
        }
        .product:hover{
            background-color:rgb(84, 84, 84);
        }

        .about{
            height:20px;
            width:30%;
            position:relative;
        
            top:10px;
            left:600px;
            border:4px solid rgb(255, 0, 0);
            text-align:center;
            padding:15px;
            font-family:'Gill Sans MT';
            font-size: large;  
        }
        .about:hover{
            background-color:rgb(84, 84, 84);
        }

        h1{font-size: xxx-large; color: rgb(255, 0, 0);
        font-style: italic;
        margin-top: 200px;
        opacity: 0.9;
         font-family: Aboreto;
        font-weight: bolder;
         text-align: center;}

         h2{font-size: xxx-large; color: rgb(255, 0, 0);
        font-style: italic;    
        padding-top: 0px;
        padding-bottom: 30px;
        opacity:0.9;
         font-family:Aboreto;
        font-weight: bolder;
         text-align: center;}

         h3{color: aliceblue;
        text-align: center;}
        p{color:aliceblue;
        font-size:25px;
        text-align: center;
        
        background-color: black;
        width: 500px;
        -webkit-text-fill-color:rgb(255, 255, 255);
        -webkit-text-stroke-color: rgb(106, 106, 106);
        -webkit-text-stroke-width: 0.5px;
        
        }
         

            </style>
    </head>
    <body>
        <div class="b-img">
            
         <div class="box">
            
            <div class="home1">
                <a href="home-site.html" title="Home" style="color:rgb(255, 0, 0); text-decoration: none;"><b>HOME</b></a>
            </div>

            <div class="product">
                <a href="products.html" title="Products" style="color:rgb(255, 7, 7); text-decoration: none;"><b>PRODUCTS</b></a>
            </div>

            <div class="about">
                <a href="about_us.html" title="About Us" style="color:rgb(255, 0, 0); text-decoration: none;"><b>ABOUT US</b></a>
            </div>
        
            <div class="contact">
                <a href="contact_us.html" title="Contact Us" style="color:rgb(255, 0, 0); text-decoration: none;"><b>CONTACT US</b></a>
            </div> 
             
            <div>
                <center>
                    
                    <h1>Gymania</h1>
                    
                    <p><br>Here you can browse different types of<br> gym accessories for home work-out,<br> gym wears and gym supplements powders for beginners</p>
                
                </center>
                
            </div> 
           
           
             <div>
                
                <center>
                
                <footer class="footer">&COPY; Copyrights,Roobesh Rao.E.D</footer>
                </center>
             </div>

             
             
         
         
         
    
        </div>
        
    </body>  
</html>
```

## products.html:

```
<html>
    <head>
        <title>Gymania</title>
        <style type="text/css">
            body{background-color: black;}
           
            
            footer{
                background-color: rgb(0, 0, 0);
            color: aliceblue;
            font-size:medium;
            text-align: center;
            margin-left: -750px;
           margin-right: 245px;
            margin-top: 698px;
            
            height:27px;
            width:1000px;
            

            }
            .b-img{
            background-image: url(maxresdefault.jpg);
            background-repeat: no-repeat;
            background-size: contain;
            background-color: rgb(0, 0, 0);
            background-position: center;
            position:absolute;
            height:725px;
            width:1520px;
            display: flex;
            object-fit: cover;
            background-size:cover;}

            .box{background-color: rgb(0, 0, 0);
            display: flex;
            height:100px;
            width:1520px;
            position: relative;
            margin-left: auto;
            margin-right: auto;
            margin-bottom: 10px;
            opacity: 0.8;
            }

           
           
            .home{
                font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
                color: red;
                font-weight: bolder;
                font-size: larger;   
            }
            .contact{
            height:20px;
            width:35%;
            position:relative;
        
            top:10px;
            left:850px;
            border:4px solid rgb(255, 0, 0);
            text-align:center;
            padding:15px;
            font-family:'Gill Sans MT';
            font-size: large;  
        }
        .contact:hover{
            background-color:rgb(84, 84, 84);
        }

        .home1{
            height:20px;
            width:10%;
            position:relative;
        
            top:10px;
            left:100px;
            border:4px solid rgb(255, 0, 0);
            text-align:center;
            padding:15px;
            font-family:'Gill Sans MT';
            font-size: large;  
        }
        .home1:hover{
            background-color:rgb(84, 84, 84);
        }

        .product{
            height:20px;
            width:10%;
            position:relative;
            background-color: rgb(54, 50, 50);
            top:10px;
            left:350px;
            border:4px solid rgb(255, 0, 0);
            text-align: center;
            padding:15px;
            font-family:'Gill Sans MT';
            font-size: large;  
        }
        .product:hover{
            background-color:rgb(84, 84, 84);
        }

        .about{
            height:20px;
            width:30%;
            position:relative;
        
            top:10px;
            left:600px;
            border:4px solid rgb(255, 0, 0);
            text-align:center;
            padding:15px;
            font-family:'Gill Sans MT';
            font-size: large;  
        }
        .about:hover{
            background-color:rgb(84, 84, 84);
        }          
        
        img{width: 150px;
        height: 150px;
        }
        .img-text{color: aliceblue;
        text-align: center;
         font-size: large;
         
        }

        .creatin{margin-top: 100px;
        margin-left: -500px;
        margin-right: 800px;
        background-color:rgb(255, 0, 0);
        }
        .ad{margin-top: -170px;
        margin-left: -250px;
        margin-right: 550px;
        background-color:rgb(255, 0, 0);}

        .bb{margin-top: -190px;
        margin-left: 0px;
        margin-right: 300px;
        
        background-color:rgb(255, 0, 0);}

        .hoodie{margin-top: -170px;
        margin-left: 250px;
        margin-right: 50px;
        opacity:1;
        background-color:rgb(255, 0, 0);}

        .abw{margin-top: -190px;
        margin-left: 500px;
        margin-right: -200px;
        opacity:1;
        background-color:rgb(255, 0, 0);}

        .whey{margin-top: -190px;
        margin-left: 750px;
        margin-right: -450px;
        
        opacity:1;
        background-color:rgb(255, 0, 0);}

        .res{margin-top: -170px;
        margin-left: 500px;
        margin-right: -200px;
        opacity:1;
        background-color:rgb(255, 0, 0);}

        .tdm{margin-top: -170px;
        margin-left: 750px;
        margin-right: -450px;
        opacity:1;
        background-color:rgb(255, 0, 0);}

        </style>
        </head>
        <body>
            <div class="b-img">
                
            
                    <div class="box">
                       
                       <div class="home1">
                           <a href="home-site.html" title="Home" style="color:rgb(255, 0, 0); text-decoration: none;"><b>HOME</b></a>
                       </div>
           
                       <div class="product">
                           <a href="products.html" title="Products" style="color:rgb(255, 7, 7); text-decoration: none;"><b>PRODUCTS</b></a>
                       </div>
           
                       <div class="about">
                           <a href="about_us.html" title="About Us" style="color:rgb(255, 0, 0); text-decoration: none;"><b>ABOUT US</b></a>
                       </div>
                   
                       <div class="contact">
                           <a href="contact_us.html" title="Contact Us" style="color:rgb(255, 0, 0); text-decoration: none;"><b>CONTACT US</b></a>
                       </div> 
                        
                      <div class="img-text">
                        <div class="creatin">
                           <img src="creatin.jpg" title="Creatin">Creatin</img>
                        </div>
                        <div class="ad">
                            <img src="Adjustable Dumbbells.webp" title="Adjustable Dumbbells">Adjustable Dumbbells</img>
                         </div>

                        <div class="bb">
                            <img src="Barbell.jpg" title="Barbell">Barbell</img>
                        </div>

                        <div class="hoodie">
                           <img src="Hoodie.png" title="Compression Hoodie">Compression Hoodie</img>
                        </div>
                        <div class="abw">
                            <img src="Abdominal double wheel.webp" title="Compression Hoodie">Compression Hoodie</img>
                         </div>
                         <div class="whey">
                            <img src="Whey-protien.jfif" title="Whey Protein">Whey protein</img>
                         </div>
                         <div class="creatin">
                            <img src="Compression T-Shirt.jpg" title="Compression T-Shirt">Compression T-Shirt</img>
                         </div>
                         <div class="ad">
                            <img src="Bells.jfif" title="Bells">Bells</img>
                         </div>
                         <div class="bb">
                            <img src="Dumbbels-classic.jpg" title="Dumbbels-classic">Dumbbels-classic</img>
                        </div>
                        <div class="hoodie">
                            <img src="Pull-up Bar.jpg" title="Pull-up Bar">Pull-up Bar</img>
                         </div>
                         <div class="res">
                            <img src="Resistance Bands.webp" title="Resistance Bands">Resistance Bands</img>
                         </div>
                         <div class="tdm">
                            <img src="Treadmills.jpg" title="Treadmills">Treadmills</img>
                         </div>
                         
                      </div>
                      
                      
                        <div>
                           
                           <center>
                           
                           <footer class="footer">&COPY; Copyrights,Roobesh Rao.E.D</footer>
                           </center>
                        </div>
                    </div>    
           
                        
                        
                    
                    
                    
               
                  
            </div>
            </body>    
```
## about_us.html:

```
<html>
    <head>
        <title>Gymania</title>
        <style type="text/css">
            body{background-color: black;}
           
            
            footer{
                background-color: rgb(0, 0, 0);
            color: aliceblue;
            font-size:medium;
            text-align: center;
            margin-left: -750px;
           margin-right: 245px;
            margin-top: 698px;
            
            height:27px;
            width:1000px;
            

            }
            .b-img{
            background-image: url(about.jpg);
            background-repeat: no-repeat;
            background-size: contain;
            background-color: rgb(0, 0, 0);
            background-position: center;
            position:absolute;
            height:725px;
            width:1520px;
            display: flex;
            object-fit: cover;
            background-size:cover;}

            .box{background-color: rgb(0, 0, 0);
            display: flex;
            height:100px;
            width:1520px;
            position: relative;
            margin-left: auto;
            margin-right: auto;
            margin-bottom: 10px;
            opacity: 0.8;
            }

           
           
            .home{
                font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
                color: red;
                font-weight: bolder;
                font-size: larger;   
            }
            .contact{
            height:20px;
            width:35%;
            position:relative;
        
            top:10px;
            left:850px;
            border:4px solid rgb(255, 0, 0);
            text-align:center;
            padding:15px;
            font-family:'Gill Sans MT';
            font-size: large;  
        }
        .contact:hover{
            background-color:rgb(84, 84, 84);
        }

        .home1{
            height:20px;
            width:10%;
            position:relative;
        
            top:10px;
            left:100px;
            border:4px solid rgb(255, 0, 0);
            text-align:center;
            padding:15px;
            font-family:'Gill Sans MT';
            font-size: large;  
        }
        .home1:hover{
            background-color:rgb(84, 84, 84);
        }

        .product{
            height:20px;
            width:10%;
            position:relative;
        
            top:10px;
            left:350px;
            border:4px solid rgb(255, 0, 0);
            text-align: center;
            padding:15px;
            font-family:'Gill Sans MT';
            font-size: large;  
        }
        .product:hover{
            background-color:rgb(84, 84, 84);
        }

        .about{
            height:20px;
            width:30%;
            position:relative;
            background-color: rgb(54, 50, 50);
            top:10px;
            left:600px;
            border:4px solid rgb(255, 0, 0);
            text-align:center;
            padding:15px;
            font-family:'Gill Sans MT';
            font-size: large;  
        }
        .about:hover{
            background-color:rgb(84, 84, 84);
        }          
        
        img{width: 200px;
        height: 200px;
        }
        .img-text{color: aliceblue;
        text-align: center;
         font-size: large;
         
        }

        .creatin{margin-top: 100px;
        margin-left: -400px;
        margin-right: 700px;
        background-color:rgb(255, 0, 0);
        }
        .ad{margin-top: -222px;
        margin-left: 100px;
        margin-right: 200px;
        background-color:rgb(255, 0, 0);
        }

        .bb{margin-top: -241px;
        margin-left: 700px;
        margin-right: -400px;
        
        background-color:rgb(255, 0, 0);}

        
        </style>
        </head>
        <body>
            <div class="b-img">
                
            
                    <div class="box">
                       
                       <div class="home1">
                           <a href="home-site.html" title="Home" style="color:rgb(255, 0, 0); text-decoration: none;"><b>HOME</b></a>
                       </div>
           
                       <div class="product">
                           <a href="products.html" title="Products" style="color:rgb(255, 7, 7); text-decoration: none;"><b>PRODUCTS</b></a>
                       </div>
           
                       <div class="about">
                           <a href="about_us.html" title="About Us" style="color:rgb(255, 0, 0); text-decoration: none;"><b>ABOUT US</b></a>
                       </div>
                   
                       <div class="contact">
                           <a href="contact_us.html" title="Contact Us" style="color:rgb(255, 0, 0); text-decoration: none;"><b>CONTACT US</b></a>
                       </div> 
                        
                      <div class="img-text">
                        <div class="creatin">
                           <img src="mathi.jfif" title="Mathi">Mathi (Friend)</img>
                        </div> 
                        <div class="ad">
                            <img src="me-2.jpg" title="Roobesh Rao.E.D">Roobesh Rao.E.D (Ownner)</img>
                         </div>
                         <div class="bb">
                            <img src="bharath1.jpg" title="Bharathwaj Reddy">Bharathwaj Reddy (Friend)</img>
                        </div>
                        <div class="creatin">
                            <img src="unnamed.jpg" title="Alex Eubank">Alex Eubank (Model)</img>
                         </div>
                         <div class="ad">
                            <img src="jeff.jpg" title="Jeff Seid">Jeff Seid (Model)</img>
                         </div>
                         <div class="bb">
                            <img src="dave1.jpg" title="David Laid">David Laid (Model)</img>
                        </div>
                         
                      </div>
                      
                      
                        <div>
                           
                           <center>
                           
                           <footer class="footer">&COPY; Copyrights,Roobesh Rao.E.D</footer>
                           </center>
                        </div>
                    </div>    
           
                        
                        
                    
                    
                    
               
                  
            </div>
            </body>    
```
## contact_us.html:

```
<html>
    <head>
        <title>Gymania</title>
        <style type="text/css">
            body{background-color: black;}
           
            .box{background-color: rgb(0, 0, 0);
            display: flex;
            height:100px;
            width:1520px;
            position: relative;
            margin-left: auto;
            margin-right: auto;
            margin-bottom: 10px;
            opacity: 0.8;
            }
            footer{
                background-color: rgb(0, 0, 0);
            color: aliceblue;
            font-size:medium;
            text-align: center;
            margin-left: -750px;
           margin-right: 245px;
            margin-top: 698px;
            
            height:27px;
            width:1000px;
            

            }
            .b-img{
            background-image: url(contact.jpg);
            background-repeat: no-repeat;
            background-size: contain;
            background-color: rgb(0, 0, 0);
            background-position: center;
            position:absolute;
            height:725px;
            width:1520px;
            display: flex;
            object-fit: cover;
           
           
            background-size:cover;}
            .home{
                font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
                color: red;
                font-weight: bolder;
                font-size: larger;   
            }
            .contact{
            height:20px;
            width:35%;
            position:relative;
            background-color: rgb(54, 50, 50);
            top:10px;
            left:850px;
            border:4px solid rgb(255, 0, 0);
            text-align:center;
            padding:15px;
            font-family:'Gill Sans MT';
            font-size: large;  
        }
        .contact:hover{
            background-color:rgb(84, 84, 84);
        }

        .home1{
            height:20px;
            width:10%;
            position:relative;
        
            top:10px;
            left:100px;
            border:4px solid rgb(255, 0, 0);
            text-align:center;
            padding:15px;
            font-family:'Gill Sans MT';
            font-size: large;  
        }
        .home1:hover{
            background-color:rgb(84, 84, 84);
        }

        .product{
            height:20px;
            width:10%;
            position:relative;
        
            top:10px;
            left:350px;
            border:4px solid rgb(255, 0, 0);
            text-align: center;
            padding:15px;
            font-family:'Gill Sans MT';
            font-size: large;  
        }
        .product:hover{
            background-color:rgb(84, 84, 84);
        }

        .about{
            height:20px;
            width:30%;
            position:relative;
        
            top:10px;
            left:600px;
            border:4px solid rgb(255, 0, 0);
            text-align:center;
            padding:15px;
            font-family:'Gill Sans MT';
            font-size: large;  
        }
        .about:hover{
            background-color:rgb(84, 84, 84);
        }

        
        p{color:aliceblue;
        font-size:25px;
        text-align: center;
        margin-top: 50%;
        background-color: black;
        width: 500px;
        -webkit-text-fill-color:rgb(255, 255, 255);
        -webkit-text-stroke-color: rgb(106, 106, 106);
        -webkit-text-stroke-width: 0.5px;
        
        }
         

            </style>
    </head>
    <body>
        <div class="b-img">
            
         <div class="box">
            
            <div class="home1">
                <a href="home-site.html" title="Home" style="color:rgb(255, 0, 0); text-decoration: none;"><b>HOME</b></a>
            </div>

            <div class="product">
                <a href="products.html" title="Products" style="color:rgb(255, 7, 7); text-decoration: none;"><b>PRODUCTS</b></a>
            </div>

            <div class="about">
                <a href="about_us.html" title="About Us" style="color:rgb(255, 0, 0); text-decoration: none;"><b>ABOUT US</b></a>
            </div>
        
            <div class="contact">
                <a href="web related things/index.html" title="Contact Us" style="color:rgb(255, 0, 0); text-decoration: none;"><b>CONTACT US</b></a>
            </div> 
             
            <div>
                <center>
                    
                   
                    
                    <p><br><b>Contact Us Through</b><br>Ph.No:7467567798<br>Email ID:gymania@gmail.com<br><br></p>
                
                </center>
                
            </div> 
           
           
             <div>
                
                <center>
                
                <footer class="footer">&COPY; Copyrights,Roobesh Rao.E.D</footer>
                </center>
             </div>

             
             
         
         
         
    
        </div>
        
    </body>  
</html>
```

# OUTPUT:

## Home Page:
![](Screenshot%20(67).png)
## Product Page:
![](Screenshot%20(68).png)
## About Us Page:
![](Screenshot%20(69).png)
## Contact Us Page:
![](Screenshot%20(70).png)



## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
