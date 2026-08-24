---
permalink: /projects/
title: "Projects"
author_profile: true
redirect_from: 
  - /projects.html
---

## Implementation of PPO for Multi-Agent Path Finding with Dynamic Obstacles
<div style="display: flex; align-items: flex-start; gap: 20px; margin-bottom: 1em;">
  <div style="flex: 0 0 160px;">
<!--     <img src="{{ site.baseurl }}/files/projects/mapfo/mapfo.gif"
         alt="MAPFO demo"
         style="width: 100%; height: auto;"> -->
    <video autoplay loop muted playsinline style="width:100%; height:auto;">
      <source src="{{ site.baseurl }}/files/projects/mapfo/mapfo.mp4" type="video/mp4">
    </video>         
  </div>

  <div style="flex: 1;">
    Multi-agent path finding (MAPF) addresses the challenge of enabling multiple agents to reach individual goals without collisions in shared, confined environments, such as automated warehouses. This project proposes a reinforcement learning–based decentralized policy for MAPF using a synchronized Proximal Policy Optimization (PPO) framework. By synchronizing agent weights within the same environment and leveraging the PPO objective, the method improves training stability and mitigates the data inefficiency observed in the baseline MAPPER approach. Experimental results demonstrate improved performance in terms of average reward, collision rate, and success rate compared to the baseline.
    <!-- Efficient multi-agent path finding algorithm is essential for reducing cost when deploying robots to logoistics warehouses. In this project, we train a Multi Agent variant of Proximal Policy Optimization (PPO) algorithm for multi agent path finding with dynamic obstacles. -->

    <div style="margin-top: 0.5em; font-size: 0.9em; color: #555;">
      Georgia Institute of Technology · CS 8803 RLR — Research Project
    </div>

    <div style="margin-top: 0.3em;">
      <a href="{{ site.baseurl }}/files/projects/mapfo/mapfo.pdf">[PDF]</a>
    </div>
  </div>
</div>


## Autonomous competition robot built using Arduino Nano.
<div style="display: flex; align-items: flex-start; gap: 20px; margin-bottom: 1.2em; flex-wrap: wrap;">

  <!-- Left: Image -->
  <div style="flex: 0 0 160px;">
    <a href="https://peakovershoot.weebly.com/" target="_blank" rel="noopener noreferrer">
      <img src="{{ site.baseurl }}/files/projects/peakovershoot/render.jpg"
           alt="Peak Overshoot autonomous robot"
           style="width: 100%; height: auto; border: 1px solid #ddd;">
    </a>
  </div>

  <!-- Right: Description -->
  <div style="flex: 1;">
    I co-designed and built an autonomous mobile robot for a mechatronics tournament, where the system was required to
    follow a prescribed path, interpret multiple beacon signals to infer game state, and autonomously deposit game objects
    into designated bins. The robot integrated onboard sensing, feedback control, and task-level logic to execute the full
    pipeline without human intervention.
    <br><br>
    Our team achieved <strong>second place overall</strong> in the competition.
    
    <div style="margin-top: 0.5em; font-size: 0.9em; color: #555;">
      Stanford University · ME 210 — Course Project
    </div>

    <div style="margin-top: 0.3em;">
      <a href="https://peakovershoot.weebly.com/" target="_blank" rel="noopener noreferrer">[Demo Video & Project Details]</a>
    </div>
  </div>
</div>



## Application of a Genetic Algorithm to the Optimization of Walker Delta Constellations
<div style="display: flex; align-items: flex-start; gap: 20px; margin-bottom: 1.2em; flex-wrap: wrap;">
  <!-- Left: Image -->
  <div style="flex: 0 0 160px;">
        <img src="{{ site.baseurl }}/files/projects/walker_delta/walker_delta_ga.png"
         alt="Walker Delta Genetic Algorithm"
         style="width: 100%; height: auto;">
  </div>

  <!-- Right: Description -->
  <div style="flex: 1;">
    Developed a genetic algorithm–based framework to optimize Walker Delta satellite constellations, using Earth coverage as the fitness metric. The study demonstrates how constellation design parameters and orbital configurations influence coverage performance in distributed space systems.

    <div style="margin-top: 0.5em; font-size: 0.9em; color: #555;">
      Stanford University · AA 222 — Research Project
    </div>

    <div style="margin-top: 0.3em;">
      <a href="{{ site.baseurl }}/files/projects/walker_delta/walker_delta_ga.pdf">[PDF]</a>
    </div>
  </div>
</div>


## Head-Tracking for Virtual Reality Applications using EKF
<div style="display: flex; align-items: flex-start; gap: 16px; margin-bottom: 1.2em; flex-wrap: wrap;">

  <!-- Left: Video (160px) -->
  <div style="flex: 0 0 160px;">
    <video autoplay loop muted playsinline
           style="width: 160px; height: auto; border: 1px solid #ddd;">
      <source src="{{ site.baseurl }}/files/projects/head_tracking_ekf/compensated.mp4" type="video/mp4">
    </video>
  </div>

  <!-- Right: Text -->
  <div style="flex: 1;">
    Developed a real-time head-tracking system for VR using an Extended Kalman Filter (EKF) to
    estimate headset orientation with low latency. The system fuses inertial and magnetic sensor
    data and evaluates a compensated accelerometer-based approach to mitigate gyroscope drift.
    Simulation results demonstrate accurate orientation tracking suitable for real-time VR
    rendering pipelines.

    <div style="margin-top: 0.5em; font-size: 0.9em; color: #555;">
      Stanford University · AA 273 — Research Project
    </div>

    <div style="margin-top: 0.3em;">
      <a href="{{ site.baseurl }}/files/projects/head_tracking_ekf/head_tracking.pdf">[PDF]</a>
    </div>
  </div>

</div>


## Optimal Irrigation on an Hourly Scale Using Model Predictive Control (MPC)
<div style="display: flex; align-items: flex-start; gap: 16px; margin-bottom: 1.2em; flex-wrap: wrap;">

  <div style="flex: 0 0 160px;">
        <img src="{{ site.baseurl }}/files/projects/irrigation_mpc/mpc_ns_week.png"
         alt="Optimal Irrigation using MPC"
         style="width: 100%; height: auto;">
  </div>

  <!-- Right: Text -->
  <div style="flex: 1;">
    <!-- This project investigates optimal irrigation scheduling on an hourly timescale using Model Predictive Control (MPC) to minimize total water usage while maintaining soil moisture above crop stress thresholds. The system models soil water dynamics using FAO-standard evapotranspiration and soil water balance equations, incorporating weather-driven variables such as temperature, precipitation, and solar radiation. Due to piecewise soil drainage behavior, the irrigation problem is formulated as a Mixed-Integer Linear Program (MILP) and solved within a receding-horizon MPC framework. Simulation results for a corn field in Springfield, Illinois show that MPC significantly outperforms reactive control by strategically timing irrigation around rainfall and low-loss periods, with additional water savings achieved by explicitly modeling spray irrigation losses, demonstrating the potential for scalable water conservation at the farm level -->

    Developed an MPC-based irrigation controller using weather forecasts and FAO soil models, demonstrating reduced water usage through optimal hourly irrigation scheduling 

    <div style="margin-top: 0.5em; font-size: 0.9em; color: #555;">
      Stanford University · AA 203 — Research Project
    </div>

    <div style="margin-top: 0.3em;">
      <a href="{{ site.baseurl }}/files/projects/irrigation_mpc/optimal-irrigation-hourly.pdf">[PDF]</a>
    </div>
  </div>
</div>


## Semantic Segmentation in the Traffic Environment using the DeepLabv3+ Model
<div style="display: flex; align-items: flex-start; gap: 16px; margin-bottom: 1.2em; flex-wrap: wrap;">

  <div style="flex: 0 0 160px;">
        <img src="{{ site.baseurl }}/files/projects/cs231n/results.png"
         alt="Optimal Irrigation using MPC"
         style="width: 100%; height: auto;">
  </div>

  <!-- Right: Text -->
  <div style="flex: 1;">
    Semantic segmentation in the traffic environment is an important perception task for autonomous driving. 
    This project performed semantic segmentation on the Mapillary Vistas Dataset, a novel street scene dataset containing 66 object categories. We conducted transfer learning based on the DeepLabv3+ developed by Google TensorFlow. The DeepLabv3+ model employs the spatial pyramid pooling module and the encode-decoder structure. Our fine-tuned model is able to score 23.6% mIoU on the test set of the Mapillary Vistas Dataset (being able to rank No.6 on the MVD Challenge Leaderboard as of Jun. 7, 2018).

    <div style="margin-top: 0.5em; font-size: 0.9em; color: #555;">
      Stanford University · CS 231N — Research Project
    </div>

    <div style="margin-top: 0.3em;">
      <a href="{{ site.baseurl }}/files/projects/cs231n/final_report.pdf">[PDF]</a>
      <a href="{{ site.baseurl }}/files/projects/cs231n/poster.pdf">[Poster]</a>
    </div>
  </div>
</div>


## Implementation of Reinforcement Learning and Game Theory for Optimal Path Planning with Dynamic Obstacles
<div style="display: flex; align-items: flex-start; gap: 16px; margin-bottom: 1.2em; flex-wrap: wrap;">

  <div style="flex: 0 0 160px;">
        <img src="{{ site.baseurl }}/files/projects/cs221/map.png"
         alt="Overview"
         style="width: 100%; height: auto;">
  </div>

  <!-- Right: Text -->
  <div style="flex: 1;">
    This project explores optimal path planning in dynamic environments by comparing heuristic search, game-theoretic methods, and reinforcement learning. A grid-based navigation problem with moving obstacles is formulated, where the agent must reach a goal while avoiding collisions and minimizing cost. Simulation results show that while modified A* and game-theoretic approaches involve trade-offs between optimality and computation, a Q-learning–based policy achieves near-oracle performance, delivering high success rates and low evaluation time even in complex, dynamic scenarios.

    <div style="margin-top: 0.5em; font-size: 0.9em; color: #555;">
      Stanford University · CS 221 — Research Project
    </div>

    <div style="margin-top: 0.3em;">
      <a href="{{ site.baseurl }}/files/projects/cs221/final_report.pdf">[PDF]</a>
    </div>
  </div>
</div>


## Conceptual Design and Optimization of a Long-Range Aircraft
<div style="display: flex; align-items: flex-start; gap: 16px; margin-bottom: 1.2em; flex-wrap: wrap;">

  <div style="flex: 0 0 160px;">
        <img src="{{ site.baseurl }}/files/projects/ae481/image.png"
         alt="Aircraft Image"
         style="width: 100%; height: auto;">
  </div>

  <!-- Right: Text -->
  <div style="flex: 1;">
    <!--This senior undergraduate project focused on the conceptual design and optimization of a long-range commercial aircraft for Singapore Airlines, capable of carrying 125 business-class passengers nonstop from Newark to Singapore while meeting FAR Part 25 requirements. Using Multidisciplinary Design Optimization (MDO), the team minimized Cash Operating Cost (COC) and selected a four-engine configuration powered by GEnx engines due to their lower TSFC, achieving a COC of $423,013. The final design features an optimized wing geometry yielding a cruise L/D of 16.7 and a passenger-focused cabin layout with full lie-flat seating and direct aisle access, satisfying all mission and performance requirements.-->
     The objective of this senior undergraduate project, as documented in the Critical Design Report (CDR) by Airbenders Ltd., was to provide the conceptual design and optimization of a long-range aircraft for Singapore Airlines. Specifically, the aircraft was to carry 125 business-class passengers on a nonstop route from Newark to Singapore (8,285 nautical miles plus 200 nautical miles of reserves) with a target market entry in 2025. The central design goal was to minimize the Cash Operating Cost (COC) to ensure profitability, while adhering to Federal Aviation Regulations (FAR Part 25). The team developed and utilized Multidisciplinary Design Optimization (MDO) software to achieve a design with the minimum COC, and through this optimization, a four-engine configuration was selected for its lower COC of $423,013, primarily due to the lower thrust-specific fuel consumption (TSFC) of the GEnx engine. The final design, which includes an interior layout optimized for passenger comfort with a 2-2-2 offset seating arrangement for full lie-flat seats and direct aisle access, features an optimized wing geometry (353.03 m² reference area, 57.3 m span, 23.7° sweep) that achieves a cruise Lift-to-Drag (L/D) ratio of 16.7, meeting all mission specifications. 

    <div style="margin-top: 0.5em; font-size: 0.9em; color: #555;">
      University of Michigan · AE 481 — Course Project
    </div>

    <!--<div style="margin-top: 0.3em;">-->
      <!--<a href="{{ site.baseurl }}/files/projects/ae481/final_report.pdf">[PDF]</a>-->
    <!--</div>-->
  </div>
</div>
