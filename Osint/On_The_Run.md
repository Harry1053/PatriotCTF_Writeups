# On The Run
### Category: Osint
### Difficulty: Easy
### Author: arcticx

# Description

We've been tracking the adversary for weeks, and he just slipped up and posted this gorgeous high-rise view on his Twitter. His caption was "awesome meeting with a gorgeous view!" Can you track down his location?
Flag format will be PCTF{<business name of his location>}. Not a street address. If he were in a WeWork space, it would be PCTF{wework}.

# Attachments
twitterpost.jpg: A picture of a photo taken from a Building

![twitterpost](https://github.com/user-attachments/assets/7ff4c887-955e-46f1-b52f-4d0c56425289)

(Resized duplicate)

# Initial Thoughts and Solution

In the background, the Washington Monument is to be seen. This was verified after a quick lookup, since the three bridges were also there. 
Since the broad location was now known, I took a look at the angle of the picture to find the building complex.

Once the picture was recreated in Google Earth, I just had to look at the building the camera was at, to find the flag.

![Recreation](https://github.com/user-attachments/assets/01f07c8a-ed46-40ff-b266-50eacfdf8086)
(Recreation of attachment photo in Google Earth.

(Mind, that the actual answer is not on Google Earth, but on Google Maps at the exact same location)

# Solution

PCTF{convene}
