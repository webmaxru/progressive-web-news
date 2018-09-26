# Week 39

* [__Maskable icon proposal for the #WebAppManifest__](https://w3c.github.io/manifest/#icon-masks6)  
Some platforms have their own preferred icon shape, but as web applications should work across multiple platforms, it will be possible to indicate that an icon can have a user-agent-specified mask applied by adding the maskable purpose - just follow this spec by [Kenneth Christiansen](https://twitter.com/kennethrohde) and team.

* [__Intent to Deprecate and Remove: cache.addAll() duplicate requests__](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/l2YVa_M4ODs/o0PqQOl6CgAJ)  
According [Google Chrome team](https://twitter.com/chromiumdev) plans, starting from Chrome 72 cache.addAll() will reject if there are duplicate requests. Be careful with the resource list you want to cache. 
 
* [__#PWAChat with @AaronGustafson__](https://twitter.com/i/moments/1042194377089536001)  
Six interesting questions about PWA answered by [Aaron Gustafson](https://twitter.com/AaronGustafson) in a form of Twitter Moment.


# Week 38

* [__#PWAChat by Windows Dev Docs__](https://twitter.com/WindowsDocs/status/1042111770528075776)  
Six interesting PWA questions answered by [Aaron Gustafson](https://twitter.com/AaronGustafson). Can I use web components when building PWAs? And more.

* [__Inside look at modern web browser (part 2)__](https://developers.google.com/web/updates/2018/09/inside-browser-part2)  
You type a URL into a browser. What happens next? A detailed explanation how navigation works by [Mariko Kosaka](https://developers.google.com/web/resources/contributors/kosamari) including Service Worker and Navigation Preload cases. 
 
* [__Service Worker: introducing update check to importScripts()__](https://docs.google.com/document/d/1p_2axsp96GfME5lE4Zd-p5ei80-9OD_brFUjLYyN8B0/edit)  
[Google Chrome](https://twitter.com/chromiumdev) is about to ship byte-for-byte update check for Service Worker scripts imported by importScripts() which makes updateViaCache option working according to the standard! 


# Week 36

* [__New top-level HTTP Archive Report on Progressive Web Apps__](https://medium.com/dev-channel/new-top-level-http-archive-report-on-progressive-web-apps-ba67f3084137)  
PWA part of Alexa Top 1M ranked websites keeps growing at a good pace - says the study by [Thomas Steiner](http://twitter.com/tomayac).

* [__Charting Browser Interoperability__](https://blog.chromium.org/2018/08/charting-browser-interoperability.html)  
A great helper for all webdevs working with Web Platform cutting edge: a searchable chart of all JavaScript APIs in all browsers from [Chromium Developers](https://twitter.com/ChromiumDev). Including more than [57 items](https://web-confluence.appspot.com/#!/catalog?releases=%5B%22Safari_11.1_OSX_10.13.4%22,%22Edge_17.17134_Windows_10.0%22,%22Firefox_61.0_Windows_10.0%22,%22Chrome_68.0.3440.75_Windows_10.0%22%5D&q=%22pushmanager%20or%20pushsubscription%20or%20serviceworker%22) related to ServiceWorker & WebPush. 
 
* [__Google Search now uses Service Worker for repeated searches__](https://venturebeat.com/2018/09/01/google-search-now-uses-service-worker-for-repeated-searches/)  
[Emil Protalinski](https://venturebeat.com/author/emil-protalinski/) found out that only Chrome for Android is getting the treatment because other browsers don’t support Navigation Preload, a latency optimization apparently critical for Google Search to run a Service Worker.


# Week 35

* [__An Event Apart: Designing Progressive Web Apps__](https://www.lukew.com/ff/entry.asp?1998)  
In his "The Case for Progressive Web Apps" presentation at An Event Apart in Chicago, [Jason Grigsby](http://twitter.com/grigs_talks) walked through the process of building Progressive Web Apps for your Web experiences and how to go about it. Here's [Luke Wroblewski's](http://twitter.com/lukew) notes from his talk.

* [__Progressive Web-First Apps__](https://medium.com/ben-and-dion/progressive-web-first-apps-6e35b35f073f)  
[Dion Almaer](https://twitter.com/dalmaer) explains why it makes sense to start with a PWA experience for your new idea. 
 
* [__Make your great application perfect with Google Lighthouse__](https://webagility.com/posts/make-your-great-application-perfect-with-google-lighthouse)  
Is there any way to verify quality of your app so that you can ship something you can be really proud of? [AlanSemenov](https://twitter.com/AlanSemenov) has an answer!
 

# Week 34

* [__Shipping PWAs as Chrome Extensions__](https://dev.to/samthor/shipping-pwas-as-chrome-extensions-3l5c)  
Distributing your PWA as a Chrome extension? That's possible! [Sam Thorogood](http://twitter.com/samthor) gives all the details about his Emojityper PWA.

* [__Twitter PWA Release Notes__](https://twitter.com/i/release_notes)  
[Twitter Lite](https://mobile.twitter.com/) team started to publish the version history. In the latest update: better integration with Windows 10 - viewing live events or moments will add an entry to your Windows Timeline so you can easily return later to see updates. Plus 8 more feature added. 
 
* [__Service Worker Caching Strategies Based on Request Types__](https://medium.com/dev-channel/service-worker-caching-strategies-based-on-request-types-57411dd7652c)  
[Thomas Steiner](https://medium.com/@steiner.thomas) from Google is explaining how to use Request.destination property in your service worker to determine the type and/or caching strategy of requests.


# Week 33

* [__Intent to Implement: Writable Files__](https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/U4rXcm5CE4Y/3XmVtoAPDwAJ)  
Chrome team started to work on a standard web platform feature (proposed by [Web Incubator CG](https://github.com/WICG)), making it possible to write things like document editors as PWAs. This includes open files and folders for read and write access, saving files to a user selected location, and persisting references to files/folders to later access again.

* [__Google rolls out Windows 10 Action Center support for Chrome__](https://windowsreport.com/google-chrome-windows-10-action-center-support/)  
[Peter Beverloo](https://twitter.com/beverloo/status/1027258639688654854) from Google Chrome team announced the native (via Action Center) support for Web Push notifications of the PWAs installed on Windows 10 via Chrome 68+. This feature is hidden behind the flag though.
 
* [__Vue CLI 3.0 is here!__](https://medium.com/the-vue-point/vue-cli-3-0-is-here-c42bebe28fbb)  
[Evan You](https://twitter.com/youyuxi) is introducing the next major version of CLI which now includes pwa-plugin based on WorkboxJS. This plugin generates the web app manifest and registers a service worker which is precaching the core app files, so you have offline-ready app shell.


# Week 32

* [__A one year PWA retrospective__](https://medium.com/@Pinterest_Engineering/a-one-year-pwa-retrospective-f4a2f4129e05)  
"New signups increased by 843%" and other incredible numbers + some tech details in [Zack Argyle](https://twitter.com/ZackArgyle)'s post about Pinterest PWA.

* [__The Web Push Checklist__](https://medium.com/@senthil_hi/the-web-push-checklist-3d7ee1225901)  
[Senthil Padmanabhan](https://twitter.com/senthil_hi) is writing about eBay's learnings and research to provide the best user experience when dealing with notifications.

* [__PWA: Progressive Web All-the-things__](https://paul.kinlan.me/pwa-progressive-web-all-the-things/)  
Based on the feedback gathered during 3 years of #PWA, [Paul Kinlan](https://twitter.com/Paul_Kinlan) is introducing PWA narrative in a way that every business and developer knows what they should focus on.
