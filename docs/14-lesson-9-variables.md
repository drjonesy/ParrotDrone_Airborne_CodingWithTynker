[<<](13-lesson-8-fly-in-a-circle.md)  [HOME](https://github.com/drjonesy/ParrotDrone_Airborne_CodingWithTynker) 
# Lesson 9: Variables

## Watch on YouTube

[![Play Video](images/12-vid-github-img.png)](https://www.youtube.com/watch?v=N9hTL7zcH5I&index=14&list=PLyCwPGjh8kDzoPi_4_G_BlavE3nlbkBCd)

## or Read...

### What is a variable? 
> A variable is a block that contains a value. For now, we are just going to be using variables to hold numbers.

In our last lesson, we made the Drone fly in a Circle. 

Let’s look at the code.

![](images/14-L9-step1.png)

Could you imagine if we had it 10 times or more. We would have type in the same number over and over. If we wanted to change that number just by one, we would have to do it again and again. That’s too much work.

An easier way is make a variable and have it equal the number 2.

In the Navigation on the left find the *Functions Menu*

![](images/14-L9-step2.png)

In the function menu create a **New Variable**

![](images/14-L9-step3.png)

When you click the button a pop-up will open. 

![](images/14-L9-step4.png)

Give the variable the name (num). *Uncheck Global Variable* if it is checked.

![](images/14-L9-step5.png)

Your new variable block **num** has been created. It can be found in the function menu between **hardware_drone_maxaltitute** and **set __ of select actor to 0**

![](images/14-L9-step6.png)

Next, find the block that looks like the following…

![](images/14-L9-step7.png)

Attach this block between on **start** and **take off**

![](images/14-L9-step8.png)

Drag a copy of the **num** variable onto **select variable** and change the two value to **2**

![](images/14-L9-step9.png)

![](images/14-L9-step10.png)

Last step, drag a copy of the **num** over the **repeat** number replacing the number value. Drag a second copy over the number **2** on the **forward for 2 seconds’** block.

![](images/14-L9-step11.png)

The code completed. 

![](images/14-L9-step11.png)

![](images/06-L01-playBtn.png)

And press the **Play Button**

> After you run the code. Try changing the **num** value from 2 to 4.5 or something else to see the effects.

