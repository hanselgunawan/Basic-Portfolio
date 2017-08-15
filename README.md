# Project Title
Hansel Tritama's Portfolio

## Synopsis

This is my first assignment on UCLA Extension Coding Boot Camp. It's a static website about my portfolios.

## Motivation

The motivation behind this project is to show my understandings about HTML and CSS that have been taught in the class.

## Code Example
HTML:

```html
<div id="header">
        <div class="col-left">
            <h1>Hansel Tritama</h1>
        </div>
        <div class="col-right">
            <div id="navigation">
                <a href="index.html">About</a>
                <a href="portfolio.html">Portfolio</a>
                <a href="contact.html">Contact</a>
            </div>
        </div>
    </div>
```

CSS:

```css
#header h1
{
    font-family: 'Georgia', Times, Times New Roman, serif;
    color: white;
    background-color: #4aaaa5;
    width: 75%;
    height: 70px;
    text-align: center;
    padding-top: 35px;
}

#header #navigation
{
    font-family: 'Arial', 'Helvetica Neue', Helvetica, sans-serif;
    text-align: center;
    padding-top: 45px;
}

#header #navigation a
{
    color: #777777;
    text-decoration: none;
    padding: 0px 10px 0px 10px;
    font-size: 14pt;
}

#header #navigation a:nth-child(2)
{
    border-left: 2px solid grey;
    border-right: 2px solid grey;
}

#header #navigation a:hover
{
    color:black;
    font-weight: bold;
    transition: 0.1s all ease-in;
    font-size: 12pt;
}
```

## Installation

```
1. Clone this project - git clone https://uclax.bootcampcontent.com/hansel.tritama/Basic-Portfolio.git
2. Open the HTML file on any text editor application
3. Open on a browser, such as: Google, Safari, Firefox, etc.
```

## Contributor

Hansel B. Tritama - [www.hanseltritama.com](http://www.hanseltritama.com)
