---
layout: project
title: Space Domain Awareness Simulator
description: Advanced CAD Project
technologies: [Solidworks, Python, MatLab]
image: /assets/images/sdas.png
---

The Space Systems Design Studio (SSDS) designs satellites and cubesats for space exploration. The
Space Domain Awareness Simulator (SDAS) is a simulator system of two spacecraft. One spacecraft is
supported on a spherical air bearing that provides unconstrained motion in all six degrees of freedom,
so that the physical response of a spacecraft can be tested. The other spacecraft moves around the
first spacecraft, exhibiting the relative-orbit motion one would see in space. This ongoing research
will allow robust testing of guidance navigation and control systems, docking, and space domain
awareness. I am a member of the ACS and Mechanical subteams, working on the design and testing
of the star tracker for attitude determination. Attitude determination involves designing new hardware
and implementing accurate algorithms to estimate the attitude of the SDAS. The hardware design
focuses on determining the layout and combination of lighting and testbed hardware to enable attitude
determination, essentially creating a homemade star tracker. At a high level, the star tracker processes
a video stream to detect LED stars in captured images, and my algorithm identifies the centroids of
the LED stars. I am creating a defined star catalog, based on the known positions of the LED
stars, which will serve as a database. This catalog will be referenced with respect to the bay room
coordinates. To determine the star tracker’s attitude, I measure the LED star positions from the
spacecraft’s perspective. Using the star catalog, the spacecraft’s attitude will be determined relative
to the LED star positions using Singular Value Decomposition. The telemetry will be represented as a
quaternion, describing the spacecraft’s attitude with respect to time. The software I’ve implemented
using MatLab and Python OpenCV includes the feature detection, centroid calculation, station mode
configuration, and attitude determination using SVD



