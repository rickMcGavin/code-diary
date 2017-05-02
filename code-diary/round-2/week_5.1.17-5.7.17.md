# Week of 5.1.17 - 5.7.17

### May 1, 2017 - Monday

#### TIL

I finished Wes Bos's Redux tutorial. I'm starting to gain a better understanding of Redux, but the learning is essentially too passive. I'm realizing to really effectively learn something, you need to apply it. 

This lack of application to my own project is likely why I've managed to take Stephen Grider's and Wes Bos's redux courses without fully knowing how to build an app using redux myself. 

What I definitely did start to understand better is how to pass state up and down between components. For example, with the recipe box app that I'm building. I was able to create state in my App overall that holds the recipes, which is also where I created the method to add a singular recipe to the state. By passing the method down to my recipe form via props, I was able to call the method through props, and update my state on the whole App. 

It's fairly simple once you realize it, but it can be kind of elusive. 

#### What Did I Like?

I liked making real progress today on my recipe box app. I felt so stuck, and largely that was because I was confusing myself and getting hung up. I was trying to answer too many unknowns at once. I was trying to make it so you could edit each recipe, and it would switch the same field you were editing and update it. Well, it was just too much. I hadn't really solved just how to add all the information from the form to the output as it was. Forget about the other stuff that makes it complex.

#### What Didn't I Like?

This ties in to the above. I didn't like that I let myself get hung up by trying to do too much. There was a simple path forward, and that was separating the form from the output to proceed. I'm confident, I can actually figure out how to do it the way I want it later. I needed to get to a point of making forward progress. I need to remember this in the future.

**Link to work:**

[Recipe Box](https://github.com/rickMcGavin/recipe-box)