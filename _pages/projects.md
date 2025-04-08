---
layout: page
title: projects
permalink: /projects/
description: a collection of projects I have worked on
nav: true
nav_order: 3
display_categories:
horizontal: false
---

Through the course of my bachelor's, I have tried to branch out and learn about the various fields of work in aerospace as well as mechanical engineering, through my participation in Parikshit, internships, as well as lab projects for my courses. These projects are all listed below. 

The key for the projects are as follows :  🛰️ -> modules at Parikshit ; 💼 -> internships ; 💻 -> lab projects 

<details>
  <summary>🛰️ System design for a nanosatellite</summary>
  <p>
    After COVID, the team required a complete overhaul of each subsystem, as well as the overall system. Changes in STMS have been highlighted in the points below, with major changes to the satellite structure, internal layout, and the actuators. Therefore, my first responsibility as a system engineer was to work on designing the system for the team from scratch. This included outlining the system requirements and a V diagram to outline the various stages in the satellite design process. The designed V diagram was essential in developing a tentative timeline for the project as well as the budget the team would require to see the project through. 
  </p>
  <p><strong>Objectives:</strong></p>
  <ol>
    <li>generate system requirements to track the progress of the team till completion</li>
    <li>form a tentative timeline till the satellite can be ready for launch</li>
    <li>
      form a budget for the satellite, including but not limited to:
      <ul>
        <li>tentative launch costs</li>
        <li>tentative costs for testing</li>
        <li>manufacturing costs</li>
        <li>costs of on board components</li>
      </ul>
    </li>
  </ol>
  <p>
    This information was then used as the basis of all the team's communication with the college administration, IN-Space, and any other administrative meetings the team had with the college and outside of it. 
  </p>
  <p>As the system engineering position doubled as the position of a team leader, I also led the team, gaining invaluable insight into managing a large group of talented and passionate individuals, and eventually, trained a select group of juniors to take over as system engineers</p>
</details>



<details>
  <summary>
    💼 GE Aerospace - Manufacturing
  </summary>
  <p>
    I spent the summer after my third year working at the GE multi-modal manufacturing plant in Pune, where I worked specifically on laser cutting machines. My tasks during this two-month internship included the following:
  </p>
  <ol>
    <li>Generating manufacturing operating sheets for the 5-axis laser cutting machine
    <p>The manufacturing operating sheets were essentially guidelines for how the machine operators should run the machines, with information such as:</p>
    <ul>
      <li>Setup</li>
      <li>Protective coating</li>
      <li>Name of the G code file to be used</li>
    </ul>
      <p>During my internship, I also developed a way to automatically generate first drafts of these sheets by porting over information for data dumps available on various excel sheets onto a template using VBA plugins</p>
    </li>
    <li>
      Getting certified in 6 sigma yellow belt - statistical process control
      <p>Conducted an SPC analysis of parts that were machined in the 5-axis laser cutter using the measurements from FARO arms as a way to find the capability of the laser cutting operation</p>
    </li>
    <li>Process chart for the production of brackets
      <p>To find the amount of time taken to produce one bracket, I generated a process chart mapping out the amount of time taken to cut geometries of a certain complexity on the sheet laser cutting machine, the amount of time taken per bend, and each step in the bracket fabrication process. This framework was then used to estimate the cost of production of a part based on its complexity.</p>
    </li>
  </ol>
</details>

<details>
  <summary>🛰️ 2U nanosatellite structure - meeting calypoly specifications and industry standards</summary>
  <div>
    <p>
      To allow for an outsourced battery pack, solar panels, and an onboard computer to be placed in the structure,  
      a complete overhaul of the satellite structure was done. In the process, we managed to reduce the weight of  
      the structure by 33% while maintaining satisfactory structural strength to overcome launch loads. The design  
      was made on Fusion360, and the preliminary analysis was done using ANSYS.
    </p>
    <p><strong>Objectives:</strong></p>
    <ol>
      <li>The structure shall be able to mate with an industry-standard 2U class deployer</li>
      <li>It shall be capable of surviving launch loads:
        <ol>
          <li>Acceleration loads</li>
          <li>Vibrational loads of the launch vehicle</li>
        </ol>
      </li>
      <li>The newly designed structure shall allow for outsourced parts</li>
    </ol>
    <p>
      The redesign also led to the reworking of the onboard burn wire mechanisms and the killswitch mechanism.
    </p>
  </div>
</details>

<details>
  <summary>🛰️ Redesign of on-board reaction wheels - reducing manufacturing complexity while maintaining moment of inertia</summary>
  <p>
    <p>The existing setup of the reaction wheels in the satellite faced two problems:</p>
    <ol>
      <li>The design was too complex to allow for easy manufacturing, which led to high manufacturing costs</li> 
      <li>They were too large in diameter for them to fit inside the newer vertically stacked internal layout of the satellite.</li>
    </ol>
    <p>This led to the following <strong>objectives</strong> for this redesign :</p>
    <ol>
      <li>The wheels shall be designed keeping in mind DFMA concepts</li>
      <li>The wheels shall have a reduced diameter, while maintaining a similar moment of inertia </li>
    </ol>
    <p>To meet these objectives, the simplest possible design was considered - a flat disk. This, however, did not meet the moment of inertia requirements with the diameter constraints. To compensate for the MOI requirements, circular walls were built on the circumference of the reaction wheel up to a height calculated by working backwards from the required slew rate. The proposed design was then compared to the previous design with spokes with respect to the following:</p> 
  <ol>
    <li>weight</li>
    <li>deformation under the actuation RPM</li>
    <li>tolerated imbalances</li>
  </ol>
  <p>The newer design, once sufficiently analysed, was then chosen to go ahead with, after which the calculations were done to find the size of the motor shaft hole on the wheel for its interference fit. This marked the end of the reaction wheel redesign.</p>
  </p>
</details>


<details>
  <summary>💼 Defence Research and Development Laboratory, DRDO - project intern</summary>
  <p>
    As an intern, I worked on learning the basics and key principles of computational fluid dynamics, initially through theoretical texts provided by DRDL itself, and later through various simulations. Towards the end of the two-month internship, I worked on a literature review for the aerodynamic analysis of a jet vane thrust vectoring system for a missile. Observations and learnings from the internship included : 
    <ul>
      <li>conducting CFD analysis for the NACA 0012  airfoil and comparing results with established values of the drag and lift coefficients - results were within 10% of the established values</li>
      <li>conducting a literature review on previous analyses done on jet vane thrust vectoring control systems</li>
      <li>modelling of the thrust vector control system, including the converging-diverging nozzle and the arrangement of the fins for the control system</li>
      <li>analysis of the generated model using boundary conditions taken from the literature review</li>
    </ul>
    The internship was my first foray into the field of computational fluid dynamics. The time spent under my guide at the internship also built the basis of my understanding of how a literature review is to be conducted, and how one builds from existing literature to furthering the studies previously done. During my time at DRDL, I was also fortunate enough to see wind tunnel testing on a particular part of the projects being developed. These experiences, to a second-year student cemented my interest in the field of engineering and were a great motivator to the work I did after this internship. 
  </p>
</details>

<details>
  <summary>🛰️structural analysis of the satellite</summary>
  After joining the team, I was introduced to the satellite. The modules taken up by me as a team member in the Structures, Thermals and Mechanisms Subsystem were more or less all centered around conducting the static structural analysis on the satellite body. During this time, I experimented with various ways to set up the analysis to allow it to give us the most accurate results possible with the computational facilities we had on hand. Key takeaways from this task were: 
  <ul>
    <li>Meshing tools on ANSYS and conducting mesh convergence studies</li>
    <li>Identifying the different contacts and their effects on computational time</li>
    <li>simplification methods for a complex geometry while maintaining accuracy</li>
  </ul>
  All of these tasks were possible due to the support and guidance I was given by my seniors in the team, without whom I would not have been able to learn half of what I did during my first year of mechanical engineering.
</details>
