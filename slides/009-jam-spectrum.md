---
notes: |
  Who here is working on a single page app in production? or even a side project? The reason I'm asking about SPA is because if you have ever written one then you're already using JAM principles. This doesn't mean that every SPA is 100% JAM filled, but there are some things that you can do to your SPA to make it more Jammie.

  We'll go through a few things and show you how to move up the JAM continuoum.

  If you are writing a SPA you would usually have a separate repo for your frontend app. I know monorepos are all the rage right now but for simplicity i'll talk about it as a single repo!

  IF you're building your own SPA that hits your own api that would move you towards the less jammie side of this spectrum. not a completely empty jar but maybe one that used to have JAM in it and is a bit sticky still.

  to move up the jam scale you need to be hittin an EXTERNAL API. Why? well remember back to who invented the JamStack, Netlify doesn't support server hosting. Technically it has serverless functions but they in themselves are more of a mid-jam technology

  so what do I mean by an external API? well you could use something like the Github api directly or you could use something like contentful to be able to create something custom. If you wanted to build a JAM site that allowed you to buy things you could use something like Moltin. These are starting to put you into the serious Jam category.

  so now that we've set up our app with an external api, what else do we need to do to move our SPA closer to the JAM stack?
---

### JAM Spectrum

![Jam Spectrum](/images/jam-spectrum.jpg)



![Empty jam jar](/images/empty-jam.png) <!-- .element class="fragment" style="position: absolute; top: 200px; left: 0px" -->
![Most jam](/images/most-jam.png) <!-- .element class="fragment" style="position: absolute; top: 300px; right: 0px" -->
