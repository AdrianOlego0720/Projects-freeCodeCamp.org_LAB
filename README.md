# I'm Adrian, entering college to get a "Bachelors Degree In Computer Engineering" whilst learning to be a "Full Stack" web developer.
As a kid I liked breaking my stuff to fix them, it was a fun moment for me, and if we had all the money in the world I'm sure I would have ended up with a room full of perfectly fine tech, broken to be fixed.
My degree can be concerned with programming, so while it's summer (or break) I'd like to get a feel for it, learn the basics, and have web development as one of my career paths in coding. 
# Coding is, so far, very fun.

This repository serves as a place for projects that I made while learning to be a "Full Stack Developer" with freeCodeCamp.org, and working towards completion to get a certification. Here, I'm not looking to just make the project that works and can be submitted but rather have something I can contiously expand as I gain more knowledge and skills. Feel free to look around my commits, I put them here for me and others to see (also because I like how that green github commitments looks).

# <--- 6/11/2025 ---> [recipelistPage HTML]
This project took me 2 hours and 10 minutes. Though, me being scared outta my mind seeing the empty editor and running back to the CatPhotoApp tutorial probably had something to do with it. I had a lot of fun so I went the extra mile to add a few more things that weren't required after I had submitted the project.
Coding has been great so far, and I hope it keeps its magic.



# <--- 6/12/2025 ---> [travelagencyPage HTML]
This project, I honestly didn't bother to check the time before I started. Though, I assume it took me a solid 45 minutes. I was introduced to a few "Search Engine Optimization" techniques with meta, also had to take a quiz on the lessons, and was required to make this website alongside some practice on &lt;figure&gt; elements. It was great, didn't have many errors and got everything approved the first time around.
After working on [travelagencyPage] I was still up for more, so I went and revisited my [recipelistPage]. I put [recipelistPage] through AI (Bing Copilot) to get some feedback on how I structured it, and while it praised me on my semantic HTML structure, playful content, proper image usage, and accessibility consideration, I did receive feedback on three things I got wrong:
1. Incorrect &lt;main&gt; tag placement - which was in two parts the &lt;head&gt;, and &lt;body&gt;. I went ahead and fixed that by making sure &lt;main&gt; is only within the &lt;body&gt; structure.
2. Metadata considerations - I did not have a &lt;metadata&gt; description for SEO, in my defense I was only introduced to it today, so to fix I added an appropriate description for the page contents.
3. List structure - My &lt;img&gt; elements were just sitting plainly in the &lt;ul&gt; element after the listed item. I went ahead and fixed it by wrapping each image inside a &lt;figure&gt; element.

TLDR: Learned a few new things today which are SEO practices through metadata, as well as character entities. Furthermore, I practiced and repracticed lines I did for [recipelistPage] to create [travelagencyPage], as well as updated [recipelistPage] to my current knowledge, which help me get a better understanding on why if you write code, you should write it to be readable for humans aswell. 
( P.S I'm not saying that last line because I struggled to read my first HTML code, just that I realized I needed to work on my spacings :) )



# <--- 6/13/2025 ---> [videocompilationPage HTML]
This project was rather simple, it taught me the basics of embedding links, and permission lines required to make outside links work. Though, I only used YouTube links, not maps or audio files. For now, I'll avoid trying to update it with an audio file as I understand this involves a call script and I don't really know how to make folders within GitHub repositories. Lazy, I know, but the heat in my room is becoming increasingly unbearable now that the rainy weather is coming to a halt so I will shift my schedule to practice to account for that.

During this lab I revisited and picked up on a few things: 
1. I forget to incorporate &lt;section&gt; to my &lt;body&gt; element --- It's important sections are clearly labeled within the code to ensure proper accesibility to on-screen readers.
2. &lt;footer&gt; Should be within the body, but just outside the &gt;main&lt; element --- This ensures that any disclaimers for the website, or other vital information are always loaded regardless of the page the user may branch into.

Issues that happened today:
1. Embeded links failed to load --- I had forgotten a core concept of embedding with YouTube and that is to replace the &#47;watch?v=nqO6cEbXyKM line with the &#47;embed&#47;nqO6cEbXyKM line. P.S that link goes to the Youtuber that pointed it out with a rather straightforward video, wasted opportunity to rickroll I know, but I wanted to document the first YouTube video I'd have consulted for a simple issue.
2. I had this moment where I thought I had encountered an issue, the embeded links would load properly but never play audio. I begun messing around with the &lt;iframe&gt; string, and thought I was coming to a eureka moment where I'd solve my first issue. I was even comparing the embeded link Youtube provides, to the embeded link i had typed. Turns out, no, it was never a problem with the code, my system was just muted. &#40;Note to self: You have a 60% hall effect keyboard where it's very easy to press the FN key and access a shortcut option during heavy typing sessions&#41;
