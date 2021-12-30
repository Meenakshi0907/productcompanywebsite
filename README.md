# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using HTML and CSS.

### Step 3:

Updating the sample content.

### Step 4:

Choose the appropriate style and color scheme.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :
### Home Page:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Mee Softwares</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Mee Softwares</div>
      <div class="menu">
        <div class="menuitemselected"><a href="home.html">Home</a></div>
        <div class="menuitem"><a href="products.html">Products</a></div>
        <div class="menuitem"><a href="products.html">People</a></div>
        <div class="menuitem"><a href="contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/logorm.png" alt="Meelogo" />
          <div class="contenttext">
            At Tally, we believe in the power of technology to make business
            owners efficient, empowered and happier, so they can focus on what
            matters most for their business. We design our products to focus on
            just that to make our products work for you, and not the other way
            around.
            <br />
            Our new product TallyPrime takes this to a new level, making your
            start to automation, or your switch to Tally simpler than ever
            before. You can now discover the product much more easily and make
            the product do more for you, without learning anything new. There is
            greater flexibility as the product adapts to your business and your
            way of working. And the transformed look and feel will only make you
            love the product even more.
            <ul>
              <li>Simple to learn, easier to use</li>
              <li>Insightful , actionable & customizable reports</li>
              <li>Anywhere, anytime and secure access</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Mee Softwares, Developed by Meenakshi.
      </div>
    </div>
  </body>
</html>
~~~
### Product Page:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Mee Softwares</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>
        </div>
      <div class="content">
            <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/djangorm.png" alt="django">
                  </div>
                  <div class="itemname">DJANDO</div>
                  <div class="itemprice">Price: Rs.1500</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/fusionrm.png"  alt="fusion360">
                  </div>
                  <div class="itemname">FUSION 360</div>
                  <div class="itemprice">Price: Rs.2000 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/googlerm.png" alt="google">
                </div>
                <div class="itemname">GOOGLE</div>
                <div class="itemprice">Price: Rs.2000 </div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/internetrm.png" alt="internet expo">
              </div>
              <div class="itemname">INTERNET EXPLORER</div>
              <div class="itemprice">Price: Rs.1500</div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/javarm.png" alt="java">
            </div>
            <div class="itemname">JAVA</div>
            <div class="itemprice">Price: Rs. 2000</div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/matlabrm.png" alt="matlab">
          </div>
          <div class="itemname">MATLAB</div>
          <div class="itemprice">Price: RS.1000</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/mysqlrm.png" alt="mysql">
        </div>
        <div class="itemname">MY SQL</div>
        <div class="itemprice">Price: RS.3000</div>
    </div>
    <div class="productitem"> 
      <div class="itemimage">
      <img src="/static/img/phprm.png" alt="php">
      </div>
      <div class="itemname">PHP</div>
      <div class="itemprice">Price: Rs.2500 </div>
  </div>
  <div class="productitem"> 
    <div class="itemimage">
    <img src="/static/img/pythonrm.png" alt="python">
    </div>
    <div class="itemname">PYTHON</div>
    <div class="itemprice">Price: Rs.2000 </div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="/static/img/rrm.png" alt="R">
  </div>
  <div class="itemname">R</div>
  <div class="itemprice">Price: Rs.2000</div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="/static/img/rubyrm.png" alt="ruby">
  </div>
  <div class="itemname">RUBY</div>
  <div class="itemprice">Price: Rs.1500</div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="/static/img/skyperm.png" alt="skype">
  </div>
  <div class="itemname">SKYPE</div>
  <div class="itemprice">Price: Rs.2500</div>
</div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 Mee Softwares, Developed by Meenakshi.
      </div>
    </div>
  </body>
</html>
~~~
### People Page:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title></title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Mee Softwares</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitemselected"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
            <h1>SUPPORTERS OF OUR SOFTWARES</h1>
            <div class="productitems">
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="/static/img/billgatesmicrosoft.png" alt="bill gates">
                    </div>
                    <div class="itemname">BILL GATES</div>
                    <div class="itemprice">MICROSOFT</div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="/static/img/DaveCutlerwindowsnt.png"  alt="dave cutler">
                    </div>
                    <div class="itemname">DAVE CUTLER</div>
                    <div class="itemprice">WINDOWS NT</div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="/static/img/JamesGoslingjava.png"  alt="james gosling">
                    </div>
                    <div class="itemname">JAMES GOSLING</div>
                    <div class="itemprice">JAVA</div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="/static/img/JimmyWaleswiki.png"  alt="jimmy waleswiki">
                    </div>
                    <div class="itemname">JIMMY WALES</div>
                    <div class="itemprice">WIKIPEDIA</div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="/static/img/MichaelWideniusmysql.png"  alt="michael widenius">
                    </div>
                    <div class="itemname">MICHAEL WIDENIUS</div>
                    <div class="itemprice">MY SQL</div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="/static/img/PaulBuchheitgmail.png"  alt="paul buchheit">
                    </div>
                    <div class="itemname">PAUL BUCHHEIT</div>
                    <div class="itemprice">GMAIL</div>
                </div>

          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Navi company, Developed by Naveenkumar.
      </div>
    </div>
  </body>
</html>
~~~
### Contact Page:
~~~
<!DOCTYPE html>
<html lang="en">   
  <head>
    <title>Mee Softwares</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>
        </div>
      <div class="content">
                <ul>
              <h1>Address:</h1> 
                <li>Mee Softwares,KANCHIPURAM <br></li>
              <li><h1>Contact:</h1>123456787;<br></li>
              <li><h1>E-mail:</h1>meesoftwares@gmail.com</li>
              <br>VERIFIED*
          </ul>    
        </div>
    </div>
    </div>
    </div>
      <div class="footer">
        Copyright &#169; 2021 Mee Softwares, Developed by Meenakshi.
      </div>
    </div>
  </body>
</html>
~~~
## OUTPUT:

### Home Page:

![output](./companywebsite/static/img/homepage.png)

### Product Page:
![output](./companywebsite/static/img/productpage.png)

### People Page:
![output](./companywebsite/static/img/peoplepage.png)

### Contact Page:
![output](./companywebsite/static/img/contactpage.png)
## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
