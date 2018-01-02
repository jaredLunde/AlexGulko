## Title

### Current
Alex Gulko: Custom engagement &amp; wedding rings, custom jewelry-Ann Arbor, MI

```html
  <title>
    Alex Gulko: Custom engagement &amp; wedding rings, custom jewelry-Ann Arbor, MI
  </title>
```

### Recommended
Alex Gulko Custom Jewelry - Ann Arbor, MI

```html
  <title>
    Alex Gulko Custom Jewelry - Ann Arbor, MI
  </title>
```

### Why?
There's no use in filling the title with stuff we can include in the description. The name of the business and the city should suffice.


----


## Description

### Current
Design your own custom engagement and wedding rings in Ann Arbor, MI.

```html
  <meta
    name="description"
    content="Design your own custom engagement and wedding rings in Ann Arbor, MI."
  >
```

### Recommended
Custom jewelry as unique as your partner. Show them how special they are with a custom engagement and wedding ring. Meet Alex at our downtown Ann Arbor location today to get started.

```html
  <meta
    name="description"
    content="Custom jewelry as unique as your partner. Show them how special they are to you with a custom engagement and wedding ring. Come to our downtown Ann Arbor location today to get started."
  >
```

### Why?
The meta description tag is half marketing and half SEO. It should be attention grabbing, but keyword rich.


----


## Main menu
![main menu](/assets/main-menu.png)

### Current
```html
<div class="main_menu_inside">
  <!--div class="main_menu_div m_menu1">&#160;&#160;<img src="./images/home_icon.gif" />&#160;&#160;</div-->
  <div class="main_menu_div m_menu1" onclick="window.location='index.htm';">HOME</div>
  <div class="main_menu_div m_menu2" id="jewelry_td" onmouseover="mshow('gallery_menu'); menucolor('jewelry_td','over');" onmouseout="mhide('gallery_menu');menucolor('jewelry_td','out');" style="background-color: rgb(85, 85, 85);">JEWELRY</div>
  <div class="main_menu_div m_menu3" onclick="window.location='computer.htm';">COMPUTER DESIGN</div>
  <div class="main_menu_div m_menu4" onclick="window.location='about.htm';">ABOUT ARTIST</div>
  <div class="main_menu_div m_menu5" onclick="window.location='testimonial.htm';">TESTIMONIALS</div>
  <div class="main_menu_div m_menu6" onclick="window.location='appraisal.htm';">APPRAISAL</div>
  <div class="main_menu_div m_menu7" onclick="window.location='pricing_policies.htm';">POLICES &amp; PRICING</div>
  <div class="main_menu_div m_menu8" onclick="window.location='location.htm';">LOCATION</div>
  <div class="main_menu_div m_menu9" onclick="window.location='contact.htm';">CONTACT US</div>
</div>
```

### Recommended
```html
<nav class="main_menu_inside">
  <!--div class="main_menu_div m_menu1">&#160;&#160;<img src="./images/home_icon.gif" />&#160;&#160;</div-->
  <div class="main_menu_div m_menu1">
    <a href="/" rel='home'>
      HOME
    </a>
  </div>
  <div class="main_menu_div m_menu2" id="jewelry_td" onmouseover="mshow('gallery_menu'); menucolor('jewelry_td','over');" onmouseout="mhide('gallery_menu');menucolor('jewelry_td','out');" style="background-color: rgb(85, 85, 85);">
    JEWELRY
  </div>
  <div class="main_menu_div m_menu3">
    <a href="/computer.htm">
      COMPUTER DESIGN
    </a>
  </div>
  <div class="main_menu_div m_menu4">
    <a href="/about.htm">
      ABOUT ARTIST
    </a>
  </div>
  <div class="main_menu_div m_menu5">
    <a href="/testimonial.htm">
      TESTIMONIALS
    </a>
  </div>
  <div class="main_menu_div m_menu6">
    <a href="/appraisal.htm">
      APPRAISAL
    </a>
  </div>
  <div class="main_menu_div m_menu7">
    <a href="/pricing_policies.htm">
      POLICIES &amp; PRICING
    </a>
  </div>
  <div class="main_menu_div m_menu8">
    <a href="/location.htm">
      LOCATION
    </a>
  </div>
  <div class="main_menu_div m_menu9">
    <a href="/contact.htm">
      CONTACT US
    </a>
  </div>
</nav>
```

----

## Header
![main menu](/assets/header.png)

### Current
```html
<div id="header">
  ...
</div>
```

### Recommended
```html
<header id="header">
  ...
</header>
```

----

## Header logo
![main menu](/assets/header-logo.png)

### Current
```html
<span style="white-space:nowrap;">
  &nbsp;
  <img id="header_logo" src="./images/header_logo_v2.jpg">
</span>
```

### Recommended
```html
<a href="/" rel="home" title="Alex Gulko Custom Jewelry" style="white-space:nowrap;">
  &nbsp;
  <img alt="Alex Gulko Custom Jewelry" id="header_logo" src="./images/header_logo_v2.jpg">
</a>
```

----

## Main content
![main content](/assets/main-content.png)

### Current
```html
<div id="slideshow">...</div>
<div id="IMG_Main">...</div>
```

### Recommended
```html
<main>
  <div id="slideshow">...</div>
  <div id="IMG_Main">...</div>
</main>
```

----


## Footer
![main menu](/assets/footer.png)

### Current
```html
<div id="footer">
  ...
</div>
```

### Recommended
```html
<footer id="footer">
  ...
</footer>
```


----


## Store Hours
![hours and address](/assets/store-hours.png)

### Current
```html
<div class="header_inside_div hdr3">
  Store&nbsp;Hours:
  <br/>
  <font color="#999999">
    Tue,&nbsp;Wed,&nbsp;Fri&nbsp;10&nbsp;-&nbsp;6
    <br/>
    Thur&nbsp;10&nbsp;-&nbsp;8
    <br/>
    Sat&nbsp;10&nbsp;-&nbsp;4
    <br/>
    Sun,&nbsp;Mon&nbsp;closed
    <br/>
    <span style="white-space: nowrap;">
      <img src="./images/phone_icon.jpg">&nbsp;&nbsp;734.741.0652
    </span>
  </font>
</div>
```

### Recommended (http://schema.org/LocalBusiness)
```html
<div itemscope itemtype="http://schema.org/LocalBusiness" class="header_inside_div hdr3">
  Store&nbsp;Hours:
  <br/>
  <font color="#999999">
    <meta itemprop="openingHours" content="Tu-We 10:00-18:00">
    <meta itemprop="openingHours" content="Fr 10:00-18:00">
    Tue,&nbsp;Wed,&nbsp;Fri&nbsp;10&nbsp;-&nbsp;6
    <br/>
    <meta itemprop="openingHours" content="Th 10:00-20:00">
    Thur&nbsp;10&nbsp;-&nbsp;8
    <br/>
    <meta itemprop="openingHours" content="Sa 10:00-16:00">
    Sat&nbsp;10&nbsp;-&nbsp;4
    <br/>
    Sun,&nbsp;Mon&nbsp;closed
    <br/>
    <span style="white-space: nowrap;">
      <img src="./images/phone_icon.jpg">&nbsp;&nbsp;
      <a itemprop="telephone" href="tel:7347410652">
        (734) 741-0652
      </a>
    </span>
  </font>
</div>
```

----


## Store hours and address
![hours and address](/assets/address.png)

### Current
```html
<div id="footer_inside_5">
  <a href="https://www.google.com/maps?f=d&amp;source=s_q&amp;hl=en&amp;geocode=%3BCdVq_HoGP5PYFW8ehQIdZRkC-ym3lHllPK48iDGiaRW23bqOgA&amp;q=alex+gulko+ann+arbor+michigan&amp;sll=37.0625,-95.677068&amp;sspn=35.410182,56.513672&amp;ie=UTF8&amp;hq=alex+gulko&amp;hnear=Ann+Arbor,+MI&amp;cid=9263546944953084322&amp;t=m&amp;z=14&amp;vpsrc=0&amp;iwloc=A&amp;daddr=Alex+Gulko+Custom+Jewelry,+337+South+Main+Street,+Ann+Arbor,+MI+48104" class="press" style="color:#7AC3E3;" target="_new">
    Get directions
  </a>
  &nbsp;►
  <br/>337 S Main St
  <br/>Ann Arbor, MI
  <br/>48104-0652
  <br/>(734) 741-0652
  <br/>
  <a class="press" href="mailto:alexgulko@sbcglobal.net" style="color:#7AC3E3;">
    AlexGulko@sbcglobal.net
  </a>
  <br/>
  <br/>
  <div class="address">
    <font color="#7AC3E3">
      Store Hours:&nbsp;&nbsp;&nbsp;
    </font>
    <br/>
    Tue,&nbsp;Wed,&nbsp;Fri&nbsp;10&nbsp;-&nbsp;6<br>Thur 10 - 8&nbsp;&nbsp;&nbsp;<br>Sat 10 - 4&nbsp;&nbsp;&nbsp;<br>Sun, Mon closed&nbsp;&nbsp;&nbsp;
  </div>
</div>
```


### Recommended (http://schema.org/LocalBusiness)
```html
<div itemscope itemtype="http://schema.org/LocalBusiness" id="footer_inside_5">
  <a href="https://www.google.com/maps?f=d&amp;source=s_q&amp;hl=en&amp;geocode=%3BCdVq_HoGP5PYFW8ehQIdZRkC-ym3lHllPK48iDGiaRW23bqOgA&amp;q=alex+gulko+ann+arbor+michigan&amp;sll=37.0625,-95.677068&amp;sspn=35.410182,56.513672&amp;ie=UTF8&amp;hq=alex+gulko&amp;hnear=Ann+Arbor,+MI&amp;cid=9263546944953084322&amp;t=m&amp;z=14&amp;vpsrc=0&amp;iwloc=A&amp;daddr=Alex+Gulko+Custom+Jewelry,+337+South+Main+Street,+Ann+Arbor,+MI+48104" class="press" style="color:#7AC3E3;" target="_new">
    Get directions
  </a>
  &nbsp;►
  <div itemprop="address" itemscope itemtype="http://schema.org/PostalAddress">
    <div itemprop="name">
      Alex Gulko Custom Jewelry
    </div>
    <div itemprop="streetAddress">
      337 S Main St
    </div>
    <div>
      <span itemprop="addressLocality">
        Ann Arbor
      </span>,
      <span itemprop="addressRegion">
        MI
      </span>
    </div>
    <div itemprop="postalCode">
      48104-0652
    </div>
  </div>
  <div>
    <a itemprop="telephone" href="tel:7347410652">
      (734) 741-0652
    </a>
  </div>
  <br/>
  <div>
    <a itemprop="email" class="press" href="mailto:alexgulko@sbcglobal.net" style="color:#7AC3E3;">
      AlexGulko@sbcglobal.net
    </a>
  </div>
  <br/>
  <div class="address">
    <font color="#7AC3E3">
      Store Hours:&nbsp;&nbsp;&nbsp;
    </font>
    <meta itemprop="openingHours" content="Tu-We 10:00-18:00">
    <meta itemprop="openingHours" content="Fr 10:00-18:00">
    <br/>
    Tue,&nbsp;Wed,&nbsp;Fri&nbsp;10&nbsp;-&nbsp;6
    <meta itemprop="openingHours" content="Th 10:00-20:00">
    <br/>Thur 10 - 8&nbsp;&nbsp;&nbsp;
    <meta itemprop="openingHours" content="Sa 10:00-16:00">
    <br/>Sat 10 - 4&nbsp;&nbsp;&nbsp;
    <br/>Sun, Mon closed&nbsp;&nbsp;&nbsp;
  </div>
</div>
```

----


## Remove this
![for removal](/assets/remove-this.png)
```html
<div style="width: 97%; color: #999999; padding: 10px 0px;">
  Serving customers in Michigan: Ann Arbor, Adrian, Brighton, Belleville,  Birmingham, Chelsea, Canton, Dearborn, Farmington Hills, Dexter, Detroit, Grand Rapids, Howell, Jackson, Kalamazoo, Lansing, Midland, Monroe, Novi, Pinckney, Plymouth, Saginaw, Saline, Troy, Ypsilanti, also in Chicago, Toledo, Illinois, Ohio, Indiana.
</div>
```


----

## Other tips
- Redirect http://www.alexgulko.com/index.htm to http://www.alexgulko.com
- Add robots.txt and sitemap.xml files to website
  - [robots.txt](/assets/robots.txt)
    - Should be available at http://www.alexgulko.com/robots.txt
  - [sitemap.xml](/assets/sitemap.xml)
    - Should be available at http://www.alexgulko.com/sitemap.xml
- Use CloudFlare to set up SSL and protect your website from bots
  - https://www.cloudflare.com/plans/
    - You can have your web developer set you up with the free plan
  - Your URL will go from http://www.alexgulko.com to https://www.alexgulko.com
  - Why?
    - [Google values HTTPS sites more](https://searchengineland.com/google-starts-giving-ranking-boost-secure-httpsssl-sites-199446)
    - It should be an easy change for your developer to make
