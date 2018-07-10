+++
# Date this page was created.
date = 2018-07-09T00:00:00

# Project title.
title = "Swimming Of A Microorganism Inside A Drop Covered With Surfactant"

# Project summary to display on homepage.
summary = "In this work, we look at the swimming of a microorganism encapsulated within a cage which is covered in surfactant. Due to hydrodynamic interactions, the swimmer is able to propel the drop. This problem is solved purely by Analytical methods, using Regular Perturbation and Lamb’s general solution. The effect of surfactant of its locomotion is investigated. We see that Scallop theorem breaks due to the presence of surfactant.We also see that surfactant makes the swimmer move slower. When the swimmer makes only tangential actuations, the drop is always slower than the swimmer. When both tangential and normal actuations are concerned, for a particular gait of the swimmer, we observe that swimmer and drop can co-swim."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "intern.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["microfluidics"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = true

# Optional featured image (relative to `static/img/` folder).
[header]
image = "intern_header.png"
caption = "Velocity field for a swimming microbe"

+++

Introduction 
============

In recent times, medical science has been looking at micro-robots to
revolutionize the way we treat various diseases. Drug delivery, which is
one of its key applications, can use the microorganism to deliver
pharmaceutical compounds to targeted cells. Side effects of drugs can be
minimized, and overall efficiency can be improved. In such a scenario,a
droplet encapsulating the microbe, functioning as its armor, will be of
advantage. The question arises, whether the swimmer inside the drop will
be able to propel the drop along with itself.

Microbial swimming is characterized by very low Reynold’s number. $Re$
is a measure of the relative importance of inertial and viscous forces.
At low Reynold’s numbers, inertia does not aid in swimming. As a result,
most swimming mechanisms that we see around us, like the swimming of a
man, or a boat propelling itself, do not work at this scale. The
microorganism needs to change its surrounding in a time-irreversible
manner to be able to swim. This is called the Scallop Theorem.

Previous works have shown that if the microbe deforms its surface in a
time-irreversible manner, then it would swim. In the current work, we
are trying to see if the presence of a surfactant breaks the Scallop
theorem instead. The motivation for this approach is that impurities are
omnipresent; there is no such thing as a clean interface. These
impurities or surfactants can be made use of to propel the swimmer and
the drop.

{{% staticref "/files/intern_report.pdf" "newtab" %}}Full Report{{% /staticref %}}.
