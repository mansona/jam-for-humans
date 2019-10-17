---
notes: |
  So now that you know what it looks like, let's go back over the structure. we have 3 things that are working together, an Ember app that I will call our "host" application <SLIDE>, this is just a regular ember app with no modifications and we saw it being created with ember-new a second ago. and then we install two addons, one core "system" addon and then a template addon.

  The core system addons for an Empress product is essentially the brains of the operation. It does some fun things like generating example content <SLIDE> for you and installs any extra addons that are necessary in the host app. this is a pretty powerful and useful part of the Ember addon API that is definitely underutalised in my opinion :joy:.

  It also contains the build process that converts your markdown into a static api for your ember app to consume <SLIDE>. And because of the joys of Ember addons you don't need to do anything at all to wire it up, that is just done for you. And lastly the core system addon is where the routes are added to your app. this means that, apart from the auto generated content your host app is still practically un-touched.

  then we come to the template addon. in the core system addon I said that we have the routes, but that does **not** include any templates. All templates and styles are added from the template addon. This is the next point that I think makes Empress interesting
---
# empress-blog Architecture

![step 1](/images/chart-1.svg) <!-- .element class="fragment" style="position: absolute; top: 80px; left: 150px" -->
![step 1](/images/chart-2.svg) <!-- .element class="fragment" style="position: absolute; top: 230px; left: 150px;" -->
![step 1](/images/chart-3.svg) <!-- .element class="fragment" style="position: absolute; top: 480px; left: 160px;" -->
![step 1](/images/chart-4.svg) <!-- .element class="fragment" style="position: absolute; top: 392px; left: 520px;" -->
