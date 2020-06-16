---
ID: 1072
post_title: 'How to make 3D models &#8211; Beginner guide to 3D modeling'
author: Kérian Fiter
post_excerpt: ""
layout: post
permalink: >
  https://kerian.fiter.net/how-to-make-3d-models/
published: true
post_date: 2019-04-04 14:42:57
---
<!-- wp:heading -->

## Introduction

<!-- /wp:heading -->

<!-- wp:paragraph -->

Two years ago, I wondered how 3D models were made: how do they work and how do I make my own ones.

<!-- /wp:paragraph -->

<!-- wp:paragraph -->

In this article, I’m going to give you some keys to understand theses basics concepts and start creating stuff. Without further ado, let’s get started!

<!-- /wp:paragraph -->

<!-- wp:heading -->

## Understanding how a 3D model works

<!-- /wp:heading -->

<!-- wp:paragraph -->

* For the clarity of this article we are not going to cover procedurally or scanned made 3D models*

<!-- /wp:paragraph -->

<!-- wp:paragraph -->

The idea behind a 3D model is very simple. The core of 3D modeling is a point in space represented by coordinates in the X, Y and Z axis. It's called a vertex. If there are two vertices, you can join them and it makes what is called an edge. And with 3 vertices, you can join them all and decide whether the formed triangle should create a face. This face represents what you are going to see.

<!-- /wp:paragraph -->

<!-- wp:image {"align":"center","id":1082} -->

<div class="wp-block-image">
  <figure class="aligncenter"><img src="https://kerian.fiter.net/wp-content/uploads/2019/04/cube-vertex.png" alt="" class="wp-image-1082" /><figcaption>The highlighted vertex is one of the 8 vertices of this cube</figcaption></figure>
</div>

<!-- /wp:image -->

<!-- wp:paragraph -->

A face composed of 4 vertices is called a quad, and more than 4 it is called an NGon. Usually people try to avoid to make NGons because it can lead to distortions and other issues, but there are a few cases where you could use it.

<!-- /wp:paragraph -->

<!-- wp:paragraph -->

*In the end the 3D model is going to be triangulated on export (every face is going to be transformed to triangles) so using NGons won't optimize the model*

<!-- /wp:paragraph -->

<!-- wp:image {"align":"center","id":1088} -->

<div class="wp-block-image">
  <figure class="aligncenter"><img src="https://kerian.fiter.net/wp-content/uploads/2019/04/cube-ngon.png" alt="" class="wp-image-1088" /><figcaption>The highlighted face is an NGon because it is made of 9 vertices</figcaption></figure>
</div>

<!-- /wp:image -->

<!-- wp:heading -->

## Time for creation!

<!-- /wp:heading -->

<!-- wp:heading {"level":3} -->

### I) Installation

<!-- /wp:heading -->

<!-- wp:paragraph -->

Okay, now comes the good stuff. What you are going to need is a computer with an internet connection and a bit of free disk space. And before you ask, I do not recommend *at all* to use your phone or your tablet for modeling as it will just be a pain to use and will discourage you.

<!-- /wp:paragraph -->

<!-- wp:paragraph -->

Now you have the choice of the software. And, like for everything, there are some pros and cons to every one of them. But I don't want you to fall in the trap of comparing softwares but not starting anything, which is a common mistake that you should avoid. I personally use [Blender][1], an open source 3D modeling software which has a very good reputation and is free.

<!-- /wp:paragraph -->

<!-- wp:paragraph -->

*You should also find out about softwares like [Maya ][2]or [Cinema4D][3], considered by some people as industry standards*

<!-- /wp:paragraph -->

<!-- wp:paragraph -->

To download Blender, head over the [Blender download section][4] and download the latest Blender version. I recommend you to download the 2.8 (or more) version as this is where Blender is going in terms of user interface and functionalities.

<!-- /wp:paragraph -->

<!-- wp:paragraph -->

*If you downloaded a .zip file just unzip it to your dekstop*

<!-- /wp:paragraph -->

<!-- wp:paragraph -->

Then launch the Blender executable and get ready, the real part is starting now!

<!-- /wp:paragraph -->

<!-- wp:heading {"level":3} -->

### II) Your first shape

<!-- /wp:heading -->

<!-- wp:paragraph -->

*Before starting, I would like to mention that a lot of videos are covering this subject, and I can only recommend this very good [Guide to Blender 2.8 video][5] by [Blender Guru][6] (if still up to date)*

<!-- /wp:paragraph -->

<!-- wp:image {"id":1117} --><figure class="wp-block-image">

<img src="https://kerian.fiter.net/wp-content/uploads/2019/04/blender.png" alt="" class="wp-image-1117" /><figcaption>This is the interface you should see</figcaption></figure> <!-- /wp:image -->

<!-- wp:paragraph -->

If you're not familiar with Blender, you are probably wondering what all of these icons are. Don't worry, everyone went through this. What I want you to do is **click on the cube until an orangish outline shows up**. You just selected the cube in a mode called *Object Mode*. Modes in Blender a like specialized workshops, each one allows you to modify the object you selected but they have specialized features, like painting the model or sculpting it.

<!-- /wp:paragraph -->

<!-- wp:paragraph -->

We are just going to focus on the modeling mode called the *Edit Mode*. To enter this mode, **press tab with the cube selected**. The model's color should have changed to be all orange. Now you can see the vertices, the edges and the faces we talked to in the first part of this article.

<!-- /wp:paragraph -->

<!-- wp:paragraph -->

*You can undo an action with ****CTRL + Z**** or redo it with ****CTRL + SHIFT + Z****, and if you modified something you didn't want to just close and relaunch Blender, everything will be back in place*

<!-- /wp:paragraph -->

<!-- wp:paragraph -->

Now with everything selected (= full orange in Edit Mode), press **CTRL + B and drag your mouse towards the opposite of the cube**. This will create what is called a *bevel*. You can control its precision by scrolling with the mouse wheel. Then when you are ready **left click** to keep the changes. If you wanted to cancel the action you would just have to **right click**.

<!-- /wp:paragraph -->

<!-- wp:paragraph -->

**Press tab again** and you will get back to Object Mode. Then **right click with the cube selected** to open up a contextual menu. Its content will change depending on the context, for example if the mode is different. Then **click on *Shade Smooth*** to smooth the model.

<!-- /wp:paragraph -->

<!-- wp:paragraph -->

*Taddaaaa you made your first model !*

<!-- /wp:paragraph -->

<!-- wp:heading -->

## It's not the end

<!-- /wp:heading -->

<!-- wp:paragraph -->

Of course, I simplified a lot the process and did not explain everything, and with time and practice you can make amazing models. This tutorial is just meant to make you do something, even if you knew nothing about 3D modeling. In fact, we tend to avoid being uncomfortable and face the unknown, so people often struggle to start something. ***Start before you are ready***.

<!-- /wp:paragraph -->

<!-- wp:paragraph -->

Now, you also need to consider how much time you want to invest into learning 3D modeling. It is a long process. You will need to spend hundreds of hours if you want to create decent models. You *will* struggle. But you will learn something new each time. And there is no end to how much you can learn.

<!-- /wp:paragraph -->

<!-- wp:paragraph -->

*Thank you for reading to the end. If this article helped you, please consider sharing it with your friends or leaving a nice comment as it will help me out too ! I will also post other articles related to this topic so stay tuned. And if you have some questions, do not hesitate to contact me !*

<!-- /wp:paragraph -->

 [1]: https://www.blender.org/
 [2]: https://www.autodesk.fr/products/maya/overview
 [3]: https://www.maxon.net/fr/produits/cinema-4d/cinema-4d/
 [4]: https://www.blender.org/download/
 [5]: https://www.youtube.com/watch?v=lPVpg4_POww
 [6]: https://www.youtube.com/user/AndrewPPrice