Email guests to your website
============

email-guests is a tiny snippet of code that you can embed or link to to allow visitors to your website to subscribe to your newsletter or drip email sequence.

Come Again?
===========

You can place this snippet of code in your blog footer, and then routinely email them with interesting content and discussions.

Hasn't this been done before?
=============================

Kind of. Certainly newsletter companies allow you to embed similar things to your site, but userfox has a few distinct advantages:

* it's much easier to use
* you can create drip sequences (day 0, day 30, day 45, etc etc)
* you can send newsletters in addition to afforementioned drip sequences
* it's free!
* 

Okay, I am sold. What next?
===========================

Download index.html and sign up for [userfox](http://userfox.com) – enter your [ClientID](https://app.userfox.com/settings/integration) on line 39

    		      clientId: ""  // paste your client ID here! you MUST do this.
              
becomes              

    		      clientId: "123493278482374832742"  // paste your client ID here! you MUST do this.

and you're done! You can then upload this file somewhere, host it on github (instructions coming very soon!) or copy and paste the contents onto your own web server. 


I need a demo
=============

Bjoern has a great newsletter [here](http://newsletter.zinssmeister.co)!


Can I list my demo?
===================

YES!

What about RSS integration?
===========================

We don't support that. We thought about it, but decided they're usually terrible. Our solution: blog and then manually write the email linking to it! It's more work, but it won't suck.


Do you even embed
=================

Yes! Just link to the site via an iFrame, boom!
