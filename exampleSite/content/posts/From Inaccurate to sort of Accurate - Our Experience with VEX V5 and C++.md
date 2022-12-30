+++
title = "From Inaccurate to sort of Accurate: Our Experience with VEX V5 and C++"
author = "Florian"
date = 2022-12-14T05:00:00Z
description = ""
categories = ["Vex Robotics", "Programming", "Robot", "Competition"]
type = "post"
+++

![Banner](../../images/banner/road-to-turnament.svg)


It's been a while since my last update, but I have a couple updates to share! Most importantly, we completed the build of robot (picture below).

![](../../images/post/bot.jpg)

Since completing the build, I have spent most of my time programming the autonomous section. I decided to learn C++ for this task, as it is the language with the most documentation related to VexCode v5. The code for our autonomous routine at our first competition was written without the usage of an inertial sensor. This lack of sensor integration resulted in a bit of inaccuracy and the use of arbitrary-looking values in the code.

For our second competition, we switched over to using the smartdrive using the inertial sensor. Around that time, we also got a optical sensor, which enabled me to write two short functions that automatically turned the roller to the desired color, without using hardcoded values. 

Our autonomous routine was quite basic - it drove up to the roller, turned it, and then made a shot at the high goal using the two preloaded disks. Of those two disks, usually at least one landed successfully.

In competition number two, we ranked quite well with place 21 and there fore qualifying. We even mhad one draw with 58 to 58 points, which was quite rare. 

After the competition, we decided to completely rebuild our robot. We are now switching over to a six-motor drive with a catapult, even though I initially objected to that idea, due to a good flywheel working better with its higher range and single shot capabilities.

Overall, I am pretty satisfied with the progress we've made and can't wait to see how our new robot performs in future competitions.

You can find our Videos of or matches below:

---

### Scrims

{{< rawhtml >}} 
<video width=100% controls >
    <source src="../../videos/gord-trousdell/scrims1.mp4" type="video/mp4">
    [Video Player Error]  
</video>
{{< /rawhtml >}}

{{< rawhtml >}} 
<video width=100% controls >
    <source src="../../videos/gord-trousdell/scrims2.mp4" type="video/mp4">
    [Video Player Error]  
</video>
{{< /rawhtml >}}

{{< rawhtml >}} 
<video width=100% controls >
    <source src="../../videos/gord-trousdell/scrims3.mp4" type="video/mp4">
    [Video Player Error]  
</video>
{{< /rawhtml >}}

### Skills Run

Our skills runs were a bit demotivating at first, since we started out with a driver skills only resulting in 33 points, which we beat later with 48. Combined with the 33 points from our programming skills this still only resulted in a score of 81, still resulting in place 28.

{{< rawhtml >}} 

<video width=100% controls >
    <source src="../../videos/gord-trousdell/skills1.mp4" type="video/mp4">
    [Video Player Error]  
</video>

{{< /rawhtml >}}

{{< rawhtml >}} 

<video width=100% controls >
    <source src="../../videos/gord-trousdell/skills2.mp4" type="video/mp4">
    [Video Player Error]  
</video>

{{< /rawhtml >}}

{{< rawhtml >}} 

<video width=100% controls >
    <source src="../../videos/gord-trousdell/skills3.mp4" type="video/mp4">
    [Video Player Error]  
</video>

{{< /rawhtml >}}
{{< rawhtml >}} 

<video width=100% controls >
    <source src="../../videos/gord-trousdell/skills4.mp4" type="video/mp4">
    [Video Player Error]  
</video>

{{< /rawhtml >}}

### The Qualifiers

**Match 1 - Won**

Our first match wasn't really anything special, resulting in us winning with a score of 64 to 28.

{{< rawhtml >}} 

<video width=100% controls >
    <source src="../../videos/gord-trousdell/match1.mp4" type="video/mp4">
    [Video Player Error]  
</video>

{{< /rawhtml >}}

**Match 2 - Tie**

Match two was a bit special: we managed to tie! This was mostly thanks to our teammate that while only being a push bot still managed to push enough disks in the low goal to achieve a tie of 58 to 58.

{{< rawhtml >}} 

<video width=100% controls >
    <source src="../../videos/gord-trousdell/match2.mp4" type="video/mp4">
    [Video Player Error]  
</video>

{{< /rawhtml >}}

**Match 3 - Lost**

During Match 3 one of our opponents managed to push us out of the arena, due to its shotty construction. This pretty much disabled us for the rest of the match. On top of that we were paired up with a push bot against two shooting robots making a loss inevitable. This resulted in a score of 88 to 19.

{{< rawhtml >}} 

<video width=100% controls >
    <source src="../../videos/gord-trousdell/match3.mp4" type="video/mp4">
    [Video Player Error]  
</video>
{{< /rawhtml >}}

**Match 4 - Won**

This match was as expected mostly decided by the rollers, since our opponents didn't have any shooting capability. Fortunately our teammate managed to get us 3 out of 4 rollers in the end, winning us the match 93 to 25.

{{< rawhtml >}} 
<video width=100% controls >
    <source src="../../videos/gord-trousdell/match4.mp4" type="video/mp4">
    [Video Player Error]  
</video>
{{< /rawhtml >}}

**Match 5 - Lost**

Match 5 was once again decided by the rollers. Our teammate couldn't shoot and wasn't able to make up for it with their driving skills, loosing us the match with 66 to 74, even though we had more disks in the high goal.

{{< rawhtml >}} 
<video width=100% controls >
    <source src="../../videos/gord-trousdell/match5.mp4" type="video/mp4">
    [Video Player Error]  
</video>
{{< /rawhtml >}}

**Match 6 - Won**

In Match 6 we were paired up with another robotics team from our class. Knowing each other quite well we let 98549R score in the high goal, while we defended our rollers. Fortunately 98549R had expansion, therefore winning us the match 90 to 48.

{{< rawhtml >}} 
<video width=100% controls >
    <source src="../../videos/gord-trousdell/match6.mp4" type="video/mp4">
    [Video Player Error]  
</video>
{{< /rawhtml >}}

### The playoffs 

In match number 1 in the playoffs we teamed up with 10012T, with which we competed in match number 4, since we got along with them quite well and them having a decent robot & driving. Unfortunately we were competing against a team with a great auto and a very high accuracy, resulting in us loosing 81 to 178.

{{< rawhtml >}} 
<video width=100% controls >
    <source src="../../videos/gord-trousdell/playoffs.mp4" type="video/mp4">
    [Video Player Error]  
</video>
{{< /rawhtml >}}