---
layout: project
title: Blade Design Project
description: Advanced CAD Project
technologies: [Autodesk Fusion, MATLAB]
image: /assets/images/BladeCAD.jpg
---

For a class, we were asked to design a wind turbine blade. Wind turbine blades are designed to extract maximum power at a certain RPM and wind speed; however, structural limitations also need to be considered since a flow will exert a certain force on the blades. We designed blades that were optimized to extract maximum power in a flow with a velocity of about 4.8 m/s, and we also expected it to withstand the forces that the flow exerts on it during that operating condition. We had some constraints to deal with during the design of the blades in order to be able to properly test them; namely, the blade length had to be less than 6 inches, we needed to design for an RPM less than 2000 to avoid material failure in the blade, and flow velocities could only go up to 15 m/s (in the wind tunnel). The design process of the blades included using data on our chosen airfoil cross section (the NACA 4412) from airfoils.com to calculate how variations in the chord and pitch of the airfoil as a function of the blade length could optimize lift and reduce drag. We also wanted to maintain the structural integrity of the blade so we ran calculations to ensure that the flexural strength of the blade material would not be exceeded in the operating conditions we wanted to test in.

![Shaded rendering of earlier version]({{ "/assets/images/BladeCAD.jpg" | relative_url }}){: .inline-image-r style="width: 200px"}
![Shaded rendering of earlier version]({{ "/assets/images/BendingStressDistribution.jpg" | relative_url }}){: .inline-image-r style="width: 200px"}

In order to test our blades, we placed blades that we designed into a wind tunnel to find the RPM and flow speed that the blades actually extracted the most power from, and we also wanted to verify that the blades were structurally sound at that flow speed and RPM. To do this, we set the fan frequency to about 7 Hz and then measured the power output as we increased the resistance torque slowly until the RPM of the blades was 0. We repeated this for flows at 6 Hz, 8 Hz, and 9Hz so that we could compare all of our data to see which combination of flow speed and RPM had the greatest power output all while carefully watching the blades to make sure that the material was not failing. We made sure that the RPM did not surpass 2000, which is when we expected failure.

![Photo of old radio]({{ "/assets/images/PowerCurve.jpg" | relative_url }}){: .inline-image-l}
![Shaded rendering of earlier version]({{ "/assets/images/TurbineTest.jpg" | relative_url }}){: .inline-image-r style="width: 200px"}

After testing, our results showed that our blades actually extracted more power in higher wind velocities than expected. We had the highest power output when we set the wind tunnel fan frequency to 9 Hz and when the blades were rotating at about 1700 RPM, but we had expected those values to be about 7 Hz and 1900 RPM. We think that this may be because when we were plotting theoretical power curves, we found that peak power output in a flow at 4.8 m/s would occur for our blades somewhere over 2000 RPM, but we didn’t want to exceed that value in order to avoid increasing stress in the blades, so we just chose 1900 RPM as the value to optimize our blades for.

My largest contributions to this group project were that I worked on the CAD of the airfoil and I did a lot of the data analysis and graphing (such as the power curves). However, the group generally worked on everything equally, so I also took part in things like the calculations for the shape of the blade, the write up of our final report, and the design of our experimental procedure.
