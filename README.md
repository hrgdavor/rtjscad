# rtjscad
Repository for jscad modules that go beyond just providing a utility to make shapes/volumes. The purpose is to explore different levels of sacrificing precision for faster preview or easier development.

Possible directions with different usages that can improve dev experience
 - reduces precision for curves in preview mode
 - full precision prior exporting (configurable)
 - simplified preview for further performacne gain (show only 2d outline of extrusion)
 - make long running operations interruptible (this actually bring down performance for ability to cancel early if a new job wants to start)

Other considerations
 - deploy procedure that produces a version that only has the code taht produces the shapes, without the dev/perf/debug functionalities

