#Sideburns
###Because nothing else goes better with handlebars.

----------------------------------

[Hnadlebars.js](http://handlebarsjs.com/) is great. It's one of the more widely used javascript templating libraries out there. 

#####But there are a few things missing. 

Sideburns aims to be a no-brains wrapper for Handlebars.js, for when you want some good old-fashioned templating right where you want it.  
It supports locally-hosted templates (as opposed to in-line) as well as easy rendering/insertion.  

#####Here, look: 

~~~

//Make a new template.
var title = new Template()
title.init("/templates/article")

//Give it some context and a place to live.
var context = {title: "Hi there", subtitle: "I really enjoy your moustache."}
title.render(context, "#title");


~~~