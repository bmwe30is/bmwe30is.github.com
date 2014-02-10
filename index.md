---
layout: page
title: Introduction to Selenium Automated Testing
tagline:
---
{% include JB/setup %}

A comprehensive Selenum documentation and example blog.

## A Brief Introduction to Selenium Testing

Selenium was created with the intention to automate UI browser testing. 

It contains support for Internet Explorer, Safari, Chrome, Firefox, and a multitude of other browsers. You can find more information
directly from the Selenium site: 

     http://docs.seleniumhq.org/

I've combined Selenium, JUnit, Maven, and Jenkins to automate full UI testing of my company's UI.  The big picture has been 
to implement automated tests within test suites to perform periodic regression tests of our UI.  


## Practical Application of Selenium's Framework

The problem we're trying to address with automation is:  

- How do we test features and perform regression of a continously changing user interface with changing various back-end services?  
- How do we provide reporting on test passes and test failues? 
- How do we know the browser and UI state at time of failure? 
- How do we build up a robust testing solution that will grow with the application that's being tested? 


The solution comes to us with scheduled periodic automated testing.  Selenium affords the ability to test multiple browsers and platforms simultaneously.
The aim of this blog is to provide some insight into implementing and deploying a Selenium solution for your various testing needs. 

I plan on introducing each piece of my solution as separate posts in this blog and include code samples that will hopefuly help you along your 
automated test journey. 
    

