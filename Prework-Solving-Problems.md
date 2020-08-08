# Solving Problems  
[Table of Contents](README.md)  
[Link to Article](https://simpleprogrammer.com/solving-problems-breaking-it-down/)  

### A simple set of Steps

1. Read the problem completely twice.
2. Solve the problem manually with 3 sets of sample data.  
3. Opitmize the manual steps.  
4. Write the manual steps as comments or pseudo-code.  
5. Replace the comments or pseudo-code with real code.  
6. Optimize the real code.  

#### 1. Read the problem completely twice
- This is step one and the most import step. Before doing anything, read the problem entirely, pause, then read it a second time. If it is still unclear maybe a 3rd or 4th time is required. Try to identify the problem domain, what exactly are they asking and keep note or write it down.  

#### 2. Solve the problem manually with 3 sets of sample data.  
- 9/10 times you can't skip straigt to automated code. That leaves you doing it manually first then optimizing second. Get it to work, see your proof of life even if the code is ugly. Over time you will begin to code with syntactic sugar skills and will not have to worry about ugly code. Seek out your edge cases for the problem. Try and think of things that will break or challenge your code, and use those to make your code edge proof. Note you may not find them all right away, that is what testing is for and debugging.  
- Red, Green, Refactor:  
    - Red: Its broken, does not work.  
    - Green: Its works.  
    - Refactor: Make it pretty, optimize it.  

#### 3. Optimize the manual steps.  
- Often skipped, and it is noticeable by other devs. This is the refactor stage, where you can re read your manual steps and see if it can be done better. Think of other ways, try and identify places of repeated code. Repeated code, is usually a sign for place of refactoring, (dev's are lazy we hate to repeat ourselves, so they say....)  

#### 4. Write the manual steps as comments or pseudo-code.  
- Comments comments comments. When you are traversing through a problem domain, keep track of whats happening with comments. It can help trouble shoot and debug a non working solution, especially if you have a comment on each line to "walk yourself through your code". Now Do you need comments on every line? Maybe. Most likely not but if the code is complex, it can help to have key points commented. Pseudo-code, use it if you get stuck, you know the start of the problem, and the end but not the mid, write some pseudo for the mid and research how to solve that piece. Dont get stuck on one piece for to long.  

#### 5. Replace the comments or pseudo-code with real code.  
- Comments and pseudo code are your guidelines to the real code. They can define your algorithm, and give you the steps you need to reach your desired output. As you read your comments write the real code, and either remove the comment, or change it to something more meaningful it that comment should stay for other devs. Just don't leave personal comments, as they were only there for you, and you are done with them.  

#### 6. Optimize the real code.  
- Yay! If you are here, you have a working solution and things are going well. You are done! Just kidding, this is often skipped in lab or school assignments, go back and re read your code, clean up comments, see if you can make it more efficient. Ensure your syntax is correct, indenting, spacing, spelling, meaningful variable names, etc. 