---
layout: post
title: Week 1
---
The first week of the DREU program began with a couple of meetings. The first meeting was with the graduate student, Stav Ashur, I will be working with. Since this project is one I already started on in the previous semester, we discussed the next steps that we needed to accomplish. The roadmap we are creating for this project has balls of free and obstacle space. Since we are taking a lazy approach, there is a good chance that a free space ball will contain an obstacle or vice-versa. As such, we need to be able to resample the ball. Thus, my task was to create a function that resamples the ball.

After this meeting, we had another meeting for the undergraduates and graduate mentors. In this meeting, we started the crash courses, where we will be learning about motion planning and different motion planning algorithms. We were also given assignments to complete for the crash course, to make sure we are keeping up with the lessons. 

Once I completed the method, I had a meeting with Stav and we came to the conclusion that the original code needed to be split into two different files, the strategy (the original code) and a tool. The tool would be a data structure that contains two vectors of balls, one of free space and one of obstacle space.

This concludes my first week of the summer! 

For next week, I plan on separating the tool and the strategy, and then integrating them back together.
