# Odin Landing Page Project (Flexbox)

## Requirements
The requirements for this project were to recreate a landing page using the two images provided. One image provided color codes and font specifications to be used, and the other was an image the full design that is to be created.


## Purpose
The purpose of this project is to practice implementing the principles of css flexbox that were taught in the flexbox unit of The Odin Project.

## Languages Used
- HTML
- CSS


## Challenges
### - Margin & Padding

One item that I kept getting tripped up on was deciding on which items to assign margin and padding to. In some instances, I added padding to the most senior elements, and other times I added padding to various descendants. I would have preferred to be consistent through out the design of this page, but whenever I tried to make a "rule" to follow, a different way seemed to work better in the next section. I am not sure if there is a best practice for these scenarios, but maybe I will get better at being consistent with time and experience.

### - Class Naming Convention

Another thing I struggled with was what to name the different classes. I used `.container` in many different locations throughout the webpage without giving that specific class any attributes (they were always used with the descendant combinator). It might have been better to name them like `.quote-container`, `.sign-up-container`, etc. I Actually did this for the `.nav-container` and `.nav` classes with the container class being the parent. This worked because the `.nav` class was a child of the `.header` class, but for the later sections, I didn't want to rename the parent section classes to have "container" in the name (I would have preferred to have it be a child), but then it would not have been consistent with the way I did the `.nav` class. In the end, the route I went with also was not consistent. Again, I think experience and time will play a big part with these kinds of issues in the future.

### - When to use flexbox
Initially, I tried to apply flexbox to everything. For example, the `.header` class contains a nav bar and then a banner below. I wanted to use flexbox and the `flex-direction: column` attribute. I ran into some issues (I'm not sure if they were related to the column flex direction) but ultimately I ended up realizing that it was totally unnecessary in this case.

## Conclusion
I am very proud of what I have created. It is gratifying to see my skills improve as I continue to work through The Odin Project.