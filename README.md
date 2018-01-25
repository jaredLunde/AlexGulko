## ~~Title~~
----


## ~~Description~~

----

## ~~Schema.org scoping~~

----

## ~~Twitter cards~~

----

## ~~Facebook open graph tags~~

----


## [HIGH PRIORITY] Main menu
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

## ~~Header~~

----

## ~~Main content~~
![main content](/assets/main-content.png)

----

## ~~Footer~~

----


## ~~Store Hours~~

----


## ~~Store hours and address~~

----


## ~~Remove this~~

----

## Other tips
- [HIGH PRIORITY] Redirect http://www.alexgulko.com/index.htm to http://www.alexgulko.com
- [MED PRIORITY] Add robots.txt and sitemap.xml files to website
  - [robots.txt](/assets/robots.txt)
    - Should be accessible from http://www.alexgulko.com/robots.txt
  - [sitemap.xml](/assets/sitemap.xml)
    - Should be accessible from http://www.alexgulko.com/sitemap.xml
- [LOW PRIORITY] Use CloudFlare to set up SSL and protect your website from bots
  - https://www.cloudflare.com/plans/
    - You can have your web developer set you up with the free plan
  - Your URL will go from http://www.alexgulko.com to https://www.alexgulko.com
  - Why?
    - [Google values HTTPS sites more](https://searchengineland.com/google-starts-giving-ranking-boost-secure-httpsssl-sites-199446)
    - It should be an easy change for your developer to make
- [HIGHEST PRIORITY] Each page should have a unique `<title>`
  - http://www.alexgulko.com/about.htm
    - **Learn about Alex Gulko**
  - http://www.alexgulko.com/computer.htm
    - **See your jewelry before it's made**
  - http://www.alexgulko.com/testimonial.htm
    - **Reviews for Alex Gulko Custom Jewelry**
  - http://www.alexgulko.com/appraisal.htm
    - **Professional jewelry appraisal in Ann Arbor**
  - http://www.alexgulko.com/pricing_policies.htm
    - **How we price our jewelry**
  - http://www.alexgulko.com/location.htm
    - **Where to buy Alex Gulko Custom Jewelry**
  - http://www.alexgulko.com/contact.htm
    - **Contact Alex**
  - http://www.alexgulko.com/engagement_a.htm
    - **Custom antique engagement rings by Alex Gulko**
  - http://www.alexgulko.com/engagement_cl.htm
    - **Custom engagement rings by Alex Gulko**
  - http://www.alexgulko.com/engagement_co.htm
    - **Custom contemporary engagement rings by Alex Gulko**
  - http://www.alexgulko.com/weddingrings.htm
    - **Wedding bands by Alex Gulko**
  - http://www.alexgulko.com/gemstone_rings.htm
    - **Gemstone rings by Alex Gulko**
  - http://www.alexgulko.com/earrings_pendants.htm
    - **Earrings and pendants by Alex Gulko**
  - http://www.alexgulko.com/high_jewelry.htm
    - **High-end custom jewelry - Ann Arbor, MI**
  - http://www.alexgulko.com/recent.htm
    - **Recent designs by Alex Gulko**
