So in this project, we're going to build a little application that shows you the key code and the code
for any key on your keyboard.

So if I come to the page here, it says, Press any key to get the key code.

I'm going to hit L and it'll show me the actual key, which is L, the key code which is 76 and the

code which is key L If I hit a if I hit one, we get 49 digit one.

If I hit tab, we get tab nine is the key code.

So I mean, this is going to be really simple, but it can be useful if you need to get the code for

something.

I just want to show you if I search for JavaScript key codes.

The first result here is is the application that this is based off of.

So if I hit a key, it gives me the code.

Key code also gives you the the which property which is deprecated.

And I also want to mention that key code.

So this one right here is actually deprecated.

So if we look at the MD Docs, you'll see that this is deprecated and it's recommended to use code,

which we're also showing and it says this property is useful when you want to handle keys based on their

physical positions on an input device rather than the characters associated with those keys common in

games and stuff like that.

All right.

So I mean, this key code does still work.

If it doesn't, if you're watching this in the future, then you can just simply get rid of this box

and just display the code.

Okay.

So let's get started with the HTML and CSS.

So basically what we're going to do first is just create the three boxes.

We're just going to put it directly in the HTML later on that will be replaced with JavaScript because

when we come to the page, we only want to see that one box.

And then as soon as we hit a key, we'll see the three with the three values, the key, the key code

and the code.

So let's start here by just changing the title here to say just say event key codes.

And then let's see, we're going to have a rapper div here with the ID of Insert.

And in here we're going to have some classes, some dibs with the class of key, which is basically

just the box, the border, the background color and so on.

So this will be let's just say it's the a key that we hit.

This will be dynamic later on.

We'll add this with the JavaScript.

But for now I'm just going to hard code the letter A and have a small tag here.

And we'll just give this a label of event key because that's what it is on the event object.

It's going to be the key value.

And then under that div we'll have another class of key.

And this is going to be the key code which for a is 65.

So I'm just going to hard code that in there and let's say this is the event dot key code and then we'll

have another class of key.

And this is going to be the code which in this case would be key a and inside small tags here we'll

say event dot code and then we'll have one final div with the class of key.

And this is just going to be like the welcome box.

It'll say press any key to get the key code and code.

We'll just say to get the key code.

All right.

So that should be it for the HTML.

Pretty simple.

Let's jump into the stylesheet and the styling is not going to be too bad either.

I just want to use a different font, so I'm going to say CSS question mark family and let's set that

to Muli and we'll set that on the body here and I change the font also on the body.

I'm going to add a background color of e13 times and let's set we can get rid of the Flex Direction

column and I just want to add a text aligned center here.

So text align center and then all we really need to style is the key class and then the small tags inside.

So for key, let's give this a border.

So the border will be one pixel solid and it'll be hexadecimal nine, nine, nine.

And then I'm going to give it a slightly lighter background color of Tripoli and then let's add a box

shadow, just a very slight shadow.

I'm going to do one one pixel for both the horizontal and vertical offset and three pixels for the blur

and then for the color.

Be a black 000 for red, green, blue and 0.1 for alpha.

So just a very slight shadow on the right and bottom.

So let's set I'm going to set the display actually to an inline flex.

So they're going to be side by side.

And then let's set align items to center and let's set the font size to be bigger.

I'm going to set that to 20 pixels and let's set the padding of this of each 1 to 20 pixels and let's

set the I'm actually going to set the flex direction to column and then let's set the margin.

We'll break them apart a little bit.

So let's do ten pixels margin.

And let's see.

What else do you want to do here?

Let's set the font weight to bold.

So I'll go right here and say font weight.

Set that to bold.

What else do we want to do here?

Is that the correct font?

Doesn't look like it.

No, it's not.

So right here.

We should have an ampersand.

There we go.

And then let's set a min width here for each box as well to 150.

All right, so now we'll do the small tags.

Actually, one more thing I want to do is position this relative, because the small tags inside of

the key class are going to be positioned absolute.

So when you position something absolute in case if you want to position it inside this container, then

you would make that position relative.

So let's take the key class and small tags inside of it and let's position that absolute.

As soon as I do that, it's going to it's going to get put here.

But I actually want to move it up here.

So let's set the top value to a negative.

So -25, 24 pixels because I want to bring it out of that box and I'll set the left value to zero.

But I do want it in the middle.

So I'm going to set text, align to center and also set the width to 100%.

That'll put it in the middle.

Let's add or let's change the color to five, five, five and I want it smaller.

So let's set the font size to 14 pixels.

That and I think we should be good.

Yeah.

So that looks okay.

So in the next video, we want to give this some functionality where we don't even show these three

boxes until we actually hit a key.

And then obviously whatever key we hit, this data in here is going to be different.
