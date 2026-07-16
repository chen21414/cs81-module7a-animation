What part of the code was most confusing and why?

The most confusing part was understanding how the remainder operator worked in index % frames.length. I learned that it keeps the frame position within the the frames array. When the index becomes equal to the length of the array, the result returns to zero, allowing the animation to begin again.

And also setInterval() does not work like a normal for loop. Instead of completing all iterations immediately, it schedules the callback function to run repeatedly after an amount of time.

How does the animation help visualize asynchronous behavior?

The animation makes asynchronous behavior easier to understand because the browser does not freeze while waiting for the next frame. 


What did you change or improve, and what effect did it have?

I added a progress percentage, changing background colors, and a restart button. The progress percentage helps the user to see how soon the animation is about to complete. The changing background colors make the animation more easy to see.

