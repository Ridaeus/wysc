# Widgets

- [Brand Guidelines](#brand-guidelines)
    - [Colors](#colors)
- [HTML](#html)
    - [Template](#template)
    - [Iframe lazy load](#iframe-lazy-load)
    - [Widgetbot](#widgetbot)
- [Docs](#docs)
    - [Page table of contents](#page-table-of-contents)


<br><br>
## Brand Guidelines

### Colors
```
#9C5D49 red-light
#05679D blue-light
#082B3E blue-dark (Home-bottom blue)
#704529 blog
```


<br><br>
## HTML

### Template
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, minimum-scale=1.0, maximum-scale=1.0, user-scalable=no" />
    <meta name="description" content="For students striving to be better, Wysc is the study Discord server that delivers a cohesive, global online studying experience, as the first Discord server to present an edu-social cafe experience to an audience of hundreds.">
    <meta name="keywords" content="study discord, study voice chat, wysc, productivity discord, homework discord, studying discord server, work study chilling, work studying chilling, music discord server, lofi discord, vaporwave discord, students discord" />
    <meta name="robots" content="index, follow" />
    <meta name="theme-color" content="#9C5D49" />
    <link rel="manifest" href="app.webmanifest">
    <link rel="shortcut icon" type="image/x-icon" href="favicon.ico">
    <link rel="stylesheet" href="css/styles.css">
    <link rel="stylesheet" href="css/bootstrap-4.3.1.min.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato:300,400">
    <link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Gochi+Hand">
    <title>Wysc – Virtual Study Cafe</title>
    <meta property="og:title" content="Wysc – Virtual Study Cafe" />
</head>
<body>
    


<!-- js -->
<script src="js/jquery-3.4.1.min.js"></script>
<script src="js/popper-1.14.7.min.js" defer></script>
<script src="js/bootstrap-4.3.1.min.js" defer></script>
<script src="js/cssrelpreload.js" async></script>
<link type="text/javascript" href="js/script.js">
<!-- og: meta tags // title-type-img-url required -->
<meta property="og:type" content="website" />
<meta property="og:image" content="media/wsc-sp-rounded.png" />
<meta property="og:url" content="https://wysc.bookmark.com" />
<meta property="og:site_name" content="Study Discord Server" />
<meta property="og:description" content="For students striving to be better, Wysc is the study Discord server that delivers a cohesive, global online studying experience, as the first Discord server to present an edu-social cafe experience to an audience of hundreds.">
<!-- apple -->
<script async>async function supportsWebp(){if(!self.createImageBitmap)return false;const webpData='data:image/webp;base64,UklGRh4AAABXRUJQVlA4TBEAAAAvAAAAAAfQ//73v/+BiOh/AAA=';const blob=await fetch(webpData).then(r=>r.blob());return createImageBitmap(blob).then(()=>true,()=>false);} (async()=>{if(await supportsWebp()){console.log('webp > jpg');} else{
    document.getElementById("webpheader").style="background: url('media/T_1hsMH9CQY.jpg');background-position:center;background-attachment:fixed;background-size:cover;overflow:hidden;";
    document.getElementById("webpback01").style="background: url('media/daan-evers-1480187-unsplash.jpg');background-position:center;background-attachment:fixed;background-size:cover;overflow:hidden;";
}})();</script>
<link rel="stylesheet" type="text/css" href="js/add-to-homescreen-master/style/addtohomescreen.css"> 
<script src="js/add-to-homescreen-master/src/addtohomescreen.js" defer></script> 
<script defer>addToHomescreen();</script>
<meta name="mobile-web-app-capable" content="yes" />
<meta name="apple-touch-fullscreen" content="yes" />
<meta name="apple-mobile-web-app-title" content="Wysc" />
<meta name="apple-mobile-web-app-capable" content="yes" />
<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent" />
<link rel="apple-touch-icon" sizes="180x180" href="images/icons/ios-180x180.png" />
<link rel="apple-touch-startup-image" href="images/splashscreens/iphone5_splash.png" media="(device-width: 320px) and (device-height: 568px) and (-webkit-device-pixel-ratio: 2)" />
<link rel="apple-touch-startup-image" href="images/splashscreens/iphone6_splash.png" media="(device-width: 375px) and (device-height: 667px) and (-webkit-device-pixel-ratio: 2)" />
<link rel="apple-touch-startup-image" href="images/splashscreens/iphoneplus_splash.png" media="(device-width: 621px) and (device-height: 1104px) and (-webkit-device-pixel-ratio: 3)" />
<link rel="apple-touch-startup-image" href="images/splashscreens/iphonex_splash.png" media="(device-width: 375px) and (device-height: 812px) and (-webkit-device-pixel-ratio: 3)" />
<link rel="apple-touch-startup-image" href="images/splashscreens/iphonexr_splash.png" media="(device-width: 414px) and (device-height: 896px) and (-webkit-device-pixel-ratio: 2)" />
<link rel="apple-touch-startup-image" href="images/splashscreens/iphonexsmax_splash.png" media="(device-width: 414px) and (device-height: 896px) and (-webkit-device-pixel-ratio: 3)" />
<link rel="apple-touch-startup-image" href="images/splashscreens/ipad_splash.png" media="(device-width: 768px) and (device-height: 1024px) and (-webkit-device-pixel-ratio: 2)" />
<link rel="apple-touch-startup-image" href="images/splashscreens/ipadpro1_splash.png" media="(device-width: 834px) and (device-height: 1112px) and (-webkit-device-pixel-ratio: 2)" />
<link rel="apple-touch-startup-image" href="images/splashscreens/ipadpro3_splash.png" media="(device-width: 834px) and (device-height: 1194px) and (-webkit-device-pixel-ratio: 2)" />
<link rel="apple-touch-startup-image" href="images/splashscreens/ipadpro2_splash.png" media="(device-width: 1024px) and (device-height: 1366px) and (-webkit-device-pixel-ratio: 2)" />
<!-- google -->
<meta name="google-site-verification" content="zqAmu3gsMd4YRk6M3zUMkIprDgoQGQV7prZEMaZu6LA" /> <script async src="https://www.googletagmanager.com/gtag/js?id=UA-122660061-2"></script> <script>window.dataLayer=window.dataLayer||[];function gtag(){dataLayer.push(arguments);} gtag('js',new Date());gtag('config','UA-122660061-2');</script>
<!-- pwa -->
<script>if('serviceWorker'in navigator){window.addEventListener('load',function(){navigator.serviceWorker.register('service-worker.js').then(function(){console.log('[ PWA Fire Bundle ] Service Worker Registered');});});}</script> <script type="module">import{Workbox}from'https://storage.googleapis.com/workbox-cdn/releases/4.0.0/workbox-window.prod.mjs';if('serviceWorker'in navigator){const wb=new Workbox('/service-worker.js');wb.register();}</script>
<div style="color:#dedede;padding-top:40px;">&copy; 2019<script>new Date().getFullYear()>2019&&document.write("-"+new Date().getFullYear());</script>,&nbsp;Wysc Services.</div>
<div class="text-center p-4 fontgochihand" style="color:#aaa;font-size:1.8em;"><span onclick="window.scrollTo({ top: 0, behavior: 'smooth' });" style="cursor:pointer;">Wysc.</span></div>
</body>
</html>
```
```
<!-- desktop topnav -->
<div class="d-none d-md-block noselect">
    <nav class="navbar fixed-top navbar-dark bg-transparent">
        <a class="navbar-brand hoverscale" onclick="window.scrollTo({ top: 0, behavior: 'smooth' });" style="cursor:pointer;">
            <img src="media/wsc-square-sm.png" width="70" height="70" class="rounded-circle d-inline-block align-middle shadow" alt="logo">
            <span class="d-inline-block align-middle fontgochihand wlogo">Wysc.</span>
        </a>
        <ul class="navbar-nav navbar-expand ml-auto align-middle">
            <li class="nav-item active p-3">
                <a class="nav-link" onclick="window.scrollTo({ top: 0, behavior: 'smooth' });" style="cursor:pointer;">Home<span class="sr-only">(current)</span></a>
            </li>
            <li class="nav-item p-3">
                <a class="nav-link" href="/wysc/blog">Blog</a>
            </li>
            <li class="nav-item p-3">
                <a class="nav-link" href="/wysc/docs">Docs</a>
            </li>
            <li class="nav-item p-3">
                <a class="nav-link" href="/wysc/start">Web App</a>
            </li>
        </ul>
    </nav>
</div>
<!-- mobile bottomnav -->
<div class="d-md-none noselect">
    <nav class="nav-extended fixed-bottom rounded-top shadow-lg p-2 wnavmb">
        <div class="nav-content text-center">
            <ul class="nav nav-justified">
                <li class="nav-item align-middle">
                    <a class="nav-link pulsate-fwd wnavmblinkactive" onclick="window.scrollTo({ top: 0, behavior: 'smooth' });">
                        <i class="material-icons">home</i><br>
                        <div>Home</div>
                    </a>
                </li>
                <li class="nav-item align-middle">
                    <a class="nav-link pulsate-fwd wnavmblinks" href="/wysc/blog">
                        <i class="material-icons">class</i><br>
                        <div>Blog</div>
                    </a>
                </li>
                <li class="nav-item align-middle">
                    <a class="nav-link pulsate-fwd wnavmblinks" href="/wysc/docs">
                        <i class="material-icons">vertical_split</i><br>
                        <div>Docs</div>
                    </a>
                </li>
                <li class="nav-item align-middle">
                    <a class="nav-link pulsate-fwd wnavmblinks" href="/wysc/start">
                        <i class="material-icons">apps</i><br>
                        <div>Apps</div>
                    </a>
                </li>
            </ul>
        </div>
    </nav>
</div>
```

### Iframe lazy load
```
<script defer> // iframe lazy load 0.190720
function init(){var vidDefer=document.getElementsByTagName('iframe');for(var i=0;i<vidDefer.length;i++){if(vidDefer[i].getAttribute('data-src')){vidDefer[i].setAttribute('src',vidDefer[i].getAttribute('data-src'));}}} window.onload=init;</script>
```

### Widgetbot
```
<script src="https://cdn.jsdelivr.net/npm/@widgetbot/crate@3" defer> // widgetbot 0.190720
    new Crate({
        server: '319372945929666571',
        channel: '590703218049286163',
        shard: 'https://disweb.deploys.io',
        location: ['bottom', 'right'],
        notifications: false,
        defer: true,
    });
    if (window.innerWidth < 768){
        crate.setOptions({
            location: [-90, 'right'],
        })
    } else {};
</script>
```

<br><br>
## Docs

### Page table of contents
```
<div class="col-12 col-md-6 docutoc pt-4 pb-4"> <!--0.190727-->
    <div class="card rounded-lg shadow-sm">
        <div class="card-body">
            <ol class="docutdn mt-2 mb-2">
                <li><a href="#infrastructure">Infrastructure</a></li>
                <li><a href="#apis">APIs</a></li>
                <li><a href="#discord-server">Discord Server</a></li>
                    <ol>
                        <li><a href="#non-critical-functionality">Non-Critical Functionality</a></li>
                    </ol>
                <li><a href="#start-web-app">Start/Web App</a></li>
                <li><a href="#website">Website</a></li>
            </ol>
        </div>
    </div>
</div>
```