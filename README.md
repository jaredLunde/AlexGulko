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
    content="Custom jewelry as unique as your partner. Show them how special they are with a custom engagement and wedding ring. Come to our downtown Ann Arbor location today to get started."
  >
```

### Why?
The meta description tag is half marketing and half SEO. It should be attention grabbing, but keyword rich.

----

## Schema.org scoping
Should go in the `<head/>` part of the document

### Recommended
```html
<!-- Schema.org markup for Google+ -->
<meta itemscope itemtype="http://schema.org/LocalBusiness">
<meta itemprop="name" content="Alex Gulko Custom Jewelry">
<meta itemprop="description" content="Custom jewelry as unique as your partner. Show them how special they are with a custom engagement and wedding ring. Come to our downtown Ann Arbor location today to get started.">
<meta itemprop="image logo" content="http://www.alexgulko.com/images/header_logo_v2.jpg">
<meta itemprop="email" content="alexgulko@sbcglobal.net">
<meta itemprop="telephone" content="7347410652">
<meta itemprop="address" content="337 S Main St Ann Arbor, MI  48104-0652">
<meta itemprop="legalName" content="Alex Gulko Custom Jewelry">
<meta itemprop="map" content="https://www.google.com/maps?q=alex+gulko+custom+jewelry&amp;um=1&amp;ie=UTF-8&amp;sa=X&amp;ved=0ahUKEwiggtz2hbrYAhVD_4MKHZ6VAJAQ_AUIDygA">
<meta itemprop="photo" content="http://www.alexgulko.com/images/inside_store_v2.jpg">
```

### Why?
It tells Google and Bing stuff it would otherwise have to guess about your business.


----

## Twitter cards
Should go in the `<head/>` part of the document

### Recommended
```html
<!-- Twitter Card data -->
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:site" content="@alexgulkodesign">
<meta name="twitter:title" content="Alex Gulko Custom Jewelry">
<meta name="twitter:url" content="http://www.alexgulko.com/">
<meta name="twitter:description" content="Custom jewelry as unique as your partner. Show them how special they are with a custom engagement and wedding ring. Come to our downtown Ann Arbor location today to get started.">
<!-- Twitter summary card with large image must be at least 280x150px -->
<meta name="twitter:image:src" content="http://www.alexgulko.com/slide_pics/slide_pic_02c.jpg">
```

### Why?
If someone shares your site on twitter it will display a cool looking card that is a good marketing tool.


----

## Facebook open graph tags
Should go in the `<head/>` part of the document

### Recommended
```html
<!-- Open Graph data -->
<meta
  property="og:image"
  content="http://www.alexgulko.com/slide_pics/slide_pic_02c.jpg"
>
<meta
  property="og:title"
  content="Alex Gulko Custom Jewelry"
>
<meta
  property="og:type"
  content="business.business"
>
<meta
  property="business:contact_data:street_address"
  content="337 S Main St"
>
<meta
  property="business:contact_data:locality"       
  content="Ann Arbor"
>
<meta
  property="business:contact_data:region"       
  content="Michigan"
>
<meta
  property="business:contact_data:postal_code"    
  content="48104-0652"
>
<meta
  property="business:contact_data:country_name"  
  content="United States"
>
<meta
  property="business:contact_data:email"    
  content="alexgulko@sbcglobal.net"
>
<meta
  property="business:contact_data:phone_number"    
  content="7347410652"
>
<meta
  property="place:location:latitude"             
  content="42.2785"
>
<meta
  property="place:location:longitude"             
  content="-83.7483"
  >
```

### Why?
It tells Facebook stuff it would otherwise have to guess about your business and
makes sharing your site on Facebook look nice.


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

### Why?
It tells Google and Bing that this is the main navigation of your site.
It also changes un-followable `<div/>` tags to followable `<a/>` tags.


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

### Why?
It tells Google and Bing that this is the header of your page.

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

### Why?
It makes your logo clickable which is good for user experience purposes. It also
provides a nice home link at the top of your page for Google.

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

### Why?
It tells Google and Bing that this is the main content of the current page.


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

### Why?
It tells Google and Bing that this is the footer of your page.


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

### Why?
It provides Google and Bing with your opening and closing hours and also
makes your telephone number clickable so I can just click the number to call
you.


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

### Why?
It provides Google and Bing with your opening and closing hours, your address information and also
makes your telephone number clickable so I can just click the number to call
you.


----


## Remove this
![for removal](/assets/remove-this.png)
```html
<div style="width: 97%; color: #999999; padding: 10px 0px;">
  Serving customers in Michigan: Ann Arbor, Adrian, Brighton, Belleville,  Birmingham, Chelsea, Canton, Dearborn, Farmington Hills, Dexter, Detroit, Grand Rapids, Howell, Jackson, Kalamazoo, Lansing, Midland, Monroe, Novi, Pinckney, Plymouth, Saginaw, Saline, Troy, Ypsilanti, also in Chicago, Toledo, Illinois, Ohio, Indiana.
</div>
```

### Why?
Google may interpret this as spam


----

## Other tips
- Redirect http://www.alexgulko.com/index.htm to http://www.alexgulko.com
- Add robots.txt and sitemap.xml files to website
  - [robots.txt](/assets/robots.txt)
    - Should be accessible from http://www.alexgulko.com/robots.txt
  - [sitemap.xml](/assets/sitemap.xml)
    - Should be accessible from http://www.alexgulko.com/sitemap.xml
- Use CloudFlare to set up SSL and protect your website from bots
  - https://www.cloudflare.com/plans/
    - You can have your web developer set you up with the free plan
  - Your URL will go from http://www.alexgulko.com to https://www.alexgulko.com
  - Why?
    - [Google values HTTPS sites more](https://searchengineland.com/google-starts-giving-ranking-boost-secure-httpsssl-sites-199446)
    - It should be an easy change for your developer to make
- Each page should have a unique `<title>`
  - http://www.alexgulko.com/about.htm
    - Learn about Alex Gulko
  - http://www.alexgulko.com/computer.htm
    - See your jewelry before it's made
  - http://www.alexgulko.com/testimonial.htm
    - Reviews for Alex Gulko Custom Jewelry
  - http://www.alexgulko.com/appraisal.htm
    - Professional Ann Arbor jewelry appraisal
  - http://www.alexgulko.com/pricing_policies.htm
    - How we price our jewelry
  - http://www.alexgulko.com/location.htm
    - Where to find Alex Gulko Custom Jewelry
  - http://www.alexgulko.com/contact.htm
    - Contact Us - Alex Gulko Custom Jewelry
  - http://www.alexgulko.com/engagement_a.htm
    - Custom antique engagement rings by Alex Gulko
  - http://www.alexgulko.com/engagement_cl.htm
    - Custom engagement rings by Alex Gulko
  - http://www.alexgulko.com/engagement_co.htm
    - Custom contemporary engagement rings by Alex Gulko
  - http://www.alexgulko.com/weddingrings.htm
    - Wedding bands by Alex Gulko
  - http://www.alexgulko.com/gemstone_rings.htm
    - Gemstone rings by Alex Gulko
  - http://www.alexgulko.com/earrings_pendants.htm
    - Earrings and pendants by Alex Gulko
  - http://www.alexgulko.com/high_jewelry.htm
    - High end custom jewelry - Ann Arbor, MI
  - http://www.alexgulko.com/recent.htm
    - Recent designs by Alex Gulko
