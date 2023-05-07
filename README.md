Download Link: https://assignmentchef.com/product/solved-esc794-homework-6
<br>
<ul>

 <li>The application of serial distributed MPC for a traffic intersection with autonomous vehicles has been discussed in class and the centralized solution posted on the course website. Obtain a serial MPC implementation for the same example, with any suitable sequence. Feel free to redefine the collision-avoidance constraint formulation. Time the centralized solution vs. the serial distributed case in order to make a meaningful comparison.</li>

 <li>Write a function that simulates a dual decomposition MPC controller for the system</li>

</ul>

<em>x</em><sup>+ </sup>= <em>Ax </em>+ <em>Bu</em>

with A=[1 1 1;0 0 -1;1 0 0];B=[2 0;0 1;1 0]. The objective is regulation to the origin under an LQR cost, where <em>Q </em>and <em>R </em>are chosen block-diagonal compatibly with your chosen system partition. Include a terminal equilibrium constraint and unit box constraints for the control vector. Tune the system for good performance by varying <em>Q</em>, <em>R</em>, the prediction horizon and the convergence rate of the steepest ascent Lagrangian iteration.