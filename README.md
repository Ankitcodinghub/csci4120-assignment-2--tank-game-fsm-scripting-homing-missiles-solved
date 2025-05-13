# csci4120-assignment-2--tank-game-fsm-scripting-homing-missiles-solved
**TO GET THIS SOLUTION VISIT:** [CSCI4120 Assignment 2 -Tank Game (FSM Scripting & Homing Missiles) Solved](https://www.ankitcodinghub.com/product/csci4120-assignment-2-tank-game-fsm-scripting-homing-missiles-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92216&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI4120 Assignment 2 -Tank Game (FSM Scripting \u0026amp; Homing Missiles) Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Scripting refers to the techniques of writing scripts for pawns in 3D games so that the pawns will have desired behavior according to the game design. In this assignment, you are required to implement a finite state machine (FSM) to control some tanks in Unity game engine with various behaviors, and with a special weapon being built for the player.

Requirements

You can use the level built according to our tutorial document to continue the work in this assignment. You should :

</div>
</div>
<div class="layoutArea">
<div class="column">
1. 2.

I.

The tanks should have common behavior (in addition to the working style later) as follow:

1) The tank should scan for whether the player is nearby continuously. If the player is visible within a distance of 30 units, then the tank should enter attack mode. The scanning process should be able to : I) detect the player within its view cone of angle 120 degree forward with 30 units distance,

II) check visibility of the player through an unobstructed line of sight i.e. no walls or other objects in between.

</div>
</div>
<div class="layoutArea">
<div class="column">
write the scripts for two different behaviors to apply on two enemy tanks. write the scripts to produce a formation based weapon for the player.

</div>
</div>
<div class="layoutArea">
<div class="column">
Finite State Machine

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Assignment 2 2) In attack mode, the tank will first check whether player is within attack distance (30 units). If yes, it

will then orient itself towards you, and fire a missile at you. Then it will wait for 1 second and repeat step 2. Otherwise eg. Enemy tank leave, the tank will return to normal(original working state) mode.

In addition, the tanks should have two different styles of working. 1) Goal seeking

A goal point is set in the level (the flag of the player). The tank should proceed towards the goal point. 2) Patrol

Three waypoints will be set up in level (ordinary GameObject with collider). The tank should patrol between these waypoints.

Each tank should have a life point of 300, and with each hit by missile, no matter from friendly fire or player, a reduction of 10 life points will be deducted. A zero life point will see the removal of the tank from game.

The fired shell should also be removed from game if they collide with tanks or player tank. However you need not handle those fired shells which did not collide with tanks.

II. Homing Missiles

Homing missiles are very cool in their actions. We would like to implement a homing missile in this part. The missile should be able to target at a moving target i.e. the missile should update its course of direction according to the position of the target. In this case, the missile need to update its direction according to the target’s position.

Your implementation should be as follow.

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
CSCI4120 Principle of Computer Game Software

Assignment 2 The homing missile will be triggered when player press right mouse button. Once it is pressed, the player

tank should check all the current enemy tanks within a radius of 50 unit distance. Now for all those tanks within range, a homing missile should be created with its corresponding target, one missile per tank.

On colliding with the target tank, the target tank should be eliminated immediately no matter the life point is.

Remark

<ol>
<li>This assignment need you to use extensive scripting and physics engine knowledge. Unity official scripting documentation should help.</li>
<li>You can learn a lot on Unity by following this nice tutorial series
<iframe title="Unity Camera Object: Unity 3D Tutorial (Part 4)" width="980" height="551" data-src="https://www.youtube.com/embed/WNmT6U74Lcc?feature=oembed" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload" data-load-mode="1"></iframe>

g
</li>
<li>Waypoint in Unity http://forum.unity3d.com/threads/a-waypoint-script-explained-in-super-detail.54678/</li>
<li>Game object rotation is a relatively difficult issue. In this assignment, you are not required to handle them cleanly. We will only focus on the actions taken by the tanks.</li>
<li>Homing missiles are very interesting to implement though it looks a bit complicated at start. You may consult the following tutorial by “Dapper Dino” for details. https://www.youtube.com/watch?v=t_-kTapjfhM</li>
</ol>
</div>
</div>
</div>
