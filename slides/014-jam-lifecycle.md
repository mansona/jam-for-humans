---
notes: |
  the lifecycle of a jam project can be split into 2 parts. Server-side or "build time" and client-side or "run time".

  at the end of build time we end up with a while bunch of index.html files arranged in folders like you might expect in the 90s. There will be one index.html for every route in the app (ideally)

  we can deploy these somewhere, think Amazon s3 or as I said a few too many times Netlify (I'm not being paid). The key here is that they are dumb servers or CDNs

  Now that you have a ubnch of static html deployed you can fvisit your site with JS turned off and it should still work. At this point we are at parity with static site generators. wehn the JS loads you get the benefits of the SPA where subsequent page loads only download a bit of json and rendering happens in the browser giving lighning fast loading times. and in some case you might already have the data so it is instantaneous.


---

# jam lifecycle
