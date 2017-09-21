# SCSS-Grid-System

Customizable grid system created with SCSS. It resemblances Twitter's Bootstrap framework syntax because it's already pretty good and intuitive and I also like it. I've created this frameworks because I needed a lightweight and customizable css grid-system.

# It allows the following:

- changing the number of columns
- changing the name and value of breakpoints
- creating scalable font for different device sizes
- creating classes of colors for background and text on the fly

# Implemented stuff:

- the grid system itself
- offseting for each breakpoint
- ordering columns first and last
- scalable fonts
- aligning columns (good old flexbox stuff)

# TODO

- add scalable margins and paddings
- tidy the code
- customize the syntax even more
- add a responsive navbar  made without js
- etc

# How it works

Change the variable values in the sass file, compile it and enjoy.

#  Example
```html
  <div class="container">
    <div class="row">
      <div class="font-scale col-xs-12col-lg-8 col-xl-12">sm-1 md-6 lg-8 xl-12</div>
      <div class="font-scale col-xs-12 text-center col-sm-2 teal">2</div>
      <div class="font-scale col-xs-12 text-center col-sm-3 orange first">3</div>
      <div class="col-xs-12 col-sm-4 blue-grey col-lg-offset-1 col-md-offset-6 first">4</div>
      <div class="font-scale col-xs-12 text-center col-sm-2 orange">2/ 5</div>
    </div> 
    <div class="row">
       <div class="col-xs-12 text-center col-sm-12 teal">12</div>
    </div>
    <div class="row space-between">
      <div class="col-md-1 orange text-center">12</div>
      <div class="col-md-1 orange text-center">12</div>
      <div class="col-md-1 orange text-center">12</div>
      <div class="col-md-1 orange text-center">12</div>
      <div class="col-md-1 orange text-center">12</div>
      <div class="col-md-1 orange text-center">12</div>
      <div class="col-md-1 orange text-center">12</div>
      <div class="col-md-1 orange text-center">12</div>
      <div class="col-md-1 orange text-center">12</div>
      <div class="col-md-1 orange text-center">12</div>
      <div class="col-md-1 orange text-center">12</div>
    </div>
  </div>
```

# Browser compatibility

Same as for flexbox:

|       Chrome       | IE / Edge | Firefox |    Safari    |                   Opera |
|--------------------|-----------|---------|--------------|-------------------------|
| 29.0 21.0 -webkit- |    11.0   |   28.0  | 6.1 -webkit- | 17.0 15.0 -webkit- 12.1 |

# License

<a href="https://www.gnu.org/licenses/gpl-3.0.en.html">GPLV3</a>
