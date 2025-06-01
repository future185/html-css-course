Welcome to the complete HTML and CSS course. In this course,

we're going to learn how to build websites from a beginner to a professional

level, and by the end of this course, we're going to build youtube.com.

Now you don't need any previous coding or technical experience.

This course is designed to be your first step to becoming a software engineer.

We're going to start from the very basics of HTML and CSS and build our way up

step by step. And along the way,

we're going to learn all the major skills that we need to create websites at a

professional level.

You can find the different sections of this course below the video here and

here. And after each section,

I'm going to give you a bunch of exercises that you can do on your own to

practice the skills that we learned in total.

This course is going to have more than 100 exercises. Lastly,

you don't have to worry about taking notes.

I created an HTML and CSS reference that will list everything that we learned in

this course. With that said, let's get started.

I am going to be doing this course on a Mac,

but everything is the same for a Windows computer. Before we begin,

we're going to need two pieces of software, a web browser and a code editor.

A web browser lets us view websites on the internet.

It's also going to let us view the website that we create in this course.

The most popular web browser for web development is Google Chrome.

A code editor helps us write our HTML and CSS code.

The most popular code editor for web development is called VS.

Code or Visual Studio Code. To install both of these,

we can go to google.com and then search for Google

Chrome or for VS code and then

open the first result and follow the instructions to download and install.

Once we have those two installed, we can start the course.

We'll begin by learning what is html. HTML stands for

hypertext markup language. You don't have to worry about what that means.

Just know that it's a tool that we use to create websites.

Every website from YouTube to Google to Amazon uses a combination of

HTML and CSS to create everything that we see on the website.

The easiest way to understand what HTML is,

is that we're simply giving instructions to a computer.

We're telling the computer what to do step by step.

The computer will then follow our instructions to create our website.

So I find the best way to learn HTML is to jump in and give it a try.

So we're going to create our first HTML file and our first website.

Let's go to our computer and we're going to create a new folder.

So this folder is going to contain all the code for this course.

I'm going to call this HTML dash CSS dash course.

Next, we're going to open this folder in our code editor.

So I'm going to open vs code,

and then I'm going to click file open

and I'm going to find the folder that we just created, which is this one.

Now once that's open,

you should see the folder name at the top here and on the side here.

Now let's create our first HTML file.

We're going to click this icon to create a new file and we're going to call this

file website dot html.

So we have to make sure that this file ends with html.

This tells a computer that this file contains HTML code rather than just text.

So as I mentioned, HTML is basically some instructions you give to the computer.

We're going to learn our first instruction,

which is less than button greater

than, and we also need to type lesson slash button greater than,

but our code editor might auto complete this for us.

So this is an instruction to create a button and inside the button we're

going to have the text. Hello.

Now let's save our file and we're going to learn how to open this in our web

browser. To open our new website,

we're going to go to the folder that contains our code.

We're going to find our HTML file.

We're going to right click open with Google Chrome.

And now you can see that we have our first website that has a button with a text

Hello inside. And if we look back to our code,

that's exactly the instruction that we gave to the computer. So as you can see,

HTML is pretty straightforward. It's pretty easy to understand what's going on.

Now let's try another instruction. We can give to the computer on a new line.

We're going to type less than P, greater than,

and we also need to type less than slash p greater than,

and our code editor might auto complete this for us too.

So the P here stands for a paragraph. This is a paragraph of text.

Inside our paragraph, we can put some text.

So let's put the text paragraph of text.

Now we can save this and to get our website to reflect our most current code,

we're going to go to our webpage and refresh. And now you can see that our

website is displaying a paragraph of text just like we told the computer to do.

So that's basically how HTML works.

The computer reads our HTML code from top to bottom and then

follows those instructions and creates a button and a paragraph

of text.

If we reverse the order of these lines, for example,

if I put the paragraph up here and I save it and refresh

the page, then the paragraph will appear on top because again,

the computer is just following our instructions one by one.

Now I'm going to introduce some terminology.

So each of these things that we're displaying on the webpage is called an HTML

element.

So a button is a type of HTML element and a paragraph is another type of

HTML element.

So element is just a generic term that we use to describe anything that we can

display on the webpage,

and we're going to be using this term element throughout this course. So now I

want to explain why we have to write all of these symbols that's less than this,

greater than, and this less than slash This is something called syntax.

Syntax are the rules for how a coding language like HTML should be written.

If you think of a language like English, we have something called grammar,

which is the rules of the language.

Syntax is basically the same thing except for coding languages. Now,

the biggest difference between a language like English and a coding language is

that in English, you don't have to follow the rules of grammar perfectly.

People can still understand you, but in a coding language,

if you don't follow the rules of syntax,

the computer won't understand your code. For example,

let's break the rules of syntax by deleting this greater than symbol,

and now we're going to save our file and we're going to go to our website and

refresh. And now you notice that our button is gone,

and that's because we're not following the proper syntax.

So the computer doesn't understand our HTML code anymore.

So let's put that greater design back so that we're following the proper rules

of syntax and we don't need this.

So let's save and refresh our page.

And now our button is back because we're following the rules of syntax.

👉
So what exactly are the syntax rules for H T M L?

So this part of the code is called an H T M L tag.

It basically tells a computer what we're trying to create.

We write a tag by writing the less than symbol. This is the tag name,

which tells a computer what kind of element we're trying to create,

and then the greater then symbol.

So every element consists of two tags in opening tag and a

closing tag. The closing tag is the same as the opening tag,

except it has a slash in front of the tag name.

That's how you can tell it is a closing tag.

You can think of the opening tag as the start of the button and the closing tag

as the end of the button.

And then in between is a content or the text inside the button.

And the same thing for the paragraph. The paragraph has an opening tag,

a closing tag, and some content inside the paragraph.

So as long as we follow these syntax rules for html,

we have an opening tag and a closing tag,

and the closing tag starts with a slash in front of the tag name.

Then our computer will know what to do and display our elements on our webpage.

👉👉
The next element that we're going to learn is a link to another website. For

example, if we go to Google and we search for something on Google,

it will give us a bunch of links and when we click these links,

it will take us to another website.

So we're going to learn how to do that in our HTML code.

So we'll go back to our website here and in our code we're going to type less

than a greater than.

So this A here represents an anchor element.

An anchor is basically a link to another website.

So inside this anchor we're going to put the text of our link.

So let's put the text as link to YouTube.

We're going to save this and the refresh, and now we have a link,

but if we click this, it doesn't actually take us to YouTube,

and that's because we haven't told the computer where this link is supposed to

take us. Right now we just have a link without a destination.

So to set a website to link to,

we have to learn a little bit more HTML syntax.

So we're going to go into the opening tag and we're going to type space

HREF equals double quotes, double quotes.

So inside these quotes we're going to copy and paste YouTube's website url.

So to get that we can go to our webpage and then type in youtube.com.

And at the top here we have the url.

So we're going to copy this and paste this into our quotes.

And now we're going to save our file.

We're going to go back to our website and refresh.

And now we have a link that we can click. So when we click this link,

it's now going to take us to youtube.com.

So that's how we create a link to another website with html.

Now let's go back here and explain what this syntax means.

So this is called an HTML attribute.

An attribute basically modifies how an element behaves. In this example,

we are using the href attribute and it determines where this link element will

take us When we click it right now it's going to youtube.com,

but if we change this, it will take us to a different website.

So this attribute is modifying how the link element behaves.

So the syntax rules for an attribute are we have to have a space between the

attribute and the tag name. Otherwise, if I write href here,

the browser is just going to think that this whole thing is a tag name.

So that's why we have to have a space.

So then we're going to have an equal sign and double quotes.

So the text to the left of the equal sign is known as the attributes name,

and on the right side is the value. The value must be surrounded by

double quotes as you can see here. So you can kind of think of it like this.

The name tells us what we're modifying.

The value tells us what we are modifying it to.

So the H tells us we're modifying the destination of this link and we're

modifying it to youtube.com.

We can also have multiple attributes on an element to add another attribute,

we just separated with a space like this,

and now we're going to add another attribute to our link element,

and this one is called target.

So the target attribute determines whether this link opens in the current page

or in a new tab. So by default, if we don't have a target attribute,

it opens in the current page like this.

But if we set the target attribute to underscore blank,

now this link element will open in a new tab.

So let's go to our webpage and refresh and click this link.

YouTube will now open in a new tab.

So by using attributes we can modify different parts of this element's behavior.

The H RF attribute modifies where this link goes and the target attribute

modifies whether this link opens in a new tab or in the current page.

Keep in mind that the h r and target attributes only work on the link element.

The button and the paragraph elements have their own set of attributes that we

can modify, and we're going to learn these later on in the course. But for now,

I just wanted to introduce you to the idea of using attributes to modify our

HTML elements.

The last thing we're going to learn in this lesson is some weird quirks of the

HTML syntax.

So something that a lot of beginners have trouble with is that in html,

if you have multiple spaces like this, for example,

if we save this file and we reload,

you'll notice that all of these spaces just appear as one space on the website,

and that's because according to the syntax,

extra spaces are essentially ignored.

So beginners usually have trouble with this because for example,

if they want to add space between this button and this link,

they would start adding spaces in front of the link thinking that it will

move it away from the button. So if we save this and we refresh,

nothing happens.

And that's because all of these spaces are essentially ignored in html.

So later in the course, we're going to learn how to deal with these situations,

but for now, just keep this in mind.

So let's get rid of these extra spaces for now.

And another weird quirk of the syntax rule is that if I put my

cursor here and I press enter to create a new line and I put my cursor here,

again, these new lines also count as spaces,

so the browser essentially ignores them.

If I save the file and reload, you'll see that the new line doesn't do anything.

So this actually makes organizing our HTML code very flexible.

For example,

if I wanted some more space between these elements so that it's easier to read

in my code,

I can just add as much spaces as I want and it won't get reflected in the

website because extra spaces like these new lines are just ignored.

A lot of people like to put the content of the element on its own line like this

so that the tags basically align with each other in the same column.

And same thing for here. You'll notice that this line is really long.

We can actually add new lines here to make our code easier to read.

So when we organize our code like this,

we generally indent or add spaces in front of these lines. This helps us

clearly tell the difference between the elements, tags and its contents.

If we didn't have this indenting,

then it's pretty hard to tell where this element starts and where it ends,

especially when we have a lot of code.

Now your indents might look a little different from mine.

It might look something like this where you have more spaces than I do.

This happens because by default vs. Code uses four spaces per indent.

Generally in HTML and css, we use two spaces per indent.

To update this,

we're going to go down to this bottom toolbar and click this section,

and then we're going to click indent using spaces,

and we'll change this from four to two.

So now this file is going to use two spaces per indent,

so we can get rid of this and press tab to have proper indenting.

Now that only affects it for the current file.

We can change it for every file going forward by going to the bottom left here

and clicking this icon and then going into settings.

And in here we're going to search for tab size,

and I'm going to scroll down and we'll change the tab size from four to two.

All right, so we just learned the basics of html, how to write HTML code,

and then turn that into a website.

We also learned how to write HTML attributes which modify the behavior of an

element, and we learned about syntax,

which are the rules that we had to follow when writing our code.

Here are some exercises that you can try on your own to practice what we learned

in this lesson. Feel free to pause the video here if you need to.

You can find these solutions as well as more exercises on my website.

Super simple.dev. The link is below the video.

In this lesson,

we're going to learn CSS or cascading style sheets based on the name.

It's used to style our webpage,

so it's used to change the appearance of our H C M L elements.

So I've actually prepared a project that we can do in this lesson.

So we're going to open this project by going to super

simple.dev/exercises/buttons.

So on this webpage I have some really nice looking buttons from famous websites,

namely YouTube and Twitter that we can copy and practice our CSS with.

So we're going to go into our code and we're actually going to create a new file

for this exercise.

So let's create a new file and let's call it buttons dot

html.

And we're going to open our new HTML file in our browser.

So that's open the folder that contains our code.

We're going to right click open with Google Chrome.

And now I'm going to set this up by moving our reference design to the

bottom like this so that it's easier for us to copy it with css.

I'm just going to move that to the corner and then we can work here.

So first, let's work on creating the subscribe button.

So just like we learned before, we're going to create a button using H T M L,

so less than button, greater than,

and then insider button. We're going to have the text subscribe.

And now let's save and refresh our page. And now we have our button.

Next we're going to start changing the appearance of this button so that it

looks like the subscribe button from YouTube.

Let's go into our code and we're going to start writing some CSS to change the

appearance of this H T M L element. So to write css,

we have to create a new element called a style element.

So this style element is unique in that it doesn't appear visibly on the page.

So for example, if we save our file and then we reload the page,

the style element doesn't actually create anything.

So the purpose of this element is that inside this element we can write CSS code

which modifies the appearance of other elements. For example,

let's write our first bit of CSS code. We're going to type button

open squiggly bracket, close squiggly bracket.

And then inside these brackets,

we're basically going to give instructions to the computer on how to modify the

appearance. For example,

we can set the background dash color

red and semicolon.

So make sure that you write this out exactly as I have it here so that we're

following the syntax rules for css.

So let's save this file and refresh our page.

And now you can see that we set the background color of the button to red.

So as you can see, c s s is similar to H T M L.

We're simply giving instructions to the computer and then the computer follows

our instructions step by step. And just like H T M L,

we have to follow certain syntax rules when writing our CSS so that

the computer understands our code.

So what are the syntax rules for css? How does this code work?

So the word at the front here is called a CSS selector.

It tells a computer which elements on the page we are targeting with our CSS

code. In this case,

we are targeting all buttons on the page and we're going to change the

background color of all buttons on the page to red.

Now, inside these brackets, there are other rules that we have to follow.

The text to the left of this colon is called the CSS property.

It tells a computer what we are changing to the right of the colon

is the CSS value. It tells a computer what we're changing the property to.

In this case, we're changing the property background color to red,

and that's exactly what the computer did. The colon is here to just separate the

property and the value and the semicolon here is just like a period in

English. In English, you end sentences with a period in css,

you end a style with a semicolon.

So that's what all of this syntax means.

So we can actually add multiple styles inside these brackets.

So let's go ahead and add another style.

We're going to change the text color to white to match this design.

So the property for changing the text color is called color.

So notice that it's not called text color,

it's just something that we have to remember.

We're going to change it to white and we'll end it with as semicolon.

Let's save and refresh.

And now you can see that we change the text color of this button to white.

And that's basically how c s s works.

We tell the computer what we're targeting and then we give some styles and the

computer is going to apply these styles one by one.

So let's do another example. This time we'll set the border property.

So notice that our button has a border while the subscribe button here doesn't

have a border. So we're going to set the border property

colon two, none,

and we're going to save this file and refresh.

And now we just remove the border. So if you look at our styles here,

it's actually pretty straightforward. They're pretty easy to read.

We set the background color to red, text color to white and border to none.

So just like html, CSS is pretty straightforward.

We're essentially just giving the computer instructions.

So the general technique for going from something that looks like this to

something that looks like this is to just change these styles one by one.

So we're going to continue changing styles one by one until we get our design

here.

The next style I'm going to change is the height. So our button's a little bit

short, I'm going to make it taller.

So I'm going to set the height to something like 50 px.

The PX here represents pixels.

Pixels are a very common unit of measurement in the digital world,

image sizes are measured in pixels, video sizes are measured in pixels,

and your screen sizes also measured in pixels. In this case,

we're going to set the button high, two 50 pixels.

And don't worry too much about knowing what 50 pixels looks like.

The more that you write CSS and work with pixels,

the more you get a sense for how big these measurements turn out to be.

So for now, let's save this file and refresh the page.

And now we have a button that is 50 pixels tall,

but it actually looks like it's a little too tall.

So I'm going to change the heights to something like 30 pixels,

and I'm going to refresh the page again,

and I actually want it to be a little bit taller,

so I'm going to change it to maybe 36. I'm going to

refresh and I think that looks pretty good to me.

So you see that in css.

We do a lot of trial and error to get our measurements right

Now let's keep working step by step to get to our design. Next,

we're going to adjust the width.

So let's change this to something like a hundred pixels.

Let's see how that looks. I'm going to save it refresh,

and I think it looks a little bit too small,

so I'm going to increase it just a little bit. 1 0 5

and refresh. Okay, I think that looks good enough for me.

Next we're going to change the background color because currently our red is not

the same as our design.

So VS code has a really nice feature which is a color picker.

So if we hover over this color box here,

it gives us access to a color picker that we can pick another color with.

So I'm going to pick something that's a little closer to what I see at the

bottom, and don't worry, it doesn't have to be perfect.

I'm going to pick something like 200 0 0.

I'm going to save this and refresh. Okay,

so I think that looks close enough.

So you might be wondering what this value means.

We went from a color of red to RGB

200 0 0.

So this RGB value is another way of measuring color.

It's a more precise way of measuring color than just using a word like red or

white.

So the way that RGB works is that pretty much every color can be created using a

combination of red, green, and blue.

So that's what this syntax represents.

The R represents how much red we have in this color.

G represents how much green and B represents how much blue.

And these three numbers represent how much red we have, how much green,

and how much blue. The minimum value is zero and the maximum value is

255.

So if we removed all the red and green and we just have maximum blue

and we save, that's going to get us a blue color.

On the other hand, if we have all green color and we get rid of the blue,

we're going to have a green color. So this is basically how RGB works.

It's a combination of red, green, and blue to create any color that we want.

Now, don't worry too much about knowing what an RGB value looks like.

For example, if you have a random value like this, if you gave this to me,

I wouldn't even know what this color was.

Usually I just use the color picker to pick the color that I want and then it

will give me the RGB value that I need.

The only RGB values I suggest you remember are if we set

all the colors to the maximum value. So 2 55, 2 55,

and 2 55, this creates white.

So we save it and refresh that creates white.

If we set all of these three to zero,

that creates black and we refresh, that creates a black color.

So now let's go back to what we had before,

which I think was 200 0 0, and we'll save and refresh.

And the next thing we're going to change is here.

We might not be able to see it, but if we zoom in here,

this button has rounded corners while our button has pointy corners.

So to make rounded corners,

the CSS property for doing that is border

dash radius, and the border radius takes a pixel measurement.

The higher the pixels, the more round the corners will be. So for now,

let's try colon two pixels and save.

Now if we refresh the page,

our button now has rounded corners just like our design.

So I'm going to zoom back out and zoom back out.

So the last thing I'm going to change is if we hover over this button,

you'll notice that our mouse turns into this sort of hand.

This hand is called a pointer.

So we're going to change the cursor, the mouse.

This thing that you point around is usually called the cursor,

and we're going to change the cursor to a pointer.

Let's save and refresh.

And that's how you get this hand whenever your mouse is over this button.

So that's basically how we go from a basic HTML button to something that

looks more professional. We create the button with html,

and then we set the styles one by one. Now you might be wondering,

how do I know all of these CSS properties?

How are you supposed to memorize all of these?

So usually when I don't know the CSS property for something, for example,

if I want to create rounded corners,

I would go to Google and search something like CSS and what I

want to do, so let's say I want round corners,

and usually the first few links give some really good suggestions

on what the property is. So here,

right away we have the border radius property in the first link and it gives

us some sample code that we can use.

So that's how I discover all of the CSS properties.

I look at a design and I ask myself, okay,

what do I need to achieve this design? And then I search for it in Google.

So don't worry. As you use CSS more and more,

you're going to have to Google things that you don't know and you're just get

used to the process of finding answers by searching for them.

But for the purposes of this course,

I'm going to give you a lot of these CSS properties so that you can get some

good practice with them.

The next step we're going to do is to copy this join button.

So let's create a new button on our page with html,

and this is going to be the join button.

So we're going to put the text join inside this button,

let's save it and refresh. And unfortunately,

it looks like our join button looks like the subscribe button,

and that's because in our C s s,

this word button means that all of these styles are targeted

to all buttons on the page. So how do we get these styles to

only target the subscribe button?

So we're going to learn a new HTML attribute that we can use for this.

So remember in the previous lesson we learned that attributes modify the

behavior of elements. In this lesson,

we're going to learn a very useful attribute that is used a lot in css.

We're going to go to the opening tag again,

and we're going to add a new attribute called the class attribute.

So we're going to type class equals quotes. Quotes.

So the class attribute basically lets us label HTML elements.

For example, let's label this button the subscribe button.

And also my code is getting a little long for this line,

so I'm going to put the text on a new line to make it easier to read.

So remember, according to HTML syntax, these extra spaces don't matter.

They're ignored. So now that we set the class attribute,

we've essentially set a label to this button and we can target this label in

our css. So to target a class in css,

we can start with a dot, and then we're going to type out the class name.

So we're going to type out subscribe dash button.

So according to CSS syntax, if we start this code with a dot,

that means we're going to target a class name instead of an element name like

button.

So here we're going to start targeting just any element that has the class

subscribe button.

So if we save and refresh now you'll see that all of these

styles only apply to elements that have the class subscribe,

and our join button does not have any of these styles. Now,

multiple elements can have these same class. So for example,

if I set the class of the join button to subscribe dash button,

all these styles will be applied to any element with the subscribe button class.

That's what this dot means.

And that means these are going to be applied to this and this.

So if we save and refresh,

now the join button has these styles again because it has a class of subscribe

button. But for our purposes,

we actually want this to have a different set of styles.

So let's give a different class to the join button.

We're going to give the class join,

and I'm also going to reformat my code a little to make it easier to read.

So let's save and refresh.

And now we're back to where we can start modifying our join button.

Now let's start styling our join button to match our design. So remember,

the general strategy is to create the element with HTML like this and

then style it one by one until you match your design.

So first we're going to target the class. That's what this dot means.

We're going to target the class join dash button. Okay,

so let's set the background dash color to white.

Let's save it and refresh. And next,

let's deal with the border.

So our border is a little bit gray.

We can set it to maybe border dash color to

blue, and let's see how that looks. Let's save it and refresh.

Okay, so it looks a little darker than what we have in our design.

Let's go into our color picker and pick a more accurate color.

So I'm just going to do this by eye. Don't worry if it's not totally accurate.

We're just trying to get something that's close enough.

I'm going to go over here and I'm going to pick something like

maybe something like this. Let's save it refresh,

and that's a little bit too dark.

So I'm going to pick something a little bit lighter,

save it and refresh. Okay,

I think that's pretty good. But we also noticed that our border's a little

weird. So on the top it looks like it's a darker, it's a lighter shade of blue,

and at the bottom it's kind of a darker shade of blue. So to fix that,

we're going to set the border style to be

a solid color.

Let's save this and refresh.

And now we get a solid color all around.

The next thing we can change is our border looks a little bit thick compared to

the design, so we're going to change the border dash width.

So you'll see that a lot of these styles are pretty self-explanatory.

So we're going to set the border width to let's say one pixel.

Let's save it and refresh. Okay, so that looks pretty good.

Next we're going to set the tex color.

So we're going to set the tex color to blue and have it the same as our border.

So remember, the property to set Tex color is called color colon,

and we're going to copy this color down here,

save it and refresh. Okay, so that looks,

it's a little light, but I think it's okay.

Now we're going to set the height and the width.

So let's set the height to be something like 36 pixels to

match our subscribe button

refresh. Okay, and now we're going to set the width.

So let's try, I don't know, 60 pixels.

Let's see how that looks. Save and refresh. Okay,

I'm going to set it to maybe 62.

Okay, let's save and refresh. And again,

we're going to set some rounded corners.

So that is border dash radius,

two pixels. We're going to save it and refresh.

And now we're almost there to matching this design.

The last one we're going to set is cursor pointer to get that nice hand

pointer when we're hovering over the button.

So refresh now when we're hovering over the join button,

we have this nice pointer icon.

So another thing we notice is that there's a lot of space between these two

buttons and there's not a lot of space between ours.

So in CSS space is called margin. So to add space,

we're going to add some margin. So let's go to the subscribe button styles.

And we're going to add some margin dash, right?

So we're going to add some margin or some space to the right of this button.

And we're going to set this space to maybe eight pixels.

Let's see how that looks. Save and refresh,

and that looks pretty good to me. So now we're done with the join button.

Lastly, we're going to create this tweet button. Let's go back into our code.

And remember, our general technique is to number one,

create the element with html, and then number two,

style it with CSS one by one.

So we're going to create a button with a text

tweet. I'm going to move my editor a little bit to the right here so we can see

it. I'll move this here as well.

And let's refresh your page.

So now this button has the same style as a join button because it has a join

button class, and that's being targeted up here.

So instead of the join button,

we're going to give a class or a label of tweet button.

Now save and refresh. And now we're back to the default styles.

So in our css, we're going to write some code. We're going to target the class.

So we start with a dot. To target a class,

we're going to target the tweet button class.

So just like our other buttons,

we're going to adjust the style of this button one by one until we match our

design. So let's start off with the background dash color.

That set us to blue to start off with.

Now I'm going to try my best to match the Twitter blue that we have here.

So I'm going to pick something like this,

and I think that looks pretty good.

Save it and refresh. Okay,

we'll leave it like that for now. We might adjust it later.

Let's change the color now to white.

So that'll change the text color. Okay,

let's get rid of the border

refresh and save.

Let's give it a height of 36

pixels to match our other buttons.

And the color's a little bit off, so I'm going to adjust it just a bit.

Maybe it should be a little more like this.

Save it refresh. Okay, I'm pretty happy with this.

Now we're going to adjust the width to maybe

105. Let's see how that looks.

Okay, that's a little too much. Let's adjust it to 80.

Let's adjust it to 70. So as you can see,

there's a lot of trial and error when we're working with c s s. Now,

to get this rounded effect, we can set a border radius.

Let's start with two pixels. If we refresh, we get rounded corners.

If we start increasing the pixels for the border radius, let's save and refresh.

It starts getting rounder and rounder.

So the trick to getting these round buttons is we have to set the border radius

to half the height or the width, whichever is lower. So in this case,

the height is 36. If we set the borderer radius to half of that, which is 18,

save and refresh. That's how we get this rounded color.

The last thing we're going to do is to bold the text in here.

So in our design, this tweet text here is very bold,

so we're going to make our font bold as well. So do that.

We're going to set this property called font dash. Wait,

I'm going to set it to bold save and refresh.

Okay, looks pretty good.

It looks like this font is actually a little bigger than ours.

So let's actually set the font dash size,

set it to maybe 15, see how that looks,

save and refresh. Okay, I think that looks pretty close.

I'm going to change the width to maybe 74.

See how that looks? Okay, so I think this is good enough.

Currently we're just trying to copy things by eye. Later.

I'll show you a technique of how to copy these colors and measurements exactly,

but for now,

it's good enough to be able to achieve these designs just by looking at them.

So the last thing for this button is to add the cursor pointer.

Let's save it and refresh. So if we hover over this button,

we now get a nice pointer for our cursor. So the last thing I'm going to adjust

here is the spacing between these two buttons. Remember,

spacing and CSS is called margin.

So we're going to add to the join button. Actually,

let's add it to the tweet button just for practice. We're going to add spacing.

So we're going to add margin

to the left colon,

and let's make it eight pixels like we had it for the subscribe button.

Let's save it and refresh. And there we go.

So we took our basic buttons and we were able to copy these really nice

looking designs just by looking at them.

And the technique that we use for doing this is first we create the element with

html,

and then we style it with CSS one by one until it looks close enough to

our design.

So here are a bunch of exercises from other popular websites that you can try

out for yourself.

This is a good challenge for you to be able to look at a website by I and use

CSS to copy the styles that you see.

In this lesson, we're going to learn some intermediate CSS skills,

such as how to create hovers, transitions and shadows.

For most buttons you see on the internet, if we hover over them with our mouse,

they change their style slightly, some of them get darker,

some of them get lighter. We're going to learn how to do that in our code.

So we're going to use the same exercise as before. As a reminder,

you can find it at super simple.dev/exercises/buttons.

These buttons, when we hover over them, they actually change their style.

So this is going to help us practice learning about hovers. In addition,

you'll notice that if we hover in and out,

they change their style smoothly so we can also learn about transitions.

And lastly, this tweet button, if we hover over it,

it casts a little bit of a shadow, so that'll help us practice shadows.

But first, let's work on the hover styles for the subscriber button.

Let's go into our code and find the styles for the subscribe button,

which is everything here. And now to create a hover effect,

we're going to create a new block of css.

We're going to use a.to target a class.

So this time we're still targeting the subscribe dash button,

but this time we're going to add colon hover, open bracket,

close bracket.

So inside these are styles that will apply only when we hover over the button.

That's what this colon hover means. For example,

we can set the background dash color two green.

Now let's save our file and refresh the page.

And when we hover over this button, you'll notice that it's green.

So the way that this works is that if we are not hovering over,

all of these styles apply. So the background color is red.

If we are hovering over the button,

these styles now apply in addition to these styles.

So we're essentially adding extra styles when we hover.

So this colon hover is known as a pseudo class.

It basically adds extra styles in a certain situation. So in this case,

it's going to add extra styles when we hover.

Another example of a pseudo class is dot subscribe button

colon active.

So the active pseudo class activates when we click on the element.

So when we click on the button, we can set the background dash color to blue.

Let's save this and refresh. Now when we hover over,

we're going to apply these styles. So the background color is going to be green,

and then when we click, we're going to apply the active styles,

and then the background color is going to be blue.

So let's look at our design and see what kind of hover styles we have.

Let's refresh. So when we hover over our subscribe button,

it seems to turn a little bit more light, and if we click it,

it becomes even lighter.

So the way to make our button lighter is using a new property that I'm going to

introduce. So let's get rid of these for now. Let's save and refresh.

So we got rid of those pseudo classs styles.

We're going to set a CSS property called opacity.

So opacity tells us how SeeThrough and HTML element is.

It takes a value between zero and one.

A value of one means that this element is completely normal.

So if we save this and refresh, you can see that if we hover over it,

it's completely normal. And as we decrease the opacity,

let's decrease it to 0.7.

The elements start to fade.

So if we decrease it even more to 0.3

refresh, now it's even more faded.

So the opacity is used to fade out an element.

If we go from one to zero, the element's going to fade out.

So if we said it's a zero and refresh,

now it's basically completely transparent and see through.

If the opacity goes from zero to one,

that means the element's going to start to fade in.

So that's how opacity works for now. If we hover over it,

let's set the opacity to maybe 0.8.

So it's going to be a little bit see through, but not totally see through.

So let's refresh and hover over it. Okay,

let's look at our design. So that looks pretty close to what we have next,

let's set the active styles. So in our design, if we click on this,

it gets even lighter. So we're going to set an even lower opacity to make our

button fade out even more. When we click on it,

let's set it to something like 0.4

or 0.5. Let's say save it and refresh.

Now when we hover over it, now when we click,

the button gets lighter and we can compare that to our design,

and that looks pretty good to me.

Now we're going to work on the hover styles for our join button.

So if we look at our design, the colors for this drawing button sort of inverts.

So the background color and the text color, they reverse. So to do that,

we're going to go into our code, and again,

we're going to target the join button with a dot join

button.

And we're going to add a pseudo class called colon hover.

And now all the styles inside here will apply when we hover over this button.

So when we hover over it, we want to invert the colors.

So we want to set the background dash color to

our text color, which is this

copy paste.

And we also want to set the text color to our background color.

So we're going to switch them up. Let's copy paste here,

save it and refresh.

And now when we hover over our join button, that looks pretty good.

The next thing is when we click the join button,

you'll notice that it also fades out.

So we're going to add an active pseudo class to this button as well.

So target the join button class and add a pseudo class called

active.

So these styles will activate when we click this element.

So let's set the opacity to maybe 0.7,

maybe save it, refresh, click it. Okay,

so I think that looks close enough. So 0.7 looks pretty good.

So that is how we set hover styles and other pseudo classes with our CSS code.

Next, we're going to learn how to transition smoothly between these two styles.

So for example, if we go back into our project and we hover over this button,

you notice that the background color and the text color change smoothly,

but for our colors, it changes almost instantly.

So how do we make this transition? So to do that,

we're going to scroll up to our subscribe button. First,

we're going to add a property called transition.

So transition property takes two values.

The first one is what we want to transition. So in our case,

we want to transition the opacity smoothly.

So we want to smoothly fade out the button when we hover over it instead of

instantaneously. So let's transition the opacity.

And the second value is how long this transition will take.

For example, let's set it to one s, which is one second,

end it with a semicolon and save. Let's go back and refresh.

And now when we hover over our button,

you'll notice that the opacity changes smoothly.

Now it might be a little bit hard to see,

so let's change this to 0.1 to show you the effect

refresh.

So now you can see that the opacity is changing smoothly over one second.

So this is how you transition between different styles when you're hovering over

them. Now let's set it back to 0.8,

and we're going to change one second because it's a little bit too long.

So usually a good transition duration is something like

0.15 seconds. So it's pretty fast,

but it's not too fast and it's not too slow.

Let's go to our webpage and refresh. Now when we hover over it,

we get a nice smooth transition. It might be a little bit hard to tell,

but we do get a nice smooth transition

instead of what we had before, which transitioned immediately.

Let's work on the join button now.

So this one is a lot easier to see the difference.

Let's scroll down to the join button. And again,

we're going to add a transition. So we're going to add transition,

and we're going to give it two values,

what we want to transition and how long. First,

let's transition the background dash color and how long we're

going to transition for one second. As an example,

let's save our file and refresh. Now,

when we hover over the join button,

the background color changes smoothly over one second,

but you notice that the tax color changes immediately,

whereas the tax color here also kind of transitions.

So to make the tax color transition as well,

we need to add another property to transition.

So we can actually transition multiple properties.

We just have to separate it with a comma. So if we have a comma here,

we can add another property to transition. This time,

I'm going to transition the color, and we're also going to give it a duration,

which is one second. So how long it takes to transition this property,

save it, and refresh. Now, when we hover over this button,

it will transition both background color and the color smoothly over one

second. And that's basically how transitions work.

So sometimes you might be tempted to put this transition property into the

hover because you think that we want to transition when we hover,

so we have to put it here. Now, the problem with this is that if we refresh,

when we hover over the button, everything looks good.

But as soon as we hover out, these styles change immediately.

And that's because remember, these styles only apply when we're hovering.

So if we are hovering, then we have a transition.

But as soon as we take off the hover,

it's the same thing as having no transition at all.

So that's one common pitfall of the transition property.

So let's move it back here where it should be.

So just make sure that you put the transition always in sort of base CSS

style.

The last thing we're going to learn in this lesson is how to create shadows.

If we go to our project and we look at our design, I'm going to zoom in here.

When I hover over the tweet button, it creates a faint shadow under the button.

So we're going to learn how to create this. So let's zoom out for now.

We're going to go down to the tweet button styles,

and the shadow is just another CSS property.

So the property for a shadow is box dash shadow

colon. Now, box shadow actually takes four values.

So I'm going to set the values to zero for now,

and then we're going to change them one by one to see how they work.

Let's save this and refresh. And now we do have a shadow,

but we can't see it because it's right underneath the button.

So the first value here determines the horizontal position of the shadow.

For example, I can set it to 10 pixels, and if I save,

the shadow will appear 10 pixels to the right.

The second value sets the vertical position of the shadow. For example,

if I set it to 10 pixels in the second value,

it will push a 10 pixels down.

So now you can see we actually do have a shadow 10 pixels to the right and 10

pixels down from the button.

Now the third value here is the blur.

So if we set the blur to maybe 10 pixels,

save and refresh, now the shadow becomes blurred,

and the last valley is obviously the color.

So we can actually change it to whatever we want.

We can actually change it to something like red, save it refresh,

and we get a red shadow.

So this is basically how shadows work. We have a horizontal position,

a vertical position, blur and color. So don't worry,

the more that you work with shadows,

the more you'll get familiar with what these four values can do.

So let's try creating a more realistic shadow.

Usually shadows aren't red or any color.

They're usually kind of a darker shade of whatever they're covering.

So to create a color like that,

we're going to need a new way of measuring color. So let's get rid of this,

and we're going to use something called R G B A.

Rrg. B A is the same thing as rrgb,

except there's an A value.

So this a value essentially means the opacity of the color,

how SeeThrough it is.

We can set the RGB 2, 0, 0, 0.

That gets us to black as we learned.

And then the fourth value is our A value. If we set it to one and save,

this is going to be pure black. But as we decrease a value,

the color is going to get more and more faded out and more and more transparent.

So if we decrease it to 0.6,

save and refresh.

Now this color is getting more transparent and faded out.

So a pretty natural color for shadow is something pretty faint,

like 0.15. So for shadows,

we usually don't want it to be too noticeable.

Shadows are best when they're very subtle.

And now we kind of want to move the shadow a little bit closer to the button so

it looks a little more natural.

So let's actually move it maybe five pixels and five

pixels. Let's see how that looks. Save it and refresh. Okay,

I think that looks pretty good.

So that's how we create a natural looking shadow with the box shadow property.

We have four values, the horizontal position, vertical position, the blur,

and the color measured. With R G B A,

the value means opacity or how C through this color is.

The final step of this lesson is to only make this shadow appear when we hover

over the button. So for example, for here, if we hover over,

we can see the shadow. If we're not, the shadow's gone.

So this is another style of button that we can create.

So let's use what we learned so far. Remember,

we first use a.to target the class.

So we're going to target the tweet dash button class.

We're going to add a pseudo class here called hover,

and then we're going to move our shadow into the hover pseudo class.

Let's cut and paste in here.

So remember, the way this works is that let's refresh first.

If we are not hovering over the button, we get all of these styles.

If we are hovering over the button, we're going to get these styles,

these hover styles,

as well as all of these. So these styles get added on when we hover.

So now when we refresh and we hover over this button,

we're going to get a pretty subtle shadow. It's not perfect,

but I think it's close enough to what we want.

Now the last thing we're going to do is to transition the shadow.

So we can actually transition the shadow pretty easily by just adding the

transition property,

and we're going to tell it what we want to transition and how long.

So you want to transition the box dash shadow,

and let's transition it to something natural, like 0.15 seconds.

Now save and refresh. Now, when we hover over this button,

we get a nice transition on the shadow like this.

All right,

so the last thing we're going to do is I realize I forgot to change the

durations here.

So let's change it to 0.15 and 0.15.

Let's save it and refresh.

So now this looks something like what we have in our designs.

So we just learned some intermediate H C M L skills,

such as creating hover effects, other pseudo classes, transitions,

and shadows.

Here are some more exercises from famous websites that you can try to copy.

This time. We're also going to copy the hover styles.

As always, you can find these solutions and more exercises below the video.

In this lesson,

we're going to learn about one of the most useful tools for web development

called the Chrome Dev Tools,

and we're going to use the dev tools to get perfect colors for our buttons.

So first of all, what are the Chrome dev tools?

So I find that it's all easier to demonstrate it than to try to explain it.

So let's go to our website

and we're going to click in an empty area and we're going to click

inspect, and this will open up the dev tools.

So the cool thing about this is that we can now see all the HTML on our page.

If we draw down here, we can see all the buttons.

So this is a great way to visualize the HTML as well as the CSS on our page.

If I click into one of these buttons,

I can see all the CSS that is applied to this button. So what's

better is that we can open the dev tools in any website that we want,

so we can actually open it in super simple.dev

and you can see all the HTML that is on this website as well as all the

css.

So this is a really great tool where you can open it in any website that you

want and see the exact styles that they're using on that website.

The next feature I want to show you is this pointer icon in the top left.

So instead of trying to find these buttons in all of this html,

we can actually click this pointer icon and it will let us hover over any

element on the webpage and show it down here.

So if we hover over this tweet button and click it,

it will find the element for us in the html.

And now we can look at these styles here to see what kind of styles and more

importantly,

what kind of background color is set on this button so that we can get a perfect

background color. So one thing to note is that this background color is

actually another way of measuring color.

So currently we learned about rgb.

Now we have another way of measuring color, and this is called hex.

It's basically the same as rgb. The first two characters here,

one in D represent how much red. The second two represent how much green,

and the third two represent how much blue. So with a little bit of math,

we can convert from hex to rgb.

So I just google a hex to RGB calculator and I

find any calculator and then I use it to convert

the hex value.

So I'm going to copy this into the calculator and then convert it

and it will give me the RGB value, so it'll do that math for me.

So that's just another way of measuring color called hex.

The next feature I want to show you in the dev tools is this computer tab. So

this tab actually shows us all the final styles that are applied to this

element.

So we can actually scroll down here and we can find the background color in the

RGB value.

We can also find things like the height,

the final calculated height,

the final calculated width so that we can get the perfect size as well as the

perfect background color.

So let's actually just use the background color here,

and we're going to copy this and paste this into our code.

So we're going to get an exact color instead of trying to guess it like we were

before. So if I copy and paste here, save it,

and now refresh.

Now our button has the exact same color as what we have here.

So the same thing happens for the join button.

Let's click this icon here and hover over the join button to find it in the

html click. And now we can see all these styles,

all the final computed styles on the join button. So most importantly,

we can find the order color, which is this.

Let's go into,

let's copy it and put it into our CSS so that we can get a perfect color.

End it with a semicolon to follow the syntax rules.

Copy it there and copy it here.

Now we're going to save refresh,

and now our button color is going to match the design. Exactly.

So that's how you use the dev tools to get perfect color for our HTML

elements.

Now we're going to learn about the CSS box model,

which basically allows us to add space between our elements like this as well as

add space inside our element to make it bigger.

The first part of the box model is spacing on the outside of the element.

This is called margin. If we look at our code,

we already worked with margin before here.

We set the margin right to eight pixels.

That means that we added space on the outside of the button on the right of

eight pixels. If we change the margin right to 30 pixels for example,

and save and refresh. Now there's 30 pixels of space on the outside,

on the right side of the button. So we can add margin to all four directions,

top right, bottom and left.

Let's try adding margin to the left side of the button.

This time we're going to add margin left of 20 pixels,

save it and refresh.

And that adds space on the outside of the button on the left of 20 pixels.

So that's basically how margin works.

It lets us add spacing on the outside of the element.

The second part of the box model is spacing on the inside of the element.

So basically all these spacing in here around our text.

So currently if we look at our code,

we're setting the height and width of our buttons.

And this is not actually a good idea. I'll show you why.

I'm going to scroll down to the join button because it's a little easier to

see and I'm going to change the text to join my

channel, save it and refresh.

And you'll notice that the text is actually overflowing the button like this,

and that's because if we scroll up,

we're setting the height and the width.

That means that we're forcing the button to have a height of 36 pixels and a

width of 62 pixels. But here, notice that our content is too big.

So what we want to do is to remove these lines and save it

and refresh the page. And by default,

our button actually adjusts the size automatically based on the content.

So now instead of setting the height and the width,

we're going to achieve the same thing by adding spacing on the inside of the

button.

So the spacing on the inside of the button is called padding. Let's go into our

code and give it a try.

So we're going to add padding dash left of 30

pixels, save it and refresh.

And you can see that padding add spacing on the inside of the button.

And just like margin, we can set padding in all four directions.

So let's try adding padding dash top

to 20 pixels, save that and refresh.

And now you can see that we added padding on the top by 20 pixels.

So we can actually use the chrome dev tools that we learned earlier to visualize

the margin and padding of our elements.

Let's go into a blank area of our webpage and we're going to right click and

inspect and then click this top left icon and then click our

subscribe button.

So I'm going to drag this down and then we're going to go into the computed

tab.

So this section is basically the box model. We have our margin,

which is a space on the outside of the element.

You can see that highlighted in orange. We have the border,

which we learned earlier, and we have the padding,

which is the space on the inside of the element,

which you can see highlighted in green buttons by default,

have a padding of six pixels on the left and right and one pixel on top and

bottom.

So let's click this top left again and go to our drawing button and click this

button. In this example we have padding on the top of 20 pixels,

which is what we have in our code. We have padding on the left of 30 pixels,

also what we have in our code.

And then we have a default padding of six pixels on the right and one pixel at

the bottom. And for this button we have a border of one pixel wide,

which you can see here in our code.

So all of these combined make up the c s s box model.

This basically determines how much space and element takes up on the page and

how far it is away from other elements.

So now that we learned the box model,

we're going to use it to recreate our design here.

So currently if we look at our code, we're using height and width.

Let's replace this with the box model.

Let's get rid of this and save it and refresh.

And now our buttons back to what it was before.

And now we're going to add padding to this button so that it matches the design

at the bottom here.

So let's add some padding dash top of 10

pixels.

So we'll add spacing on the inside of the button at the top here of 10 pixels.

We're also going to add padding dash bottom of 10 pixels.

So let's save that and refresh. Okay,

so now we have space at the top and bottom, so that looks pretty close.

We're also going to add space on the inside on the left, right?

So we're going to add padding dash left of 16

pixels and padding on the right

of 16 pixels.

So let's save that and refresh.

And I think this looks close enough. So using padding,

we added spacing on the inside of our button.

And the good thing about this is that if we change the text like this and save

it and refresh, the button will resize with the text,

but it will keep the spacing on the inside.

So using padding is a better alternative to height and width.

So let's save that and refresh the page

and let's actually move these buttons back closer together.

So currently if we scroll up,

we have margin on the right of 30 pixels. So spacing on the

outside of the button on the right of 30 pixels,

we're going to change back to eight pixels so that it's closer like we have

in our design, save it and refresh. Okay,

so that looks pretty good.

Now one thing you'll notice is that our buttons are not aligned with each other.

So the join button is all the way at the top while our subscribe button is a

little bit below. So why is this happening? By default,

the browser tries to align our buttons based on the text.

So notice that the text is in one line like this.

So that's the default behavior of the browser.

This is because browsers in the beginning were mostly text-based.

Now to override this behavior and align everything to the top like we had

before,

we can go into our CSS and we're going to add a property called

vertical dash Align,

and we're going to set this to top. So instead of aligning the buttons based on

the text like this,

we're just going to align everything to the top If we save that and

refresh. Now the subscribe button is aligned to the top,

which is right there. Let's do the same thing for the tweak button.

We're going to scroll down and we're going to add

vertical dash align top here as well.

Save and refresh. And now everything's aligned properly again.

Now let's work on the join button.

I'm going to scroll down and remove this extra text here,

save it and refresh. And now we're going to go to our CSS for the join button.

So I'll scroll up to right here and we're going to adjust the padding.

So let's actually just borrow the padding from the subscribe button because they

look pretty similar.

So I'll scroll up here and copy these and just

move them down to the joint button right here.

Save that and refresh. Okay, so that looks pretty good,

except our joint button looks a little bit off.

It looks a little bit taller than our subscribe button,

and that's because the border actually adds a little bit of size to this button,

so it adds one pixel on the top and bottom.

That's why this button is taller than the subscribe button. So to compensate,

we're actually going to reduce the padding at the top and the bottom by one

pixel, say save it and refresh.

And now they're the same size. We have nine pixels of space on the inside,

plus the one pixel of the border width,

and that matches the 10 pixels of space on the inside of the subscribe button.

And I'll leave changing the tweet button up to you as an exercise.

So that is a CSS box model.

Every element can have spacing on the outside called margin space on the inside

called padding as well as a border.

And these properties determine how much space and element takes up on the page.

Here's some exercises of using the box model to get yourself more familiar with

this concept and these properties.

For most of the course, we've been working with buttons. In this lesson,

we're going to work with text and we're going to learn how to style text.

So just like our button lesson,

I've created an exercise that we can practice with text.

So we're going to go to super

simple.dev/exercises/text.

And now we have some texts from YouTube and Apple that we're going to learn how

to copy. So first of all,

let's create a new HTML file where we can focus on practicing text

styles.

So I'm going to go here and create a new file and let's just call this

text dot html.

And now we're going to open this file in our browser.

So open the folder that contains our code and right click

open with Google Chrome.

I'm actually going to put this up here. All right,

so now we're ready to begin.

If you've ever written a text document before using something like Google Docs

or Microsoft Word, you've probably seen something like this.

This is a toolbar that allows us to change the style of our text.

We can change the font, the text size, we can make it bold, we can center it,

et cetera. In css, we have a style for each of these things.

Let's go to our code and we're going to first start by creating some text on our

page.

So let's first create a paragraph and then insider paragraph.

Let's start with the text here.

So I'm going to copy and paste this into our paragraph,

and I'm just going to reorganize the code a little bit and save.

Remember that in H T M L, these extra spaces and new lines don't matter.

Now refresh the page and we have our first paragraph that we can practice with.

Next, let's create a style element so we can write some CSS code.

Now we'll set a class on this paragraph so that we can target it in CSS

class equals video dash title because

this is a video title that I copied from YouTube.

So let's save it and refresh.

And now we can start targeting this paragraph in our css.

So remember, we're going to start with a.to target a class,

and we're going to target video dash title.

So the first thing we're going to change is the font to change the

font. The CSS property is font dash family.

So websites by default use the font called Times New Roman.

We're going to change the font to a font called aerial,

save it and refresh. And now you can see we changed the font.

Let's go to the next one.

So this is the font size and we can change the font size using the property

font dash size,

and let's change it to something like 30 pixels,

save it and refresh. And now we have a bigger font.

The next example is, let's make it bold.

We're going to go here and we're going to set the font dash weight

to be bold,

save it and refresh. And now we have bold font.

So as you can see, CSS has properties for doing all of these things,

and for most of these properties it's pretty easy to Google them. For example,

let's Google for how to make a font italic.

So we'll go to Google and we just need to search something like css,

text italic. And now in the first result,

we're going to go in here, and if you scroll down,

you can see this CSS font style italic.

So I'm going to copy this and paste it in my code,

save it and refresh. And now we have italic text.

The last one I'm going to show you for now is how to center this text because in

our exercise we have an exercise where the text is centered to center

text. We're going to go to our code and we're going to type text dash a

line.

So this is the property for centering text or putting it to the left or to the

right. Now we're going to give a value of center,

save it and refresh, and that's how we center our text.

So that was pretty easy right now let's go ahead and try to copy this style in

our exercise. So if you remember,

the general strategy for creating anything that we see is first create the

element with HTML and then style it with CSS one by one.

Let's go ahead and do that for this exercise.

So I'm just going to resize this back and we're going to start

by resetting all of these styles, save it and refresh.

First I'm going to start with the font family. So for this exercise,

I actually use the font family aerial just to make it easier for us. So we're

going to set the font dash family to

aerial, save it and refresh.

Next, I'm going to change the font weight.

So this font is bold and I want to make my font bold as well.

So I'm going to add font, dash weight, bold,

save it, and refresh. Next, let's change the font size.

So I'm going to change this font size to something bigger,

like maybe 20 pixels,

save it and refresh.

And it looks a little too big comparing to the design.

So let's tone it down just a little bit. Maybe 18 pixels,

save and refresh. Okay, so I think that looks close enough.

Next, you'll notice that this text sort of wraps around to a second line,

while ours doesn't.

The way to make this happen is we're going to set a width on this title. Now,

I know that in the previous section we said it's bad to set a width,

but here it's actually what we want because if we set a width,

we're going to force the text onto a second line. So let's go ahead and set a

width right now,

and I'll set it to something like 400 pixels. Let's see how that looks.

Save it and refresh. Okay, so it needs to be less than that.

Let's do 300 pixels, save and refresh. Okay,

so that looks right to me now.

And the final thing with the title is I notice there's more spacing between the

lines here than what we have.

So to adjust the spacing between lines,

the property is called line dash height.

So don't worry if it seems like we're learning a lot of new properties.

The point of this lesson is for us to go through some complicated examples

together,

which will prepare you for the exercises that you can practice on your own.

So for this line height, let's try something like 20 pixels,

save it and refresh. Okay,

so it looks like that didn't work. Let's change it to 26,

maybe save it and refresh. Okay,

maybe 24, save and refresh. Okay,

so I think that looks pretty close. Next, let's work on the second paragraph.

So we're going to create a new paragraph,

3.4 M views.

And now to create this dot,

we're going to create something called an HTML entity.

So an HTML entity lets us type out special characters, for example,

this dot and this check mark to get the H html entity. For this dot,

we're going to Google html entity

middle dot. And now if we scroll down,

this will give us some HTML code that we can copy into our code.

So I'm going to copy this and then paste it here.

And that's going to create a dot on our page.

So if I save it and refresh, that's what we get.

Now I'm going to type out the rest of the text in this paragraph.

Now save that and refresh.

So now remember the general process is we created the element with html.

Now we're going to style it one by one. First,

let's give this a class so we can target it.

Let's call this video dash stats.

And now in our S, we're going to style this text.

We're going to start with font, dash family, aerial,

save, and refresh. And then we're going to change the font size.

So it looks like our design is a little bit smaller than what we have.

Let's change the font size to maybe 14 pixels,

save and refresh, and I think that looks pretty close.

Next, let's change the color.

So let's set a color of maybe gray

and refresh. Okay, so that's a little too light.

So to get an exact color,

we can right click in a blank area of the webpage, click inspect,

and then we're going to inspect the styles of this element.

So the trick to doing that is we're going to click this top left icon,

hover over this element and click it.

And then we can find all its styles in the computer tab.

So if we scroll down, we can get the text color.

So let's copy this and save.

Let's refresh. And that looks pretty good compared to the design.

Next, let's adjust the spacing between these two paragraphs.

So remember from the previous lesson,

the spacing outside of an element is called the margin,

but if we look at our code, we didn't actually set any margin yet.

So why is there so much space between these two paragraphs?

And the reason is if we write,

click in an empty area of the webpage and click inspect,

And we click this icon And hover over this paragraph.

This paragraph already has margin at the top and bottom.

So if we click this,

go to computed as 14 pixels of margin at the top and 14 at the

bottom. And the same thing for this paragraph.

And the reason for this is because paragraphs by default come with margin at the

top and at the bottom.

So that's why there's all this spacing that we have here where we didn't set it

in the css.

So the general process is we're going to remove the default spacing,

and then we're going to set our own spacing. So let's go into our code,

and first we're going to remove the margin dash bottom

of the title, set that to zero,

and we're also going to remove the margin at the top of the

second paragraph and set it to zero,

save that and refresh.

And now there's no default spacing between these and they're really close

together. Next, we can set a more precise margin bottom.

So let's set it to maybe 20 pixels. Let's see how that looks.

Save it and refresh. Okay, so let's way too much space.

Let's tone it down to something like maybe five,

save and refresh. Okay,

so I think this looks pretty close to the design actually.

Let's move on to the next paragraph.

We're going to move all the way down and create a new paragraph element with

this text inside.

And now for this check mark, we're also going to use an HTML entity.

Now I know that you can actually copy this and put it into our code directly,

but some browsers might not support this,

so that's why we're using HTML entities.

We're going to go to Google and we're going to search HTML entity check

mark.

And I'm going to scroll down and grab the HTML entity here.

So here we actually have three. I'm just going to take the first one, copy,

paste, save it. Let's go back and refresh.

Okay, so that looks pretty good. Next, let's keep styling these one by one.

So I'm going to go a little bit faster here because it's basically the same

thing that we've been doing for the first two.

It's called this one video author, and then we'll style it up here.

So we'll set the font family to your aerial, like the rest of the paragraphs.

Going to set the color to the same as this paragraph,

it's a copy and paste.

Okay, that looks pretty good. Oh yeah,

we have to set the font size looks a little too big right now.

Set the font size to 14 pixels. Next we're going to

reset the default spacing here.

So we're going to set the margin dash bottom and remove it by setting it

to zero, and also remove the margin top

and set it to zero, save and refresh.

And now we're going to set a more precise margin.

So let's try maybe 30 pixels, see how that looks.

Okay, that's way too much. Maybe 20 pixels. Okay,

I think that looks about right. Then we're going to do the third paragraph.

Let's go down here,

create the element and then style of it with css.

I'm just going to copy and paste this in here,

save and refresh.

First, let's give a class to the text so that we can target it.

Let's call this video dash description.

Go up here, video dash description.

We want a font family of aerial,

a font size

of 14 pixels and the same color,

and we save it and refresh. Okay, that looks pretty good.

And now we want to give it a width to make it wrap around like this.

So let's set the width to the same as the title, which is 300

with 300 pixels,

save and refresh. Okay,

so it looks like this IO is actually on a separate line.

Let's make it two 80,

save and refresh. All right, so that looks pretty good,

and I'm also going to make it two 80 up here just to make sure they're the same.

So the last thing I'm going to change is the height or the space between these

lines. To do that, we're going to use line height.

Let's scroll down and then add another property called line dash height.

And let's set this to 20 pixels. Let's see how that looks.

Save and refresh,

and let's set it to maybe 22 pixels,

save and refresh. Okay, so I'm pretty happy with this.

And lastly, we're going to modify the space between these two paragraphs. First,

we're going to reset the default margin.

Let's get rid of the margin bottom on the first one here and the margin top

on the second one. So margin dash top,

I'm going to get rid of it and set it to zero, save and refresh.

And then we're going to set a margin bottom, maybe the same thing as up here,

20 pixels, save and refresh.

All right, so that looks really good to me.

We just recreated a really nice looking style that you can find on youtube.com.

And the general process that we use is first we created the elements with html,

and then we style them with CSS one by one.

So before we move on to the next exercise,

I'm going to show you a way to clean up our code.

So if you notice all of our styles right now have a line called font,

family Aerial.

Now we can actually clean this up and remove the duplication by creating a new

style.

This time we're going to target all paragraphs on the page and we're going

to give all paragraphs, font, dash, family colon,

ariel, save.

So this style is going to apply to all paragraphs, which means all of these.

That means that we actually don't need this line in any of these

class styles anymore, so we can actually remove all of these.

Now if I save it and I refresh,

you can see that nothing changes because this is doing the same thing as the

code that we had before.

So you can also see from this example that an element can be targeted by two

sets of styles. For example, for this code here,

we're targeting all P elements on the page and all elements with a class of

video dash title. If we scroll down here,

here we have AP element that has a class of video dash title,

which means it's going to be targeted by both this set of styles and this set of

styles. So it's being targeted by multiple sets of styles.

Now another thing that we can clean up is remember how we reset the margins

for all of our paragraphs. Instead of doing it for each one individually,

we can actually put it all up here. So for example,

we can set the margin dash top to zero

and the margin dash bottom to zero zero,

we save it and we refresh.

It looks pretty much the same except we're now cleaning up all of the default

styles up here so that we don't have to do it in our code at the bottom. So we

don't need this anymore or this

or this. If we save that and refresh,

we still get the same thing because we've reset all of our styles in this set of

styles.

Now the last concept I want to show you before we move on to the next exercise

is the fact that in this set of styles,

we're setting the margin bottom to zero,

but here we're also setting the margin bottom to five pixels and the margin

bottom to 20 pixels. So how does that work?

We're setting it to zero here and to five and 20 here.

Which style does the element actually get?

And the answer is we're getting these style down here. So if we refresh,

you'll notice that there's still 20 pixels of space between these two

paragraphs.

Now you might think that it's because this line is at the top,

and then once we get to this line,

it overrides anything that comes before it. But if we actually move

this to the top

and we save and reload,

you'll see that we still have 20 pixels of margin bottom.

So why is this happening? This is something called CSS specificity.

If we have multiple lines setting the same property,

there's actually a priority that the browser follows. So in this situation,

this style has more priority than this style,

and to determine which one has more priority,

we have to look at this word before the brackets.

So this word tells us what these styles are targeting.

This is known as a selector.

This is another selector that targets a particular class.

Now the selector that is the most specific is going to have higher priority.

So this selector is actually more specific than paragraphs.

So what I mean by specific is that this targets all paragraphs on the page,

and this targets a specific class. So not all paragraphs are going

to have this class of video dash stats.

So that's why this is more specific.

It targets a smaller group of elements than this.

That's why this line has priority over this line.

So that's just an introduction to CSS specificity. For now,

just know that a class name like this has more priority

than an element name like this.

So I'm going to move this code back and we'll continue with the rest

of this exercise. Next,

we're going to copy this text from Apple.

So you can see that there is a background color and the text is centered.

And also if I hover over this part of the text,

we get a pointer on our mouse and we have an underlying

text. So let's see how we can do this.

First we'll create the element and then we'll style it one by one. So we'll go

down here and we're going to create a new paragraph

and let's copy this text into that paragraph.

Let's copy and paste. Whoops. Okay,

save it and refresh. Okay, so that looks good.

So usually if you have a greater then or less than symbol,

you want to create it with an HTML entity because the browser could confuse

these symbols with an HTML tag.

So I'm going to search for the HTML entity for

greater than. So this is the symbol that we want,

and I'm just going to copy and paste this into our code,

save it, and refresh. Next,

let's actually add some space at the bottom of this paragraph so that we can see

our new paragraph clearly.

So we're going to here and just add some

margin to the bottom because it's a little bit too cluttered right now.

All right, so that looks pretty good.

We're going to start by adding a class to our paragraph,

so we can target it in our CSS class equals maybe

apple dash text,

save it and refresh and

apple text. Okay,

and first I'm actually also going to give some spacing at the bottom

so it's easier for us to see our actual code.

So 50 pixels at the bottom, save and refresh,

and now it's a little easier to see what we're working with.

So next I'm going to change the font size.

One thing you'll notice is that the font family is already aerial.

If we scroll back up,

we have this set of styles that target all paragraph elements.

So it's already set our font family two aerial.

Let's scroll back down and let's adjust the font size.

So this one looks a little bit smaller,

so let's set it to maybe 14 pixels. Let's see how that looks.

Save it and refresh. Okay,

so I think that looks pretty similar to the design.

And now the next step is let's set a background color of red.

Now,

a trick for getting the background color is we're going to right click in an

empty area, inspect,

click this icon and click the element we want to copy styles for,

and then go to the computer tab and scroll down.

Now we have the background color.

I'm just going to copy this and paste it in here.

So background dash color,

we're going to paste that save and we refresh.

Okay, we next we're going to do the text color.

So let's set the text color to white color dash white

save and refresh. And now if we look at our design,

this text is actually centered on the page. So remember,

the property for centering text is text dash,

align center,

save and refresh. Okay,

and the last thing is there's some spacing at the top and the bottom here.

So here we actually want to add spacing inside our paragraph. And remember from

the previous lesson, spacing on the inside of an element is called padding.

We're going to add some padding to the top,

maybe 10 pixels and then padding to the bottom

and 10 pixels. Let's see how that looks. Save and refresh.

Okay, so I think we could add a little bit more padding,

so let's change it to maybe 18 pixels,

save and refresh. All right, so I think this looks close enough.

Now the last thing we're going to work on is this text here that becomes

underlined when we hover over it. First,

let's learn how to create underlying text.

We're going to practice our Googling skills and we're just going to search for

CSS text underlying. So keep it simple.

And then in the first link we have the text decoration property.

We scroll down, we have an overline line through and underline.

So let's grab this piece of code. I'm going to just copy it in here,

save and refresh. Now unfortunately,

this property actually affects the entire paragraph,

but we want it to only affect this part of the text. So how do we do that?

We're going to need to learn something called a text element.

So a text element is an element that is inside a line of text.

So let's do an example just to see how it works.

We're going to go to the bottom and we're going to create a new paragraph to

practice with. And let's actually just copy this text and put it in there,

save and refresh.

And now we're going to create some text elements on this paragraph.

So the first text element I'm going to show you is called the strong

element.

So now let's copy maybe this text and then put it in there

and save and refresh.

So the strong element here creates this bolded text that you see on the webpage.

So the thing to know about text elements is that they essentially exist inside a

line of text and then they modify that part of the text so they're not

modifying the whole thing.

Another text element we can create is the you element.

So this one creates some text that is underlined.

So if we move this text into here,

save it and refresh,

we now get an underlying text element.

So that is how we style specific parts of a line of text.

The final text element I want to show you is called the span.

So let's create a span element and we're going to put this

text inside. So cut and paste,

save it, and refresh. Okay,

so the span element is here, but you'll notice that nothing changed.

And that's because the span element is the most generic text element. It has

no styles.

So the span is really useful because we can actually give it a class

and we can style it ourselves and give it any style we want.

Now we could add the class attribute to these other text elements like the

strong and the U element,

but notice that these text elements come with a default style,

and that may not be what we want,

especially in this situation where we don't actually want a style until we hover

over it. So that's why we use the span text element.

It lets us modify a specific part of the text without affecting the whole thing,

and it's the most flexible and we can style it however we want.

So if we give it a class of span example

and then go to our css,

and then we target span example,

we can give it any styles that we want. For example,

we can set a color of red.

Now if we save this and refresh the span,

now turns this part of the text red.

The other cool thing is that everything we know about CSS still applies.

So we can target span example colon hover,

and these styles will only apply when we hover over the span.

So in this case, let's underline it because that's what we want.

So if we do text dash decoration and underline

just like up here, save it and refresh.

Now this span has a color of red here,

and when we hover over it, these style apply and it's going to get underlined.

Let's use what we learned here. To finish up our example,

we're going to first remove this line because we don't want to underline the

whole thing.

Let's refresh and we want to create a span so that we only target this part of

the text. Let's go back down.

I'm going to resize it a little bit just so that we can see.

Okay, so we're going to scroll down to here.

I'm going to wrap this in a span.

So just going to move this into here,

save refresh.

And now we're going to style this span.

So remember we're going to give it a class so that we can target it in our css.

Let's call this the shop link, save it,

and let's go here and we're going to style it now.

So shop dash link.

So remember the style for this is that the mouse turns into this pointer.

So to do that, we're going to use a property cursor, dash pointer,

save and refresh. So now when we hover over it, our mouse is a pointer.

And the last thing is that we want it to be underlined when we hover over it.

So let's create a hover style shop dash link,

and we're going to give this pseudo class colon hover,

and we're going to underline it with text decoration,

underline,

save it and refresh. And now when we hover over this,

it's going to turn our mouse into a pointer and it's going to underline it.

So we've achieved the exact same styles as art design.

So there's one last thing I'm going to show you in this lesson.

Let's go back into our code.

We're going to scroll all the way to the bottom and recall that in H T M L,

if we have multiple spaces like this, it will combine them all into one space.

So if I save this and refresh,

you'll see that only one space shows up here.

So I'm going to show you how to get over this problem. Basically,

instead of typing out multiple spaces in our html,

all we have to do is set a margin left on this text element.

So we're going to set a margin left on this element and it's going to add spaces

on the left. So as an example, let's scroll up

and we're going to add margin left

to our span element here, and let's do something like 12 pixels,

save it and refresh. And now we have spacing between our words.

So this is how we achieve multiple spaces between our words,

even though H T M L combines them.

So that is how we create really professional looking text like this and

like this, we first create the element with H T M L,

and then we style it one by one with css.

And if we want to style only just a part of the text,

we have to use a text element like a span.

In this lesson,

we're going to learn the proper structure of html and that's going to give us

access to all the features of html. So up until this point,

we've actually haven't been following that structure. For example,

if we look at our code, if we scroll down,

we can see that we're creating elements directly like this.

If we go to our website however, and we write click and

we look at our html,

we can see that we have some elements here called the HTML element,

the head element and the body element.

So this is a structure that we're actually supposed to have in our HTML file,

and because we don't have it, the browsers automatically creating this for us.

So this was fine in the previous lessons because we're just learning,

but it's actually best to have this structure in our code because we're actually

missing some useful features. So let's go ahead and learn what this structure

is and add it to our code.

So we're going to go back to all of our code and add in this structure.

Let's go back to our very first HTML file,

and at the top I'm going to add some spaces and we're going to learn what the

proper structure is.

Every HTML file is going to start with less than exclamation

doc type space, H T M L, greater that.

So you just have to type this line out exactly as I have it here.

This is not really an element,

it's just a special line that has a meaning to the browser.

This tells a browser to use a modern version of html. If we don't have this,

it sort of falls back to an older version that has less features.

The next part of these structure is to create an H T M L element.

So this says there's a webpage inside this element.

There's not much meaning to it,

we just have to have this at the top and the closing tag at the bottom of every

H T M L file. Next we're going to create this head element,

so head and closing tag,

and we're going to create the body element. So body

and closing tag.

So this is the proper structure of all of our HTML files and this is how we're

supposed to start and end our files.

So here you can see that we have an element inside. Another element,

this is called nesting. So not only can we have text inside an element,

we can have other elements inside elements.

We've actually already seen an example of this in the previous lesson.

We put a text element, like a span inside a paragraph,

and that allows us to have some text in the paragraph that was styled

differently. Here we have our second example of nesting.

We have a head and a body element inside an HTML element.

So this doesn't actually do anything visually unlike our previous example,

but it's part of the HTML syntax rules that we have to follow.

Every file has one and only one HTML element,

and this element represents the entire webpage.

And the HTML element is designed for nesting.

It's designed to contain one head element and one body element,

and then everything on our webpage is supposed to go either inside the head or

inside the body.

So both of these elements are also designed for nesting or to have elements

inside.

The body element here is supposed to contain all the elements that are visible

on the page. So let's actually open this website.

We're going to go into our folder that contains our code and we're going to

right click open with Chrome.

So on this website you can see that the paragraph is visible,

the button and the link is visible. So all of this is visible on the website,

so it should go into this body section.

Inside the head element are all the elements that are not visible on the page.

So here's an example of such an element.

We're going to create an element called title.

So the text inside the title here is going to change the text in the tab

here. So for example,

if I use the text first website,

that's going to show up in the tab. So if I save and refresh,

that's where the title element shows up.

But notice that this title element doesn't actually show up on the page and

that's why it belongs in the head section.

So the title is the first feature that we get from following this structure.

The second feature that we get that's really useful is the ability to

automatically reload our webpage whenever we change our code.

So you may have noticed that every time we change our code,

we have to go to our website and then refresh the page to see our new code.

Now we can actually avoid this by following this structure and then installing a

VS code extension.

So let's go to this extension area here and we're going to install the extension

live server. I'm going to install this,

and now we can use the live server to reload our page automatically.

Whenever our code changes to open this website in a live server,

we're going to right click and we're going to click open with

live server.

And now we've opened this website and it will automatically refresh whenever we

change our code. So if I change the code like this and I save now,

it automatically refreshes without having us to go back and forth.

So that's a really useful feature to speed up our development.

Now let's get some more practice and we're going to convert both of these HTML

files to use the proper structure First.

I'm going to actually just delete all the extra tabs here.

And now let's work on the buttons file.

Now the live server doesn't really work if we don't have that HTML structure in

our code. So let's add that structure first.

I'm going to go up here and we're going to create the structure.

So remember we start with a doc type

space, H T M L, and then we're going to create an H T M L element.

And then inside we're going to create a head

and we're going to create a body element.

And remember, the body contains everything that is visible on the page.

So if we scroll down,

these three buttons are visible on the page.

So we're going to you move these into the body element

And now they're in the right place. Now for this style element,

remember that we said the style element doesn't actually create anything visible

on the page, but it could change the style of other elements.

So this is a good example of something that should go in the head element

because it doesn't show up visibly on the page.

So we're going to copy all of this and put it into the head element.

We're going to go up and we're going to save this in here.

So now all of our CSS code is in the right place,

and now that we have the proper structure,

we can open this with our live server just to make sure everything looks good,

let's go here and add a title like we learned.

And this is going to change the text at the top of the tab.

So let's call this buttons practice, save it,

and you'll notice that it automatically reloads. Now we're going to learn

another feature that we get from following this structure.

If we look at our code,

we have all of our CSS code together along with our HTML code. Now,

this gets confusing because we have a lot of lines of code and we're mixing two

different languages. To solve this problem,

we can move all of our CSS into a different file.

So let's copy all of this and we're going to create a new file to just

contain our css.

We're going to go here and create a new file and let's call it

buttons dot css.

Make sure your file ends in dot CSS to tell the computer that this file contains

CSS code.

And now we're going to move our code into that file

and save and save here.

Now you'll notice that we lost all of our styles,

and that's because we now need to load this new CSS file into our

html. To do that,

we're going to learn a new element called the link element.

So the link is sort of a special element because it doesn't require a closing

tag like we've seen so far.

Elements like these are called void elements.

So if we search for Google and we search Void

elements html,

this will give us a list of elements that don't need a closing tag.

So these are the exceptions to the rule that everything has to have a closing

tag. So don't worry too much about memorizing all of these.

You'll get more used to it the more that you write H T M L.

And I'll introduce Void elements to you one by one.

So here we're going to learn our first void element,

which doesn't need a closing tag, but this element takes two attributes.

The first one is called r e L, which stands for relation.

So what kind of thing are we linking? In this case,

we're going to link in a style sheet,

and then we have to tell it another attribute,

which is H Ref. So this tells a link,

we what file we're going to link into this file.

So here we're going to link our CSS file into our html.

So we're going to link buttons css. Okay,

now let's go back to our page. You notice we don't have our styles,

and now when I save this, we get all of our styles back,

and that's because we're loading all the CSS code found in Buttons css,

which is all the code we had before into our html.

So this is another way to load CSS without having to write it all in our

HTML file. Now,

the big benefit of this is that each file contains less code and each file

contains one type of code. So in this file we only have H T M L code,

and in this file we only have c s s code.

So it makes the files smaller and more focused,

and that's going to help us develop easier. Now, before we move on,

I do want to talk about the HF attribute.

So the way that the computer finds this file is that it's going to search

right beside our HTML file.

So it's going to search right beside the file that this code is in.

So it's going to look for a file called Buttons Dos css,

it finds it and it loads it into our html.

But if this file was in a folder, let's create a new folder.

Let's call this styles.

Let's put the CSS file in our new folder.

And now you notice that these styles are gone,

and that's because this link can't find Buttons dot CSS anymore.

What it's trying to do is it's trying to look for a file called Buttons dot css

beside our html, and there's nothing there.

So to link a file that's inside a folder,

you first have to give the name of the folder that's beside the HTML file. In

this case it's Styles. Next,

we have to type a slash.

So this slash means we're going into the Styles folder,

and then inside we're going to find the buttons dot css.

So this is something called File Paths,

and this is basically how we locate different files within our HTML code.

So let's save this, and now we're able to successfully link our CSS file.

So that's a little bit about how file paths work.

We're going to need to use this later on in this course when we recreate

youtube.com. Now let's get some more practice,

and we're going to convert our final file into the proper HTML structure.

So let's create the structure first because we can't use Live Server just

yet. We're going to write a doc type space,

HTML at the top, and then we're going to have an HTML element.

And then inside we're going to have a head element,

and then we're going to have a body element.

Now everything that is visible is going to go inside the body.

So if we scroll down, all of our paragraphs are going to go inside the body,

cut and paste, save it,

and now anything that's not visible is going to go inside the head. So if we

scroll down, the style element is not visible on the page,

so it's going to go inside the head element, cut

and paste. All right,

so now we have a proper HTML structure.

We're going to open this with live server, move it to the left here,

everything looks good, and we're going to do some more practice.

We're going to set the title again just to get more repetition.

It's called this text Practice, save It.

And you'll notice that the title is set up here.

And we're going to move all of this into a CSS file.

So let's create a new file called text dot

css,

and we're going to move all of the CSS code into there.

So let's cut and paste it into here.

Next we're going to link the CSS file in this HTML file.

So let's create a link element. It needs two attributes,

R, e, L, and H ref.

So we're going to link a style sheet,

and the file is located right beside the HTML file.

So all we need to do is link text, css,

save it, and refresh.

And it's back to where we were again. Let's practice moving this into a folder.

Now we're unable to find text CSS beside our HTML file,

but there is a Styles folder.

So we're going to look inside the Styles folder.

Going to use a slash to go inside,

and we're going to link this text CSS file.

And that is how we use file paths to link CSS files.

The last feature we're going to look at that we get from this structure is the

ability to add a new fonts onto our website.

So websites have a set of fonts by default that we can use. For example,

one of them is called Aerial.

Another one that we've seen is called Times New Roman.

That's basically the font that we get on a fresh website. Now,

in addition to these default fonts,

we can actually load new fonts from the internet,

and we're going to learn how to do that within this structure.

So let's go to our webpage.

And Google actually provides a lot of really great free fonts that we can use.

So we're going to open a new tab,

and we're going to search for Google Fonts,

and we're going to go into this first link. Now,

this website might look a little different for you,

but the general process is the same. First,

we're going to search for a font that we like.

So a good font to use here is Robo,

and this is the font that we're going to use for our final project. We're going

to pick this font,

and then inside here we're going to pick the styles that we want.

So for example, I'm going to pick the regular style.

And I'm also going to pick the bold style here.

So I'm going to pick the bold style and then I'm going to go

to the basket of fonts that I selected,

and then Google is going to give me the code that I need to load these fonts.

All we need to do is copy this code exactly and then

put it in our head section of our html.

So we're going to put it in our structure in this head section.

And now we've loaded a new font that we can use on our website.

So now let's go back to our website and we're going to use this new font.

So remember that currently we set our fonts to aerial.

This time we loaded the font called reto, and that's what we're going to use.

So let's change aero here to Reto.

Now when I save the font is going to change.

And there you go.

It might not look that much different because Reto is very similar to aerial.

But if we inspect and we click on this element and

go to the computer tab,

we'll see that the font family has now been to Reto.

So this is how we can load a huge selection of fonts from Google onto

our webpage and use them on our website.

So those are the features that we get from following this HTML structure.

Every website that we create from now on will always have an HTML tag,

a head and a body and a doc type at the top.

Now we're ready to work on the final project of this course,

recreating youtube.com. Just like before,

I've created a page on my website that'll show us what the final project looks

like.

So first we're to close all of our browser tabs because we're going to start

over again,

and then we're going to open a new page and we're going to go to

super

simple.dev/exercises/youtube.

So on this page you can see what our final project will look like.

So we're going to learn how to recreate youtube.com that you see here.

So first, let's set up our project in our code editor.

So let's go into here and let's actually create a

folder that's going to contain all of our previous code.

So the final project is going to contain a lot of code,

so we don't want to get it confused with the previous lessons.

So let's call this intro dash two dash html

and we're going to put everything inside this folder.

We're going to put this in here and these HTML

files in here as well.

Next we're going to create a new HTML file for our final project.

So let's create a file called YouTube dot html,

and I actually put it inside this folder.

I'm going to take it out by dragging it down here.

So now we have an intro to html folder and our YouTube dot html

and we're ready to get started. First,

we're going to set up the proper structure of HTML that we learned in the

previous lesson.

So we're going to start off with a lesson exclamation doc type

and html,

and then we're going to create an HTML element that's going to contain our

entire webpage. And inside here we're going to have a head element

And we're also going to have a body element.

Now that we have the structure, we can open it with live server.

And now we have our blank page.

So this page is going to automatically reload when we change our code.

Now before we can work on the final project,

we need to learn two more HTML elements,

how to load images onto our website and how to create a search box.

So let's start with loading images first.

So I'm going to show you how you can download these thumbnails from my website.

We're going to right click in a blank area and inspect.

Now if we click this icon in the top left and hover over an

image and click it,

and you might need to drag this down to see the html,

we can find the image in the html, and here is the URL for the image.

So we can actually click this and it will open the image in a new tab

and we can control S to save it. So make sure we save this image

in the folder that contains all of our code. So that's this folder for me.

I'm going to save it. And now in my code editor I can see the image.

Next we're going to create an HTML element to load this onto our page.

So I'm going to go back to my page here,

and then we're going to go into the body and create the image element which

is less than img, greater than.

Now the image element is unique because it's another void element.

So we mentioned void elements briefly in the previous lesson.

It's an element that doesn't require a closing tag.

So this is one of those exceptions to the rule.

So the image element takes one attribute called src.

Now this attribute tells a computer which image to display on the website.

So for us,

that image is the one we downloaded called thumbnail one WebP.

So we're going to display thumbnail dash one dot WebP,

and when I save it, the image is now loaded onto our website.

So this source attribute works the same way as the

link attribute that we saw earlier.

It follows the rules of file paths to locate our file.

So just as a reminder, if we type thumbnail one dot WebP here,

it's going to look for a file named thumbnail one dot WebP right beside our HTML

file. It's going to find it and then load it onto our website.

But now we're actually going to create a folder because we have multiple

thumbnails and we want to organize them,

we're going to create a folder called thumbnails and we're going to drag this

into that folder. So now for this source attribute,

we don't have a file beside our HTML called thumbnail one WebP,

and then you see this error here.

So this means that there is an error loading an image.

Now to find it in the thumbnails file,

we're going to type thumbnails slash thumbnail one

WebP. So first it's going to look for a file or folder called thumbnails.

Beside the HTML file, it finds this one,

and then the slash here means to go inside the folder and then find

this file inside that folder, which is here.

So that's how we load images onto our page.

Now we're going to learn how to style our image elements.

So let's go into our head section here and create a style element.

Now before we do that,

I forgot to do something which is let's create a title for our page.

So we can call this youtube.com clone,

and if we save this, the title will show up in the tabs. All right,

so let's learn how to style our image. So as always,

we're going to give it a class attribute and let's just call this thumbnail.

And now we can target this class in our css.

So dot thumbnail.

Now all of the CSS properties that we learned so far apply to the image.

Some of them make sense and some of them don't.

So one property that obviously doesn't make sense is something like font dash

size. So if I save it,

you'll see nothing changes because there is no text inside this element.

It's an image. So even though this works, it doesn't really change anything.

Now a property that does make sense for an image is width.

So this was set the width of this image.

Let's make it smaller to match what we have here.

So let's make the width something like 300 pixels.

Now we save it and now the width of this image is 300 pixels.

So one thing you might notice is that when we set the width of an image,

the height also changes. So before we had this

notice that the image was a lot taller, but as soon as we set the width,

the height also adjusts. So that's one behavior of images that we should know.

When we set the width,

the height will also adjust so that the image has the same dimensions.

What I mean by same dimensions is that it keeps the same shape. So for example,

if I set the height as well,

this is going to cause the image to lose its shape or lose its dimensions.

Let's set the height to something like 600 pixels, save it,

and now you'll see that the image is 600 pixels tall,

but it's lost its shape and now it's become stretched.

So that behavior of an image sort of keeps us safe,

so it keeps the image looking nice. Now,

if we really wanted an image that was exactly 300 pixels

by 300 pixels, what can we do? So this image, as you can see,

is getting stretched out. So in addition to all the CSS properties

that we've learned so far,

the image element has its own properties that are specific to an image.

So one of these is called object fit.

So this determines what happens if this size doesn't match the images

dimensions or the images shape. So for example,

I can set a value of cover.

So this tells the image to cover this 300 by 300 area,

but it's also going to keep its shape.

So this area might not be big enough to show the whole image,

which may or may not be okay depending on what we want to do.

Now we can adjust which part of the image that we see using another property

called object dash position.

So currently we're looking at the center of the image.

We can set the object position to left to view the left side of the image,

or we can also set it to the right to view the right side of the image in the

case that the image doesn't fit in our area.

Another value we can give to object fit is contain.

So if we save this,

the entire image is going to shrink until it is contained in this 300 by

300 area. So I'm going to set a border so that we can see what this is doing.

I'm going to set a border of two pixels, Border width, two pixels

border style of solid order color of red.

So here the border shows us our 300 by 300 area and

contain makes the image shrink until it is contained in the area,

but that means that it might not be able to cover the entire area if it's not

the right shape. So in this case,

the object position can move the image to the top

or to the bottom.

So that's basically how images work. As you can see,

a lot of the CSS properties that we learned before like width and height and

border can be applied to the image element.

And the image element also has some of its own properties that determine how the

image is displayed. So for now,

let's create something that's kind of like our final website.

So I'm going to set the image with two 300,

and I'm not going to set a height so that the image doesn't stretch and we don't

have to do all this stuff and I can actually just remove all of this.

So the only thing I'm doing is telling the image to shrink down to a width of

300 and to shrink the height as well so that the image keeps its shape.

So we're going to stick with this for now and this is going to correspond to

this part of our final project,

and we're going to start learning how to build out the entire video preview.

The next element we're going to learn in this lesson is how to create search

boxes like the one you see up here.

So let's go back into our website and we'll learn the code for creating a search

box.

The HTML for creating a text box is less than

input greater than.

So the input element is a void element, just like the image element,

it doesn't require a closing tag.

So the input element has several attributes that we can give it.

One of them is called the type.

So we set the type equals text, it's going to give us a text box.

I'm going to save this,

and now in our HTML you can see we have a text box.

Another type that we can give to this input is called checkbox.

So if I save this, now we have a checkbox.

So for our purposes we're going to set the type to a text box because we want to

create the YouTube search box up here.

So you also notice that this text box has a word search in it,

and when I start typing, that search word is gone.

So this is sort of like a label for the user telling them what to put into this

text box. And this is known as a placeholder.

So if we go back to our website,

we're going to add a placeholder to our new text box. To do that,

we're just going to give the attribute placeholder

and let's set the placeholder as search. We save it.

Now we have a placeholder that disappears when we start typing.

So that's how we create what we see on YouTube. So for the text

box,

all of the CSS properties that we learned so far can be used on the text box.

So let's look at some examples. Let's add a class attribute first,

like always so that we can target it. Let's call it search dash bar.

And then inside our css,

we're going to target dot search bar class.

And then inside we can set our usual CSS properties. So for example,

in this case,

we can set a font dash size and let's add it to 20 pixels,

save it and reload. And now you can see that the font size has changed.

Another thing we can change is margin or the spacing.

So let's add some margin to the left

of 12 pixels, save it.

And now we have some spacing on the left.

So basically everything that we've learned so far about CSS properties we can

use on the search box. For now,

let's remove these example styles and we're going to style the search box to

look like our final project later in the scores.

In this lesson,

we're going to learn one of the most important CSS properties called the display

property, and we're going to use this to start building out our final project.

We're going to start off by taking a look at our final project and we're going

to start building out the text here.

So we're going to create paragraphs for these text.

So let's go into our code and we're going to create three paragraphs.

So here's one of them, and we can copy the text.

So copy and paste.

So here's another paragraph and we're going to copy this

and paste it in our code.

And here's a final paragraph

and we'll save. So here,

I'm actually going to use the H T M L entity again instead of this special

character. So to save us some time, I'm just going to type it out here.

Now I'm going to save this and go back to my webpage.

And now we have the text that we're going to use,

but you might notice something weird.

How come this text box is beside our image?

If we look at our paragraphs, they are on top of each other,

so one after another on each line.

How come text boxes and images appear on the same line?

So this is due to the display property in C S s and we're going to learn what

that is right now. In H T M L, there are three types of elements.

The first type of element is called a block element.

A block element takes up the entire line.

So a paragraph by default is a block element.

We can see that in our dev tools by right clicking in the browser and then

clicking inspect, And then clicking this icon in the top left

right here and then hovering over our paragraph.

So you can see that even though the text goes to here,

the paragraph extends to the end of the line because the paragraph by default

is a block element. Block elements take up the entire line.

So let's go into our code and I'm going to demonstrate another property of block

elements.

If we set a class on the paragraph and we style it,

so let's set a class of video dash title,

let's save it and we're going to style it and let's

it a width of 300 pixels,

save and refresh.

And now this paragraph is only 300 pixels,

so it's not stretching to the end of the line anymore.

Let's verify that using the dev tools by clicking this top left and then

hovering over.

So you see that the paragraph itself only takes a width of 300 like we set in

our css,

but it still takes up the entire line denoted by the orange part

on the right here. If we click on this paragraph and we go to the

computer tab, notice that there is no margin on the right side,

but we still have a ton of orange area on the right.

So this is how block elements work.

Regardless of how much space they actually take up,

they take up the entire line,

so they're forced to be on their own line like this paragraph and these two

paragraphs. So that's what a block element means.

The second type of element is an inline block element.

An inline block element only takes up as much space as it needs to and doesn't

take up the entire line.

An example of an inline block element is the image element and the input

element.

They only take up as much space as they need to and they don't take up the

entire line.

So another element could appear beside them like we see here. So that's the

inline block element.

The third type of basic HTML element is called the inline element.

Inline elements are basically just text elements.

They appear within a line of text. So if you remember,

we briefly introduce the element strong.

So this element appears within a line of text like

this.

So this element makes a part of the text bold and it appears within a line of

text. So those are the three basic types of HTML elements,

a block element, which takes up the entire line and inline block element,

which only takes up as much space as it needs to,

and an inline element which appears within a line of text.

Now the most interesting of these three are the block elements and the inline

block elements because they determine how these elements are displayed on the

page, whether beside each other or above and below. In addition,

we can use a CSS property called display to easily switch between block and

inline block. So let's see how that would work.

So first let's start by switching from block to inline block.

We're going to switch both of these paragraphs to inline block elements.

Let's go into our code and we're going to give this a class.

Let's call this video dash author and let's call this

video dash stats. And we're going to style these classes.

So we're going to style the video dash author as well as the

video stats,

and we're going to set both of these to display inline dash block

and this one as well display inline dash block.

I'm going to introduce a little bit of CSS syntax here.

If we have two sets of CSS styles that are the same,

we can actually use a different syntax by adding a comma here.

So this comma means that we're going to target both the video author class

and the video stats class with this set of styles.

So this is how we target multiple things in CSS with a comma.

So as you can see, these two elements now appear beside each other.

They're both inline block elements and only take up as much space as they need

to. If we click the top left in the DEF tools and hover over this,

you'll notice that this paragraph is now only taking up as much space as the

text and the same thing for this paragraph. So as you can see,

even though paragraphs by default are block elements,

we can change them very easily to inline block with the display property so that

we can put them beside each other.

Next we're going to try the opposite direction.

We're going to go from an inline block element to a block element,

and we're going to put these two on separate lines. So let's go into our code

and we're going to style the thumbnail class.

So I'm going to scroll up here and I'm going to convert this to display

block, and now it will turn the image into a display block,

and this will cause the image to take up the entire line pushing the text box

down to the next line. If I save it,

now you can see that this image is taking up the entire line.

We're going to verify this by clicking the top left and then hovering over this

image. So using this property,

we can control whether an element appears on the same line or on a different

line, and that's what we're going to do to copy this design.

The search bar is at the top.

We have an image and then three paragraphs each on a different line.

So we're going to use a display property to achieve this.

Let's go into our code.

And first let's put the search box at the top,

Save it. And since our image is already display block,

it's going to take up the entire line,

so it's forced to take up a line below the search box.

So I think this is pretty good as long as these search box is up there,

then we're good to go. Next,

we're going to turn these back into display block because we want these on

separate lines like our design here. So to do that,

we're going to go into our code and we could change this to display block,

but remember that paragraphs by default are display block,

so we can just get rid of this code, save it,

and now our elements are appearing at least in the same structure as the design

from top to bottom. And each element is taking up its own line.

So that is the display property.

It allows us to control how an element is displayed,

whether they're a block element and take up the whole line or they're an inline

block element and only take up as much space as they need to.

In this lesson,

we're going to learn about the most important HTML element called the diviv

element. For example, here's twitter.com.

If you look at the HTML that Twitter uses,

you can see that they're using lots and lots of divs. Here's another example,

Instagram. If we look at Instagram's html,

we can also see that they're using lots and lots of divs.

So what exactly is a diviv and why is it used so much?

So the diviv element stands for division,

but an easy way to understand this is that the diviv is just a box.

We're going to go into our code and look at an example.

So below our paragraphs, let's create a diviv element,

and inside we're going to have some text. This is a diviv,

save it.

And now we have our first diviv element on the page to show you that the diviv

is just a box. We're going to right click and inspect,

And then we're going to click this top left icon and hover over the diviv.

So as you can see, we created a box around our text.

You'll notice that this box stretches to the end, and that's because the diviv,

like the paragraph by default is a block element,

so it takes up the entire line, but like we learned in the previous lesson,

we can easily change this to an inline block using the display property.

So let's go ahead and do that and it'll be more clear that this is really a box.

So we're going to set a class here.

We're going to call this diviv dash example,

and now we're going to style it

and change the display to inline block

So that it doesn't take up the entire line anymore, save it.

And now if we go to our webpage, click this icon and hover over.

You can clearly see that the diviv just creates a box around our content.

In this case, our content is some text. So that's basically what a diiv is.

Now the second question is why is a diiv so useful?

The key feature of a diiv is that it can contain any other inside.

So right now we only have some text inside the diviv,

but we can actually put paragraphs, we can put images,

we can put any elements inside divs as well as other divs.

Divs are meant to be containers.

And if we look at the YouTube design that we have in our project,

we use containers everywhere. So here's a container,

here's another container, and here's another container.

These containers allow us to group all of these elements together so that we can

create a layout that looks like this. Here's another example from Twitter.

Here's a container, here's another container, and here's another container.

In order to build complex real world website,

we need containers to group our elements together and lay them out on the page.

And the diviv is the perfect solution for this container problem,

and that's why it's used so much.

Let's go back to our website and we're going to practice using our diviv as a

container.

So we're going to create a container just like our final project for this entire

video preview here. So that means we're going to put all of these elements,

this image, and all three paragraphs inside our diviv. Let's see how that works.

So I'm going to get rid of this text first and then I'm going to change this div

to a class of video dash preview

because this is going to contain all these elements that are part of a video

preview.

And then I'm going to move the image and the three paragraphs

into the diviv.

Now save,

and you might not notice any difference because the diviv is simply just drawing

a box around the content inside,

but we can right click and inspect and we can see the

diviv in our H T M L here.

And inside the diviv we have our image and our paragraphs.

The diviv is just creating a box around all this content.

So now I'll show you why containers are so useful.

We're going to go into our code and we're going to change the width of our diviv

element here. So we're going to go up here and we can remove this.

Let's style the video preview class,

and we're going to set a width of 300 pixels.

Let's see how that looks.

So the page doesn't look any different,

but if we click the icon in the top left and then hover over our paragraphs,

we'll notice something interesting. This paragraph is a block element,

so it's supposed to take up the entire line, but in this case,

because this paragraph is inside a diviv,

it takes up the entire line in diviv.

So the way that block elements actually work is that they take up the entire

line in their container rather than on the page.

So that's really useful because if we look at our final project,

so for these paragraphs, we want them to appear on separate lines like this.

So we do want them to take up their own line,

but we don't necessarily want them to take up the line on the entire page

because we have some stuff on the right side here. So to solve this problem,

we put the paragraphs inside a container so that they take up their own line

in the container and not in the page. And that's how we can create a layout like

this. Let's go back to our website.

If we hover over our diviv now,

so this blue box on the left is our container.

It groups all the elements together and keeps it within that blue area that you

see. Now,

a really cool thing about this is that notice that the blue box doesn't actually

take up the entire page.

So we can actually have a second box beside it on the right.

So we can add another blue box on the right containing another video preview.

So now we're going to do that, but first of all,

a diviv by default is a block element.

So notice on the right side it's all orange.

That's because this diviv is taking up the entire line. In this case,

we don't want it to take up the entire line anymore.

That's why we're going to convert it into an inline block element.

So let's go into our code.

We're going to go into the video preview and we're going to type display

inline block. Let's save it.

And now we can see that our diviv is a display inline block and it's actually

appearing beside our search bar because this is also an inline block.

So they're both only taking up as much space as they need to,

and now they can appear beside each other. However,

we do want the search box to be at the top in its own line.

So we're going to practice using the display property. Again,

we're going to set the search bar to display block

so that it takes up the entire line and everything else is forced below it,

save it and refresh. And now if we hover over this input element,

we can see that we forced it to take up the entire line. Next,

we're going to create another video preview beside this one because this is

inline block.

Now we can put another diviv here. So I'm just going to simplify this

by making a copy of our current code.

So I'm just going to copy and paste,

and now we have two video previews, save it.

And there we go. We now have two video previews beside each other.

So they are two containers right beside each other.

And remember in our css,

we set the width of these containers to 300 pixels.

So that's the amount of space that they take.

And we set their display to inline block so they don't take up the entire line

and they can appear beside each other.

And now we're on our way to creating a layout that looks like this. In fact,

let's actually replace the second video preview here with this

content. So to do that,

we're going to download the thumbnail and then change the text.

So let's right click and inspect.

I'm going to click this top left and then click this image.

And now I can download the thumbnail by going to this url.

And then clicking down here,

I'm going to control S to save the thumbnail.

So I'm going to save it in the folder that contains my code in the

thumbnails folder along with our previous thumbnail. So save it here,

and I should see it in my code editor right there.

Next, we're going to swap out the thumbnails. So instead of thumbnail one,

we're going to set thumbnail two and we're going to change the text.

So I'm going to change this text here to be my title.

And I noticed we're still using the strong element,

which we can now delete because it was just for an example.

And I'm also going to change the channel name here

and the video stats, which is 19,000,004 years

and for years ago. So now if I say

this, we have two different video previews, but now we have a problem,

you'll notice that these two aren't aligned with each other,

and that's because this container is actually a little bit taller than this one.

This piece of text here wraps around to a second line.

While this one does not, however, to make it look better,

we want to align these at the top.

So we learned this way back in one of the earlier lessons,

and we're going to review how to do that. We're going to go into our code

And we just have to set this property vertical align,

and we're going to set it to top so that these elements align at the top.

I'm going to save it. And now that looks pretty good.

We now have two different video previews and they are aligned with each other.

The last thing we'll do is to add some space between them. So remember,

the space outside of an element is called margin,

and we're going to add margin to this entire container right now.

So we'll go into our code. And in the video preview styles,

we're going to add margin dash, right?

And let's set it to something like 15 pixels, save it.

And now we add in margin on the right.

And now the interesting thing about this is if we right click and inspect,

and then in our HTML we find our diviv, which is here,

you'll see that the margin is applied on the entire diviv.

So that's how the div element works.

It's a container that groups other elements together so that we can create

complex layouts like this and eventually our YouTube project.

All right, so this is probably the most important lesson of this course.

We're going to learn a technique called the nested layouts technique,

and this is going to get us to a professional level with HTML and css.

So what is the nested layouts technique?

The basic idea is that there are two types of layouts.

The first one is a vertical layout, which looks like this,

where items are on top of each other. And then the second one is a horizontal

layout, which looks like this where items are beside each other.

And by using a combination of vertical and horizontal layouts,

we can create almost anything that we see on a website. So for example,

let's take the YouTube video preview that we've been working on.

We can break this down by using a vertical layout.

And then inside this vertical layout, we're going to have a horizontal layout.

And then inside this horizontal layout, we're going to have a vertical layout.

So as you can see, we have layouts inside layouts, inside layouts,

and that's why it's called the nested layouts technique. And using this,

we can pretty much break down almost everything that we see on a professional

website into a series of layouts and then recreate them using our code.

So now we're going to go through together a way that we can practice using the

nested layouts technique to break down a design. We're going to go to our final

project. If you close it,

you can go to super simple.dev/exercises/youtube.

And what we're going to do is we're going to take a screenshot of one of these

designs,

and then we're going to use an image editing software to draw out the layout.

So first, let's create a screenshot on Windows.

You can use an app called SNP on Mac.

We're going to type command shift n four to create a screenshot.

So let's take a screenshot of this

and then we're going to upload this into an image editing software. Now,

feel free to use anything that you're comfortable with,

but if you don't know what to use, we can go to a new tab.

And we're going to search for Google drawings,

And we're going to use this to practice the nested layouts technique.

So once we have this open, we're going to upload our image.

I'm going to go to my computer and upload the screenshot.

And now we're just going to draw some rectangles to represent our layout.

So we're going to go up here to shapes and we're going to create a rectangle.

And first we're going to create a vertical layout one and two.

So I'm just going to draw a rectangle here.

Let's change the background to transparent so we can see what's underneath.

And I'll make the border a little more thick and change it to red

so it's easier to see.

And now I'm going to copy this and paste it to create a

duplicate. And I'm just going to move it down here

and resize the rectangle like this. All right,

so just like that we created a vertical layout for now.

Don't worry about the video time here.

We're going to recreate this later in the course using another feature of css.

And now looking at our design, we have a horizontal layout one and two.

So to create a horizontal layout,

we're going to draw it out again using rectangles.

So let's go in here and we're going to create another rectangle,

and we're going to draw out the horizontal layout like this.

So here's one,

change the background to your transparent and make it bold.

And I'm going to use the blue color to represent a horizontal layout.

Now I'm going to copy this and paste it here

and resize it a little bit

like that. And now we have our horizontal layout.

And finally inside here we're going to have a vertical layout like this.

So again, we're just going to keep drawing rectangles.

I'm going to copy this and paste it and move it

down here and resize it a little bit so that we can see it.

So right here, and then copy this

and then paste it again.

We're going to create the second part of our vertical layout

like that, and then copy and paste it one last time

Down here.

So that's how we use the nested layouts technique to visualize and break down a

design into a combination of vertical layouts and horizontal

layouts. Now let's do some more practice.

We're going to take another design and break that down using this technique.

So we're going to open a new tab and we're going to go to

twitter.com/super

simple dev,

and we're going to take,

just take one of my tweets here and take a screenshot of this.

And we're going to break down this design using the same technique.

So let's go back to Google drawings,

and we're going to create a new drawing to practice with.

And let's upload that screenshot that we just took

onto this new drawing right here.

So now we're going to do the same thing.

We're going to draw rectangles to represent the nested layouts.

So let's take a look at this to see how we can break this down immediately.

I see that we have a horizontal layout one and

two, so we can break it down into that. First,

let's draw a rectangle to represent that.

So here's the first one,

and I'm just going to make it blue to represent a horizontal layout And

copy and paste it like this.

Okay, so that's our horizontal layout.

And now looking at the design inside here,

I can see that we can break it down further into a vertical layout.

So I'm going to draw some more rectangles,

and I'm just going to draw right here

and style it a little bit and make it red to represent the vertical layout.

So copy and paste,

and I'm just going to move it down here.

Okay. Okay,

so that's two copy and paste

to get three.

So it doesn't have to be perfect.

It's just here to help us visualize the design. All right,

so we have a horizontal layout, and then inside we have a vertical layout.

And now looking at this, we can also break this down into a horizontal layout.

Let's draw some more rectangles. Actually,

I'm going to just copy this one and paste it and

resize it here. So I'm going to break this down further

into a horizontal inside here.

And finally, we can break this part down further into a horizontal layout.

So let's copy this again and paste it here.

And I'm just going to

create a few of them Like this.

So just like that,

we broke down this design into a combination of vertical and horizontal

layouts using the nested layouts technique.

So now that we have a good understanding of how this works,

we're going to learn how to recreate this using code.

So let's go back into our project.

I'm going to delete all these extra tabs here.

So we're going to go from something that looks like this to something that looks

like our final design here. Now, before we start,

we actually need to download this channel profile picture.

So remember to do that, we can right click and inspect,

click the top left icon here, and then click this picture.

And we have the URL to download it here. So I'm going to hover over it,

scroll down and click this link. Now, control S to save.

And I'm going to save it in the folder that contains our code,

which is right here.

And now this should show up in our code editor.

So I'm actually going to create a folder to store all of these channel profile

pictures since we're going to have a lot of them.

So I'm going to call this channel dash pictures,

And I'll put this in there.

Now we're ready to create our layouts. So let's go back to our final design

and see what kind of layouts we have.

So we're going to have a vertical layout, that's one and two,

so two rows. And then inside the second row,

we're going to have a horizontal layout, which is one and two.

Now, inside the second horizontal layout,

we're going to have a vertical layout one, two, and three.

So that's how we're going to break down this design. And again,

don't worry about the video time here.

We're going to recreate this later in the course.

Let's go into our code and we're going to implement that.

So make sure that we have our project open on the left here.

And we're going to start by creating some vertical layouts.

To create a vertical layout. We're going to create two divs.

So this is going to be our vertical layout.

Now remember that divs are block elements by default,

so they're going to take up the entire line and appear one on top of another.

And that's exactly what we want for a vertical layout.

So let's look at our design. Here. We have the image in the first row.

So I'm going to move this up, Cut and paste.

And then in the second row we have everything else.

So I'm going to put everything here in the second row.

So cut and paste.

Let's save it and refresh.

Now we're going to create a horizontal layout down here.

One column's going to have the channel profile picture,

and the other column is going to have the text.

Let's create the channel profile picture. First,

we're going to create an image element. We're going to give it the source

Of the picture that we downloaded in the beginning.

So that picture is in this folder. So we're going to go into this folder first,

which is channel dash pictures.

And then remember to have a slash to go into that folder.

And then channel one jpeg, save it.

And now if we look at our current website, the image is actually in its own row,

and that's because the paragraph is a block element,

so it has to appear on its own line.

We're going to change this by creating a horizontal layout, like one and two.

So to do that, we're going to create two divs. Here's one diviv,

and here is another diviv.

Now the difference here is that we're going to make these divs inline block

elements.

So remember that inline block is what allows elements to appear beside each

other like this,

while block elements force the element to take up the entire line so they will

appear vertically.

So we're going to make these two divs inline block elements to create our

horizontal layout. Let's reference our design first. In the first column,

we have the channel profile picture. So I'm just going to move this

Into the first diviv here. And then in the second diviv,

we have all the text. So I'm going to move all of the text here,

cut and paste.

Now let's make these divs inline blocks so that they appear next to each other.

I'm going to give a class so that we can target it with css.

Let's call this the channel picture.

And then we're also going to give a class to this div so that we can target it.

Let's call this the video dash info.

And now in our css,

we're going to make the channel picture

picture display in line dash block.

And we're also going to make the video info display inline block.

So they appear next to each other video dash info

display in line block,

save it and refresh.

Now you'll notice that they're still on top of each other,

and that's because divs by default have a width of a hundred percent.

So we need to decrease the width of these two divs so that they appear next to

each other. So remember that for the video preview card. So this whole thing,

we set the diviv to 300 pixels,

and that's how they can appear beside each other.

So we're going to do the same thing for our horizontal layout down here

for the channel picture,

let's set a width of 50 pixels.

And then for the video info,

we're going to set a width to 200 pixels.

So this is the first column of our horizontal layout. It's going to take up 50

pixels like this, and then this is the second column.

It's going to take up 200 pixels.

It's going to appear beside the first column because both of them are display

inline block. So let's save this,

and you'll notice it looks really weird.

So let's look at our code and see what the problem is.

I'm going to scroll up here,

and you'll notice that we set the width of the video title,

which is this text to 300. So we're forcing it to overflow here,

and that's not what we want. So we just need to remove this

and not force the width.

So if we don't force a width of 300,

the paragraph will just take up the entire space of the container,

which is 200 pixels.

Now the second thing we notice is that this image is overflowing,

and that's because images by default,

they overflow. So they keep their original dimensions,

so they keep their original size and that causes them to overflow.

So we want to resize this image so that it only takes up 50 pixels.

Let's go ahead and do that right now.

Let's give it a class so that we can resize it.

And I'm going to call this the profile dash picture.

And then I'll scroll up here dot profile dash

picture.

And then I'm going to resize the width to 50 pixels so that it

fits exactly this column. Going to save it.

And now that looks pretty good.

We can actually see the layout in our browser by right clicking

inspect and finding this html.

So I can click this top left icon and just click this picture.

So I'll show you what it looks like in the html.

So here we have a vertical layout, so one and two,

and then here we have horizontal layout one and two.

Now, a better way to do this is actually to set this to a hundred percent.

So this means the image will take up the entire space of its container.

So if we look at our html, this image is inside this container.

If we set it to a hundred percent, it'll take up the space in the container,

which is basically the 50 pixels that we have here. Let's save it.

Next. Remember that we've seen this problem before, they're not aligned.

So we're going to align this inline block element to the top.

To do that, we're going to use this property here,

vertical align top that we've seen before.

So vertical dash, align, top,

save it. All right, so we're almost there,

but notice that these two aren't aligned.

This paragraph has some margin at the top.

Remember that paragraphs by default come with margin at the top and at the

bottom.

So we're going to go into our code and we're going to get rid of this margin at

the top. So let's scroll up. Oh,

so we actually deleted that style. So let's create a new style here.

We're going to target the video dash title.

We're going to target the class video dash title,

set the margin dash top two zero,

and that's going to eliminate the space up here.

So I'm going to pause here because we've actually created the nested layout that

we need. Let's look into our H T M L in the dev tools.

And if we look at this video preview,

we have a vertical layout one and two.

Inside the vertical layout, we have a horizontal layout one and two.

And then inside our horizontal layout, we have another vertical layout,

1, 2, 3.

So that's a practical example of using the nested layout technique to create a

layout that's a similar shape to this.

The only thing that's left to do is to style our website with CSS

one by one until it looks like this. So we're going to do that right now.

So let's go into our code, and we're going to style these elements one by one.

So I'm actually going to move this down here so that I can see it a lot easier.

So the first thing I noticed is that the image is round.

So remember to create a round image or round anything,

we're going to use rounded corners.

So we're going to set the border dash radius to

let's say 20 pixels. Save it. So we have rounded corners,

and it's getting more round, but it's not a full circle yet.

So let's set this to maybe 50 pixels.

So now it looks a little too big.

Let's set the width to something like 40 pixels.

I think that looks pretty close and we can always change it later. Next,

there's some spacing between the first row and the second row.

So let's go in here. I'm going to set a class here.

Call this the thumbnail dash row.

And then we're going to style this thumbnail row.

And remember to add spacing to the bottom, we add margin

dash bottom, and let's add a margin of maybe 10 pixels.

Save it. Okay, maybe 12 pixels. Okay, so that looks good enough.

And finally, we can style the text.

So this YouTube project is actually using the Google font called reto.

We learned in a previous lesson how to load Google fonts and in particular,

how to load robo. So we're going to do that again.

Let's go to a new tab.

We're going to search for Google fonts,

and we're going to load reto onto our page. So if you don't have this here,

this is from my previous session, we can actually search for robo

and then just open it here. And then we select these styles that we want.

So I'm going to get the regular style,

and then this seems like a bolded font.

So I'm going to get the medium font and the bold font just in

case. So I'm going to go up to see the styles I selected.

And then that looks pretty good.

And Google will give me the code that I need to load this onto my website.

So I'm going to copy this

and just paste it into my head section.

So right in between here. All right,

so now I loaded the robo font, and we're going to use it in our page.

So we're going to target all paragraphs and we're going

to change their font family to reto.

And we're also going to use a backup font with this comma of aerial.

So this syntax here with a comma is called a font stack.

This basically lets us set up a backup font.

If for whatever reason Reto fails to load from Google,

then it will fall back to our backup font, which is aerial,

save it. Next,

I'm going to change the size of the font.

So let's change the video title to maybe

14 pixels. Save it. Okay,

I think that looks pretty good. Next, I'm going to make it bold.

So font dash weight bold,

save it.

So this looks like it's a little bit too bold compared to this font.

So I'm actually going to change this valley to 500.

So if you recall, we actually selected three styles of fonts,

the irregular 400, medium, 500, and bold 700.

So when we set the font weight to bold, it actually corresponds to a number,

which is 700. A regular font weight is 400,

and a semi bold is 500.

So usually we use the number value because it's a little more precise.

So usually instead of typing font weight bold,

we wouldn't use font weight 700. In our case,

our font is a little too bold, so we're going to decrease this to 500,

which is the medium size that we picked on Google fonts.

So let's save this. And that looks pretty close.

Next, we're going to change the space between the lines.

So remember the property to do that, it's called line height.

And let's try 14 pixels. That's not enough,

maybe 20 pixels. All right,

so I think that looks pretty good and close to our design.

You might notice that the text here is shorter than what we have in the design.

You may or may not see this because this text actually depends on the size of

the webpage. So depending on how wide your webpage is,

the length of this text will change. And in our current website,

we actually haven't implemented this resizing,

so we are going to fix this later. Next,

I'm going to style this paragraph.

So let's go into our HTML here and look at the class name.

So it's the video author,

and it looks like we don't have any styles for that yet.

So I'm going to write it down here.

So we're going to style the class video dash author.

The first thing I notice is the font size. So it's a lot smaller.

So font dash size. Let's try 12 pixels. Let's see how that looks.

Okay, so I think that looks pretty close. And we're going to change the color.

Color. Now remember to get an exact color,

we can right click inspect spec,

and then click this top left icon. Click this text,

go to the computer tab. And if we scroll down,

we should get the text color right here.

So RGB 96, 96, 96, save that.

And if we go back,

okay, that looks perfect. Next, I'm going to style this paragraph.

So in our code, this paragraph is called video dash stats,

and I'm not sure if we have a style for this. Doesn't look like we do.

So I'm going to write a new one. so.video dash stats,

we're going to set the font size to 12 pixels because these two look the

same. Okay,

and then we're going to set the color as well since these two look the same.

And now remember that whenever we have these duplicate styles like this and

this, we can actually target multiple classes by adding a comma.

So we're going to target the video dash author class as well as the video

dash stats class.

So this is going to help us reduce duplication of our code.

So I'm going to delete these lines, save it, everything looks okay.

And the last thing we're going to modify is the spacing between the paragraphs.

So remember that paragraphs by default come with margin at the top and at the

bottom. Now, instead of removing them individually,

I'm actually going to go up to the top of our page. So we did this once before.

We're going to get rid of the default margin for all paragraphs on the page.

So to do that,

we're going to go into these styles and we're going to set the margin dash top

to zero.

And we're also going to set the margin dash bottom two

zero. And this will get rid of all the default margins. Save it.

And now we can set a more precise margin at the bottom here.

So under the video title,

let's set a margin bottom of maybe 15

pixels. Save it. Okay, looks like it's a little too much,

maybe 12 pixels. Okay,

I think that looks pretty good. And now under the video author,

we're going to add some margin.

So currently we have some styles that apply to both of these.

I'm going to target.video dash author individually down

here. So for the video author,

I'm going to add a margin dash bottom

of maybe six pixels, save it,

and maybe four pixels. Okay,

so I think that looks pretty close. And now if we look at our website,

you can tell that it's actually really close to the final design that we have

now to finish off the second video preview you have a choice.

You can either do everything that we did in the code here to give yourself more

practice or if you want to save time and move on to the next section,

we can just copy all of this HTML and replace this part here

And then just swap out the thumbnail as well as the channel profile

picture, which you'll need to download first from here,

as well as swap out all of the text.

So I'm just going to fast forward this video to finish up this second video

preview,

but feel free to pause it and try yourself to give yourself more practice.

And there we go. In this lesson we learn in the nested layouts technique,

which is one of the most important techniques for being able to break down a

design that you see on a website and recreate it using code.

In this lesson we're going to learn about CSS grid,

which is a much better way to create these horizontal layouts as well as to

create a grid like this that you see in our final project. First,

we're going to open up the website we were working on.

So I have it open right here.

And remember that for our horizontal layouts,

we were creating them using something called display inline block.

So if we go into our code and we scroll down,

we were using display inline block and a width to put these two

side by side.

Now there are some problems with display inline block that I want to show you

right now.

We're going to set the background color of these to gray,

so this will make it easier to see what the problem is.

Now let's save it.

And now you can see that there's a little bit of space between these two,

and this causes some alignment problems.

So the width of this entire container here, the width here,

we set it to 300 pixels,

but we set the channel picture to 50 pixels here and the video info to 200.

So you would expect that we can actually set this to two 50 to take up the

entire 300 pixels, but if I save it,

you can see that it's too long and it wraps to the next line.

So we have to set it to something like 2 45 and that will cause it to

appear beside each other.

So this is one problem with inline block is that it has some alignment problems.

Now you might be wondering where this space is coming from.

If we scroll down to our html,

we can see that there's actually some space between these two divs,

and we learned earlier that H TML combines multiple spaces together and that's

what shows up here. So we could remove this and save and get rid of that

space, but that means our code is less easy to read.

Now the second problem that inline block has is that it's not vertically aligned

like you see here.

So now we're going to learn a new technique called CSS Grid that's going to help

us create perfectly aligned horizontal layouts to learn grid.

We're going to create a new file where we're just going to practice using grids.

So let's go into our code editor and we're going to create a new file

called grid html.

And remember, for every HTML file, we want the proper structure.

So at the top we're going to have a doc type,

and then we're going to have an HTML element.

And then inside we're going to have a head element and a body

element. Now that we have the proper structure,

we can open this file in live server.

So let's right click and open with live server.

And then let's set the title or the text in the tabs here

to two grid practice

so we know what this file is about. Let's save it.

So I'm going to resize my windows here just so we can see what's going on.

We're going to start off in the body and we're going to create a diviv.

And then inside this diviv we're going to create two divs.

So let's call this Diviv one and let's call this

Diviv two. Save it. And now to help us learn,

I'm actually going to show you a new way of writing c s s.

So if we go to the opening tag here,

we can set a special attribute called a style attribute.

Now the style attribute is unique because it lets us write CSS code inside.

So let's write the code background dash color light

blue, And we save it.

We can see that these styles that we wrote here are applied to this element.

So this code here is another way of writing CSS called inline

styles. We're writing our CSS inside a line of html.

We've already learned two other ways of writing css.

One of them is the style element and the other is to put our CSS in a separate

file. This is a third way of writing css.

Now generally we don't use this in Rio websites because it makes our HTML harder

to read. In Rio websites, we put our styles in a separate file,

but for now, since we're learning, this is pretty useful because number one,

it only affects the element with the style attribute.

And the other thing is that the CSS code is right beside our HTML

so that when you go and review this file later,

it's very easy to see what's going on.

So let's practice with the style attribute.

We're going to add another one to this second div.

So let's set this style to background color,

and we'll set a background color of light pink.

Let's save it. And now we have the two divs we're going to work with.

Now, currently we just have two divs inside another.

There's nothing new going on here, but now we're going to create our first grid.

So what is a grid? A grid is a layout that has rows and columns.

For example, this is a two by three grid.

We have two rows and three columns. This is a one by two grid.

We have one row and two columns.

So we're going to learn how to make this kind of structure in our html.

To do that, we're going to style this outer diviv or the container.

So let's see how that works. We're going to set a style attribute here.

And to create a grid, we're going to need two steps.

The first step is to set the display property,

and we're going to set display to grid.

The second step is we need to set how many columns our grid has.

So to do that we're going to use this property grid dash template,

dash columns,

and we're going to give this property two values,

100 pixels and 100 pixels.

So these two values define how wide our grid columns are.

The first column is going to have a width of 100 pixels,

and the second column is going to have a width of 100 pixels as well.

And our grid will have two columns. So if we save this,

you'll see that we created our first one by two grid.

Now I want to point out a few characteristics of a grid. First of all,

notice that this diviv is no longer taking up the entire line.

So recall that divs are displayed blocked by default.

They're supposed to take up the entire line,

but when this element is inside a grid,

it's actually placed into the grid,

so it only takes up the entire column instead.

The second thing you'll notice is that there's no extra space between these two,

unlike with display inline block.

And the third thing to notice is that, for example,

let's add another element into the second. Let's add a paragraph

of text, save it when we add more elements.

This makes the second taller than the first one, but they're vertically aligned,

and that's another difference between grids and display.

In line block grids maintain alignment much better.

All right, so that is our basic grid.

Now we're going to create another grid to practice with.

We're going to go into our code, we're going to copy all of this,

and then we're going to paste it below.

And it's a little bit weird, the formatting.

So we can select this and press tab to move it back into a normal

position. Let's save it. And now we have our second grid,

but let's actually add some space to the top so that we can see it more clearly.

We're going to add some margin dash top of 30

pixels. Save it. Okay, that looks pretty good.

And this time we're going to add a third column.

So this property actually takes any number of values that you give it.

So if we add a third value here of 200 pixels,

it's going to create a third column that is 200 pixels wide.

So the number of values determine the number of columns and the value itself

determines the width of the column. So if we save it,

we do have three columns here, but we only have two divs,

so we need another div to fill out the third column. To do that,

let's copy our first diff,

and then we're just going to paste it down here and call it div three.

So now we have three diffs to fill out the three columns,

and you can see that our third column is 200 pixels versus 100 pixels that we

saw right here. So let's actually change the text here so that we can

see what's going on. So 100 pixels, 100 pixels,

and 200 pixels. Save it.

So now let's see what happens when we add another div to our grid here.

So let's copy this second diviv and then duplicate it.

Copy it and paste.

Can actually get rid of this paragraph here and save it.

And now you can see that this fourth diviv wraps around to a second row.

So whenever we have more elements than we have columns here,

it starts to wrap around and create new rows.

So that's the basics of how grids work.

Now I'm going to show you a special value that we can use with grids. First,

let's copy this and then create a new grid to practice with

space it here. And then select this and tab.

And this time we're only going to have two columns.

So let's get rid of this third column. And let's only have two diffs here.

And we can also get rid of this paragraph. For this grid,

we're going to have two columns. The first one is 100 pixels,

and the second one, we're going to change it to one fr.

So FR is a special value in grid that stands for free space.

It means to take up the remaining amount of space on this grid.

So if I save it,

you can see that the first column here is 100 pixels and the second column

has a width of one fr.

So it takes up the remaining amount of space that we have. If I resize the page,

it'll take up the remaining amount of space. So that's what one FR means.

I'm going to change this to one fr so that it's easier to see when we review

this file.

So this fr value is exactly what we need in our final design.

If I open my final design,

you can see that we have a horizontal layout here.

The first column is about 50 pixels,

and we want the second column to take up the remaining amount of space,

which is exactly what we need, one FR four.

Now before we go and update our project,

I'm going to show you another property of this FR value.

Let's copy on this diviv and create another grid

below it.

And this time we're going to add a third column that is also one

fr. And I'm going to add another diviv to fill out this third column.

Let's copy this and paste it into a third diviv.

This one is also going to be one F fr. So let's save it here.

And for this example, the second column and the third column,

both have one ffr.

So one FFR tells the columns to take up the remaining amount of space and the

number in front of it tells us relatively how much of the remaining space

this column gets. Since in this example, both of them are one,

they'll get an equal amount of the remaining space.

So here these two are equal and they take up the remaining space.

If we change the third column to two fr,

so let's change this to two fr and save.

The second and third column will take up the remaining space,

but the third column will be twice as wide as the second column.

So this number here is sort of like a ratio.

This second column will have a one-third of the remaining space,

and this third column will have two thirds of the remaining space.

Now that we understand that concept,

we're going to go back into our project and use grids to create this horizontal

layout instead of inline block.

Let's go to our code and we're going to scroll down into the

H T M L for this which is right here,

and I'm going to collapse it so it's easier to see.

We have the channel picture and the video info, which is these two.

So to create a grid, remember we need to create it on the container,

which is this diviv.

So let's set a class name video dash info dash

grid, and then we'll target this class in our CSS above.

Going to scroll up, and I'm going to actually put it right here,

video dash info dash grid,

because this is right above the channel picture and the video info.

So it's beside other related styles. Now remember,

to create a grid, we need two steps.

The first one is to set the display property to grid.

This creates our grid, and then we need to set how many columns our grid has.

So we're going to set grid dash template, dash columns.

And for our purposes,

let's set a column of 50 pixels for the channel profile picture.

And then we want the second column to take up the remaining amount of space.

So as we learn, that is one fr. Now if we save it,

you'll notice that the space between the inline blocks is gone. So unlike here,

and you'll also notice that these two are vertically aligned.

So now that we have our grid,

we can actually remove all of these inline block styles because we're not using

them anymore. So we can actually remove all of these

and all of these. Let's save it.

And now let's set a grid for the second video preview.

We're going to scroll down.

So remember we're going to set the styles on the container here,

and then these two divs are going to appear in our grid.

So we've already created this CSS at the top.

We just need to set a class of video, dash info dash grid,

save it,

and then all the styles that we wrote up here will target that class.

So now we have both of our grids and you can see our horizontal layout is

perfectly aligned with the rest of our layout.

And now we can remove this background color

and this part of the project is done.

The last thing we're going to learn about grids is if we go to our final design,

we're going to learn how to build a bigger grid like this. So

notice that there's a little bit of spacing between the columns as well as

between the rows. Now before we start,

you might have a bigger screen and you might see four videos in each row.

So for now,

let's actually resize the browser so that we see three videos in each row.

So I'm doing this because not everyone has a big screen to work with,

and this will make sure that everyone can follow along.

So I'm going to zoom back in and just make sure I have three videos in each row.

And we're going to learn how to create this kind of layout.

Let's go into our grid practice file,

and we'll go back into our code again and into our grid html file,

and we're going to create another grid to practice with.

So let's copy this and then just paste it down here.

And now for this example, let's look at our final design.

We essentially want three columns of equal size.

And when we resize the page, notice that the columns resize as well.

So notice that if I resize too much, it becomes two columns.

We're going to deal with this later in the course.

We're not going to deal with that.

We're just going to deal with three columns that we have here.

So for this layout, we want something like one F fr, one F fr,

and one FFR to divide this space evenly.

Let's go into our file here and we're going to set three columns,

one F fr, one F fr, and one ffr.

So this will create three equal columns that will resize with the page.

Let's set this to one FFR as well so that it's clear what's going on.

Let's save it.

And now we have the three columns we're going to be working with.

Let's also set the height so that it looks a little bit like our video

previews that we have here.

So let's go into our HTM file and we're going to set the height

to 200 pixels.

And let's also set the height of these other columns as well.

200 pixels and 200 save it. Okay,

so that looks pretty good, but they're a little bit too much.

At the bottom of the page,

we're going to add some spacing at the bottom of the website so that we can

scroll these up.

Let's go back up into our HTML and we're going to scroll up to the body

tag.

We're actually going to add some spacing inside the bottom of the body tag.

So remember that spacing on the inside is called padding.

So padding dash bottom. And let's set it to something

like a thousand pixels. So it's a lot easier for us to practice.

So now that we have a lot of space at the bottom, we can scroll all the way up

and see our grid clearly.

So remember that in a grid, if we have more elements, then we have columns,

it'll start wrapping around to the second row.

So all we had to do is add three more divs. So we're just going to,

let's actually copy the pink one first.

Let's copy it and paste it,

and then we'll add a blue and a pink at the bottom. So let's copy

and paste it.

So we just need six divs to work with that have alternating colors like this.

So let's save it.

And now we essentially have our video preview that we see here,

and we're going to learn how to create these space between the columns and the

rows. So it's actually really easy to create this space.

We just need two CSS properties.

The first one is called column dash gap.

So it's pretty straightforward what this means.

We're setting some space or a gap between the columns.

So let's set a column gap of 20 pixels. Let's see how that looks. Save it.

And now all of our columns have a gap, just like our final design here.

Next we're going to set the space between the rows and we have

a similar and straightforward property for that called row dash cap.

And let's set this to something like 40 pixels, save it.

And now we have space between the rows, just like our final design.

So that's how we create a grid like this.

First we define our three columns. So in this case,

we want to divide it up into three equal columns that resize with the page.

That's why we used one ffr, one ffr, one ffr.

And then we just add some space between the columns using column gap,

which creates this. And we add space between the rows using row gap,

which creates this.

Let's go back into our website we were working on and we're going to apply these

skills to here. Let's go back here.

We're going to scroll down. And first of all,

let's just create six of these video previews so we can organize them into a

grid that looks like this, two rows and three columns.

So we're going to go into a code and we're going to copy both of these

and we're just going to make duplicates.

So copy it and paste it.

So now if we save, we have four and we're going to create two more.

So paste it again, save. And now we have six.

So remember to create a grid, we need a container.

So we need a container for all of these video previews.

So let's create a diviv, and this is going to be our container.

We're going to call this the video dash grid.

And now let's move all of these video previews inside our new grid.

Just going to move all of them,

cut it and paste it in here.

Let's save it. Scroll back up. And now to create the grid,

we want to set styles on this container element.

So let's go into our css.

We're going to target the video dash grid.

And remember we have two steps.

The first step is to set the display to grid,

and the second step is to set how many columns we have grid dash

template, dash columns,

and for our example,

we want three equal columns that take up the entire space.

So let's set one fr, one fr and one fr.

Now if we look at our page, we now have the three columns in our grid,

but you might notice that if I resize this down,

it actually doesn't resize with the page.

So the reason this happens is because if we go and scroll up,

we set a width on the video preview,

which sort of forces the width to be 300 pixels and earlier we also set

the width of the thumbnail to 300.

So instead of setting the width like this, which will force the width,

we actually just want these elements to take up all the space in the columns

that they're inside of. So to do that,

we can remove this property here and let's save it.

And for images,

a weird behavior is that they always keep their original size to get them to

fit inside their container or inside the column of the grid. We have

to set a width of a hundred percent save it,

and now they'll only take up a hundred percent of their container. Now,

we also don't need the display block here anymore,

so this image is taking up a hundred percent. It's already on its own line,

so display block is not necessary. So let's delete that.

And now we're going to deal with this video preview with for this,

we can just get rid of the with here and the display inline block

and also vertical line, which relates to inline block.

And we can get rid of the margin since we're going to create this space using

the column gap property we learned earlier.

So let's just get rid of all of these styles. And now if we save,

we can now see that our video previews are fitting perfectly inside of our grid.

The final step is we're going to add some space to the columns and to the rows.

So let's go into our CSS here. And remember the two properties,

they're pretty straightforward are column dash gap,

and let's set a column gap of maybe 15 pixels. Save it.

Okay, let's compare that to our design,

and I'm going to resize it a little bit.

So I think this looks pretty close to what we have,

maybe 16 pixels.

And then we're going to set a row gap.

Let's set a row dash gap of maybe 40,

save it and compare it to our design.

So I think that looks pretty close to what we have now,

the design might look a little bit smaller,

and that's because we have the sidebar here,

but we're going to deal with that in a later lesson. So for now,

this looks perfect.

The last thing we're going to do is to swap out the thumbnails,

the channel profile pictures as well as the rest of the text to match our

design. So I'll let you get some practice doing that. Remember,

you'll have to download the thumbnail and the channel profile picture first.

For now,

let's just do six of these videos and then we can add the rest of them at the

end of the course.

So pause the video right now and swap out all the thumbnails,

the channel pictures and the text, and I'll see you back after you've done that.

So this is what it looks like after I swapped everything out.

So that's the end of this lesson. We learned about CSS grid,

which is a great way to create these horizontal layouts that are perfectly

aligned and to create this bigger grid that we see here.

Here's some exercises to get yourself familiar with grids.

In this lesson we're going to learn about Flexbox,

which is another way to create layouts.

And we're going to use Flexbox to create the header at the top of the page.

So Flexbox is similar to CSS Grid. It can create the same kind of layouts,

but it's more flexible just like the previous lesson.

Let's go into our code and create a new file just to practice Flex Box.

We're going to create a new file by clicking this icon and let's call it

flex box dot html. And remember,

we always start with the HTML structure.

We're going to have a doc type at the top and then an HTML

element,

a head element and a body element.

Let's save it. And now we can open this in live server.

So right click and open with live server.

Now in this lesson we're also going to compare Flexbox to grid to show what

these similarities and differences are.

So we're also going to go into our code and open the grid dot html from the

previous lesson. And we're also going to open this in live server.

So right click and open with live server.

Just going to move these beside each other and resize the page.

And now we're ready to begin.

So we're going to start off in our flexbox dot html.

And first we're going to go into the head section and we're going to add a

title.

Let's call this flex box practice and then save.

So this is just going to remind us that this file is for flex box practice and

it's going to show up here.

Next we're going to go into the body and start creating some flex boxes.

So just like for grid, we're going to create a diviv,

and inside we're going to have two divs,

so diviv one and Diviv two.

So we're going to use inline CSS again just like we did for grid like here,

so that we keep our CSS code close to our HTML code,

and it'll be easier to understand what's going on when we review this file in

the future. So insider diviv set a style.

And for this div we're going to set the background color to light blue like

before. And then for the second diviv,

we'll also set it to light pink.

So style equals background, dash color,

light pink, save it.

And now we have the two divs we can work with. So just like with grid,

Flexbox requires a container or this outer diviv.

This container is going to be the flex box.

And then these elements are going to be placed into our flex box.

So now let's learn how to turn our container into a flex box.

We're going to set a style here and we're going to do two steps.

The first one is to set the display property to flex.

This creates a flex box. In the second step,

we're going to set the flex dash direction to row.

This means we're going to align these elements horizontally in a horizontal

layout.

So now let's save this file and we can see the effect that Flexbox has.

So inside of Flexbox, these divs, which are block elements,

don't behave like block elements anymore.

They behave more like inline block elements.

They only take up as much horizontal space as they need to.

Now compare that to grid where we first set the columns and then the

elements went inside the columns. So the layout is a little more rigid for grid.

If we go back to our flex box,

if we add some more text to this first diviv and save

notice that it expands to take up as much space as it needs to.

So this is a flexible box and that's why we call it flex box.

Now there's one other thing I want to point out about flex box is that if we

make this second diviv taller, just like our grid example here,

the flex box will be vertically aligned.

Let's go into our code and let's add a paragraph to make this diviv

taller. If I save it, you'll see that it got taller,

but we still maintain vertical alignment.

So flexbox is another way to create these horizontal layouts while maintaining

alignment. All right,

let's go through some more examples to see these similarities and differences

between flex box and grid. We'll start with these similarities. First,

we'll go into our code and we're going to create another flex box to practice

with. So we'll just copy this and then paste it down here.

I'm going to select this and press tab. I'll scroll down.

So we'll also add some spacing to the top of this because we want to make it

easier to separate.

So let's add some margin dash top of 30 pixels,

save it. That looks pretty good. And now for this first diviv,

we're going to set the width to 100 pixels.

So I'm just going to organize my CSS a little bit here and we're going to set

the width to 100 pixels and let's also

change the text to 100 pixels so that we know what's going on. So let's

save it.

So now our first flex box element is 100 pixels wide.

For the second diviv,

we're going to tell it to take up the remaining amount of space.

So if you remember from grid, that's equivalent to one fr,

we're going to learn how to do that in flex box. So for this one in our code,

we're going to add a new style and we're going to add a

style specific to flex box called flex.

And we're going to set this to one.

And we're also going to change this text here to flex

one. Let's save it.

And now we can see that flex one causes this diviv to take up the remaining

amount of space.

So Flex one is the flex box equivalent to one FR in grid.

So let's go through another example.

We're going to copy this and then paste it again.

And for this example, we're going to add another diviv to the bottom here.

So let's copy this first diviv,

copy it and paste so that we have alternating colors.

And then we're going to set the flex on the second diviv to flex

two. And let's change the text to flex two.

So you can see that flex two is the equivalent of two FR and grid.

So two items that both have flex are going to take up the remaining amount of

space.

But this number here tells us relatively how much of the remaining space it

takes.

So this element with flex two is going to take twice the amount of the remaining

as this element with flex one.

So the value here works the same as E value with fr.

So you can see that the basic things that we do with the grid we can also do

with flex box. Now let's talk about the differences.

So if we go to our grid examples and we look at that, this example here,

the layout is more rigid for grid.

If we go into our grid code and we scroll down to this example,

which is right here, one FFR and two ffr,

you'll see that we first define three columns and then these elements go into

those columns. So if I move this element to the second

position, so I'm just going to cut and move it down here.

This item is now going to go into the second column and it's going to take up

one FR of space, even though we wrote 100 pixels here.

So if I save this,

you'll see that this one FR element goes into the 100 pixel column.

So it only takes up a hundred pixels of space.

And the layout here is not changing for flex box. However,

if we go to our flex box example and our code,

if we change the order of the elements,

so let's cut this and paste it down here, save it.

You'll notice that the layout actually changes.

So this element here actually keeps its width of flex one,

and then the second element keeps its width of a hundred pixels.

So the elements take their width along with them if they move around,

and that causes us to have flexible layouts depending on how many elements we

have and what order they're in. So that's the biggest difference between

flex box and grid.

So what's the advantage of having a flexible layout like this?

Let's go to our final project and we're going to resize the browser.

And you'll notice that in the header in the right section we have four icons or

images. Now we could create this horizontal layout using a grid.

However, when we're locked out of YouTube,

you'll notice that we only have three icons.

So the layout actually changes because we only have three elements now.

So this would be a great situation to use flex box instead of grid when we want

a flexible layout dependent on our content.

So that's the basics of how Flexbox works to create layouts and the main

difference between Flexbox and grid.

We're going to go back to our practice file and we're going to go through some

other examples of Flexbox to help us build the header of our final project.

So first,

let's actually save this as it is so that we get a reminder that the

layout is flexible.

I'm going to change this to light blue and the other one to light pink so that

we have alternating colors and it's easier to see.

All right, let's go back into our grid coat,

and we're also going to move this back into its original position.

So just to remind us that for grid, the layout is more rigid,

let's save it. And now we're back.

So we'll go back to our Flexbox file and our flex box html,

and we're going to do another example.

So let's copy this and we're going to create another flex box to

practice with.

Now for these next examples,

we're going to use them to learn how to create the header up here. So first,

let's create something that looks like the header.

We're going to create a box that has roughly the same shape.

So we'll go into our file here and we're going to make this flex box have the

same shape as a header.

So let's set the height to 70 pixels and let's

set a border so that we can see the actual box.

So we're going to set a border width of one pixel,

a border style of a solid color,

and we'll set the border color to gray. And when we save it,

we can now see our flex box using the border.

I'm going to add a little bit of spacing to the bottom of the page here so that

we can scroll this up. So remember to do that,

we're going to scroll up and add some padding to the bottom of the body.

We're going to add a style to the body,

and we're going to add some space to the bottom.

So padding bottom 1000 pixels,

and now we can scroll this flex box up to the top so that it's easier to work

with. Now let's scroll back down to the example we were working with,

which is right here. So for each of these divs,

let's change the width to 100 pixels.

So I'll change this one to 100 pixels,

and let's also change the text to 100 pixels

for this one's also 100 pixels and the third one to 100 pixels.

Now let's save it. And we have our three divs here.

So notice that these three divs are aligned to the left side,

so we can actually change how they are aligned horizontally. To do that,

we're going to use a flex box property called justify dash content.

So this determines how these elements are laid out horizontally. For example,

the default value is start. If we save it,

they'll be aligned to the start or the left side.

If we change this to end now,

they will be aligned to the end or the right side.

We can also change this to center to put all of our elements in the

center. So that's how we control how these elements are positioned horizontally.

We're going to go through another example here.

We're going to copy this whole flex box and we're going to create another one

below it. Let's copy it and paste it.

And for this one we're going to set a special value of space

dash between.

So what space between does is that it spreads out our elements evenly across

this horizontal space and to make sure that there's equal amount of space

between each element.

So this is really useful if we go back to our header to spread

out these four icons evenly.

Now the last example we're going to go through for flex box is how to align

elements vertically. So let's copy this again and create another flex box.

So let's copy this, paste it down here.

And for this one we're going to set another flex box property called align dash

items. So this determines how these elements are aligned vertically.

The default value is stretch,

which you can see here the elements are stretching to fill up the vertical

space, but we also have some options. We can align them to the start,

so they will no longer stretch to the vertical space.

They will just take up as much vertical space as they need to,

and they will be placed at the top or we can put them at the end,

which will place them at the bottom of the container and we can put them in

the center,

which will place them vertically centered. If we look at our final project,

again,

you'll notice that all of these things in the header are vertically centered.

So now we learned all these skills that we need and we're ready to build the

header for our project.

Let's go to the code for our project we were working on,

which was YouTube dot html. And make sure you have this open in your browser.

I'm going to resize the window here and also the code editor so that it's

easier to see what's going on. As we code,

We're first going to create an element at the top to represent our header.

So let's scroll down. And currently all we have is this input.

So we're going to create a new diviv

and we're going to give it a class of header.

So this diviv is going to represent the header in the final project.

And now let's put our search bar into our new header.

So we'll cut this and paste it in here.

Next. If we look at our final project, the header has three sections.

We have a section on the left,

a middle section with the search bar and the right section here with some icons.

So we're going to simplify this by first creating these three sections and then

aligning them and then filling out these sections with the appropriate elements.

So let's go back down here and we're going to create three sections.

So we'll just use three divs here.

So let's call this class equals left dash section.

We'll create another diviv, we'll call it class equals middle dash section.

We'll create another div and we'll give it a class of right

dash section

and we'll put the search bar into the middle section Right here.

And now let's style this diviv so that we have roughly the same dimensions.

So before we do that,

you'll notice that we already have a lot of CSS code in this file,

and the best practice is actually to put the CSS in a separate file.

So before we write even more css,

let's go ahead and put this into its own CSS file.

So we're actually going to have multiple CSS files,

one file for styles of the video preview and another for every

style of the header.

So let's actually create a new folder first to organize all of our different

files of css. So we'll create a new folder and let's just call this styles.

Inside we're going to create two CSS files.

The first one is going to be called video dot css,

and the second is going to be header dot css.

So first we're going to go into our YouTube htl.

We're going to move all of this into the video dot CSS file.

So let's move this into here.

Now all these styles for these videos are separated into their own file.

Now if I scroll up to the top here,

you'll notice we also have some styles for the header.

So this actually belongs in the header,

and we're going to move this into our header dot CSS file.

So we're grouping related styles together to make it easier to read. Now,

for the top of this file, again,

we have this code that targets all paragraphs on the page.

So this is not actually specific to our videos.

So I'm actually going to create another file called general

dot css,

and that's going to contain all the general CSS code like this

where we target all paragraph elements on the page.

So move this piece of code into general.

So just like that,

we have three CSS files and they're all very focused on one part

of our webpage. So this is generally what we want to do.

We want to organize our code and separate them into different files depending on

what the code does. Next,

we're going to go into our HTML file and we can remove this and let's save it.

But now you can see that all of these styles that we had are gone,

so we need to link them back into our html. To do that,

we're going to create a link element. We'll have an attribute of re,

which tells it what we're linking.

So we're linking a style sheet and we also tell it what file we're linking with

hf. So here beside our HTML file,

we have a styles folder. So we're going to first link the styles folder,

and then we're going to type a slash to go into it and link general dot css.

And now we're going to link our other two CSS files. So to do that,

we just need to copy and paste this,

and then we're going to link header dot css.

And for the third one, we're going to link video dot css.

And if we save it,

we linked all of our code in three separate files and we're back to where we

were. Next,

let's focus on our header styles and create our header.

We're going to go into this file And we actually don't need this display block

anymore. So we use this to put the search bar on a separate line,

but now the search bar is inside a bunch of divs,

so the divs will create that separate line for us. Now,

the one other thing that we had to do is that notice that there is some spacing

on the left side, on the right side and at the top. So by default,

if we right click and inspect and we look at the body.

So the body element has eight pixels of margin on every side by default.

Now to get a more precise design, we actually want to set this to zero.

So we're going to reset these default styles.

So we'll go into our CSS code and we're going to go into the general file

and we're going to target the body and we're going to get rid of all margins.

An easier way to do this is to set the margin property and set it to

zero. So this will set all margins in all directions to zero. Let's save it.

And now our elements are right up to the edge of the page.

Next we're going to work on our header.

So I'm actually going to make this wider so that we can have both of these

files on each side.

So we're going to have the HTML on the left and the CSS on the right.

So the first thing we'll do is we're going to add a height to this header so

that it looks like our design here.

So let's go into our header file. And remember we set a class of header,

so we'll target that using dot header,

and we'll set a height of maybe 40 pixels.

Okay,

so let's compare that to our design. Looks like our design is a lot taller.

Let's change it to maybe 55 pixels.

Let's compare that. So I'm just comparing this to the bottom edge of here,

and that looks pretty good.

So next we're going to position these three sections, the left section,

the middle section, and the right section.

So in our code,

we can't actually see the sections right now because they don't have any content

in them.

Let's just call this the left section and then add the text here

as well. The right section,

save it. And now we have these three. However,

you'll notice that they're being aligned vertically,

and that's because divs by default are display block,

and we haven't made this into a flex box yet.

So to create a horizontal layout,

we're going to turn our header container here into a flex box.

We're going to set the display to flex,

and we're also going to set the flex dash direction to

row to lay them out horizontally slots safe.

And now our sections only take up as much space as we need to as we saw in our

examples. Next,

let's give these a background color so it's easier to see them.

So for the left section we're going to target it And we'll set a

background dash color of light blue.

And for the middle section

we'll set a background color of light pink.

And for the right section, we're going to set a background color of light blue,

right section,

background color of light blue.

So now how do we create this layout? So let's analyze it a little bit.

If we resize the page, notice that this middle section is also resizing.

So to achieve this, we're going to use a property called flex.

So if you recall in our examples, flex takes up the remaining amount of space.

So if I look at the header in our final project,

when I resize this right section is not changing,

its width and neither is the left section.

So these will have a predefined width,

and then this will be flex because as you can see,

it's growing as the page is being resized.

So that's an example of how to analyze these layouts. Don't worry,

you'll get better with more practice. For now,

we're going to do this example together. On the left section,

we're going to set a fixed width. Let's set this to maybe 200 pixels.

See how that looks. We'll compare it to our design.

So it's actually a little too much.

I wanted to end right here after the YouTube logo.

So we're going to go back and let's change this to one 50 pixels.

And let's compare it. So that looks pretty close.

For this middle section, we wanted to stretch.

So remember the property to do that is called flex one.

So now the middle section is stretching. And for the right section,

we also want a fixed width. So let's compare it.

We want it to be somewhere here.

Let's try setting a width of 200 pixels

and then let's compare these two. Okay,

so I think this is pretty close to the structure that we have here.

So what we're doing is we're just simplifying the structure into the bigger

picture, and then we'll go in and add these smaller details.

Now we're going to set some spacing on the left and the right side of this

middle section. So remember to do that, we're going to set our margins.

So on the left side,

let's set a margin dash left of maybe

30 pixels, save it. And let's compare.

There's definitely more than 30 pixels. Let's change it to maybe 70 pixels.

Save it and compare. So this compared to this,

I think that's close enough. So now for the right section,

we're also going to add a little bit of space. So if we look at our design,

so it's less space than we have here.

So we're going to add a margin to the right of the middle section,

and we'll set it to maybe 30 pixels, save it.

And that looks pretty close to what we have here, maybe 35 pixels.

Okay, so now if we resize our page,

you'll notice that the middle section is growing and shrinking with the page.

And the right and left are staying the same width,

which is exactly what we have here.

So there's one other detail we're going to copy for this middle section.

Notice that if I resize the browser and make it wider,

at some point the middle section stops growing. So at roughly this point,

the middle section will stop growing.

If the browser gets wider and it just keeps the same width and is centered

horizontally, we're going to learn how to do that.

Let's go back into our project and we're going to limit the width of this middle

section first.

So we'll go into our code and the property to do that is called

max dash with.

And let's set it to 300 pixels.

So this property says the width can be less than 300 pixels,

but as soon as it grows to be over 300 pixels, we're going to limit it to 300.

So that's what we see here. Now,

when we resize the browser to be less than 300 pixels,

notice that it's shrinking and growing again, but when the browser gets wider,

it's limited to 300 pixels because of this line of code.

Next,

we want to distribute these three sections evenly across our horizontal space.

So just like what we have here. Now remember to do that in flex box.

We have an example here.

If we go back into our code and go into our flex box practice file,

we can find that example in our code.

And remember that we achieved this using a property called justify

content space between,

and we set this property on our flex box container,

and that's what we're going to do for our project right now.

So we're going to go up to our flex box container.

Let's go back to our YouTube hdml and to spread these out evenly

across the entire horizontal space.

And we're going to set justify dash content space

dash between. Let's save it.

And now they take up the entire space. So if we compare this to our design,

we'll notice that the middle section is still a little bit too narrow compared

to our design. So let's increase the max width here.

So let's increase it to 400 pixels, see how that looks.

Okay, so it's still bigger.

Let's increase it to 500 pixels.

See how that looks. Okay, so I think that looks close enough to our design.

So this middle section in pink is roughly equal to this middle section

over here. So that's the end of this lesson.

We learned about Flex Box and we used it to create the layout for our header.

So in this situation, we were mostly focused on our content size.

We wanted to make sure the middle section had a max width and at least some

space in between.

So that's why we used a flex box because we were focused on our content size

first. And then the layout doesn't matter as much.

We just use a flex box to spread out our content evenly across the horizontal

space. So when we focus on content size first, we use a flex box.

When we want to create a grid, we use grid. And for most other situations,

for example, this horizontal layout that we created in the layers technique,

we can use either grid or flexbox. In most situations, they do the same thing.

So here are some exercises that you can practice using Flexbox to get yourself

more familiar with how it works.

And now that we have the general layout,

we're going to finish up the rest of the header. Before we do that,

we're going to download all of these icons and images that you see here.

To do that, we're going to right click inspect,

and then click this in the top left and then click the icon we want to download.

And then we can find the URL down here.

I'm going to hover over it and then click this link to open in a new tab

and then save it with control S.

So I'm going to save this in the folder that contains our code,

which is this one. So I'm going to save it.

And then in our code editor, we should see this icon,

so we can collapse this by pressing that.

And then now we have our icon right here called the hamburger menu.

Now looking at our header, we have a lot of icons to download.

So let's organize them using a folder. We're going to create a new folder,

and let's call this icons.

And we're going to put the icon we downloaded into that folder.

So this one right here into this folder.

And now we're going to do the same steps to download all of these other icons

and this image that we see here. So we're going to do the same steps.

Click the top left and then click the icon we want to download and we can find

the link here.

I'm going to fast forward the video here because it's just a bunch of repetitive

steps, and we'll continue after we downloaded all the icons.

So when you get to the notification icon,

don't worry about this notification number here.

We're going to learn how to do that in the next section.

And for this channel profile picture, when I download it,

I'm actually going to save it in a different folder from the other icons.

So if I download this here and save it,

I'm going to put this in the channel pictures folder instead of the icons

folder, because technically it's a channel picture.

So once we have all of that downloaded,

let's check in our code editor and we should see all of the icons that we need

for the header inside the icons folder,

as well as the channel profile picture on the right in the channel pictures

folder.

And now we're ready to complete our header in our current project.

So in our left section we have this,

which is a called a hamburger menu and the YouTube logo.

So N our HTML. In this file, in our left section,

we're going to have an image and we're going to tell it what to

load. So loading and SVG is the same thing as any other image.

And we're going to go into the icons folder and we're going to load the

hamburger menu dot svg.

And then we're also going to load the YouTube logo,

which is right here.

So YouTube logo dot svg,

save that and look at our webpage and refresh.

So the images are loaded, but they're way too big. Let's make them smaller.

We're going to set a class so that we can target them with css.

So hamburger dash menu. And for this one,

let's set a class of YouTube dash logo.

And now in our css,

let's go in here and target the hamburger

menu class.

And let's set the height to something like 20 pixels.

And same thing for the YouTube logo.

We'll set the height to 20 pixels.

So that looks pretty good. Now, if we look at our design,

we'll notice that these images are actually aligned vertically in the center.

So in our flex box practice file, we learn how to do this.

If we look at our code, again,

if we look at our flex box code,

let's scroll all the way down to the last example.

We did this using a align items center,

so that aligns them vertically in the center like this.

We'll go back to our header c s s and just have this as a reference.

So for our left section, we're going to set a line, dash items,

colon center. However, you'll notice that it didn't do anything.

And that's because if we look at our html. The header is a flex box,

but this left section here is still a regular,

it's a element inside the flex box, but this itself is not a flex box.

So Align items doesn't do anything Now to fixes.

We can actually turn the left section into a flex box using Display

Flex, And if we save it now the left section is a flex

box, so align items will align it vertically in the center.

So Flex Box doesn't actually go down two layers.

It only affects elements on the first layer like this Diviv and this Diviv.

If we go down another level, like here, flex box doesn't affect it.

That's why we have to turn this into a flex box as well in order to use

properties like Align Items center.

So this situation of putting a flex box inside another flex box is totally

valid. If we want to target another level of elements like this,

let's go into our design and compare it.

And you can see that for our design there is some spacing on the left and

right of the hamburger menu.

So we can create that right now using margin

dash left of 20 pixels and margin dash right

of 20 pixels. So we'll add 20 pixels on both of these sides.

So if I go back and forth,

you'll notice that this icon is a little bit bigger than our project,

so we can actually adjust our height here to make our icon a little bit bigger.

We can maybe set this to 24 and let's compare

it. Okay, so that looks pretty close.

So now I notice that this icon is a little bit to the right of our website,

which is here. So you notice that it's a little bit to the right,

we need to add more spacing.

So let's add margin left of maybe 24 pixels. Save it.

Now if we compare the two.

So that looks pretty much close to what we need and the YouTube logo is also in

the same place, so that's a bonus for us.

So now it looks like the left section is pretty much done in our project and we

can get rid of this background color that we were practicing with.

First. We're actually going to remove the width.

So this width of 150 pixels is forcing the left section to only end up here.

However, if we remove this,

the left section will stretch to contain all of its content. So if we save it,

you can see that it stretches. Now we can remove the background color

and that's done. Next we're going to work on this middle section.

So for this middle section in our design, we have an icon here,

a button here. And if we resize,

you'll notice that the search box also resizes. So this search box is going to

grow with the rest of the page. So we already learned how to do that.

As a reminder, it's flex one.

So first let's go in and create these two buttons first because that's the easy

part.

Let's go into our code in the middle section here.

After the search bar, we're going to create two buttons.

So let's create one button here and another button down here.

So inside this first button we're going to have this search icon.

So if we go into our icons folder, it's this icon here, search dot svg.

So we can create an image element,

source and icons slash search svg.

In the second button we're going to have our voice search icon,

which is this one,

and we're going to create another image element and we're going to load

icons slash voice search icon.

Now let's save it and see how that looks. Okay,

so that didn't work out very well probably because if you remember when we

loaded this icon here, it was super big.

So the two icons we loaded are probably super big and we only see the top left

corner, which is empty.

So first let's make our icon smaller and make our buttons a little bigger.

Let's go into our html.

We're going to add some classes so that we can target it with css. It's class.

Let's call this the search dash button.

And let's call this one the voice dash search dash

button.

So we're going to go to the middle section here.

We're going to target the search button first.

Let's set the height to something like 40 pixels and set the

width to something like 60 pixels.

And for the voice search button, if we look at our design,

it's pretty much round. So let's target voice search button.

Let's set a height of 40 pixels and we'll set the width

to 40 pixels as well. So let's save it. Okay,

so that looks super weird, but we're going to fix this right now.

So remember that we want to align these in the center vertically just like this.

To do that, our middle section is also going to be a flex box,

and then we can use the align items property that we use for the left

section.

So let's make this middle section a flex box and we're going to set

display to flex and we're going to set a line

dash items

to center just like our left section. So now if we save,

you'll see that everything is aligned to the center and now it's ready for us to

style. So there is one thing that I left out which is flex direction row.

So this tells a flex box to lay out our content horizontally.

And this is actually the default value, so we don't actually need it.

I put it here just for our practice code before our header.

We can be safe actually leaving that line out and just having display flex and a

item center. So now that the layout is good,

we're going to go back to our tried and true method of styling this one by one

with css. The first thing I'm going to adjust is this search bar.

So notice that it stretches to fill up the content when we resize the page.

To do that, we're going to go into our code,

we're going to target the search bar,

search dash bar right here. And remember to

stretch it to take up the remaining space.

We're going to set flex one and save.

Now let's make the search box similar to the design.

So I'm actually going to move this here side by side so that it's easier

to copy from.

So I'll go back into my code and the first thing I'll adjust is the height.

So let's set a height of 40 pixels.

That looks a little too much. Let's set the height to 36. See how that looks.

So I think it's still a little too much. Let's set a 2 34.

And that looks pretty good to me. Next, let's adjust this placeholder text.

So to adjust the placeholder, we actually need another sort of pseudo class.

So we're going to type dot search bar to target the search bar,

and then we're going to type colon, colon placeholder.

So this is how you target the placeholder on an input element like this.

So first, let's set the font dash family

to the one we're using for this page. If we go to general css,

we're using Reto aerial,

so we're going to set that to Roberto Aerial,

save it. So the font changed a little bit.

We're going to change the font size to make it bigger.

Font size 16 pixels. Let's see.

Okay, I think that looks a little bigger.

And the next we'll notice that on the inside of this input we have a little bit

of space, while we don't have that much space here.

So we're going to set some padding on the left of our search bar.

So let's set the padding dash left to 12 pixels,

save it. Okay, that looks okay. Let's actually set it to 10 pixels.

And then when we start typing into the search bar,

notice that the font is bigger,

but for here we still have the small font. So we can set the font size

to 16 pixels, see how that looks. Okay,

so that looks pretty close to what we have.

And next I'm going to change the border.

So I'll set the border dash width to one pixels,

the border style, we want it to be solid.

And finally I'm going to set a border dash color of gray.

Let's see how that looks. Okay,

so I can't really tell the color because of the background.

We're going to remove this light pink background because we don't need it

anymore. And that looks a little too dark.

So I'm going to pick something lighter, maybe something like this

save. And I think that's close enough to that. Next,

let's adjust the height again, because when we set the border,

it actually made it a little bit smaller.

So we'll set the height to 36 and now aligns with the buttons.

And I'm also going to create rounded corners.

So that property is border dash radius.

Let's set it to two pixels.

Now the last style we're going to adjust for this is the shadow.

So if we zoom into this search box,

there's actually a little bit of shadow in the inside while our search box does

not have that. So we'll go back into our code and we're going to add a shadow.

So we're going to use this from one of the very early lessons box dash

shadow.

And if we want a shadow on the inside of the element instead of the outside,

we just need to set inset at the beginning.

So this will put this box shadow in the inside.

Now we have our usual values, which is the horizontal position.

So let's set it to one pixels.

So it's going to be moved one pixels to the right and the vertical position,

let's set it to two pixels.

The shadow will be moved two pixels to the bottom. Let's set a blur of

maybe five pixels and we'll set the shadow color to R G

B A 0 0 0, which is black.

And then transparency set to only 0.15 to get a very

transparent black. So let's save this.

So that's way too much.

Let's actually reduce the blur to three pixels maybe and then change

this to 0.05. So we're doing a lot of trial and error with css,

which is normal. So I think this looks pretty close to our design.

I think it looks close enough for now we're going to move on and style the

buttons. So first,

let's resize this icon inside the button.

So let's give this a class of search dash icon,

save it,

and then in here in the dot search icon,

we're going to make it a little smaller. So let's set the height to 20 pixels,

see how that looks. Okay, so that looks too small. I'm going to try 25 pixels.

All right, so that size looks pretty similar.

Now you'll notice that this one is vertically aligned while ours is not.

So we can either turn the search button into a flex box or we can just do a

simpler solution.

We're going to add some spacing to the top of this icon to push it down.

So margin dash top of maybe four pixels

to push that down just a little bit. Okay, so I think that looks close enough.

Let's finish off this button. We're going to set a background color

of gray,

and then I'm going to adjust it to match that. So I'm going to pick something

like this, maybe two 40

and then save it. That looks pretty good, but now our borders are messed up.

So we're going to set the border border with of one

pixel border dash style of

solid color and border color is going to be the

same as our text box. So we can go up here and just copy that

and right there, save it. And there we go.

That looks pretty close right now.

So now we want to move this button into this input element a little bit like you

see here, so that we only have one edge to do that. Here's a little trick.

We can set some spacing on the left, some margin left,

except this time we're going to add negative spacing.

So we're going to add negative one spacing, normal margin adds space,

and it pushes the element negative margin subtracts space and pulls the element

to that side. So margin left of a negative number, we'll pull it to the left.

So let's pull it to the left by one pixel, save it,

and that looks really good.

Now we're going to make our button a little bit longer.

Let's change it to 66. Finally,

we're going to style this voice search icon first.

We notice that there's a little bit of space between these two.

So let's set a margin on the right side of the button.

So this time it's normal margin margin of

maybe eight pixels.

I think that looks pretty close. I'm actually going to set it to 10.

And then for this button, I'm first going to make it round.

So let's go into these styles of this button. And to make it round,

we just have to make the corners as round as possible.

Let's set the border radius

and I'm going to set it to 20 pixels.

So a trick here is that if you set this to half the width of the height,

it will make it round. So let's save this. And now we have a round button,

but we have a weird border.

Let's actually get rid of it because it's not in our design.

So border and none to get rid of the border.

So it's looking really close. Our icon is a little bit bigger than this one,

so we're going to target it in here.

Class equals voice dash, search dash icon,

and then NR css. We'll target that. So voice dash,

search dash icon. So for this,

let's set a height of maybe 20 pixels. See how that looks.

It's a little bit small. Let's increase it to 24.

I think that looks pretty good.

And next we're going to try to vertically align it.

We're going to add a little bit of margin on the top to push it down.

So margin dash top and four pixels.

Okay, that looks pretty good. The last thing is to change the background color.

So we're going to change the background color to let's

say gray. And then I'll pick another color.

So this time let's pick maybe 2 45

and then save. Oh, so I accidentally put it on the icon.

We actually want to put this on the entire button.

So I'm going to cut and paste this onto the button styles.

Let's save. And I think that looks pretty close.

So this color is a little bit off from this,

but I think it's okay if we look at the bigger picture.

So now we've completed the middle section and you can compare it here

to here. So we're looking really good so far.

Next we're going to finish the right section.

So I'm going to put them side by side again so it's easier for us to copy.

So the right section has three icons and an image.

So we're going to add them to our HTML first.

So let's go into the right section here.

And we're going to create an image and we're going to load this,

which is the upload icon.

So icons slash upload

dot svg, and then we'll add another one. So image.

And this one is going to be icons slash.

This one is called YouTube apps svg.

And then the last one is the notification icon, which is here.

So image element.

And we're going to load icons slash notifications

svg.

And finally we're going to create another image and we're going to load this

channel profile picture. So source.

And this one is located in a different folder.

It's in the channel pictures folder, and it's called my channel dot jpeg.

So let's save it refresh. And again,

our SVGs are massive, so let's go ahead and resize them in our css.

So first, let's add classes to all of these images.

So we're going to set this one to upload dash icon,

so upload dash icon. The next one is going to be YouTube apps icon.

So class equals YouTube dash apps dash icon.

Next one we'll do notifications dash icon.

So class equals notifications dash icon.

And lastly, we're going to name this a little bit different.

Let's give it a class and let's call this one current dash

user dash picture so it's a little more clear that this is different

and we can target it with css.

So let's go down into the right section here and we'll scroll up and we'll

first resize the icons. Let's resize the upload icon.

Let's set a height of 24 pixels and then we'll do the

YouTube apps icon that's set a height of

24 pixels. And then the notifications icon,

which is right here. Icon.

Let's set a height of this 24 pixels again

and the current user picture. So notice it's a little bit taller.

Let's target that current dash user dash picture,

and we're going to set a height of 32 pixels to make it a little bit taller.

Let's save it. And now we have the icons we're going to use.

Again, we want to align these vertically in the center.

Remember to do that we're going to scroll up to our middle section,

which is all the way up here.

We first have to turn this container into a flex box,

and then we can use online item center. So inside our H C M L,

we have to turn this into a flex box. Let's scroll down

to the right section styles here.

We're going to turn this display colon flex,

and then we're going to set align dash items colon center

to align them vertically. So let's save it. Okay,

next we want to distribute them evenly across the horizontal space.

And remember from our practice code,

that one's called justify dash content space

dash between. Let's save it.

And now these icons are space evenly across the space,

so it looks like they're a little bit too far apart from each other.

We can adjust that by adjusting the width.

So let's decrease the width to bring everything closer together to match our

design. And I actually think this,

all the icons look good enough.

The only last thing we're going to change is this picture here.

So notice it's still a square. We want to make it a circle. So as a review,

we're going to use border radius to make it a circle.

So let's set it to border radius.

And the trick we learned is half of this will make it round. So 16 pixels,

save it. And now we have a round channel profile picture. Lastly,

we're pretty much done with this so we can get rid of the blue background color.

So we'll scroll up and get rid of this.

Now I actually noticed that we have spacing to the right here in our design.

So that's one thing I missed. So let's add that right now.

So we're going to add margin right to this section of

maybe 24 pixels. Save it.

And I think that's a little too much. I can't really tell.

Let's send it to 20 just to be safe. Okay, so I'm happy with how this looks.

All right, so that's basically the content in our header.

If we look at it right now, it looks really professional.

So I know that while we were working on it, it looked a little bit weird,

it looked unfinished, but you just got to trust the process.

And at the end we have a really professional result that looks like our design.

Now there's going to be one last case I'm going to show you,

and this is a weird behavior of flex box.

So if I resize my browser and I make it smaller,

notice that these icons start to get closer to each other.

So this happens because flex Box is flexible.

When we start not having enough space, it'll start shrinking the items inside.

But if we look at our final project and we shrink the browser,

notice that this doesn't shrink and we sort of forced only the search bar to

shrink. So let's go back into our project and into our code.

And Flexbox has a special property to prevent certain items from shrinking.

So we're going to scroll down to the right section here.

And to prevent the right section from shrinking,

we're just going to set this property flex dash shrink

colon zero. So this means that no matter what happens,

we're going to keep this width and we're not going to shrink.

So zero means don't shrink if we save it.

And now you're going to see that it doesn't shrink,

but now when we resize it,

notice that the search bar doesn't actually shrink all the way like our design.

So the way to achieve this is to go into our HTML and then we're going to

go into our search bar, which is right here.

So normally search bars have a default width and we can't really see that

because we set flex to one. So it's sort of growing with a page,

but as soon as it hits that default width, it's not going to go down anymore.

So to remove that default width, we can just set width to zero,

we save it,

and now you can see that the search box will start shrinking as much as

possible. So to recap,

we set flex shrink of zero to this right section so it doesn't shrink,

and then we set a width of zero to the search bar so that it does shrink.

Here are some exercises to get yourself familiar with using Flexbox to create

flexible layouts.

Now we're going to learn the last major skill that we need to finish off our

project. We're going to learn CSS position.

So position helps us do things like keep the header at top of the page while we

scroll. It also helps us keep the sidebar at the top of the page.

And lastly,

whenever we see an element on top of another element that's using CSS position,

for example here, the video time is on top of the thumbnail,

the notification number is on top of the icon. And when I hover over this,

we have a tool tip on top of the page.

So CSS position adds another dimension to our page.

So just like the previous lessons, we're going to create a new HTML file,

just a practice position. I'm going to go into my code editor,

we're going to create a new file and let's put it right here beside the other

ones new file. Let's call this position

html. Now as always,

we're going to start with the HTML structure.

So we're going to have doc type at the top and then an

HTML element inside we have a head element

and then we have a body element.

Now we can right click and open with live server and we're

ready to begin. So first,

let's add a title so that we know what this HTML file is

for. Let's call this position practice.

Say save it, and then it should show up here.

We're going to start in the body again, and we're going to create two divs.

It's called this diviv one and another diviv Diviv two.

And I'm just going to resize this a little bit so we can see it side by side.

So just like before,

we're going to use inline styles so that our CSS is close to our HTML code.

I'm going to set a style

and then we're going to set this one to background dash color and

light blue.

And we're going to set the height and the width to 200 pixels. So height,

200 pixels and with 200 pixels.

Next we're going to set the second diviv to be the same size,

but with background color light pink. So again, we set a style

and then we set a background dash color of light pink

height of 200 pixels and width of 200

pixels.

So CSS position is just the position property.

So let's go into our first diviv and we're going to set the position property

to static And then save.

So position static is the default position.

It's the same thing as if you don't have this line at all.

Now we're going to learn a second position property that allows us to stick an

element to the top of the page like this while we scroll.

And that is called position fixed.

So we're going to create a new element at the top here and let's call this our

header. So we're going to learn how to create something that works like this.

So for this diviv, we're going to set a style

of background color,

black and a text color of white.

And now we're going to learn how to stick this to the top of the page.

So first of all, we need to be able to scroll,

and right now I don't have enough content to make the page scroll.

So what I'll do is we'll go to the body here and we're going to set a style.

And then inside the body we're going to set a style of height and something

really big, like 3000 pixels.

So we just need to make sure that we're able to scroll this page. Next,

we're going to make this header stick at the top. To do that,

we're going to use the position property,

and this time we're going to set a position of fixed.

Now when I save it and I start scrolling,

notice how the header element is sticking to the page when I scroll.

So that's how we make it stick.

So the first thing to note is that when we set position fixed like this,

it doesn't take us space on the page anymore. So before we add this,

and if I save it,

so notice that it takes up the top of the page and then these two divs up here

below this header. But when we add position fixed,

it no longer takes up that space at the top of the page because it's sort of

floating above the page now. So that's one way to think about it.

So the position property has four special properties we can use to move this

element around. The first one is called top.

The way that top works is that we can set a pixel measurement. For example,

if we set zero pixels,

this is going to make the top of our element zero pixels from the top of our

browser window here. So if I save it,

notice that the top of our element is right on the top edge of the browser

window. If I set top to 10 pixels,

the top of our element is now 10 pixels from the top of the browser window.

So top specifies how far away our element is from the top of the window,

the next property we can set is left.

So if we set left to zero pixels,

then the left side of our element will be on the left edge of our window.

If we set left to 50 pixels, for example,

now the left side of our element will be 50 pixels from the left of our window.

So left tells us how much space is between the element and the left edge of the.

So we can set this in all four directions we've seen top left.

We can also set bottom.

And right now a special feature of these properties is that if

we set it in opposite directions, the element will stretch. So for example,

if we set it to left,

and so these two are opposite directions and we set the right to 50 pixels,

notice that the element stretches.

So now this element is 50 pixels from the left of the page right here,

and it is also 50 pixels from the right of the page.

So it will stretch the element to meet these two conditions.

Same thing with top and bottom.

So if I set bottom to 100 pixels and save it,

the element will stretch so that it is 10 pixels from the top and it is 100

pixels from the bottom.

So this is how we move this element around and resize it with position fixed.

Now let's try creating the header that we see here.

So as you can see for this header, it's at the top edge of the page.

It's also on the left edge and on the right edge.

So that means that it's zero pixels from the top as a shorthand,

we can just write zero.

It's zero pixels from the left and it's zero pixels from the right.

Now for the bottom we might first try to calculate how far the bottom of this

element is from the bottom of the page.

Now that's not going to work if we resize the page,

so we need a different approach. So first,

let's save this file and go into our practice file.

So now you can see that this element is sticking to the top,

the left and the right, which is what we have in our code.

Now we have to figure out the height of this diviv. So in this case,

instead of using bottom, because remember the bottom can resize,

we want to use simply height.

So in addition to these properties,

we can simply use height and width to also resize this element.

It all depends on what situation you're in.

If you want this fixed element to resize with the page,

then you would use top left, right, and bottom.

If you just wanted to have a specific height or width and you don't want it to

resize, then you use height and width.

So here we're going to set the height to 50 pixels and we don't want it

to resize with the page. So that's exactly what we have here.

Now when we start scrolling,

you'll notice that our header sticks to the top of the page.

So that's how we create something like the YouTube header that we see here.

Now, one last problem is that if we go to our practice file,

notice that if we scroll right to the top,

the header is covering our first diviv. So we need to add some spacing at the

top to push our content down below the header.

To do that, we go into our code,

and the first thing you might think to do is to add margin to the top.

So we're going to add spacing to the top,

and let's add a little more than 50 pixels, so 60 pixels.

So if we save it and make sure you scroll up all the way to the top of the page,

you'll notice that we have 60 pixels of space at the top,

and now our content is not covered by the header.

Now this is not the best solution because if our content order changes,

for example, if I move this diviv down here,

notice that it doesn't work anymore.

So what we want instead is to always have space at the top of our page

regardless of what the content is. So if I move this to the top here

and remove margin top, I'm going to show you the proper way to do this.

So to properly handle this situation,

we need to add spacing to the body element. So let's scroll up to the body.

So we have two choices for adding space to the top of our page.

We can either use margin or we can use padding.

Generally the best practice is to use padding at the top. So we're just going to

add spacing on the inside of our webpage at the top of

60 pixels, save it and scroll all the way up.

And now we have plenty of space at the top of the page and our header is not

covering our contents.

So now that we learn position fix and how to move this element around and resize

it,

we're going to go into the project we were currently working on and we're going

to put our header and stick it to the top of the page.

So let's learn how to do that first,

I'm going to resize my windows a little bit so it's easier to work with.

I'm going to put it right here.

And then we're going to open the YouTube dot html file, which is our project.

So remember we put our CSS into separate files.

So I'm going to open the header dot CSS file,

and I'll put it on the side so you guys can see it side by side.

So just like we learned, we're going to go into the header here.

We're going to set a style of position fixed,

and remember to move this, we're going to use top, left, bottom, and right.

So top we want our header to stick to the top of the page.

We're going to set that to zero. We want our header zero pixels from

the left, so on the left edge of the page and also zero pixels from the right.

And finally, we're going to set a height. So we already have it up here,

so let's save it and see how it looks.

So the first thing we noticed is that we lost our background color.

Now the only reason we had a background color was because if we didn't have

position fixed,

this header takes space on the page and the page happens to be white.

So the header appears to be white, but now that it's floating above the page,

we'll notice that it's actually transparent. So to add our background color,

again, we just need to set the background color property.

So let's set this to white, save it,

and now we're back to where we were.

Now if we go to our project and we start scrolling,

you'll notice that our header sticks to the top while we scroll.

So that's exactly what we want. Next we have this problem where the header is

covering our content. So remember,

the way to fix this is to add padding to the top of our body.

We're going to go into our code and we're going to go into this file

general css. That's where we have styles for the body.

And then we're going to set a padding dash top of maybe

60 pixels. Let's take a look. Okay, so that looks pretty good.

Let's compare to our design.

If I scroll to the top here and just compare it a little bit,

I noticed that our videos are appearing at a higher position than our design,

so we're going to push them down a little more.

Let's set this to maybe 80 pixels.

Save it so we push them down even more.

And I think that looks close enough to our design.

So the last thing I noticed is that we're missing the border at the bottom of

our header here. So let's go ahead and add that.

So let's go back into our header css.

We're going to add a border to the bottom so we can actually add borders to one

side at a time. We don't have to add borders to all four sides. To do that,

we're going to set these same border properties we had before.

So we're going to start with border width,

but in the middle we're going to tell it a direction. So we can tell it bottom.

We're going to also tell it top left. So we have all these four directions.

In this case, we want a border at the bottom,

and we're going to set it to one pixels.

And the other border properties are the same.

So border style is going to be solid,

but we only want it at the bottom,

so it's going to be border bottom style. And then lastly, border dash,

bottom dash color. And let's set it to gray.

And I'm going to pick a lighter shade of gray.

So maybe right there, save it.

Let's compare it to our design.

It looks like it's a little darker than what we have.

I'm just going to adjust the color to match our design.

And it's not going to be perfect, but remember,

you can always inspect the design and then make it perfect. Okay,

so now if I compare it, I think that looks pretty close enough.

And now if I scroll, you notice that the header is sticking to the top,

which is exactly what we want. Next,

we're going to how to create this sidebar.

So the sidebar is just like the header, it sticks while we scroll.

So this is another example of position fixed.

We're going to go back to our practice file, and I'll resize my pages here

and I'm going to open position dot html we were practicing with.

And this time below the header, we're going to create our sidebar.

So let's create a diviv, and this diviv is going to be our sidebar.

Now for the sidebar, let's set a style.

And then inside we're going to set a background color of green this time.

So a background dash, color green,

and a text color of white so that it's easier to distinguish between all of

these different elements. Next,

we're going to stick the sidebar to our browser.

So remember to do that we're going to use position fixed.

So position fixed and save it.

And now when we scroll,

you'll notice that the sidebar is sticking to our browser while we scroll.

Lastly, we're going to put the sidebar in the right place using top left,

right height or width. So let's look at our sidebar. In our design,

we notice that the sidebar is sticking to the bottom, so we want bottom zero.

It's sticking to the left, so we want left zero.

And for the top it's actually not reaching to the top of the page,

otherwise it would cover up the header.

So there's quite a difference between the sidebar here and the top of the page.

So let's go back into our practice file and learn how to position that.

Let's start with left.

We want the sidebar to stick to the left side of the page.

So we're going to say zero pixels from the left, save it.

Now we want our sidebar to stick to the bottom of the page.

So we're going to say bottom and zero pixels from the bottom.

And finally, we want it to be at the top of the page, but not cover the header.

So let's set the top to 50 pixels.

So it's going to meet right where the header ends.

We're going to set this to 50 pixels and then save.

And finally, we want to set the width of the sidebar. So for the sidebar,

we don't want it to resize with the page,

so that's why we're going to use the width property instead of something like,

right.

So let's go back into our practice file and we're going to set the width to

maybe 72 pixels, save it.

And that looks like what we have in our design, so that's perfect.

Now we have the same problem again where our fixed element is covering our

content. So let's scroll back to the top.

We're going to add padding to our body so that these elements are not covered by

the sidebar. So in this case, we want extra space on the left side.

So I'm going to set padding dash left,

and let's set it to 80 pixels,

which is more than the sidebars with 72 pixels.

So now if we save this,

we have 80 pixels of padding on the left side of the page,

and now the sidebar is not covering our content.

So that's how we position a sidebar.

Now we're going to create the sidebar in our project here.

So let's go back into YouTube dot html,

going to resize my page so that we can see it better.

And we're going to create a sidebar on the left.

So let's go into our code and we're going to put the sidebar right below our

header. So let's scroll down below our header here,

and I'm going to create a diviv. This is going to be our sidebar,

and I'm going to give a class of sidebar

so that we can target it in our css. Now for these styles,

let's actually put them in a separate CSS file. So if we scroll up to the top,

we have CSS files for our header for our videos,

so it makes sense to split up our sidebar styles into their own file so that we

organize our code better.

We're going to go into our code editor and then go into the styles folder here.

And we're going to create a new file and we're going to call it sidebar

css. And I'm going to put it on the side like this.

Next we're going to load sidebar CSS into our html.

So we just have to do one of these again, I'm just going to copy them.

And then instead of video css, we're going to load sidebar css.

And now we're ready to style this sidebar that we just created.

So let's target the sidebar class

and we're going to set position to fixed to make it stick.

Now for the sidebar, we want it to be zero pixels from the left of our browser.

So let's set left to zero.

And we also want it to stick to the bottom of our browser, so bottom to zero.

And finally, we want it to stretch to the top,

but we don't want it to cover our header.

So let's set the top to whatever the height of our header is.

So if we go to header dot css, which is here,

we can check the height of our header is 55 pixels.

So we're going to go into our sidebar here and we're going to get the sidebar to

end 50 pixels or 55 pixels from the top.

So let's set that to 55 pixels, save it.

So with position fix,

the element is no longer on the page anymore and it doesn't have a background

color, so we just have to set that. Again, background dash color.

I'm going to set it to white, save it.

And now we have our sidebar.

The final thing is to make our sidebar as wide as our design,

which is right here.

So we're going to set the width to 72 pixels,

save it, and let's compare it to our design.

And I think it's hard to see because it's white here and it's a little bit gray

here, but I think that's close enough.

Now the next problem we have is that the sidebar is covering our content.

So as we learn,

we're going to add some padding to the left to push our content over.

So let's go into our general styles. So general css,

and we're going to style the body.

We're going to add padding to the left of our body,

and let's add padding of 80 pixels again.

And now our sidebar is no longer covering our content because we added a bunch

of padding to the left of our page.

So that's how we use position fixed to create elements that stick to the page

while we scroll, like our header and our sidebar

for now,

here's some exercises that you can do on your own to get a better understanding

of CSS position.

Now we're going to learn another position property that we can use.

Let's go into our position, practice file. And the same in our code editor.

We're going to open up position, HTML and then close all of these files.

So I'm going to resize it so that we can see it better.

So this time we're going to learn position absolute.

Let's do an example to see how it works.

So let's scroll down and we're going to create a diviv below our sidebar to

practice position. Absolute.

Let's create a diviv and then let's call this absolute.

And now we're going to set some styles on the diviv. So style equals,

and then inside here we're going to set position with a value of

absolute.

And we're also going to set a background color of red so that it's easier to

see. So background color of red, and then the text color is going to be white.

So color of white, save it.

And now we have our position, absolute element. So before we continue,

make sure we scroll all the way up to the top of our page.

Now, position absolute also takes the same values as position fixed.

So top, left, bottom and right as well as width and height,

but they behave a little bit differently. So first we're going to set left.

So let's set the left property to zero and let's save it.

And now the left side of our element is zero pixels from the left side of our

page. So this works the same way as position fixed,

and we set left to 10 pixels.

Now there will be 10 pixels between our element and the left side of our page.

Now let's try setting top. So I'm going to set the top to 10 pixels,

save it and make sure you scroll all the way up.

So you'll notice that our element is now 10 pixels from the top of the page.

So mostly these properties work the same as position fixed,

but with one key difference. For position fixed,

the elements are placed in the browser window while for position absolute the

elements are placed on the page.

Now what I mean by this is that when we scroll the browser window or

just this visible part is not moving, only the page is moving up and down.

So for position fixed, we're going to put these elements on the browser window,

which doesn't move when we scroll. So if we scroll up to the header,

if I say top and 10 pixels, this puts a header,

10 pixels from the top of the browser window, not from the top of the page,

which is constantly moving up and down. But for position absolute,

if we scroll down to there,

we're putting it 10 pixels from the top of the page,

which scrolls up and down when we move.

So that's a key difference between the two position fixed positions,

the element in the browser,

which doesn't move when we scroll and position absolute positions,

the element on the page which does move when we scroll.

So let's go back up and reset this to zero so that we

have our proper header again and do some more practice with position absolute.

So for example,

if I wanted to put this absolute element in the top right corner here on our

page, we can do something like right,

and we'll put it 10 pixels from the right and then top.

We can put it maybe 60 pixels from the top, it was 60,

save it, and we scroll all the way up,

and that's how we place an element on a precise location on our page like this.

And because it's on our page when we scroll,

the page will move up and this absolute element will move up with the page.

Now, one thing that's weird is that this element is appearing above our header,

and that's because this element was written in our code below our header.

So generally,

an element that is written below is going to appear in front of elements that

are written above it. Now,

we can actually override this if we scroll up by adding another property

called Z dash index.

So Z index determines which elements appear in front and which elements appear

behind. So the default Z index is zero.

This is the same thing as if you didn't have this at all,

but an element with a higher Z index will appear in front of elements with a

lower Z index.

So if we set the Z index of the header to one,

it's going to have a higher Z index than the absolute element which has a

default Z index of zero. If we save it,

now the header will appear in front. Just as an example,

if we scroll down and we set the Z dash index

of this absolute element and we set it to two,

now it's going to appear in front again because our Z index here is greater than

our Z index here.

So usually we set this to something like 100 so that we can have a lot of

elements in between. If our page has a lot of layers,

and usually if we don't care about the Z index,

we can just remove it and have a default of zero.

Now that we learn position absolute, where do we use this?

The truth is we don't use it like this very much.

This is not a common situation that we run into when we're creating websites.

However, position absolute has another key feature that makes it really,

really useful to demonstrate.

We're going to take this element and we're going to make a copy of it and we're

going to put it inside the sidebar. So right here.

So we're going to put a position absolute inside a position fixed.

So now when we save,

you'll notice that this element is not being placed on the page anymore.

What it's actually doing is placing this element relative to this position fixed

element. So now right of 10 pixels is actually 10 pixels.

From the right of the fixed element,

which is the sidebar top of 60 pixels is 60 pixels from the top

of the sidebar, not from the top of the page.

So whenever a position absolute is inside a position fixed element,

it's going to be placed a relative to this position fixed element.

So this is the most important feature of position absolute.

So let me show you why it's so useful.

Let's say that we wanted a close button on the top right of our sidebar.

We want to be able to close our sidebar if we want to.

I'm going to change this to an X so that it's kind of like a close button.

And then to put it in the top right of our sidebar,

we just have to set the top to zero and the right to zero.

So if I save that, now this element is in the top right,

and that's because if position absolute is inside position fixed,

top zero means zero pixels from the top of the position, fixed element,

right? Zero means zero pixels from the right of the position fixed element.

So this is how we attach elements to the corners or the sides of other

elements. If we look at our final project,

we can see that going on in our videos here.

We have the video time in the corner of our thumbnail here we have the

notification count in the top right corner of this icon.

And using position absolute,

it allows us to put elements in the corner like this.

So there's one last thing we need to learn here.

We have a position absolute inside a position, fixed element.

That's why we can put it in the corner.

But notice that this is still a position fixed element and it sticks to the

page. But in our final project, these videos are not sticking to the page,

they're scrolling with the page,

and we're still able to put stuff in the corners. So how do we achieve this?

And to do this,

we're going to learn another value for the position property called position

relative. We're going to scroll down to our two divs at the bottom.

And for our second diviv,

we're going to set the position to relative

and save it. Now, if we go back to our page,

we'll notice that nothing actually changed.

And that's how position relative works.

It's still displays the element as normal,

except if we put position absolute in here,

it will position it relative to this element instead of relative to the page.

So let's go through an example to see what I mean. If I scroll up here,

let's copy this absolute element.

Let's copy it and then paste it inside this position,

relative element, save it,

and then reformatted a bit, press tab. And if we save this,

you'll notice that we get the same effect as when we put position absolute

imposition.

Fixed right of 10 pixels now means 10

pixels from the right of the position, relative element, not 10 pixels.

From the right of the page,

top of 60 pixels means 60 pixels from the top of the position,

relative element, not 60 pixels from the top of the page.

So two things are happening here.

When position absolute is inside position relative,

this will be positioned on the element, not on the page.

So that's what we just talked about.

The second thing that happens here is that position relative causes this whole

element to display normally. So that's what we get in our final project.

Notice that these videos are displayed. Normally they scroll with the page,

but we have something in the bottom right corner.

So these are all positioned relative.

And then to put something in the bottom right corner,

we're going to put a position absolute inside.

So let's actually go through an example here. So we have our position,

relative element. We have position absolute inside.

I'm going to put this in the bottom right corner, just like our design.

So let's change this to five minutes

and pretend this is our final project.

Let's change the background color to black.

And now we're going to put this on the bottom right corner.

So let's get rid of this first.

And we're going to put this 10 pixels from the bottom of the

position, relative element. So we're going to say bottom 10 pixels.

And we're also going to put it 10 pixels from the right of this position,

relative element. So right of 10 pixels.

And that's how we position this in the corner.

And because this is positioned relative, if we scroll the page,

it acts like normal content.

So now that we learned the technique of position,

absolute inside position relative,

we're going to apply that to our project and create the video time as well as

the notification number here.

So let's go back to our project and we're going to add video times

first. So let's go to YouTube dot html.

And we're also going to open the video CSS file. I'm going to put it

down here because we're working with styles for the videos.

So first we're going to find our thumbnail, which is right here.

And now remember to put something in the corner.

We're going to need position absolute inside a position relative element.

So if we look at our code, what could be our position, relative element?

Well, it can't really be the image element because image elements aren't really

containers. We can't put something inside it.

So what we could use is this thumbnail, row element.

This could be our relative element.

And then the video time will be the absolute element inside of here.

So first, let's create our video time. We're going to create a diviv,

and let's give it a class of video dash time.

And then inside we're going to put a video time.

So let's go to our final project and we're going to copy one of these. So 14,

20. Then inside I'm going to put 1420.

Let's save it and go back. So right now is just a normal diviv.

Let's go to our CSS file. And we're going to style this.

Let's scroll all the way down,

and we're going to target video dash time class.

And let's set the background dash color to black and the text color

to white. So just like our final project.

So now we're ready to position it properly. We're going to need position,

absolute inside position relative. So first,

let's set the position relative on here.

We're going to scroll up to thumbnail row, which is right here.

We're going to set position relative.

And remember, position relative doesn't really change anything.

Everything appears normal. That's one of the benefits of it.

And if we scroll down, we're going to change this to position

absolute and now top, bottom, left,

and will be placed inside our position relative element.

So if we save it, and now if we want to put it in the bottom right corner,

we just have to say bottom zero pixels from the bottom,

and also zero pixels from the right.

So let's set the position from the bottom to maybe 10 pixels. Save it,

and let's set the position from the right side to maybe five pixels. Save it.

Okay, let's change this to maybe eight pixels.

So I think that looks pretty good,

and if we compare it to our final design, it's in the right position.

So that's how we put an element in the corner of another element.

We need a position absolute inside a position relative.

So finally, let's style this one by one until it matches our design.

I'm actually going to move this to the bottom here so that it's easier to

compare.

The first thing we're going to do is to change the font.

So we're going to set font dash family to

reto aerial,

like the rest of our fonts.

And next, let's change the font size.

Let's change it to font dash size of maybe 12 pixels.

That looks pretty good. Let's make it a little bit bolder.

Let's change the font dash weight to 500.

And remember a font weight of 400 is normal,

700 is bold and 500 is semi bold. Let's save that.

That looks pretty good. And next we need spacing on the inside of this element.

So that's padding.

So let's add some padding on the left of

maybe two pixels.

And same for padding on the right two pixels and then padding on

the top of four pixels,

and then padding on the bottom of four pixels. Save.

That looks pretty good. Let's add some more padding on the left and right.

Changes to four pixels and four pixels. Okay,

so I'm pretty happy with that. Next,

we're going to make our corner rounded kind of like this.

So to do that we're going to use border radius, chain Z,

border dash radius to two pixels, save it.

And I think that looks pretty close to our design. And there we go.

We created the video time in the bottom right corner of the thumbnail.

Now to give you guys a bit more practice,

I'm going to get you to add the video time to all of our other videos.

So inside our html,

you're going to add this video time to the next video here and all the

videos in the H T M L.

So take some time to complete that and then we'll continue the lesson.

So now that we have the video time for all of our videos,

we're going to run into another problem. If we start scrolling up on this page,

you'll notice that the thumbnails appear above our header.

But another thing is that the other content like this text and the channel image

will appear below our header. So what exactly is going on?

So we mentioned this briefly in the practice file. If an element like this

video preview is written below another element like the header up

here, the element that is written below will appear in front.

That's what's happening here. We have a header,

and then below that we have the thumbnail,

which is going to appear on top of the header. However,

what I didn't mention is that this rule doesn't apply to position static or

these elements with the default position. Position,

static will always appear at the back.

So that's why you see that these always appear at the back as soon as we set it

to something that's not position static like position relative.

The rules of which element was written first start to apply.

So in this case, because if we scroll up,

the thumbnail row is positioned relative and it's written below the header in

the code. It's going to appear on top of the header,

which is what we see and remember, to fix this,

we need to set a property of Z index. Let's go into our header c s s

file. We're going to open this file here.

And then inside the header,

we need to set a Z dash index to make the

header appear above the thumbnails.

So let's set a Z index of 100 so that we have room if we want to put stuff

between these two. Now, if I save it,

the header has a Z index of 100.

The thumbnail row has a default Z index of zero. 100 is greater than zero.

That means the header will appear on top of all the thumbnails.

So if we go back and we start scrolling, you'll notice that we're now all good.

The last thing we'll learn is how to create this notification count in the top

right corner of this icon. So let's go into our html,

so YouTube dot html and find where the code for this notification is.

So if we scroll down to the header and then scroll down to the right side,

that's this code here, notification icons.

So I'm going to resize my windows so we can see it properly here.

And now we want to put a notification number in the top right corner.

So remember, like we've been doing,

we need a position absolute inside a position relative.

So if we look at our html, what could we use as our position relative element?

So it can't really be this image because we can't put stuff inside an image

element. So one option is this diviv up here,

but a better option is actually to wrap this image element

inside a diviv. So we're going to create a div here,

and we're going to put this image inside this diviv.

So remember that the diviv just creates a box around whatever's inside.

So it's not going to change the appearance of this image. However,

by creating this diviv, we can now make this position relative,

and that's going to help us add stuff to the top right corner.

So let's give this diviv a class so that we can style it later.

Let's call it notifications. Dash,

icon dash container.

And inside we're going to have our notification count.

Let's create a diviv for our notification count. Let's give it a count of three.

Alexa at this class equals notifications with an

S dash count.

And now we're ready to style this and put it in the corner.

So let's go into header dot css.

I'm going to put it on the side so we can see it more clearly.

And now to start off,

let's scroll down to where we have our notification code.

So let's scroll all the way down and we'll find it right here.

And now remember, we're going to have position relative,

and then inside we're going to have position absolute.

So let's style the dot notifications

dash icon dash container

and set this to position relative.

And then the notifications count, dashed count,

and we'll set to position absolute.

So we want to put this in the top right corner.

So let's set the top to zero pixels and the right

to zero pixels and to see it better. Let's set a background color.

So background dash color of red,

and a text color of white.

And now if we save that, it's sort of in the top right corner,

but it's a little bit too big.

So we're going to style it just like our design here.

So I'm going to move this up here actually so that we have a better reference.

And now we're going to style it by first changing the font.

Let's change the font dash family to

reto aerial,

like before Next, we'll change the font size.

So this is pretty small. Let's change the font dash size to maybe 10 pixels.

Okay, should be a little bit bigger. Let's set it to 12 pixels.

That looks pretty good. And let's add some spacing on the inside of the element.

Let's add some padding left of maybe four pixels,

padding right of four pixels,

padding top of two,

and padding dash bottom of two pixels.

And remember to make this a circle, we're going to give it round corners.

So let's set the border dash radius to 10 pixels.

So it looks like we're a little bit too tall here.

We're going to stretch out the sides by adding more padding to the sides.

Let's change this to maybe five pixels left and right.

Save it. Okay, maybe six pixels left and right.

Save it. Okay, so that looks like a pretty good circle. Next,

we'll change the background color to something that looks like that.

So I'm just going to pick something like this, maybe

save. Perfect.

And I'm going to change the font size down just a little bit more because this

is pretty small. Let's change this to 11, save that,

and let's change the padding left and the right because

it'll, it's a little bit long on the horizontal side.

And now we have a circle again.

So notice that we put this element in the top right corner using these two

properties, but it's not enough. We actually want it out even more.

So we're already at the top edge of our position. Relative container,

how can we go even higher? So the trick here is to use negative numbers.

So now this will be positioned beyond the top edge of our container.

So if I save it here,

this is now five pixels beyond the top edge of our relative container.

Same thing with right, if we set it to negative five pixels here,

it's now five pixels beyond the right edge. So I'm just going to adjust the

valleys here so that it matches our design.

So let's set the top to something like negative two. Okay,

so I think that looks pretty close to our design and I'm pretty happy with it.

So in this lesson, we learned CSS position,

which is one of the most important skills in css.

It allows us to create elements like this header and sidebar that stick to the

page while we scroll, and it allows us to add elements on top of other elements.

For example,

the video time on top of the thumbnail and the notification count on top of the

notification icon. So with that,

we learned all the major skills that we need in H T M L and CSS to complete

our project. In the last lesson,

we're going to create all the other features that we're missing,

including the sidebar, the tooltip,

and making our current project look like the final design. Here

in this lesson, we're going to finish our final project.

We're going to create the sidebar,

we'll resize our video so that it looks like our design here. And lastly,

we're going to create the tooltip. When we hover over these icons,

we'll start off with the sidebar.

So I'm going to rearrange my windows here so that it's a little easier to copy.

So I put the design on the left.

I'm going to put our current sidebar on the right here,

and I'll resize my windows so we can see it better.

And now we're ready to begin.

So let's open our code editor and we're going to open YouTube dot

html. And then we're going to scroll down to the sidebar code,

which is right here.

So let's take a look at the design of this sidebar. Our reference design.

If I hover over it, you can see that is just a bunch of boxes.

And inside each box we have an icon, some text,

and they're centered horizontally and vertically.

So we're going to start step by step. We're first going to create the box.

Let's go into our code. And instead of this text,

we're going to create six boxes.

We're going to use a diviv to create each box.

Let's give this diviv a class of sidebar

dash link.

And I'm going to copy and paste this six times

4, 5, 6. Next,

we're going to style these so that they have the same size as these boxes.

I'm going to go into our css.

So let's go into sidebar css.

I'm going to put this on the right side here so we can see it better.

And now we're ready to style these.

Let's target the class sidebar link.

And for each of these, let's give it a background color so that we can see them.

And let's set it to light gray.

And we'll also give them a height because without any content in the divs,

they have a height of zero.

So let's set a height of 50 pixels and

let's save it and let's see how that looks. Okay,

so it's hard to tell the difference between them.

So let's add some spacing at the bottom of each div so that we can differentiate

them.

I'm going to add margin dash bottom of one

pixel, save it. Okay, so from this,

it looks like our boxes are a little bit too short,

so we're going to make them taller. Let's try a height of maybe 75.

Okay, so I think that's pretty close.

We can get rid of this margin at the bottom and actually increase this to

76 so that we compensate for the margin that we removed.

And next, when we look at the design, these boxes are usually white,

but when we hover over them, they turn gray.

So instead of having this background color gray here,

we're just going to set the background color when we hover over this.

So let's set a hover style dot sidebar,

dash link hover.

And when we hover, we're going to set the background color to

light and gray. Let's save it.

And now when we hover, it's light gray,

but our design is actually a lot lighter than that.

So I'm going to change the color here.

I'm going to pick something a little lighter than this, maybe something here.

Save that and check it out. And yep,

I think that looks pretty close.

Next we're going to add the content in each of these boxes.

So first we actually need to download all of these icons.

So we did the before for these icons. And just a reminder to do that,

we're going to right click and inspect.

So you'll see that this actually covers up the sidebar.

What we can do is click these three dots in the top right and then we can move

the dev tools to another side of the webpage.

So I'm going to move it to the right side here.

And now we can see the full sidebar.

Then we're going to click this in the top left,

click one of these icons and you'll get the URL to download them here.

So hover over this URL and then click this.

And now we can control S,

and I'll save it in the folder that contains my code in the icons

folder.

So make sure you do this for all six of these icons and I'll see you back after

you're done. All right,

so once we've downloaded all of the icons from the sidebar here,

we're going to add them to our html.

So let's go into each of these and add our icons

inside this first diviv, we're going to add an image element,

and we're going to set a source attribute.

And we're going to load the icon icons slash

home dot svg because this is the home icon.

And let's save it. And now we have our icon. It's a little bit too big,

but we're going to resize it after. For now,

let's copy this and add the icons for all of these other

boxes. So we're going to add for this one,

we're going to add the explore icon. So explore svg,

and for this one is the subscriptions. And then for this one,

it's originals.

And then for this one it's YouTube dash music.

And the last one is library. So I'm going to go down here,

change this to library. Perfect.

Next, we're going to make these icons smaller.

So usually we would set a class on these images so

that we can style them with css.

But for this lesson I'm going to show you another wave that we can target these

images.

So let's go into our sidebar styles and we're going to learn a new CSS

technique.

So we already learned that this text before the brackets here,

this tells a computer which elements we're styling. In this case,

the dot means we're targeting a class and we're styling all elements that have

the class sidebar link, which are these elements.

So this bit of text is called a CSS selector,

and there's actually a lot of different selectors that we can use in css.

So we already learned the class name selector,

which looks like this and starts with a dot.

And we learned the element name selector,

which just starts with the elements name.

Another thing we can do with CSS is to combine selectors together. For example,

if we said dot sidebar,

dash link and then wrote a comma down here,

we can add another selector.

So let's say we also want to target header.

So now all of the styles inside the brackets will target all elements with the

sidebar link class and all elements with the header class.

This is an example of a more advanced selector.

Another selector we can use is instead of a comma,

we can use a space and then type another selector

like image. So when we have a space between these two,

this means that we're targeting all images inside all sidebar links.

So we're going to target these images inside sidebar links only.

We're not going to target all images on the page.

So let's style these images and make them smaller. We're going to set a height

and let's try 24 pixels. Let's see how that looks. Okay,

so I think that looks pretty close to what we have in the design. Next,

we're going to center these horizontally and vertically.

And finally add the text.

So to center something vertically is actually challenging In css,

the best way to do it is to use a flexbox.

If we look into our code editor and open our Flexbox example,

so flexbox html,

and then we right click and open with live server,

we have a bunch of examples of using flexbox.

In the last example here we're doing vertical alignment.

If we scroll down to our example in our html,

we have this property called align items center.

So this vertically centers our content here.

We also have an example of horizontal centering.

If we scroll up to that example, which is this one,

we have the property justified content center.

So using justified content center and Align item center,

we can put it both horizontally and vertically centered.

So let's go back into our project and use a flex box to center these.

We're going to go back to our CSS and we're going to make each of

these sidebar links a flex box.

So let's set the display property to flex,

and we're going to set justify dash content

to center. So this will center horizontally, let's save it.

And now they're horizontally centered.

And then align dash items center for

vertical center. So this is coming along great.

Next we're going to add the text. So underneath each of these,

let's add a diviv. So for this first one,

it's going to be called home. And I'm just going to copy these

and replace it with each of these texts. So explore

this one is subscriptions,

originals,

YouTube,

music and library.

Now let's start styling this text a little bit.

I'm going to use this advanced CSS selector. Again,

we're going to go into the sidebar link class,

and then we're going to target all the divs inside sidebar link.

So we're going to target divs.

So this is not going to target all divs on the page,

only the divs inside sidebar link.

Let's change the font here first.

So we'll set the font dash family to reto

aerial like before, and let's make the text smaller. Next,

we're going to set the font dash size to maybe 12 pixels.

Okay, maybe 10 pixels, save it.

And now the next problem we have is that our elements are appearing beside each

other, not on top of each other. So why is this happening?

So remember that we can set a property called flex dash direction

colon row.

If we go into our flex box example, Flexbox html,

let we scroll all the way to the top. This was the first thing that we learned.

Display flex and flex direction row.

So if we open this in our browser and we scroll to the first example,

flex direction row causes our elements to be displayed horizontally.

So notice that these two are divs, but they're displayed next to each other,

not on top of each other. Now to change this, we're actually going to go back

and we're going to use flex direction column.

So where flex direction row displays them horizontally,

flex direction column displays our elements vertically. So if we save it

now it's displaying our elements one on top of each other.

So this is another direction that we can use for our flex boxes. By default,

flex boxes are flex direction row, so they will appear horizontally,

but we can set flex direction column when we don't want that behavior.

So for flex direction column, these two properties are actually switched.

So if I remove both of them first and I first use

justify dash content colon center,

Save it.

Justify content now affects the vertical direction instead of the

horizontal direction with flex direction row.

And if I use align dash items,

center align items now affects the horizontal direction.

So for flex direction column, these two are reversed.

It's a little bit confusing, but the more they use flex box,

the more you'll get used to it. All right, so we're almost done.

We're just going to add some space between these two to add some space.

Let's add some margin bottom to the image.

So margin dash bottom,

maybe four pixels, save it.

Okay, I think that looks pretty close to me,

and it looks like our elements are a little bit too tall.

So I'm actually going to scroll up and adjust the height here to maybe 74.

Save it. And okay, that looks pretty good.

So one last thing with the sidebar is that I notice in our design it kind of

covers the header while ours does not. So to change that,

remember we can change the Z dash index to be

higher than whatever the header is. So if we go into our header styles,

header dot css, notice that the Z index is 100.

So we're going to change our Z index to bigger than that.

So 200 save it.

And now our sidebar is covering our header. Next,

I want to move all of these icons down a little bit more so that it's aligned.

So to do that, I'm going to add some padding or spacing to the top of this.

So we're going to add some padding

dash top of maybe five pixels. Let's see how that looks.

Okay, so that looks perfect.

And actually one last thing is I'm going to make the cursor a pointer when we

hover her over it.

So let's go into our sidebar link and we'll set the cursor

to a pointer, save it.

And now this looks good to go.

Next we're going to resize these videos to match the design.

So I'm going to move this back into one window

and I'm going to resize this so that we have three videos in each row and now

we can properly switch back and forth to compare.

So as I switch back and forth between these,

you can see that there's a size difference between the videos.

So we're going to fix that. So for our website,

I notice that the left edge here can be moved to the right a little more.

So if we look at our design, it's more to the right,

go back to our current project design more to the right.

So to move this to the right, we're actually using padding.

So we had to increase our padding on the left side of the page.

Let's go back into our code and we're going to find the padding,

which is in general css.

So remember we added padding to the left side of the body that's pushing these

elements over here.

So let's increase the padding to maybe

96,

save it and let's compare it to the design. All right,

so I think that looks perfect.

And we also have padding on the right while our website does not.

So let's actually also add padding dash right

of 24 pixels.

Now if we save that there and compare it to our design,

our videos are now exactly the right size. So that looks great to me.

The next thing we're going to tweak is if we look at our design,

the background color here is a light gray while our background color is white.

So we're going to make the background color of our entire page a shade of gray

like this.

So let's go into our CSS and in our body styles in

general css,

let's set the background dash color to

light gray.

And I'm going to hover over this and select a lighter color,

maybe 2 48. Save it.

And let's compare it to our design.

So this is our website and this is the design. I think that looks pretty close.

And the last few details I want to adjust is this part.

So if I look at my design and I compare it to my website,

it looks like our channel pictures are a little bit too big.

So if I look at the design here, so we could make them a little smaller.

So let's go into our code and we're going to go into the video

styles. Let's open video css.

We're going to find the profile picture. So if I scroll down,

so this image here is the channel picture. It has a class of profile picture.

We're going to decrease the width to maybe 36,

save it compared to our design.

So I think that's the right size. Next,

I'm going to adjust some of these spacing here. So if I compare to the design,

there's actually a little bit less spacing here, then our website.

So I'm going to decrease that. So for our website,

we're adding some margin bottom to the thumbnail.

The thumbnail row.

I'm going to decrease this to maybe eight pixels. Let's see how that looks.

And then compared to our design, so I'm pretty happy with that.

And finally, I'm going to adjust the spacing between these two.

So for our video title, if we go into our code

And scroll up here, it has a margin bottom of 12.

I'm going to decrease it a little bit to 10,

save it and compare it. Okay,

so I think that's good enough. It doesn't have to be perfect,

it's a little bit off,

but I think that our current website here looks really good to me. Anyways,

the final thing we're going to do in this lesson is we're going to create these

tooltip when we hover over these icons.

So before we learn how to make these appear, when we hover over,

let's just create these tooltip and place them below each icon.

So let's go into our website and we're going to add some tooltip to these.

So we'll go into our code and I'm going to resize the windows so we can see

better. So we're going to go into our html,

we're going to scroll up to our header.

And let's first find the search icon here,

which is in the middle section, and then the search button here.

So to create the tooltip,

we're actually going to use the position property that we learned earlier.

So remember that we use position to put this number in the top right corner.

We're going to use position to put a tool tip below the element right here.

So let's first add a tool tip inside the button.

So we're going to create a diviv

and let's call this search, let's save it.

And now that's our tool tip.

And now we need to position this tool tip relative to our button.

So remember from the previous lesson,

we need position absolute inside position relative.

So let's first add those position properties.

So we're going to go into the header CSS file because we're working with the

header. So let's open that up

and I'm going to move it to the right side here.

And now we're going to scroll down until we find our search button.

So I'm going to scroll, scroll, scroll, and it's right here.

So we're going to set this search button, which is our container to position

Colon relative save it,

and nothing happens because that's how position relative works.

And now the magic comes when we set this to position absolute.

So we're actually going to set a class here so that we can target it a little

easier. We're going to call this tool tip

and we're going to use that advanced CSS selector we learned earlier.

So we're going to target search dash button first,

and then we're going to type a space.

And then we're going to type tool tip.

So this means that we're targeting the dot tool tip class,

not on the entire page, but only inside the search button.

So now we don't have to come up with a unique name for this specific tool tip.

So if we save it, we're going to set this to position

absolute. And now we have an absolute element inside a relative element.

So if we save that, now we can start positioning this.

Let's give a background color so that we can see it better.

So background dash color of maybe gray.

And let's add the text color to white. So color colon white.

Let's give it some padding on the inside,

some padding top of maybe four pixels,

padding dash bottom,

four pixels padding left four pixels

and padding right for pixels, save it.

And let's actually increase the padding on the left and right to eight.

See how that looks. Okay, I'm pretty happy with that.

And now I'm going to set some rounded corners so we don't have to exactly match

our design. We can make it close enough so we can set some rounded corners,

border dash radius of four pixels.

It's a little too much for me set to two pixels.

And I'm also going to make the font a little bit smaller.

So I'm going to set the font dash size to 12 pixels.

Save it. I think that looks pretty good to me.

Next we're going to use the property's top,

bottom left and right to position this within the relative element.

So for our cases, let's start with bottom zero.

So this means that the bottom of our tooltip will be at the bottom of the

button. If I save this, that's exactly what we have.

Now to move it even further to the bottom, we're going to use negative pixels.

So let's set negative 20. Save it.

Okay, so I think that's looking pretty good.

Let's increase it a little bit more, increase it to 30 pixels, save it.

Okay, so I'm happy with that position.

Now we're going to learn how to make this tooltip appear when we hover over this

button.

So the trick here is we're going to set the opacity or how see through

the tooltip is to zero, which is completely invisible.

And then when we hover over this button, we're going to set the opacity to one.

So how do we actually change this when we hover over the button?

So we're actually going to use a combination of this advanced CSS

and pseudo classes which are like hover.

So first we're going to target the search dash button class,

and we're going to add a pseudo class colon hover.

And now we're going to type another selector. We're going to type dot tool tip,

and we're going to set some styles here.

So what this does is that we're going to target the tool tips only when we're

hovering over this search button.

So up here notice that we're targeting the tool tips inside the search button,

regardless of whether if we're hovering over it or not. In this case,

we're going to target all tooltip inside the search button,

but only when we hover over it. So when we hover over it,

we can set the tooltip opacity

To one.

So this is a neat trick that you can do to create tooltip like this.

So if we go into our webpage when I'm not hovering over the button,

you'll notice that the opacity is zero. But when I'm hovering over the button,

this tooltip will have an opacity of one which looks like this.

And now because we're changing the opacity, we can set a transition.

So let's set a transition. We need to tell that what to transition,

which is opacity and how long the transition will take.

Let's say 0.15 seconds, save it.

And when we hover over this, now we get our tooltip.

Now the last thing I want to show you is if we hover over the actual tooltip,

you'll notice that because it's inside this button,

when we hover over the tooltip with our mouse,

it also counts as hovering over the button.

We can fix this by disabling hovers on the tooltip and only allow hovers on the

button. So to disable the hover on this tooltip,

we're going to use another CSS property called pointer

Events none.

This means that when our mouse hovers over the tooltip,

it's not going to do anything.

So that's how we create these tooltip on our webpage.

Let's do the same thing with this voice search button.

We're going to go into our HTML and we're just going to copy this tool tip

and just move it down here into the voice search button, just like that.

And let's change the text to search with your voice,

Save it. And now remember to position this,

we're going to have position absolute inside position relative.

So let's turn this to position relative first.

I'm actually going to make it easier for us.

I'm going to first target the search dash button,

and I'm going to put this inside here.

And I'm also going to target with a comma,

the voice search button. So this one,

now this code is going to apply to both of these,

so it saves us a little bit of coding. Same thing down here.

We're going to apply all of these styles to the search button,

tooltip and comma,

the voice search button dot tooltip.

So using these advanced CSS selectors can save us a lot of code.

We're going to scroll down all the way here to and use a comma

and set this to the voice

search button. So make sure you don't have a comma at the end there. Save it.

Now when I hover over this,

you'll notice that it doesn't really work because the text is sort of wrapping

around.

I'm going to fix that by setting this property white space,

no wrap, save it.

And this will prevent the text from wrapping around.

Now the last thing I want to do is do center this tool tip with the button.

To do this,

we can use a flex box because remember with flex box we can center horizontally

and vertically. In this case, we want to center horizontally.

So we're going to make we're scroll up and we're going to make these buttons

flex boxes.

So let's set display flex. By default,

it's flex direction row.

So justify content is going to center horizontally.

So justify content center, save it.

So now if we hover over our buttons,

you'll notice that the tooltip are aligned horizontally,

but you also notice that our icons are not vertically aligned very well. So

let's go back into our code and we're going to align them in the center with

align dash items center, save it.

So that didn't seem to work, but if we scroll down into our code,

so way earlier in the course,

we actually added margin top to the search icon as well as

the voice search icon.

So we just need to get rid of this margin top and let the flex box handle the

vertical centering. So if we save that,

now the icons are perfectly centered and if we hover over,

we have a centered tooltip.

The tooltips for these icons are the same thing,

except if we scroll down, we currently just have an image.

We're going to need a container like this that's going to act as our position

relative container. So let's create a diviv

that's going to contain our upload icon.

Let's cut this and then paste it in here.

Let's give a class of upload dash

icon dash container.

And then inside this container we're going to have our tool tip.

So let's copy this and then paste it in here.

And let's call this, let's look at our design create.

So our tooltip is going to have the text create.

Next.

We're going to change this to position relative and position absolute inside.

So let's scroll up.

And we already have this code here that sets to position relative and centers

everything. And we're going to add to this the upload icon,

container dot upload, dash icon, dash container,

save it.

And then we need a position absolute on this tool tip. So again,

we can just add it in here so we don't have to copy all this code again with a

comma dot upload dash icon, dash container,

tooltip save it.

And lastly, we're going to scroll down and add it to here.

So that appears when we hover.

So let's set dot upload dash icon,

container and dot. When we hover over it,

the tooltip is going to have opacity of one.

Let's save it and hover over. All right, so that looks pretty good,

but let's change the font here.

So let's go into this code which sets our tooltip

styles,

and let's set the font dash family to reto

aerial. Like before. If we save it and we hover over it,

now we have a nice looking tooltip on our icons.

So that's how we create these tooltip.

When we hover over these icons and these buttons,

creating tooltip for these two other icons are the same thing,

and I'm going to leave it as an exercise for you to do on your own.

So in this lesson, we finished up our final project.

We created the sidebar resize, our videos created the tooltip,

and now if we compare it to our design,

our project looks pretty much perfect and ready to go.

So here's some exercises you can try on your own to wrap up everything that we

learned in this course.

In the previous lesson, we finished our final project, which is this.

In this lesson I'm going to show you some more useful features of c s s.

We're going to start off with responsive design.

If we go to our reference design here,

and I'm going to zoom out a little bit so you can see if I make the page

smaller, you'll notice that we now have two videos in each row.

If I make the page bigger, we have four videos.

So notice that at every screen size,

the layout adjusts so that the website looks good.

So that's the idea of responsive design,

making the website look as good as possible on every screen size. Now,

if we make this a little bit more narrow and we switch to our current project,

you'll notice that all of our content is sort of squished.

So we're going to learn how to implement responsive design into our project.

Let's go into our code and we're going to open the file

called video dot css, which controls the video grid styles.

Let's open that.

And now inside we're going to adjust our video grid so that when the screen

size is small, we only have two videos per row. And when the screen size is big,

we have more than three videos per row.

So let's go into our code and we're going to scroll down and find the video

grid styles. So notice that for these styles,

we set three columns of equal size.

Now to make this responsive, we're going to use something called a media query.

So to create a media query, we're going to type at media,

and then we're going to give it a screen size.

So we're going to say max dash with colon,

maybe 600 pixels.

And then we're going to type open squiggly bracket,

and then close quickly bracket.

So the way this works is that we're going to have a bunch of CSS in here,

and this CSS will only activate if the screen size is 600

pixels or less. That's what this max width means. So for example,

let's target the video grid class inside here

and let's set the grid dash template,

dash columns to one fr, one Fr.

That means from a screen size of zero to 600 pixels,

we're only going to have two columns.

So we save it and we start to resize.

Notice that once we get to 600 pixels, we now have two columns in our grid.

Now to figure out how big our screen size is,

we can right click and inspect,

and I'm going to click these three dots and move it back down to the bottom like

this. And now when we resize,

you should see the screen size at the top right of the page.

So it's really up to us to pick a screen size where we're going to go from three

columns to two.

So I think even at this screen size,

maybe at seven 50, it looks a little bit squished.

So I'm going to increase this to 750 pixels.

Let's save it. And now once we get to seven 50,

we're going to have two videos in each row and it's not going to be as squished

anymore.

So that's the basics of how to create responsive designs using these media

queries. Let's do another example.

We're going to have four videos per row when our screen size gets really big.

So let's set another at media. At media.

And for this time we're going to set a minimum width of

maybe a thousand pixels.

And then inside here we're going to copy this and paste it here.

We're going to change grid template columns to four columns. So one f fr,

one fr.

Now if we save it and we resize the browser to 1000

pixels, it's going to become four videos per row.

Now you might need to press command or control minus to make the webpage smaller

to see this,

but basically the way this works is that once the screen size hits a thousand

pixels, this will activate and we have four columns instead of three.

So the last example is that we can actually combine these two,

so we can set at media and we can set the

min dash width to 7 51 pixels

and the max dash width to

9 99 pixels.

So this will cover the space between these two measurements here.

So let's actually put this in the middle.

So from zero pixels to a max of seven 50, we're going to have these styles.

And then from 7 51 to 9 99,

we're going to have these styles. So we're going to set this to three columns,

and then from a thousand and up, we're going to have four columns.

So this is the basics of how to create a responsive design like this.

You just have to write a lot of media queries. All right,

so that's the basics of responsive design.

We're going to go back to our webpages.

I'm just going to zoom back in and we'll learn the next feature of css.

So let's go to our project here and open our code.

And let's scroll down to this dial the video time.

So the next feature we're going to learn is sort of like CSS shortcuts.

So instead of setting padding on the left,

right top and bottom separately like this,

we can actually use a property called padding,

which is sort of like a shortcut for all four of these.

So if we set the padding to four pixels,

this is the same as setting padding on all four sides.

So we don't need this code anymore.

So it makes it a little cleaner for our code to use these shorthand properties.

So another thing we can do with this is we can have two values,

let's say four pixels and 10 pixels. Save it.

So this first value is going to be the vertical padding. So padding top,

padding bottom, and the second value is horizontal padding, padding,

left and padding right?

The next thing we can do is have four directions.

So 20 pixels and 30 pixels. Let's see how that looks.

So this is how we can set padding in all four directions using one line of css.

This first value is the padding top second value is the padding, right?

Third value is padding bottom, and fourth is padding left.

You can think of this as first you start from the top and then you work your way

clockwise around. So that's what these four values mean.

Another shorthand property is margin,

and this is a substitute for margin, left margin,

right margin top and margin bottom.

So this margin shorthand property works the same way as padding.

If we have one value, this is all four directions. If we have two values,

this first value is the vertical direction. Second is a horizontal direction,

and if we have four values of margin,

this is the top right bottom and left.

So these are just examples.

We're going to move our styles back to four pixels of padding on every side,

and we're going to look at one final shorthand property, which is the border.

So let's go into our header CSS file and find these styles for this search

bar. So we're going to scroll up until we find our search bar,

which is here. And notice for our borders, we always set a width,

a border style, and a border color.

So instead of setting these styles separately,

we can use a shorthand called border. So for border,

we can set one pixel. This is going to be the width.

We can set another value of solid. This is going to be the border style,

and we can set the third value of color.

And so this one line of CSS can replace these three.

If we delete that, then we save.

You can see that everything still appears normally,

and that's because this border property is a shorthand for the other three.

The next thing we're going to learn is called inheritance.

Let's go to our YouTube dot HTML file and we're going to scroll

down to the video grid, which is right here.

So inheritance means that for certain CSS properties,

if we set the property on the outer element,

it will get passed down to the inner elements like these. Let's do an example.

We're going to set a property on the video grid.

We're going to go to the video CSS file,

and we're going to find the video grid styles, which is all of these.

We're going to set it on this style here.

So we're going to set it for all screen sizes. Let's add a style.

We're going to make the text underlined. To do that,

we're going to use this property text dash decoration

underline. Now if I save this,

you'll see that even though I set text decoration, underline on the video grid,

all of the paragraphs inside have been underlined.

So this is called inheritance.

If we set this style on the outer element, which is the video grid,

it gets passed down to all the inner elements,

which are the paragraphs here. However,

not all properties are affected by inheritance. For example,

if we go back to the video CSS file,

and we're going to add a border this time.

So let's add a border and we're going to make it two pixels wide,

a solid color, and let's just make it red.

And if I save that, you'll see that the video grid has a border around it,

but this border is not passed down to the inner elements here.

So inheritance mostly just works with text properties like text decoration,

underlying color, font, weight, and font family.

It doesn't affect things like border padding or margin,

so that's what inheritance means. Certain properties,

mostly text properties will get passed down from the outer element to the

inner elements. Now, this can save us some code. For example,

if we go back to the video dot CSS file and we scroll down,

you can see that the video time uses a style called font family reto aerial.

So this changes the font of our text,

and instead of putting it on the video time,

we're just going to put it on the entire grid,

and then it will get inherited by all the elements inside,

which includes the video time.

So I can scroll up to the video grid and I can set the font

dash family up here so I can set Roto

Ariel. If I save this,

you'll see that nothing changed with the video time because this style is

being inherited from the video grid. Now,

we can actually take this even further. If we go to the YouTube dot html file,

you'll see that this video grid is actually contained within the entire

body. So all of our elements on the page are contained within the body.

So if we want to set a sort of default textile on the entire page,

we can actually just put everything in the body and that'll save us a lot of

code. So let's actually go back to the video CSS file.

We're going to remove this and save it.

You'll see that the video time now goes back to the default font,

which is times New Roman,

and these paragraphs actually use a different set of styles.

So if we go to the file called General css,

we set the font family for these paragraphs using just a p

selector here. If we remove this

and save it,

you'll see that it goes back to the default font of times new enrollment.

Now we're going to set this style on the body so that it gets inherited

to the entire webpage inside.

So we'll go to General css and we're going to set

font dash family to Reto

aerial to take advantage of inheritance. If I save this,

you'll see that all of the fonts went back to robo,

and that's because we set it on the body and all of our elements are inside the

body. So this style gets inherited to the inner elements.

So using this,

we can save more code if we go to our sidebar and our header.

If I go to the sidebar first,

you'll notice that we're also using font family roboto aerial.

So we can simply get rid of this because this style is being inherited from the

body.

And if I go to the header dot css,

you'll notice that we're also using Fond family Reto AO in a bunch of places.

So we can just get rid of all of these and take advantage of

inheritance to save us some code.

All right, so there's one last thing about inheritance that I want to show you.

We're going to go back to our video CSS file, which is right here.

And now let's get rid of these properties that we are using to test with

Save it. This time we're going to go to General css.

We're going to set another style in the body,

and we're going to set the property color red to

change the text color of the entire page to red. If I save it,

you'll see that a lot of the text is now red,

like these sidebar and the video titles,

but not all of the text has been turned to red. So why is this happening?

We mentioned this in one of our earlier lessons.

CSS follows a sort of priority when you set the same style on the same

element.

So for these video author and video stats paragraphs,

first we set a color of red from the body, so that gets inherited down.

But then if we look at the CSS for these in video CSS and

go into the video author, which is right here,

you can see that we also set the color to this gray color. So the

color is being set both by these styles and by these styles that are inherited

from the body. However,

this style is more specific because it only targets the video author and the

video stats while the style in the body targets the entire page.

So that's why this style has higher priority than the inherited style.

This is called CSS specificity. Generally,

if we set these same style on the same elements like we have in this situation,

the style that is more specific, for example,

this style targets only the video author and video stats,

the style that is more specific has higher priority,

and it will override a more general style, which is what we have here.

So using inheritance and specificity,

we're able to both set a default style on the outer element,

and then if we need to,

we can go to the inner element and then override that style.

Now in this course,

we didn't go through a lot of detail about specificity and its rules,

and that's because we were mostly focused on building out this project,

but you can find all the details about specificity in the HTML and CSS reference

below the video. For now,

let's go back into general CSS and let's get rid of this

practice style that we were using, and now we're ready to move on.

Next, we're going to learn about semantic elements.

If we go back to our YouTube dot html file,

so we learned about a bunch of elements like the diviv, the image,

and the button. There's also another set of elements called semantic elements.

So for example, header is a semantic element,

and another example is the nav element.

So these elements actually work the same way as a diviv,

except they have a special meaning to screen readers, search engines,

and any other kind of device or robot that is reading our webpage.

So to have the structure of our webpage recognized correctly in a screen reader,

we should actually replace some of our divs with semantic elements.

So for example, we can remove this diviv and replace it with a header.

So it works the same way as a diviv, except it's for the robots.

So let's scroll down. We're going to turn this into a header,

and then we can also scroll down to our sidebar,

and we're going to change this to a nav element because

the sidebar on the real YouTube should help us navigate through the website.

Another semantic element we can use is called main.

So this should contain the main contents of your website,

which for us is this part.

We're going to move everything inside here To the main

element. So I think it's this

I might be missing. Okay, so move all of that into Maine,

and let's scroll back up. Now,

inside Maine, we're going to have a video grid,

but we might also have other things below the video grid.

So the video grid is known as a section of our main content.

Let's save that and scroll all the way down to the end of our video grid

and remove this with section.

So that's how Symantec elements work. They're just the same as divs,

except they give a special meaning and structure to our page for search engines

and screen readers. Now,

the final thing I want to show you in this course is how to write comments.

So comments are pieces of code that the computer ignores,

but you can read yourself to remind you of information or to tell yourself

what's going on in the code. So for example,

if we scroll up to our header,

maybe I forgot how we created this tool tip.

So we can actually add a comment in the code that reminds us.

So let's add a comment here.

We're going to type less than exclamation dash, dash,

and we're going to end the comment with dash greater than like this.

So this is a comment. If I save the webpage,

you'll see that this text appears nowhere on the webpage,

and that's because the computer basically ignores comments.

So we can add comments like put position,

absolute inside position relative to remind us that we

need to put a position absolute inside a position relative to create this

tool tip in css. We also have comments.

So for example, if we go here,

we can write a comment by writing slash star and ending it with

star slash. Now, everything in between here is a comment.

So we can say this style below will be

inherited. So as you can see comments,

add extra information into our code without affecting our webpage.

So it's a really useful tool when you're working on a team to document how your

code works. And now, for everything in this course, if you ever forget,

remember that you can always Google it. For example, if I go to Google,

I can search things like CSS rounded corners,

and it will give us the border radius property.

I can also search for something like css, text Don't wrap,

and it will give us the white space property and the valley white

space, no wrap. So this is how you learn from here.

You take the techniques that we learn in this course,

such as the [inaudible] technique, using grid, flexbox and position,

and then you try to recreate things that you see on the internet.

And if you ever forget, you can Google and get the exact code that you need.

So now that we learned all the major skills that we need to build complex

websites like YouTube,

here are some challenge exercises that you can do to create other popular

websites on your own.

Thanks so much for taking this course with me.

I hope you now realize that creating websites is not as intimidating as it

seems.

We just need to create each part of the website step by step using the major

features of HTML and CSS that we learned in this course. Now,

where do we go from here as the next step?

I recommend learning the JavaScript programming language.

JavaScript is what makes our webpage interactive. For example,

if we click something, type some text or drag something onto the page,

JavaScript is what updates our page.

So it's a natural progression from HTML and css. Now,

if you want to learn JavaScript,

I have a full JavaScript course for absolute beginners that you can find by

clicking on this link. Again, thanks so much. For watching.

My name is Simon from Super simple.dev.

I want to make a tech career possible for anyone. If you have any comments,

questions, or feedback, please leave them down in the comments section below.

If you want to support this channel and you want more courses like this,

please click the subscribe button. Thanks so much, and I'll see you in the next.
