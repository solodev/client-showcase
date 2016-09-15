# client-showcase
Showing off your clients and how your product or service has benefited them is integral to sales growth. Displaying them effectively so that potential clients can find relevance in the content you display is crucial to growing your business. In this tutorial, [Solodev](https://www.solodev.com/) provides you with the code you need to add a client showcase to your website.

## Tutorial

For detailed instructions, view Solodev's [Building an Effective Client Showcase](https://www.solodev.com/blog/web-design/designing-a-client-showcase-with-bootstrap.stml) article.

## Demo

Check out a working example of the Client Overview Page on [JSFiddle](https://jsfiddle.net/solodev/gd5ss581/).

Check out a working example of the Client Entry Page on [JSFiddle](https://jsfiddle.net/solodev/d9k0f6gr/).

## HTML

The client showcase includes the client overview page with the basic HTML markup below.
```
<header class="header--type2" data-background="images/clients.jpg" data-height="35%" style="min-height: 353.5px; background-image: url(images/clients.jpg);">
   <div class="inner">
      <div class="container">
         <div class="row">
            <div class="col-md-10">
               <section class="ct-page_title">
                  <div class="h1">
                     Clients
                  </div>
                  <div class="ct-page_title-content"></div>
               </section>
            </div>
         </div>
      </div>
   </div>
</header>
<main>
   <div class="container ct-u-paddingTop40 ct-u-paddingBottom100">
      <div class="row">
         <div class="col-md-12 ct-content">
            <section class="clients-home">
               <div class="container">
                  <div class="clients-logos text-center">
                     <!-- starting row div -->
                     <div class="row">
                        <div class="col-md-4 client-logos-repeater">
                           <a class="Zeina"><img alt="images/logo-zeina.png" src="images/logo-zeina.png"></a>
                           <div class="logo-title">
                              <div class="displayTable">
                                 <div class="displayTableCell">
                                    Zeina - 0
                                 </div>
                              </div>
                           </div>
                        </div>
                        <div class="col-md-4 client-logos-repeater">
                           <a class="Logic"><img alt="images/logic.png" src="images/logic.png"></a>
                           <div class="logo-title">
                              <div class="displayTable">
                                 <div class="displayTableCell">
                                    Logic - 1
                                 </div>
                              </div>
                           </div>
                        </div>
                        <div class="col-md-4 client-logos-repeater">
                           <a class="Smart"><img alt="images/client3.png" src="images/client3.png"></a>
                           <div class="logo-title">
                              <div class="displayTable">
                                 <div class="displayTableCell">
                                    Smart - 2
                                 </div>
                              </div>
                           </div>
                        </div>
                     </div>
                     <div class="row">
                        <div class="col-md-4 client-logos-repeater">
                           <a class="Softtech"><img alt="images/softtech.png" src="images/softtech.png"></a>
                           <div class="logo-title">
                              <div class="displayTable">
                                 <div class="displayTableCell">
                                    Softtech - 3
                                 </div>
                              </div>
                           </div>
                        </div>
                        <div class="col-md-4 client-logos-repeater">
                           <a class="Wheel"><img alt="images/logo-target.png" src="images/logo-target.png"></a>
                           <div class="logo-title">
                              <div class="displayTable">
                                 <div class="displayTableCell">
                                    Wheel - 4
                                 </div>
                              </div>
                           </div>
                        </div>
                        <div class="col-md-4 client-logos-repeater">
                           <a class="3designs"><img alt="images/designx.png" src="images/designx.png"></a>
                           <div class="logo-title">
                              <div class="displayTable">
                                 <div class="displayTableCell">
                                    3designs - 5
                                 </div>
                              </div>
                           </div>
                        </div>
                     </div>
                     <div class="row">
                        <div class="col-md-4 client-logos-repeater">
                           <a class="Heart"><img alt="images/client7.png" src="images/client7.png"></a>
                           <div class="logo-title">
                              <div class="displayTable">
                                 <div class="displayTableCell">
                                    Heart - 6
                                 </div>
                              </div>
                           </div>
                        </div>
                        <div class="col-md-4 client-logos-repeater">
                           <a class="Devtech"><img alt="images/devtech.png" src="images/devtech.png"></a>
                           <div class="logo-title">
                              <div class="displayTable">
                                 <div class="displayTableCell">
                                    Devtech - 7
                                 </div>
                              </div>
                           </div>
                        </div>
                        <div class="col-md-4 client-logos-repeater">
                           <a class="Chartz"><img alt="images/chartz.png" src="images/chartz.png"></a>
                           <div class="logo-title">
                              <div class="displayTable">
                                 <div class="displayTableCell">
                                    Chartz - 8
                                 </div>
                              </div>
                           </div>
                        </div>
                     </div>
                     <!-- closing row div -->
                  </div>
               </div>
            </section>
         </div>
      </div>
   </div>
</main>

```
The client showcase includes the client entry page with the basic HTML markup below.
```
<header class="header--type2" data-background="images/clients.jpg" data-height="35%" style="min-height: 353.5px; background-image: url(https://www.solodev.com/assets/clients/clients.jpg);">
   <div class="inner">
      <div class="container">
         <div class="row">
            <div class="col-md-10">
               <section class="ct-page_title">
                  <div class="h1">
                     Clients
                  </div>
                  <div class="ct-page_title-content"></div>
               </section>
            </div>
         </div>
      </div>
   </div>
</header>
<div class="container">
   <div class="clients-title text-center">
      <h1>
         Zeina
      </h1>
      <p>
         A Reputation for Quality
      </p>
   </div>
</div>
<div class="clients-slider-wrapper">
<div class="container">
<div class="row">
   <div class="clients-slider text-center col-md-8 col-md-offset-2">
      <img alt="zeina-mockup.png" src="images/zeina-mockup.png">
      <div class="clearfix"></div>
      <div class="clients-line"></div>
      <div class="clients-text">
         <h2>
            An engaging online experience for job seekers and others in the field of design.
         </h2>
         <p>
            Zenia is one of the leading talent recruitment and outplacement firms for the architecture, interior design, engineering and manufacturing industries. The focus of Devtech's business is talent recruitment and placement so security is a high priority in order to protect the confidential nature of the job search process. That's one reason Solodev CMS's secure content management software was the right choice for this project.
         </p>
         <p>
            A dynamic jobs portal integrates with Devtech's applicant tracking system and the multi-segmented blog allows visitors to select their areas of interest. A slider manager allows Devtech staff to easily keep the site looking fresh with new homepages visuals.
         </p>
         <div class="launch-site-btn text-center">
            <a href="" class="btn btn-client" target="blank">LAUNCH SITE</a>
         </div>
      </div>
   </div>
</div>
```
## CSS

The CSS is split up into two files, one for client-overview.html->(client-overview.css) and another for client-entry.html->(client-entry.css).

## External Includes

The client-overview.html includes the following third party resources.

```
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
<link rel="stylesheet" href="client-overview.css">

<script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
<script type="text/javascript" src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
```

The client-entry.html includes the following third party resources.

```
<link href="https://fonts.googleapis.com/css?family=Open+Sans+Condensed:300,700" rel="stylesheet">
<link href="https://fonts.googleapis.com/css?family=Source+Sans+Pro" rel="stylesheet">
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
<link rel="stylesheet" href="client-entry.css">

<script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
<script type="text/javascript" src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
```
