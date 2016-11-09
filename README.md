# team-design
Showcasing your team on your website puts a face to a name and adds a human element to your brand. In this article, [Solodev](https://www.solodev.com/) will show you the basics of creating a team section for your website using the [Bootstrap](http://getbootstrap.com/) framework, the most popular front-end framework for developing responsive websites.

## Tutorial

For detailed instructions, view Solodev's [Creating a Team Page with Solodev](https://www.solodev.com/blog/web-design/creating-a-team-page-with-bootstrap.stml) article.

## Demo

Try out a working example of the team overview page on [JSFiddle](https://jsfiddle.net/solodev/fbbh04bh/).

Try out a working example of the team detail page on [JSFiddle](https://jsfiddle.net/solodev/ox0n22fL/).

## HTML

The team overview page has the following basic HTML markup.
```
<header class="header--type2" data-background="http://www.webcorpco.com/core/fileparse.php/37/urlt/assets/images/sectional-images/team.jpg" data-height="35%" style="background-image: url(http://www.webcorpco.com/core/fileparse.php/37/urlt/assets/images/sectional-images/team.jpg); min-height: 301.35px; -webkit-user-select: auto;">
   <div class="inner" style="-webkit-user-select: auto;">
      <div class="container" style="-webkit-user-select: auto;">
         <div class="row" style="-webkit-user-select: auto;">
            <div class="col-md-10" style="-webkit-user-select: auto;">
               <section class="ct-page_title" style="-webkit-user-select: auto;">
                  <div class="h1" style="-webkit-user-select: auto;">
                     team
                  </div>
                  <div class="ct-page_title-content" style="-webkit-user-select: auto;"></div>
               </section>
            </div>
         </div>
      </div>
   </div>
</header>
<div class="container">
   <div id="theBioGrid">
      <ul class="row biogrid" id="biogrid">
         <li class="col-xs-3">
            <div class="imgHolder">
                <a href="/"><img alt="jia" class="img-responsive" src="http://www.webcorpco.com/core/fileparse.php/71/urlt/team-15.jpg"></a>
               <div class="description-box animateBottomName">
                   Jia Li Chung <br>
                   Product Manager
               </div>
            </div>
         </li>
         <li class="col-xs-3">
            <div class="imgHolder">
                <a href="/"><img alt="darla" class="img-responsive" src="http://www.webcorpco.com/core/fileparse.php/119/urlt/team-12.jpg"></a>
               <div class="description-box animateBottomName">
                   Darla Spriggs <br>
                   CFO
               </div>
            </div>
         </li>
         <li class="col-xs-3">
            <div class="imgHolder">
                <a href="/"><img alt="emily" class="img-responsive" src="http://www.webcorpco.com/core/fileparse.php/119/urlt/team-13.jpg"></a>
               <div class="description-box animateBottomName">
                   Emily Melton <br>
                   Director
               </div>
            </div>
         </li>
         <li class="col-xs-3">
            <div class="imgHolder">
                <a href="/"><img alt="matthew" class="img-responsive" src="http://www.webcorpco.com/core/fileparse.php/119/urlt/team-14.jpg"></a>
               <div class="description-box animateBottomName">
                   Matthew Keil <br>
                   CMO
               </div>
            </div>
         </li>
      </ul>
   </div>
</div>
```

The team detail page has the following basic HTML markup.
```
<header class="header--type2" data-background="images/team.jpg" data-height="35%" style="background-image: url(images/team.jpg); min-height: 301.35px; -webkit-user-select: auto;">
   <div class="inner" style="-webkit-user-select: auto;">
      <div class="container" style="-webkit-user-select: auto;">
         <div class="row" style="-webkit-user-select: auto;">
            <div class="col-md-10" style="-webkit-user-select: auto;">
               <section class="ct-page_title" style="-webkit-user-select: auto;">
                  <div class="h1" style="-webkit-user-select: auto;">
                     team
                  </div>
                  <div class="ct-page_title-content" style="-webkit-user-select: auto;"></div>
               </section>
            </div>
         </div>
      </div>
   </div>
</header>
<div class="container">
<div class="row">
   <div class="col-md-12 blue-box bio-detail">
      <div class="biogrid container">
         <div class="row">
            <div class="col-lg-4 col-md-5 col-sm-6 col-xs-5 bioimage">
               <img alt="darla" class="grid-image img-responsive" src="images/team-12.jpg">
            </div>
            <div class="col-lg-8 col-md-7 col-sm-6 col-xs-7 biodescription">
               <div class="bio-info">
                  <a href="/about-us/team/"><img alt="Close" class="close-backex" src="images/backex.png"></a>
                  <h2>Darla Spriggs</h2>
                  <p class="bio-subtitle"><strong>Dallas <br> CFO</strong></p>
                  <p class="bio-quote">Darla is a hardworking executive, is first to work and last to leave and has been with webcorpco since the beginnning and is considered a founding employee known for inventing the Newton at Apple Computer before joining webcorpco.</p>
               </div>
            </div>
         </div>
      </div>
   </div>
</div>
<div class="row">
   <div class="col-md-12">
      <div class="col-max-960">
         <h3>Experience</h3>
         <p>Darla was born in Omaha, Nebraska and grew up in the real estate industry before graduating from the University of Omaha and joining Apple Computer in 1996 where she designed the Newton. After the Newton, she joined WebCorpCo and changed her name.</p>
      </div>
   </div>
</div>
```
## CSS

All required CSS is in team.css

## External Includes

This tutorial contains the following third party resources.
```
<link rel="stylesheet" href="team.css">
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
```
