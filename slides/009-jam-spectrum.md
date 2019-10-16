---
notes: |
  Here we are going to define things as being not very jammy on the "empty jam jar" side of the spectrum through to the "jammiest jam donut" you can imagine!

  So as ember developers we are used to building Single Page Applications, did you know that every SPA you have ever written deserves a place on the jam stack continuoum? depending on a few things it will land at a different place on the chart, but we'll get into that.

  If you are writing a SPA you would usually have a separate repo for your frontend app and your backend. I know monorepos are all the rage right now but for simplicity i'll talk about it as a single repo!

  IF you're building your own SPA that hits your own api that would move you towards the less jammie side of this spectrum. not a completely empty jar but maybe one that used to have JAM in it and is a bit sticky still.

  to move up the jam scale you need to be hitting an EXTERNAL API. Why? well remember back to who invented the term, Netlify doesn't support server hosting. Technically it has serverless functions but they in themselves are more of a mid-jam technology

  so what do I mean by an external API? well you could use something like the Github api directly or you could use something like contentful to be able to create something custom. Or, if you wanted to build a JAM site that allowed you to buy things you could use something like Moltin which is essentially a headless e-commerse platform. Using these external tools starts to point you towards the serious Jam category, Maybe even just over half way half way by just using Ember with an external API

  so imagine now that we have an app that's hitting one of these external apis, what else do we need to do to move our it closer to Ultimate JAM!?
---

### JAM Spectrum

![Jam Spectrum](/images/jam-spectrum.jpg)



![Empty jam jar](/images/empty-jam.png) <!-- .element class="fragment" style="position: absolute; top: 200px; left: 0px" -->
![Most jam](/images/most-jam.png) <!-- .element class="fragment" style="position: absolute; top: 300px; right: 0px" -->
![Half Jam](/images/jamiedodger.png) <!-- .element class="fragment" style="position: absolute; top: 400px; right: 600px; height: 200px" -->
