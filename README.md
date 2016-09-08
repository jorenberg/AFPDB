# AFPDB<sup>®</sup> [![Apache License][license-badge]][license-status]
AFPDB®: <i>A dedicated computational biology Antifreeze Proteins (AFPs) Database.</i>

[![Build Status][build-badge]][build-status]
[![Coverage Status][coverage-badge]][coverage-status]
[![Author][author-badge]][author-url]
[![Gitter][chat-badge]][chat-url]

## About

<b>Antifreeze proteins (AFPs)</b> or ice structuring proteins (ISPs) refer to a class of polypeptides produced by certain vertebrates, plants, fungi, bacteria and fish that permit their survival in subzero environments — through evolution as a natural survival response to the freezing cold. They help prevent the formation of ice crystals that damage cells. Organisms that have these proteins can live in extreme environments and are therefore known as ‘extremophiles’.

AFPDB<sup>®</sup>, is a dedicated computational biology database for Antifreeze Proteins — that covers, it's protein sequence, structure and genes that encodes these. Also, genetic networks of all the antifreeze proteins.

## What is it?

Source files for the <b>"AFPDB<sup>®</sup>"</b> data product — features includes filtering, ordering, instant search, URL access/update, file size optimization and Data API usage for listed — proteins.

<b>Note:</b> Proteins data stored in JSON for easy modifications.

## What is used?

AXIX® (SASS), jQuery, AMD, Font Awesome, Bower, Grunt with html/css/js/json/svg/image — minify + uglify.

## How to use it?

All the sources can be found in the "[en](https://github.com/AFPDB/AFPDB/tree/gh-pages/en)" — directory. Modify the files in there and run ```grunt build``` in the root folder to get all the dependencies and minified versions of our HTML/CSS/JS/JSON/SVG/Image files generated to launch.

## Supported Browsers

It runs on all modern browsers that support [HTML5](https://html.spec.whatwg.org/multipage/) and [ECMAScript 5](http://www.ecma-international.org/ecma-262/5.1/).

This includes Chrome, Firefox, Safari, Opera and Edge. For older browsers and platforms like Internet Explorer (down to version 9) and Android 4.x, [polyfills](http://polyfill.io) for ```requestAnimationFrame``` and ```Element.prototype.classList``` are required.
