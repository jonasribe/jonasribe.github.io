---

layout: post
title: What I wish I knew when I started building my first app

---

*I want to write this post while the feeling of being clueless of Cocoa programming is still fresh in memory. Like any other creative endevour, starting out is the difficult part, but if I were to start out today here are some of the things **I** would want to know:*

## Start with a real, but simple problem

- Playing with sample code without trying to implement something new, might teach you a couple of lessons, but if you want to learn to code you need to have a specific goal.
- If you do not know what problem to solve, look at your everyday tasks and find the ones that are repetitive and can be broken down into steps. 
- Scratching your own itch is going to give you more creative freedom as you understand the product and are better able to test your code.
- Start with the simplest idea you can come up with: an aeropress timer or a [nursing clock](http://5by5.tv/buildanalyze/78) are both good ideas, but also taken. The smaller the problem, the better. Expanding is easy, simplifying is hard.
- Build on the work of others, but do not solve a problem that others have already solved better than you ever can.


## GitHub, GitHub, GitHub: 

- [GitHub](http://github.com) can easily be integrated with Xcode for versioning. Versioning is essential for deleting code with a good consciousness and deleting code is essential for getting better.
- GitHub Issues is great for collaborating, creating todo-lists (making [deadlines](http://jonasribe.com/2014/03/05/Shipping-delays/)) and planning features for future versions of your app.
- GitHub pages are great for hosting your app's website using [Jekyll](http://jekyllrb.com).
- GitHub wikis are great for maintaining documentation for your app or just yourself.
- There are loads of great Cocoa code on GitHub.
- If you are a student, you get 5 private repositories for free.

## StackOverflow > books: 

- There are many great books on programming, but they were not what I needed to get started.
- To get into Cocoa, I had to find my problem, break it into smaller problems and look for solutions to each.
- [StackOverflow](http://stackoverflow.com/) contain solutions with example code to loads of specific problem. Many of the solutions are good, some are outdated and some just bad, but they can all be what you need to figure out your own solution.
- StackOverflow is great for getting a grip of the diversity of solutions different people come up with to the same problem.
- Reading books when you are beginning to grasp the scope of your problems, might be a good idea.

## Find your heritage!

- Whenever you inherit code from Apple, look up method definitions (cmd-click on method-names in Xcode), not only will it tell you the intent of the developer, it will likely point you towards other useful methods.
- Use [Dash](http://kapeli.com/dash) for searching through documentation.
- If you are implementing something you think should be a part of the Cocoa library, it probably is, but you might have been looking in the wrong place.

## Think through your solutions, before you implement them

- When you are starting to get the hang of Objective-C, try to visualize your solutions before implementing them.
- Limiting the number of paths through your program, will make your solutions more robust and easier to implement.
- Test your code and handle exceptions well. This is more important than any feature you add. I ended up deleting loads of code because I was too focused on adding features, when in reality my app was becoming less and less usable.