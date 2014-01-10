
= url_link

* https://github.com/austriamarcelo/url_link

== FEATURES:

url_link is a simple gem to convert url from the text into the url links. It can convert the links and images perfectly.

== DESCRIPTION:

    string =  "Welcome to my website http://www.mywebsite.com"
    url_link(string)
    result => welcome to my website <a href='http://www.mywebsite.com'>http://www.mywebsite.com</a>

    image_string = "http://blogspot.com/images/screenshot.png"
    url_link(image_string)
    result => <img src="http://blogspot.com/images/screenshot.png"/>
      
    string = "Welcome to my website http://www.mywebsite.com see the picture http://blogspot.com/images/screenshot.png"
    url_link(string)
    result => welcome to my website <a href='http://www.mywebsite.com'>http://www.mywebsite.com</a> see the picture <img src="http://blogspot.com/images/screenshot.png"/>

== REQUIREMENTS:

* rails > 3.1

== INSTALL:

* gem install url_link
