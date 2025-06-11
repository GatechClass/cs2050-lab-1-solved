# cs2050-lab-1-solved
**TO GET THIS SOLUTION VISIT:** [CS2050 Lab 1 Solved](https://mantutor.com/product/cs2050-introduction-solved-4/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;112846&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS2050 Lab 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (3 votes)    </div>
    </div>
In this lab activity you will work in pairs. One of you will be responsible for implementing the Bee class, while the other will write the code for the BeeDriver class.

Bee Class

a Bee has a type, which can be 0 (for workers), 1 (for drone), and 2 (for queen); define class constants for the type of bees; a Bee always belongs to a beehive identified by a name; a Bee has a location defined by two integers x and y;

there should be two ways to create a Bee object: one that takes a beehive name and another one that takes a beehive name and a type; if the type of a bee is not specified (or invalid), assume that the bee is a worker bee;

bees are always created at location (0, 0), which means that they are created inside the beehive; define getter methods for your Bee class;

create a private helper method called getTypeAsString that returns the type of the bee as a String; use this method in toString; define a move method that accepts new coordinates for the bee;

define a isInsideHive method that returns true/false depending on whether the bee is inside the hive (x = 0 and y = 0) or outside, respectively; override the toString method returning an appropriate String from the object; see example output below for * two bees from the â€œCrazy for Nectarâ€ beehive (as you can see, if the bee is inside the beehive its coordinates should not be displayed):

worker from “Crazy for Nectar” is outside the hive @ (150, 200) drone from “Crazy for Nectar” is inside the hive!

BeeDriver Class

Note that you are NOT supposed to implement the Bee class! Just ignore the errors you will get saying that the Bee class is not defined. You can take a look at the Bee class definition to figure it out the interface you should expect (i.e., which method should be available for you to use). If in doubt, ask your teammate for clarification.

Next, move all bees to random locations in the square defined by the left upper corner [-10, 10] and the right bottom corner [10, -10]. Right after you moved each bee, print information about it using the toString method implicit call.

When you are done, ask your partner to share their Bee class code so you can incorporate it in your program. You and your teamate should work together and make any necessary adjustments so the BeeDriver application works properly.

Rubric

+2 Bee class meets the specifications

+2 BeeDriver class meets the specifications

+1 BeeDriver class works with the Bee class according to the specfications
