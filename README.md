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
```
Home:
    <!DOCTYPE html>
<html lang="en">
  <head>
    <title>EduSoft Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon 1.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Isnaj Private Limited.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/banner.png" alt="Building" />
          <div class="contenttext">
            At software, we believe in the power of technology to make business
            owners efficient, empowered and happier, so they can focus on what
            matters most for their business. We design our products to focus on
            just that to make our products work for you, and not the other way
            around.
            <br />
            Our new product software takes this to a new level, making your
            start to automation, or your switch to software simpler than ever
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
        Copyright &#169; 2021 Isnaj Private Limited, Developed by Jhansi.
      </div>
    </div>
  </body>
</html>
product:
 <!DOCTYPE html>
<html lang="en">
  <head>
    <title>Isnaj Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Isnaj Private Limited</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact_us.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:/Users/jhansi/Documents/djangoprojects/productcompanywebsite/companywebsite/static/img/mac-os.png" alt="product image">
                  </div>
                  <div class="itemname">mac-os</div>
                  <div class="itemprice">Price: Rs.7500000.0 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:/Users/jhansi/Documents/djangoprojects/productcompanywebsite/companywebsite/static/img/f360.jpg"  alt="product image">
                  </div>
                  <div class="itemname">f360
                  </div>
                  <div class="itemprice">Price: Rs.250000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="C:/Users/jhansi/Documents/djangoprojects/productcompanywebsite/companywebsite/static/img/firefox.png"  alt="product image">
                </div>
                <div class="itemname">firefox</div>
                <div class="itemprice">Price: Rs.120000.00 </div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="C:/Users/jhansi/Documents/djangoprojects/productcompanywebsite/companywebsite/static/img/ms%20office.jpg"  alt="product image">
            </div>
            <div class="itemname">ms office</div>
            <div class="itemprice">Price: Rs.2750000.00 </div>
          </div>  
          <div class="productitem"> 
            <div class="itemimage">
            <img src="C:/Users/jhansi/Documents/djangoprojects/productcompanywebsite/companywebsite/static/img/mail.png"  alt="product image">
            </div>
            <div class="itemname">mail</div>
            <div class="itemprice">Price: Rs.100000.00 </div>      
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="C:/Users/jhansi/Documents/djangoprojects/productcompanywebsite/companywebsite/static/img/jpt.png"  alt="product image">
        </div>
        <div class="itemname">jpt</div>
        <div class="itemprice">Price: Rs.45000000.00 </div>
        </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="C:/Users/jhansi/Documents/djangoprojects/productcompanywebsite/companywebsite/static/img/xtreem.jpg"  alt="product image">
            </div>
            <div class="itemname">xtreem</div>
            <div class="itemprice">Price: Rs.1000000.00 </div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="C:/Users/jhansi/Documents/djangoprojects/productcompanywebsite/companywebsite/static/img/word.jpg"  alt="product image">
              </div>
              <div class="itemname">word</div>
              <div class="itemprice">Price: Rs.10000000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="C:/Users/jhansi/Documents/djangoprojects/productcompanywebsite/companywebsite/static/img/Python.png"  alt="product image">
                </div>
                <div class="itemname">python</div>
                <div class="itemprice">Price: Rs.100000000.00 </div>
                </div>
                  <div class="productitem"> 
                    <div class="itemimage">
                    <img src="C:/Users/jhansi/Documents/djangoprojects/productcompanywebsite/companywebsite/static/img/anacondanavigator.png"  alt="product image">
                    </div>
                    <div class="itemname">anacondanavigator</div>
                    <div class="itemprice">Price: Rs.2000000.00 </div>
                    </div>
                    <div class="productitem"> 
                      <div class="itemimage">
                      <img src="C:/Users/jhansi/Documents/djangoprojects/productcompanywebsite/companywebsite/static/img/Miccrosoftedge.jpg"  alt="product image">
                      </div>
                      <div class="itemname">microsoftedge</div>
                      <div class="itemprice">Price: Rs.67000000.00 </div>
                      </div>
      <div class="footer">
        Copyright &#169; 2021 Isnaj Private Limited, FOUNDER: JHANSI
      </div>
    </div>
  </body>
</html>
people:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title></title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">ISNAJ PRIVATE COMPANY</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitemselected"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact_us.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
            <h1>MANAGER </h1>
            <div class="productitems">
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="C:/Users/jhansi/Documents/djangoprojects/productcompanywebsite/companywebsite/static/img/ps2.png" alt="product image">
                    </div>
                    <div class="itemname">VENKATESH</div>
                    <div class="itemprice">DEVELOPER</div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="C:/Users/jhansi/Documents/djangoprojects/productcompanywebsite/companywebsite/static/img/ps11.png"  alt="product image">
                    </div>
                    <div class="itemname">SNEHA</div>
                    <div class="itemprice">CEO </div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="file:///C:/Users/jhansi/Documents/djangoprojects/productcompanywebsite/companywebsite/static/img/ps12.png"  alt="product image">
                    </div>
                    <div class="itemname">CHEIF KOUSHIKA</div>
                    <div class="itemprice">MANAGER</div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="file:///C:/Users/jhansi/Documents/djangoprojects/productcompanywebsite/companywebsite/static/img/ps8.png"  alt="product image">
                    </div>
                    <div class="itemname">EMPLOYEE</div>
                    <div class="itemprice">DIRECTOR</div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="C:/Users/jhansi/Documents/djangoprojects/productcompanywebsite/companywebsite/static/img/ps7.png"  alt="product image">
                    </div>
                    <div class="itemname">EMPLOYE</div>
                    <div class="itemprice">ASSISITENT</div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="file:///C:/Users/jhansi/Documents/djangoprojects/productcompanywebsite/companywebsite/static/img/ps10.png"  alt="product image">
                    </div>
                    <div class="itemname">John Kanell</div>
                    <div class="itemprice">EMPLOYEE</div>
                </div>

          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 ISNAJ PRIVATE COMPANY ltd, FOUNDER:JHANSI
      </div>
    </div>
  </body>
</html>
contact us:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>ISNAJ</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">ISNAJ SOFTWARE</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contact_us.html">Contact Us</a></div>
      </div>
      <div class="content">
          <ul>
              <li>Address: HYDERABAD <br></li>
              <li>Contact:443568309;<br></li>
              <li>ISNAJ213@gmail.com.com<br></li>
              <br>VERIFIED*
          </ul>    
        </div>
    </div>
    </div>
    </div>
      <div class="footer">
        Copyright &#169; 2021 ISNAJ213 ltd, Developed by:JHANSI.
      </div>
    </div>
  </body>
</html>
```
## OUTPUT:

![output](homeoutput.png)
![output](productoutput.png)
![output](peopleoutput.png)
![output](contactusoutput.png)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
