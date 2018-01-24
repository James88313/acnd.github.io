<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="description" content="">
    <meta name="keywords" content="">
    <meta name="author" content="">
    <title>ACND &middot;</title>
      <link href='https://fonts.googleapis.com/css?family=Lora:400,400italic|Work+Sans:300,400,500,600' rel='stylesheet' type='text/css'>
      <link href="assets/css/toolkit-startup.css" rel="stylesheet">
      <link href="assets/css/application-startup.css" rel="stylesheet">
    <style>
      /* note: this is a hack for ios iframe for bootstrap themes shopify page */
      /* this chunk of css is not part of the toolkit :) */
      /* …curses ios, etc… */
      @media (max-width: 768px) and (-webkit-min-device-pixel-ratio: 2) {
        body {
          width: 1px;
          min-width: 100%;
          *width: 100%;
        }
        #stage {
          height: 1px;
          overflow: auto;
          min-height: 100vh;
          -webkit-overflow-scrolling: touch;
        }
      }
    </style>
  </head>
<body>
<div class="stage-shelf stage-shelf-right hidden" id="sidebar">
  <ul class="nav nav-bordered nav-stacked">
    <li class="nav-header">Examples</li>
    <li>
      <a href="bold/index.html">Bold</a>
    </li>
    <li class="nav-divider"></li>
    <li class="nav-header">Docs</li>
    <li>
      <a href="docs/index.html">Toolkit</a>
    </li>
  </ul>
</div>

<div class="stage" id="stage">
<!-- style="background-image: url(assets/img/startup-1.jpg);" -->
<div class="block block-inverse block-fill-height app-header"
    style="background-image: url(assets/img/landing.svg);" >

  <nav class="navbar navbar-transparent navbar-fixed-top navbar-padded app-navbar p-t-md">
  <div class="container">
    <div class="navbar-header">
      <button type="button" class="navbar-toggle collapsed p-x-0"
              data-target="#stage" data-toggle="stage" data-distance="-250">
        <span class="sr-only">Toggle navigation</span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
      </button>
      <a class="navbar-brand" href="">
        <strong style="color:#FFFFFF; padding: 12px; border-radius: 4px; color: #28669F;">
          ACND
        </strong>
      </a>
    </div>
    <div class="navbar-collapse collapse text-uppercase">
      <ul class="nav navbar-nav navbar-right">
        <li >
          <a href="{{site.baseurl}}/assets/downloads/acnd-whitepaper.pdf" download = "acnd.pdf">Whitepaper</a>
        </li>
      </ul>
    </div><!--/.nav-collapse -->
  </div>
</nav>


<!--  <img class="app-graph" src="assets/img/startup-0.svg"> -->

  <div class="block-xs-middle p-b-lg">
    <div class="container">
      <div class="row">
        <div class="col-sm-10 col-md-6">
          <h1 class="block-title m-b-sm">Eliminating turbulance in corporate travel payment experience.</h1>
          <p class="lead m-b-md ">A corprate travel payment solution powered by cryptocurrency.</p>
          <button class="btn btn-primary btn-lg">Pre ICO Submission</button>
          <p class = 'text-muted'>Coming Soon</p>
        </div>
      </div>
    </div>
  </div>
</div>
<!-- -->
<!-- -->
<div class="block second-feature-block block-secondary app-iphone-block post-landing">
  <div class="container">
    <div class="row app-align-center">
      <div class="col-sm-5">
        <img class="app-iphone" src="assets/img/blue-cloud.svg" style="width: 50%;">
      </div>
      <div class="col-sm-6 ">
        <h3 class="m-t-0">Clouded Thinking</h3>
        <p class="lead m-b-md">Until now the travel industry has been known to be riddled with old processes. From time intensive wire transfers to fax documentation requirements - inefficiencies are abundant.</p>
        <div class="row hidden-sm">
        </div>
      </div>
    </div>

  </div>
</div>
<div class="block second-feature-block block-secondary app-iphone-block post-landing" style="background-color: #F7F7F7;">
  <div class="container">
    <div class="row app-align-center">
    <div class="col-sm-12">
      <div class="col-sm-12 ">
        <img class="app-iphone" src="assets/img/tc.svg" style="width: 20%;">
        <h3 class="m-t-0" style="margin:0 auto;">Rerouting the Industry to a desired destination.</h3>
        <p class="lead m-b-md">Using blockchain technology, we are building a payment solution which will revolutionize the travel B2B payment landscape.</p>
        <div class="row hidden-sm">
        </div>
      </div>
    </div>
  </div>
</div>

<!-- <div class="block block-inverse block-secondary app-code-block"> -->
  <div class="container">
    <div class="row app-align-center">
      <div class="col-sm-5 col-sm-push-7 ">
        <img style="width:60%;" class="col-xs-offset-3" src="assets/img/wing.svg">
      </div>
      <div class="col-sm-6 col-sm-pull-5">
        <h3 class="text-muted">Elevating the entire experience</h3>
        <p class="lead m-b-md text-muted">ACND will enable settlement in minutes rather than days. ACND will Integrate Smart Contracts with every transaction which enable data confirmation and data delivery at the Point of Sale (POS) for everyone in the supply chain. While traditional payment methods require expensive reconciliations and manual processes, we are automating the process and generating substantial savings and efficiencies across the entire vertical supply chain. 
</p>
      </div>
    </div>
  </div>
</div>
<div class="block app-price-plans">
  <div class="container text-center">
    <div class="row">
      <div class="col-sm-4 p-x m-b-lg">
        <div class="p-x">
          <h6 class="text-muted text-uppercase m-b">Corporate Travel</h6>
        </div>
        <ul class="list-unstyled list-bordered text-left m-y-md">
          <li class="p-y">Automated reconciliations</li>
          <li class="p-y">Integrated travel policies</li>
          <li class="p-y">Savings on transactions and loyalty benefits</li>
        </ul>
      </div>
      <div class="col-sm-4 p-x m-b-lg">
        <div class="p-x">
          <h6 class="text-muted text-uppercase m-b">Agencies</h6>
        </div>
        <ul class="list-unstyled list-bordered text-left m-y-md">
          <li class="p-y">Automated commission payments via smart contracts</li>
          <li class="p-y">Reduced data maintenance overhead</li>
          <li class="p-y"> Cost efficient, fast cross-border payments</li>
        </ul>
      </div>
      <div class="col-sm-4 p-x m-b-lg">
        <div class="p-x">
          <h6 class="text-muted text-uppercase m-b">Suppliers</h6>
        </div>
        <ul class="list-unstyled list-bordered text-left m-y-md">
          <li class="p-y">Automate manual processes (i.e. eliminate fax verification for hotels)</li>
          <li class="p-y">Faster payment processing which reduces cash cycle</li>
          <li class="p-y">Reduces fraud / error for significant savings</li>
        </ul>
      </div>
    </div>
  </div>
</div>
<!--recently -->
<div class="block app-price-plans">
  <div class="container text-center">
    <div class="row m-b-lg">
      <div class="col-sm-8 col-sm-offset-2 col-lg-6 col-lg-offset-3">
        <h6 class="text-muted text-uppercase">Recent</h6>
        <h3  class="m-t-0"> Oh the places we will go.</h3>
        <img src="assets/img/teplis.jpg"/>
        <p class="teplis-partnership" style="padding-top:30px;">We are very excited to announce our partnership with Teplis Travel. An industry leader in the corporate travel Industry for over 45 years. Our partnership with Teplis gives ACND detailed intelligence into all of the real-time use case scenarios within the corporate travel payments industry. Our partnership also provides us with a direct channel to $2B of clients, in a $7 Trillion Industry. And ongoing preferred relationships with almost every supplier in the travel industry.</p>
      </div>
    </div>
    <div class="row">
      <div class="col-sm-12 p-x m-b-lg">
        <div class="p-x">
        </div>
      </div>
    </div>
  </div>
</div>
<!--
<div class="block block-secondary app-high-praise p-b-0">
  <div class="container">
    <div class="row app-align-center">
      <div class="col-sm-5 col-sm-push-7">
        <h6 class="text-muted text-uppercase">High Praise</h6>
        <h3 class="m-t-0 m-b-md">“Go Analytics is amazing. Decisions that used to take weeks, now only takes minutes and is available to everyone on my team.”</h3>
        <p class="m-b-md text-muted">Cindy Smith, founder of Cool Startup</p>
      </div>

    </div>
  </div>
</div>
-->
<!-- Begin MailChimp Signup Form -->
<link href="//cdn-images.mailchimp.com/embedcode/slim-10_7.css" rel="stylesheet" type="text/css">
<style type="text/css">
	#mc_embed_signup{background:#fff; clear:left; font:14px Helvetica,Arial,sans-serif;text-align:center;margin:0 auto;padding-top:30px;}
	/* Add your own MailChimp form style overrides in your site stylesheet or in this style block.
	   We recommend moving this block and the preceding CSS link to the HEAD of your HTML file. */
</style>
<div id="mc_embed_signup" style="padding-top:30px;">
<form action="https://Acnd.us17.list-manage.com/subscribe/post?u=0e51d46eb5f760bd2cdda8516&amp;id=b03366d368" method="post" id="mc-embedded-subscribe-form" name="mc-embedded-subscribe-form" class="validate" target="_blank" novalidate>
    <div id="mc_embed_signup_scroll">
	<label for="mce-EMAIL">Subscribe to our mailing list</label>
	<input type="email" value="" name="EMAIL" class="email" id="mce-EMAIL" placeholder="email address" required>
    <!-- real people should not fill this in and expect good things - do not remove this or risk form bot signups-->
    <div style="position: absolute; left: -5000px;" aria-hidden="true"><input type="text" name="b_0e51d46eb5f760bd2cdda8516_b03366d368" tabindex="-1" value=""></div>
    <div class="clear"><input type="submit" value="Subscribe" name="subscribe" id="mc-embedded-subscribe" class="button"></div>
    </div>
</form>
</div>

<!--End mc_embed_signup-->
<div class="block block-secondary app-block-marketing-grid">
  <div class="container text-center">

    <div class="row m-b-lg">
      <div class="col-xs-10 col-xs-offset-1 col-sm-8 col-sm-offset-2 col-lg-6 col-lg-offset-3">
        <h6 class="text-muted text-uppercase">Team</h6>
      </div>
    </div>
    <div class="row app-marketing-grid">
      <div class="col-sm-3 p-x-md m-b-lg">
        <img class="m-b" src="assets/img/startup-9.svg">
        <p><strong>Gary Teplis</strong></p>
      </div>
      <div class="col-sm-3 p-x-md m-b-lg">
        <img class="m-b" src="assets/img/startup-10.svg">
        <p><strong>Chase DuBois</strong> </p>
      </div>
      <div class="col-sm-3 p-x-md m-b-lg">
        <img class="m-b" src="assets/img/startup-11.svg">
        <p><strong>Blake Jackovitch</strong></p>
      </div>
      <div class="col-sm-3 p-x-md m-b-lg">
        <img class="m-b" src="assets/img/startup-11.svg">
        <p><strong>Tharwart malik</strong> </p>
      </div>
    </div>

    <div class="row app-marketing-grid">
    </div>
  </div>
</div>
<div class="block block-inverse app-footer">
 <div class="container">
    <div class="row">
      <div class="col-sm-5 m-b-md">
        <ul class="list-unstyled list-spaced">
          <li class="m-b"><h6 class="text-uppercase" style="color:#13103A;">About</h6></li>
          <li class="text-muted">
           Looking to acnd ? We'd love to here from you! <a style="color:#000000;" href="mailto:team@acnd.io">write us</a> here and we'll be sure to get back to you as soon as posisble.
          </li>
        </ul>
      </div>
    </div>
  </div>
</div>
<!-- </div> -->
    <script src="assets/js/jquery.min.js"></script>
    <script src="assets/js/toolkit.js"></script>
    <script src="assets/js/application.js"></script>
  </body>
</html>
