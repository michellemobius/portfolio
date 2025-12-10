---
layout: project
title: Space Domain Awareness Simulator
description: Cornell Space Systems Design Studio
technologies: [Solidworks, Python, MatLab, Simulink]
image: /assets/images/sdas.png
order: 5
---
---
The Space Domain Awareness Simulator (SDAS) is a system developed to simulate interactions between two spacecrafts. One spacecraft is mounted on a spherical air bearing, allowing it to move freely with three degrees of rotational freedom and enabling realistic testing of spacecraft dynamics. The second spacecraft simulates relative orbital motion by maneuvering around the first, replicating conditions encountered in space. This research is a collaborative project in the <a href="https://www.spacecraftresearch.com/" class="no-underline-link"> Space Systems Design Studio </a>. I lead (a team of 13) on the development of the Small Scale Space Domain Awareness Simulator and am a member of the Attitude Control System (ACS) and Mechanical subteams, with a focus on designing and testing a star tracker for attitude determination.

**Motivation:** The growing number of resident space objects (RSOs) including active satellites and space debris poses a major challenge in Earth’s increasingly crowded orbital environment. Accurate tracking and cataloging of these objects is essential to prevent collisions and damage, thereby supporting the safety and longevity of space missions. Timely and precise detection of RSOs and estimation of their orbits will help build a comprehensive catalog. This catalog will provide data on the objects’ geometry, capabilities, and ownership, and support predictions of atmospheric re-entry, communication interference, payload disruptions, and potential physical collisions. Ongoing research aims to develop a realistic space domain awareness simulator to test instruments under conditions that reflect the growing presence of RSOs and debris.

**Star Tracker:** Attitude determination involves designing new hardware and implementing accurate algorithms to estimate the attitude of the SDAS. The hardware design focuses on determining the layout and combination of lighting and testbed hardware to enable attitude determination, essentially creating a homemade star tracker. At a high level, the star tracker processes a video stream to detect LED stars in captured images, and my algorithm identifies the centroids of the LED stars. I am creating a defined star catalog, based on the known positions of the LED stars, which will serve as a database. This catalog will be referenced with respect to the bay room coordinates. To determine the star tracker’s attitude, I measure the LED star positions from the spacecraft’s perspective. Using the star catalog, the spacecraft’s attitude will be determined relative to the LED star positions using Singular Value Decomposition. The telemetry will be represented as a quaternion, describing the spacecraft’s attitude with respect to time. The software I’ve implemented using MatLab and Python OpenCV includes the feature detection, centroid calculation, station mode configuration, and attitude determination.

---



