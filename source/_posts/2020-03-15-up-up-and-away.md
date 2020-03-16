---
layout: blog
title: Up Up And Away!
lang: en
date: '2020-03-15T21:52:42-04:00'
thumbnail: /images/uploads/5-up.jpg
terms: 'Pixar, Disney, Animation, 3d, Renderman, Up, '
---
Up was a more challenging film for Pixar, but thats what they do and are good at. For Up, they needed to find a solution to manage thousands of ballon objects each with their own physics simulation. The other challenge that they had to overcome was recreating iridescence with the feathers on Kevin. The art direction of Up had a focus on grand large scale environments that were all stylized in their own way.



The physics of the balloons was managed by a python script that the Renderman engine and Maya read. An important part of this film was capturing scale, and grand environments. The balloons numbered in the thousands and were all influenced by one another and thus required a management system that took into account the physics of when they bounce into each-other. Once this was taken care of, Pixar was able to easily implement their other technologies into the film including the foliage from The Incredibles, dynamic human characters, and more soft body objects. There was yet one more thing that they still needed though.



Pixar has a keen eye for attention to detail. This may or may not be their way of making things harder than they have to be, but hey, at least they come out with awesome stuff! The feathers on Kevin needed to be physically accurate down to the micro hairs. Each feather is a separate object with its own geometry and of course there are thousands of them. Each feather is apart of a hair particle system that Pixar had developed to behave and interact with its environment. They still needed to take care of the millions of hairs that each feather contained, so the solution was to render the iridescence highlights in a realistic manner while texture maps took care of the colours that would be used. Overall, Pixar still has not let us down on their art direction and continue to explore the complex simulations that mimic the real world.
