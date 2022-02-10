## DAY 3 

### Lab
1. [Writing a custom function](https://editor.p5js.org/lee.inhye/sketches/IKpkfKgDT)
2. [conditionals and boolean](https://editor.p5js.org/lee.inhye/sketches/a4mTQrMUG)
3. [basic array functions](https://editor.p5js.org/lee.inhye/sketches/oMOe6WCH5)
4. [array.forEach() - Iteration](https://editor.p5js.org/lee.inhye/sketches/MoTuUP4mK)
5. [drawing with array, color(), lerpColor()](https://editor.p5js.org/lee.inhye/sketches/N7N9gwFCE)
6. [set the drawing mode with push pop / translate](https://editor.p5js.org/lee.inhye/sketches/B3a3izUGr)
7. [preload() - import new fontface](https://editor.p5js.org/lee.inhye/sketches/fmZqIOboI)
8. Sol Lewitt: [Logic to Visuals](https://www.youtube.com/watch?v=qIHi8FOtW0Q)

### In-Class Resource
1. [Whiteboard at Miroboard](https://miro.com/app/board/uXjVOOHyf34=/)

### Additional Learning Resources for Javascript in General
1. [Eloquent Javascript](https://eloquentjavascript.net/) - All chapters are available online for us to read. Really well written book about javascript concepts in general. 
2. [Mozilla Reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements) - Explanation + Testground
3. [W3Schools](https://www.w3schools.com/js/) - Explanation + Testground

### SMALL ASSIGNMENT 3 (Your Sketch on Paper - Legend Explanation Due: 8AM Day 4) 
(Work in Progress is fine)
#### Create a Visualiization made of Points, Lines and Planes about Contrasting Concepts. Create a legend to describe how to read your Visualization
1. Concept Examples (Our Variables Set)
- Happy - Sad, Moving - Static, Equilibrium - Chaos, Low - High, Hot - Cold, Hungry - Full, Rich - Poor
- They can have multiple values in between and it can be represented with numerical values
- (ex: overjoyed (5) - happy (4) - neutral (3) - sad (2) - depressed (1) )
- Yes, you can have your own Variables ex) Light - Dark
2. Set up **your own logic** to visually express these concepts ex) Equilibrium, Chaos
*  "Equilibrium" will be shown with lines that have same orientation and same size for the stroke thickness, 
* "Chaos" - Lines will have all different orientations and different thicknesses 
* Slightly different concept but [this](http://inhyelee.com/studio/face-clock-2019/) was my attempt to visualize 4 time variables (hour, minute, second, am/pm): 1) Setting the Logic -> Apply the Logic to variables 
3. Start with a sketch on a paper
4. When you are successful at visualizing one concept, create another one with different concepts ex) Happy, Sad
5. Now, combine two sets of concepts and see if you can create a drawing that can show multiple variable sets together.
- (Happy, Sad) X (Equilibrium, Chaos) => Happy Equilibrium, Sad Equilibrium, Happy Chaos, Sad Chaos
6. Your final drawing will have all your logics combined together
7. Create a legend in your drawing that desribes your logic - This will involve the use of text
8. Jot down your questions that may have occured while you are working on it (either technical or creative) 

### Other Rules to Consider When Code
1. The canvas can be as big as you want. Let's make it > 600, 600 - createCanvas
2. Use a variety of 2d primitive shapes  - point, line, rect, ellipse, circle, arc....)
3. Set the right drawing mode for your shapes - ex: rectMode..
4. Experiment with colors - colorMode(), fill(), stroke(), color(), lerpColor(), color Array
5. If you are just making a static drawing, you only work in setup(), If you have an element that needs animation or color change, you can also utilize draw()
6. Use an array with loop (for loop/forEach) when you see fit
7. Try setting the drawing mode with push()/pop() and displace objects using translate()
8. Import typefaces when necessary in preload()
9. Share your web links with the class 
