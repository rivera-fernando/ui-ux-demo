# UI/UX Tech Talk/Demo



## So what is UI and UX, and how are the different or alike?

### [Ken Norton](https://www.kennorton.com/) – Partner at[ Google Ventures](http://www.gv.com/), Ex-Product Manager at Google

> "UX is focused on the user’s journey to solve a problem, UI is focused on how a product’s surfaces look and function"

### [Andy Budd](http://andybudd.com/) – Co-founder of[ Clearleft](http://clearleft.com/), Founder of[ UX London](http://uxlondon.com/)

> "A UX designer is concerned with the conceptual aspects of the design process, leaving the UI designer to focus on the more tangible elements"

### Personally:

While everyone seems to have their own definitions of UI and UX these days, I consider a UI to be the sum of all entities the user of a product interacts with. Designing a UI involves the styling of these entities. On the other hand, UX is the feeling and, obviously, experience that the user derives from interacting with the product. I will be clear, **a good UI is part of creating a good UX** but **a good UI does not automatically create a good UX**.



## Everything's subjective

The entire goal of designing a "good" UI and UX revolves around a happy user. The end-goal is keeping the user hooked, engaged, and wanting more. If they can enjoy using your product, there's a better chance they will keep using it and recommend it to their friends! (given it actually has proper functionality) However, everyone has different ideas of what a good UI and UX revolves around. I'll go into a few different schools of thought.

### Types of UIs:

#### Graphical User Interface

- **Q/A Interfaces** - Think prompts, leading you to the end result (whenever you install software)
- **Menu Interfaces** - Think multiple available selections (the menu bar, duh)
- **Form Interfaces** - Think user input in fields (login, etc.)

#### Command-Language Interface

- **Command-Line** - Can be wonderful if users know what they're doing

### UI Schools of Thought / Design Languages

- [Material Design](https://material.io)
  - I won't bore you with lines of text, just listen to my sweet voice.
- [Invisible UI](https://www.usertesting.com/blog/invisible-ui)
  - More listening
- There are more, try looking at [this](https://design-languages.com/)



## Good UI (personally)

- [Cornell Tech](https://tech.cornell.edu/)
- Most MLH hackathon websites ([Cornell](https://www.bigredhacks.com/), [UPenn](http://2019f.pennapps.com/), [etc.](https://mlh.io/seasons/na-2020/events))
- [Prettier](https://prettier.io/)
- [Typora](https://typora.io) (coincidentally what I used to make this document)
- [Material Design](https://material.io/) (obviously)

## Bad UI (personally)

- [User Inyerface](https://userinyerface.com/) is the best example of what not to do, and we'll go through some aspects of it, but it was created to highlight these flaws, it was not the product of someone trying and failing to create a good UI.
- [Arngren](http://arngren.net/)
- [Pacific Northwest X-Ray Inc](http://www.pnwx.com/)



## Interesting Dichotomy

[MIT](http://www.mit.edu/) has a wonderful UI and UX, it looks clean and sharp, intuitive interactions with the website abound, and I never feel bombarded with information. However, [MIT EECS](https://www.eecs.mit.edu/) has an "ok" UI, but a UX that I cannot tolerate. I say "ok" because sure, there's some whitespace in places that I think it shouldn't be, and some organization of their cards irks me, but others might dig it, so I digress. But the two main things that provide what I consider a sub-par UX are: the lack of cohesiveness between the MIT and the MIT EECS websites, and the sheer amount of information that is thrown at the user in different pages for the EECS site.

### Deeper dive into...search bars

This analysis of the MIT website brought me upon something I consider incredibly important: searching. No matter what kind of product you are designing, the user will want to accomplish what they want as efficiently as possible. If that means finding certain information first, searching within the product is an important resource that should be designed in the best way possible. I'll get more into it.



## CSS, HTML, and all that fun stuff

This isnt a front-end talk per se, but the concepts of UI and UX obviously go hand-in-hand with the front-end technologies you leverage to create them.

### CSS Frameworks

You've likely been told (and if you haven't, let me just say) "You don't need to reinvent the wheel." This is true. People have worked very hard so that you don't have to. By using a CSS library you get access to a rather robust set of styling options that you can simply implement in order to create a rather clean, albeit not exactly *unique* UI.

**[MaterializeCSS](https://materializecss.com/)** is one of my personal favorites. (If you couldn't tell by now, I love pretty much all things Google, and Material Design is no exception). 

- The Demo on styling will in fact be using a website that I worked on with my team at SwampHacks this year and then actually deployed and polished it up slightly. Check it out [here](https://swmp-sblease.herokuapp.com/).

**[MaterialUI](https://material-ui.com/)** is a great one for React.

If you're looking for something a little bit more *ambitious* than good ol' Material Design however, you can check out this cool [list](https://geekflare.com/best-css-frameworks/) of frameworks that might interest you. In the end, you won't know whether or not you like how something makes your product look unless you use it.



## The Demo!

Because UI is rather subjective, this demo will be fairly trivial, but it will highlight, rather dramatically, the difference between no styling at all, the most basic use of a CSS framework, and then the correct usage of a CSS framework. We'll take a look at the HTML for the appropriate pages and explore the work required to style your pages. From there, if anyone has any questions or requests of websites to critique, etc. I'd be glad to address them.

**No styling** [here](https://swmp-sblease.herokuapp.com/listing_bad/)

**Basic CSS usage** [here](https://swmp-sblease.herokuapp.com/listing_med/)

**Better CSS usage** [here](https://swmp-sblease.herokuapp.com/listing/)

<!--Keep in mind this isn't a super stylistic website, at this point I will have already covered the different components in MaterializeCSS-->



## Random UI/UX Topics and Considerations

### Mobile

Please make your product responsive. Your components should resize accordingly to device, and therefore window size. This is one of the magical uses of many CSS frameworks, and I urge you to take advantage of it. In the increasingly fast-paced lives that many of us live, and with the advances in mobile technology, many people are opting to visit websites on their phones. The next topic is closely related.

### Interactions

Not only should your website be visually appealing, but it should also be easy to use. And this isn't necessarily how easy it is to find a certain tab or know what a button does. In this context, I am talking about how the user is communicating with the product. Are they using a mouse, swiping with their finger, etc. There are too many considerations for me to list, but you must be cognizant of this when designing your product. For example, if the user is on a phone, without access to a browser scroll bar, swiping the length of the screen to get to the last entry of a table would be cumbersome! I'm sure you can think of other examples.



## Questions?