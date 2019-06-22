# chatstaff-website

Rendered version is at:  https://libraryh3lp.github.io/chatstaff-website/

Changes to the code repo take a couple of minutes to show up in rendered version. Changes made here on GitHub will NOT automatically go to production at this time.

**Font Awesome info.** 
I noted the wrong FA version here originally.  The site's theme originally shipped with FA 3.0.2 (http://www.costaenzosrl.com/font-awesome-icons.html) which is older than I had said.  It does not really have a whole bunch of fonts.

I added the current free version of FA (5.0.9) on top of the existing one, so that we could add new ones and not break old ones in the process.  Cheatsheet: https://fontawesome.com/icons?d=gallery&m=free  

In order to get the black-on-hover, the New Way is like this:
  
 `<span class="fa-stack fa-1x fa-pull-left">`
  `<i class="fas fa-circle fa-stack-2x"></i>`
  `<i class="fas fa-sun fa-stack-1x fa-inverse"></i>`
`</span>`

This gets a sun icon (fa-sun) inside an orange circle and the styles are set to turn fa-stack black on hover.  Current example page is schedule.html.

Production site last updated 2019-06-21 11:06am.  https://chatstaff.org/
