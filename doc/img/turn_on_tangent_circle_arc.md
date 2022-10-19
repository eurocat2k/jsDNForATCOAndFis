# How to calculate the distance from turning point toward to an adjacent point having the aircraft's turning radius and its present location relative to both points?

<div align="center">
    <img src="img/ATCUI_turn_tangent_radius.png"/>
</div>

<bold>Figure 1</bold>: calculate turn initiation distance from present position to the turning point - **tangency point** - from where the track should change the radial toward the adjacent point.

## What we have before the calculation?

In the following section I will describe those steps to get the minimum distance between the next point - currently we are inbound - when we need to turn toward the adjacent point on a different radial.

- The current position of the aircraft at point **A (1,4)**

- The next point - **B (3, 2)** - where the aircraft should turn to the adjacent point **C (-2, -5)**

- We can calculate the radials from **B** to **A** and **C** respectively. They are **B**->**A**: **315** degrees, and **B**->**C**:**215.53767779197437** degrees

- Now we can calculate the difference between those two legs, which gives us: **γ = 99.46232220802563** degrees. *(This is the angle difference between A and C from B.)*

- Now we need the half of this angle - **α = 49.73** - to be able to calculate the angle between **GB** and **GH** - **β = 40.27** *(90 - α)*, because **GH** equals with **r=2** - the tangent circle's radius -, as it is perpendicular to **AB** segment therefore we obtain a right triange **HGB**.

- To obtain the **HB** segment we need to call the tangent of its opposite angle - *at point **G*** - multiplied by the radius. *The result shown with pink segment on the figure.* The math is: Segment length between **HB** = **tan(β) * r**. *(The first tangency point on a **H**eading **A**lignment **C**one is at point **H** - the second is at **I**)*

- As we know the distance between the turning point **B** and the tangent point **H** on **r=2** radius circle, then we can get the distance of that tangent point from our current location. Which gives us the result of **AH**=**AB-HB**.

*The figure contains temporary results of calculations.*
