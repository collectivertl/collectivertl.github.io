---
permalink: /about/
title: "About"
author_profile: false
classes: wide
sidebar:
  nav: pages
---

The free software movement has provided for significant advances over the years.  Software that once had a significant
cost associated with it now has a free alternative.  In many cases the free alternative has decimated the rival
software.  Examples include the Linux kernel, GNU compilers, OpenOffice, 
MySQL server, and the list goes on and on.


The free hardware movement has yet to acheive the same level of influence.  There aren't many whom can say that life
is different for them due to free hardware source code.  Since any hardware source code would need to be instantiated
in some form of realized hardware it may be difficult for most people to even understand if a free hardware core was
being utilized in a design.  Even if one could identify the reuse they would see very little.  A number of factors
prevent reuse by most teams.  These factors include quality, variations in style, reported testing by verification
and/or validation.  Things like core dependencies on ram(s), FIFO(s), etc, require that these dependencies and the
potentially undocumented requirements of those dependencies be available in the architecture being utilized by the
design. As the number of unknown variables increases (core quality, dependencies, pre-existing tests, available
drivers or firmware, etc) the associated risks with integration of the core increases.  These variables must be
reduced or preferrably eliminated in order for an open source hardware core to be widely adopted.

There are teams of people that develop hardware and nearly every team must develop some hardware cores that are not
mission critical. If these non-mission critical cores could be obtained freely then development time could be reduced
and engineering time would be focused on the mission critical functions of the design!  The incresed focus on mission
critical hardware helps insure that organizational resources are focused in the best possible way.

This leads to 'Why would any organization release any hardware core source code under a freely available license
then?'.  First, organizations that reap the benefit of other freely available cores will understand the benefits of
the freely available cores.  This along with the potential of reduced future maintanance as well as freely added
features to the hardware source code, should help to encourage the release of any new cores that must be developed
that are outside the scope of mission critical core IP.  The reduced support and maintenance costs would include
any reduction in associated supporting software associated with that core.

Most software driver, operating system, and firmware developers can attest to the extra work required for each unique
hardware core being utilized, since each unique core requires extra work on behalf of many developers.  This means
that the reuse of hardware cores would not only benefit hardware developers and the organizations they work for, it
would also benefit the low level software developers that need to implement the code associated with each hardware
core.

There's always an arguement for having a more custom approach that helps to reduce gate count, and better focus the
gates on what is absolutely requied.  While this is true, there is also a need to better focus engineering time where
it is best utilized.  If the open source hardware has the correct parameters to eliminate unnecessary or extraneous
features then the best of both worlds should be able to be achieved.

Presently available hardware cores vary in many ways.  Some of these variances have been barriers to usage, continued
development, and sharing of free hardware cores.  These barriers come from variances that include quality control,
other core dependencies, tool dependencies, tool migration issues, licensing concerns, and possibly others. The RTL
collective is intended to help create a standard to overcome these obstacles.  In addition assistance to help cores
to morph to the standard, and encouragement for newly created cores to use the standard is provided from the group.

Interested in helping?  Email [github-public@collectivertl.org](mailto:github-public@collectivertl.org) and/or join the collective on GitHub
