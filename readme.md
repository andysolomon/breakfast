#Breakfast

Breakfast is a mobile-first approach for fast and meaningful breakpoints.
Breakpoints represent Breakfast sizes.

#The Install
`bower install breakfast`
Use bower to install a `breakfast.scss` file into your project.  Use grunt or bowerrc file to install **Breakfast** in the desired location.

#The Idea:
> If you must eat breakfast, try to eat a medium breakfast and if you can avoid the larger breakfast avoid it.  A larger breakfast will be more expensive and will require a lot more maintenance.

#The Key Take-Aways
* Again, aim for the medium breakfast and thats it.  Rethink your design if you need a lot of continental and international breakfast.
* Basically avoid the breakpoints that are harder to spell. Keep It Simple Got Damn It.
* Simple meals make for happy breakpoints.

> Install with bower, and have usable media queries in seconds.

#The Menu
##Small
Has a maximum width of 470px.  Meaning If you dare to call this media-query it will design viewports smaller than your standard phones.
Because we are working in a mobile-first approach; you will actually never write a small breakpoint so don't worry about it.

##Small Only
If you want some thing to only show on a phone use this media-query.  But again we are working in a mobile-first nature so, please don't use this media-query unless you absolutely have to.

##Medium
Get comfortable with writing `@include breakfast(medium){color:red;}`.
This is the most commonly used breakpoint that you will approach in a mobile-first nature.  Essentially you will find once viewports reach the **tablet** width it may require something that can progressively enhance the experience.

##Medium Only
You may never use this unless, you want to design specifically for the **tablet** range.

##Large
This is what most of your users on a **desktop** will be looking at.  Try write well enough code to where you don't even have to write for this breakpoint.  Realistically you will have many medium breakpoints, and consider the larger breakpoints when writing medium breakpoints.
Use this breakpoint if you definitely want to progressively enhance the experience for **desktop** users.

##Large Only
I think you understand the patterns by now.

##Continental
Wow!  This is a **very high** breakpoint, and you should never have to write for such a high breakpoint.  This is **progressive enhancement** at its finest, progressive enhancement after this will be **very expensive**.

##Presidential
If you are writing presidential breakpoints, you should rethink your entire design process at this point, and **reevaluate** the development project....

##International
Apple 5K monitors may need a special type of design we haven't thought of yet.  Consider this breakpoint if you want to design for **televisions** and super large monitors or spaceships.
