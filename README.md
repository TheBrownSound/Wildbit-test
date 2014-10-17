#Beanstalk Pricing Page for Wildbit
Current Page: [http://beanstalkapp.com/pricing](http://beanstalkapp.com/pricing)

###Goal: Redesign Plans & Pricing Page

####Specifications:
* Don't change plans or price.
* Present plans more clearly.
* Focus on conversion.

###Design Changes:

####Header and Title:

Existing header title was easy to skip over when scanning the page. First 14 days free is a pretty important selling point. Adding the styled header for visual encapsulation as well as adjusting copy was aimed at bringing more attention to the header.

####Plans:

Exisiting plan layout packed a lot of information into a small space. Some of which didn't help me make a decision to select a plan. Also had really low contrast on both the text and the call to action button.

Increased text contrast and changed the call to action button to green to stand out better. Changed call to action button text to 'Select' from 'Sign up' which could dissuade users from clicking. This is probably something worth a/b testing.

Emphasized the silver plan which is the clear "sweet spot". Gives the user a focal point to draw thier attention. Without a focal point the user is forced to attempt to evaluate all the plans.

Removed the "servers/repository" item from plan descriptions. Did multiple usability tests on various developers. Was overwhelmingly confusing even with the tooltip and didn't contribute helping the user make a plan decision.

Moved the gold, platinum and diamond extra features down below the standard features. Existing layout did a good job of connecting the features to the individual plans, but at the expense of adding extra noise.

####Extra plans:

Assumed the free plan link was de-emphsised because the priority is on paid conversions. Kept the free plan link subtle and also added the link for users looking for larger custom plans.

####Feature lists:

Kept existing standard features. Added wrapper to additional features to better differentiate from standard features. Named extra features Enterprise to add an additional connection to the specific plans.

####FAQ:

Just added simple header title to give some additional context to the questions.

####Similar pages:
* [Assembla](https://www.assembla.com/plans)
* [Bitbucket](https://bitbucket.org/plans)
* [CloudForge](http://www.cloudforge.com/pricing)
* [Codebase](https://www.codebasehq.com/packages)
* [GitHub](https://github.com/pricing)
* [Kiln](https://www.fogcreek.com/kiln/pricing/)
* [Plan.io](https://plan.io/pricing/)
* [Heroku](https://www.heroku.com/pricing)
* [DigitalOcean](https://www.digitalocean.com/pricing/)

---

###Development

Compile and watch stylesheets:
```
sass --watch stylesheets/scss/global.scss:stylesheets/global.css
```
