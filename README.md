# Advanced-CSS-and-SASS
Working with an Advanced techniquesin CSS and SASS

<h2>Responsive Grid System:</h2>
http://www.responsivegridsystem.com/


<h2>RESOURCES:</h2>
http://codingheroes.io/resources/


<h2>CREATE SHAPES WITH IMAGES</h2>
https://bennettfeely.com/clippy/


<h2>animation-timing-function</h2>
https://developer.mozilla.org/en-US/docs/Web/CSS/animation-timing-function

<h2>Linea: a free outline iconset</h2>
http://linea.io/

<h2>CODEPEN Grid Sass</h2>
https://codepen.io/paulonova/pen/NJPNWV

<h2>CSS clip-path maker</h2>
https://bennettfeely.com/clippy/



<h1>Project´s annotations</h1>



<h3>ADVANCED CSS AND</h3>

<h4>CSS Animation:</h4>

<p>@keyframes  and   animations properties.</p>

** TO ANIMATE BUTTON:

<ul>
  <li>* I can use the pseudo element ::after</li>
  <li>* Use the same properties to it.</li>
  <li>* Positionate it using position relative and absolute</li>
  <li>* z-index: -1 to send it back to the button.</li>
</ul>


<h3>WORKING WITH SASS</h3>

<a href="https://webdesign.tutsplus.com/tutorials/watch-and-compile-sass-in-five-quick-steps--cms-28275">SASS in 5 steps</a>

<p>* npm install node-sass --save-dev</p>
<p>*In package.json write a script:</p>
<code>
  "scripts": {
  "scss": "node-sass --watch scss/main.scss css/style.css"
}
</code>

<p>This will render the SASS into the css file style.css.</p>
<p>then write in console:  'npm run scss'</p>

# install globaly =>  'npm install live-server -g'
# run => 'live-server'

<p>To Run live-server: </p>

<h1>GRIDS:</h1>

<p>I create grids using calc().</p>
<code>ex: .col-3-of-4{
    width: calc(3 * ((100% - 3*#{$gutter-horizontal}) / 4) + (2 * #{$gutter-horizontal}));
  }
</code>
  
  ** UTILITIES CLASSES ****
  I created some utilities classes to help with some small tasks.

  'u-center-text', 'u-margin-bottom-8' etc..

<strong>XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX</strong>

<h1>RESPONSIVE DESIGN</h1>

1- Desktop-first
2- Mobile-first

<h3>Screen Sizes:</h3>#

<p><strong>'max-width:' </strong>usses to desktop-first</p>
<p><strong>'min-width:' </strong>uses to mobile-first</p>

1 for mobile                      0 to 600 px
1 for portrait tablets            600 to 900 px
1 for landscape tablets           900 to 1200 px
1 for desktop                     1200 to 1800 px
1 for big desktop                 1800 to ->

ps: That can be more, but these are the basics.