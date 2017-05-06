# Week of 5.1.17 - 5.7.17

## May 5, 2017 - Friday

### TIL 

I learned a lot. Over the past couple days trying to understand the issues with my recipe box, and why it hasn't been working how I want it to, I became much more proficient with the debugger when using React. I also learned that the Chrome Dev Tools has a dark theme 😯. Who knew? It's much easier on the eyes. 

### What did I like?

I liked setting up my original idea where I could flip between an edit view and a recipe view. I liked that I was able to rather easily figure out how to expand the recipe view contents. However that leads nicely to my next section.

### What didn't I like?

Believe me, I'm grateful to feel like I finally made some forward progress with this recipe box, but I still have some issues with it that I am not loving.

I have a rather hacky Add Recipe box section. I hid a form to make it work the way it does now. I'm sure I can do better than that, but I'm going to figure that out later. Also, I am experiencing issues with the edit view and recipe view. If I click edit on one of them, it switches **all** of them to edit view. Same for when I expand a recipe. If I click to expand one of them, it expands **all** of them.

Ultimately, I feel like these will be somewhat easy to fix. I hope it will be easier than the last issue I ran in to. 

## May 4, 2017 - Thursday

### TIL

I learned how to use the spread operator a little better. I located the problem with the faulty function I was talking about yesterday. So that's great news. I realized I was only returning part of the object, and that's why I was getting errors. The bad news: It didn't fix it much!

I'm starting to feel somewhat at a loss. It's actually at a point where I might be better off stepping away from the project for a day or two. Work on some smaller things to get my confidence back up. I'm so wracked by this one little thing!

Honestly, the solution is likely just doing some hiding on the DOM. The edit mode I have no _works_. I'm just ripping the component off the DOM. I should be swapping out whether it's hidden or not. It should always **be** there. Just **not** visible. 

Well, that'll be what I learned for today and what I can go in to tomorrow with: Swap some css classes out that hide displaying of the elements. 

Although, my edit component is still broke and triples when you edit the value in it... Well, something else to deal with.

### What did I like?

Hard to say what I liked. I did enjoy learning how to properly use the spread operator. That was a plus.

### What didn't I like?

How frustrating this supposedly simple Recipe Box has become. 🤔

**Link to work:**

[Recipe Box](https://github.com/rickMcGavin/recipe-box)


## May 3, 2017 - Wednesday

### TIL

What I learned today was actually rather fun and interesting. I need a modal for my Recipe Box app that will appear when the user tries to edit a recipe so the data can be changed. I referenced [Stephen Grider's Udemy Course](https://www.udemy.com/react-redux/) for this one. He teaches a really interesting way to build a modal. It seems kind of like a run around, but it makes sense, and you learn a little more about React and DOM manipulation.

### What did I like?

I rather enjoyed building the Modal. I can keep it plain and simple like that.

### What didn't I like?

I did not like that after I went through the trouble with the modal, I still wasn't able to update the data in my form. I think I cut Wes Bos's lesson on updating data a little short, and here I am. Guess what's worse? I think that was the problem all along. I think I could have kept my switching out edit and view mode component this whole time! It seems to be my function that updates the data upon editing that's broken. 😣 

In a way that may be good news. Once I figure out how to build this damn thing, I can possibly remove the modal, and switch it back to the way I wanted all along. 

**One more TIL:** I really should have learned my lesson and built it the way I knew would work _then_ play around with it making it look a little differently or function a little differently. I'm pretty sure I came across this realization 1-2 days ago, and almost immediately broke it and coded my way in to a mess again. 

I'll figure it out tomorrow. Once I just get over this edit mode bump, it should be smooth sailing.

**Link to work:**

[Recipe Box](https://github.com/rickMcGavin/recipe-box)


## May 2, 2017 - Tuesday

### TIL 

I focused solely on my recipe box app. I utilized Wes's React course to learn how to delete each recipe component. Then I moved on to learn how to update the state and display the data. 

### What did I like?

I liked being able to leverage a tutorial I had already used to build a personal project. It made me think about learning, and some of the realizations I came across recently. I realized I fell in to the trap of 'thinking' I learned something by following along on a tutorial. That's not quite how it works. You need to struggle with the concepts to really learn them. You need to apply them to your own thing. I think I'm going to start taking that approach as I continue with my tutorials. I will do a personal project sort of in tandem. Or maybe immediately follow the tutorial project up with my own personal project that pushes what I learned further.

### What didn't I like?

I did not like that I still cannot seem to figure out how to swap an edit form out with a view 'form' with this recipe box and update it with new content. I thought I had it figured all out, and I had everything set up just right except that swapping the view seems to make it lose the data. React Tools say the node is deleted. I'm going to simply try a different approach. The same one I see most people take. Using a modal to drop in a form that will update the given recipe.

I really wanted to wrap this up today, but I did learn a lot through this entire process of not being able to swap my components out. It would probably work just by hiding the display or even transforming it off screen now that I think of it. I think I'll stick with the modal though. I have other more interesting apps I really want to get to. 

**Link to work:**

[Recipe Box](https://github.com/rickMcGavin/recipe-box)

## May 1, 2017 - Monday

### TIL

I finished Wes Bos's Redux tutorial. I'm starting to gain a better understanding of Redux, but the learning is essentially too passive. I'm realizing to really effectively learn something, you need to apply it. 

This lack of application to my own project is likely why I've managed to take Stephen Grider's and Wes Bos's redux courses without fully knowing how to build an app using redux myself. 

What I definitely did start to understand better is how to pass state up and down between components. For example, with the recipe box app that I'm building. I was able to create state in my App overall that holds the recipes, which is also where I created the method to add a singular recipe to the state. By passing the method down to my recipe form via props, I was able to call the method through props, and update my state on the whole App. 

It's fairly simple once you realize it, but it can be kind of elusive. 

### What Did I Like?

I liked making real progress today on my recipe box app. I felt so stuck, and largely that was because I was confusing myself and getting hung up. I was trying to answer too many unknowns at once. I was trying to make it so you could edit each recipe, and it would switch the same field you were editing and update it. Well, it was just too much. I hadn't really solved just how to add all the information from the form to the output as it was. Forget about the other stuff that makes it complex.

### What Didn't I Like?

This ties in to the above. I didn't like that I let myself get hung up by trying to do too much. There was a simple path forward, and that was separating the form from the output to proceed. I'm confident, I can actually figure out how to do it the way I want it later. I needed to get to a point of making forward progress. I need to remember this in the future.

**Link to work:**

[Recipe Box](https://github.com/rickMcGavin/recipe-box)