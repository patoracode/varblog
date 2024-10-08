+++ 
date = 2024-09-17T12:49:25+02:00
title = "today i set up a blog, and the unity engine"
description = "(if you see this, it probably means i set the blog up correctly.)"
slug = ""
authors = ["isaac"]
tags = []
categories = []
externalLink = ""
series = []
+++

## Setting up the blog

### Getting familiar with Hugo

We used the Hugo framework and GitHub's hosting services. i knew about the latter but Hugo was something new for me. i must admit, it was also nice to have my memory refreshed a bit on the usual git commands... i only remembered `commit` and `push`...

```console
git status
git add .
git commit -m "my commit message"
git push -u origin main
```

But, apart from that, most of it was very straightforward. we followed similar instructions to what is given on the Hugo website in the "Quick start" section. 

[The "Quick Start" section in question -- it contains everything you need](https://gohugo.io/getting-started/quick-start/)

### Images are tricky

They really are. But the 2nd method in [this one stackoverflow thread](https://stackoverflow.com/questions/71501256/how-to-insert-an-image-in-my-post-on-hugo) works perfectly.

!["if youre reading this then i messed up and the image is not showing up :("](images/thumbsup.jpg) 


### And now...

...now to add some content to it...


## Setting up Unity

We had already set up the unity engine in the dedicated class, so this was mostly the same as what we had done during the week prior. 

some of what we were taught:
- gameobjects: 3d meshes, etc
- assets: materials, prefabs (instance-able objects), c# scripts
- components, including physics (rigid bodies)
- basics of c# scripting
- basics of UI and scenes management

I now feel comfortable using all of these elements together. The assignment for the unity class being a simple game using the mechanics we studied during the dedicated class, I feel like I will be able to get enough practice with both classes combined in order to master the basics of unity at the end of the semester.

A good project for beginners with Unity is Roll-a-ball, which we actually implement later in the course.

[Unity: Roll-a-ball, a good project for beginners](https://learn.unity.com/project/roll-a-ball)

![unity roll-a-ball](images/rollaball.png)