# ULoader
Add Loader (Loading) screen into your website!

## Quick Start
+ CDN Url : `https://cdn.jsdelivr.net/gh/ScadeBlock/ULoader@refs/heads/main/release/latest/uloaderjs.min.js` 
+ How to use
  - With CDN: Add \
  `<script src="https://cdn.jsdelivr.net/gh/ScadeBlock/ULoader@refs/heads/main/release/latest/uloaderjs.min.js"></script>`\
 into your `<body>` element
  - Local Host (Better Performance): Download `ULoaderjs.min.js` from Release Tab, and then add it into your website

## Demo
Unavailable now~
___
## Ritial
+ Ritial is an alternative to ULoaderJS, but more optimized - harder to setup.

<details>
  <summary><b>How to setup</b></summary>

  ### How to setup 
+ Use cdn: `https://cdn.jsdelivr.net/gh/ScadeBlock/ULoader@refs/heads/main/release/latest/ritial.min.js` Download `ritial.min.js` from Release Tab and then import it into your site (`body` element )
+ Then add following html code into `body`
> `<div id="uloadermain" class="uloader-mainpage uloader-hiddex"><div class="uloader-content"><center><h2 style="color:#fff">Loading</h2><div class="uloader-loadingspinner"><div id="square1"></div><div id="square2"></div><div id="square3"></div><div id="square4"></div><div id="square5"></div></div></center></div></div>`

+ Also add following css code into `head`
> `.uloader-hiddex{visibility:hidden!important;opacity:0!important;transition:visibility .7s linear,opacity .7s linear}.uloader-viewex{visibility:visible!important;opacity:1!important}.uloader-mainpage{position:fixed;top:0;z-index:999;top:0;left:0;right:0;bottom:0;width:100%;height:100%;opacity:1;background-color:#000}.uloader-content{top:35%;position:relative}.uloader-loadingspinner{--square:26px;--offset:30px;--duration:2.4s;--delay:0.2s;--timing-function:ease-in-out;--in-duration:0.4s;--in-delay:0.1s;--in-timing-function:ease-out;width:calc(3 * var(--offset) + var(--square));height:calc(2 * var(--offset) + var(--square));padding:0;margin-left:auto;margin-right:auto;margin-top:10px;margin-bottom:30px;position:relative}.uloader-loadingspinner div{display:inline-block;background:#ff8c00;border:none;border-radius:2px;width:var(--square);height:var(--square);position:absolute;padding:0;margin:0;font-size:6pt;color:#000}.uloader-loadingspinner #square1{left:calc(0 * var(--offset));top:calc(0 * var(--offset));animation:square1 var(--duration) var(--delay) var(--timing-function) infinite,squarefadein var(--in-duration) calc(1 * var(--in-delay)) var(--in-timing-function) both}.uloader-loadingspinner #square2{left:calc(0 * var(--offset));top:calc(1 * var(--offset));animation:square2 var(--duration) var(--delay) var(--timing-function) infinite,squarefadein var(--in-duration) calc(1 * var(--in-delay)) var(--in-timing-function) both}.uloader-loadingspinner #square3{left:calc(1 * var(--offset));top:calc(1 * var(--offset));animation:square3 var(--duration) var(--delay) var(--timing-function) infinite,squarefadein var(--in-duration) calc(2 * var(--in-delay)) var(--in-timing-function) both}.uloader-loadingspinner #square4{left:calc(2 * var(--offset));top:calc(1 * var(--offset));animation:square4 var(--duration) var(--delay) var(--timing-function) infinite,squarefadein var(--in-duration) calc(3 * var(--in-delay)) var(--in-timing-function) both}.uloader-loadingspinner #square5{left:calc(3 * var(--offset));top:calc(1 * var(--offset));animation:square5 var(--duration) var(--delay) var(--timing-function) infinite,squarefadein var(--in-duration) calc(4 * var(--in-delay)) var(--in-timing-function) both}@keyframes square1{0%{left:calc(0 * var(--offset));top:calc(0 * var(--offset))}8.333%{left:calc(0 * var(--offset));top:calc(1 * var(--offset))}100%{left:calc(0 * var(--offset));top:calc(1 * var(--offset))}}@keyframes square2{0%{left:calc(0 * var(--offset));top:calc(1 * var(--offset))}8.333%{left:calc(0 * var(--offset));top:calc(2 * var(--offset))}16.67%{left:calc(1 * var(--offset));top:calc(2 * var(--offset))}25.00%{left:calc(1 * var(--offset));top:calc(1 * var(--offset))}83.33%{left:calc(1 * var(--offset));top:calc(1 * var(--offset))}91.67%{left:calc(1 * var(--offset));top:calc(0 * var(--offset))}100%{left:calc(0 * var(--offset));top:calc(0 * var(--offset))}}@keyframes square3{0%,100%{left:calc(1 * var(--offset));top:calc(1 * var(--offset))}16.67%{left:calc(1 * var(--offset));top:calc(1 * var(--offset))}25.00%{left:calc(1 * var(--offset));top:calc(0 * var(--offset))}33.33%{left:calc(2 * var(--offset));top:calc(0 * var(--offset))}41.67%{left:calc(2 * var(--offset));top:calc(1 * var(--offset))}66.67%{left:calc(2 * var(--offset));top:calc(1 * var(--offset))}75.00%{left:calc(2 * var(--offset));top:calc(2 * var(--offset))}83.33%{left:calc(1 * var(--offset));top:calc(2 * var(--offset))}91.67%{left:calc(1 * var(--offset));top:calc(1 * var(--offset))}}@keyframes square4{0%{left:calc(2 * var(--offset));top:calc(1 * var(--offset))}33.33%{left:calc(2 * var(--offset));top:calc(1 * var(--offset))}41.67%{left:calc(2 * var(--offset));top:calc(2 * var(--offset))}50.00%{left:calc(3 * var(--offset));top:calc(2 * var(--offset))}58.33%{left:calc(3 * var(--offset));top:calc(1 * var(--offset))}100%{left:calc(3 * var(--offset));top:calc(1 * var(--offset))}}@keyframes square5{0%{left:calc(3 * var(--offset));top:calc(1 * var(--offset))}50.00%{left:calc(3 * var(--offset));top:calc(1 * var(--offset))}58.33%{left:calc(3 * var(--offset));top:calc(0 * var(--offset))}66.67%{left:calc(2 * var(--offset));top:calc(0 * var(--offset))}75.00%{left:calc(2 * var(--offset));top:calc(1 * var(--offset))}100%{left:calc(2 * var(--offset));top:calc(1 * var(--offset))}}@keyframes squarefadein{0%{transform:scale(.75);opacity:0}100%{transform:scale(1);opacity:1}}`

</details>

# Copyright
Made with ❤ by ScadeBlock
