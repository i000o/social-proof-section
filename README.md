# Frontend Mentor - Social proof section

This is a solution to the [Social proof section on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA).

## Table of contents

- [Overview](#overview)
- [Goal](#goal)
- [Outcome](#outcome)
- [My process](#my-process)
- [Built with](#built-with)
- [Feedback](#feedback)
- [Lessons](#lessons)
- [Take forward](#take-forward)
- [Useful resources](#useful-resources)

## Overview

I need to use Grid and Flex for this layout, note the staggered nature of placed elements. I'm going to use a Desktop-first workflow and Sass to help me.

## Goal

My goal here is to practice Grid again, after some time, prioritise a desktop-first workflow where hopefully, my job at mobile will be simpler, and to use Sass to help me since I made great use of it on my last project. This challenge is a lot more content than I've worked with in the past few projects I've done.

## Outcome

![](/images/social-proof-desktop.png)

:jigsaw: [Live Site URL](https://i000o.github.io/social-proof-section/)  
:pencil2: [Solution URL](https://www.frontendmentor.io/solutions/grid-and-flex-social-proof-section-VUGR_eTz3P)

## Built with

:gear: Semantic HTML5 markup  
:gear: CSS Flex & Grid  
:gear: Desktop-first workflow  
:gear: Sass

## My process

:alien: I planned out my HTML elements carefully, as I knew this challenge had more content than I was working with in my past few projects.  
:alien: I divided the page into three sections within `<main>` 1 `<header>` for the title and subheading, 2 `<aside>` for the ratings and 3 `<section>` for the reviews.  
:alien: I made all the Flex elements first, as this was easy to do. I made the layout with a `display: flex` row with a `flex-wrap: wrap` to create the two main elements on top with the reviews underneath taking up the full width of the page.  
:alien: I was afraid that after I styled the page (which was easy), my Grids would disrupt the layout, but I think it was okay.  
:alien: I approached the grids next and found that my approach to creating the staggered effect worked. I divied the pieces into rows where I could have the elements start at different points but still be aligned. It was satisfying and looked good.  
:alien: I had a hard time with the background-image positioning. I've struggled with this before. Despite it being hard to see faded backgrounds, I find myself positioning it so specifically, only for it to break on viewport changes. I want to get better at foreseeing how to manipulate these better as it's not enjoyable to try to work around. My background also cuts off and I'm not sure which property to target to fix this. I think also working with two background images at once makes this a bit more complicated. I see other developers struggling on this challenge with the same thing so I'm not alone.  
:alien: I got stuck making the desktop design responsive. I felt there were a lot of adjustments that needed to be made as the viewport downsized. Although this took some time, the design is repsonsive, but I wonder if there could have been an easier way. I think if I had made the `<main>` content a flex row item sooner, I could have saved myself some work. This was largely because I didn't want the grid design on the second half of the page to jump from showing a 3-column to a 1-column, I wanted a middle ground, so I made a 3-tile pattern in an upside-down triangle shape. This section of the task took me the longest. I still wonder if my media queries could be even simpler.  
:alien: Once I got to mobile, it was easy to adjust. I had some margin collapsing on one side, but once I targeted the right thing and understood which property to call on, it was easy. I finished the mobile design quickly. Something I find difficult is that when I need to step away from something and take a break, I find that if I come back some days later, I don't remember exactly why/how I made the decisions I made before, so it takes me longer to decide on media queries than if I had done it sooner. But it stops me making detours at the same time so, who knows...

## Time taken

:alarm_clock: Desktop: 8hrs  
:alarm_clock: Mobile: 1 hr

## Feedback

I got helpful feedback from a fellow developer. Namely, they noted my incorrect use of semantic HTML, which was an important thing, so I'm glad they pointed it out.  
They also noted my targeting elements instead of classes, and how as my websites grow, this will become a bad practice because I'd be making global changes for specific elements which could cause a mess. I didn't realise this before, and will try to get out of the habit from now on. I knew I wasn't using classes for their proper purpose, but I didn't understand how yet.

![](/images/social-proof-feedback.png)

## Lessons

1. I need to learn about `overflow` as I don't understand this concept.
2. I need to work on my use of background-images as I don't understand this, either. Although, a lot of early developers seem to struggle here, too.
3. You don't need an `alt` class for an `<img>` if the image has a purely decorative purpose but no semantic meaning. It will only confuse screen readers.

## Take forward

:grey_exclamation: `Overflow`  
:grey_exclamation: `Background-image`  
:grey_exclamation: Be more aware of my semantic use of HTML, I initially used `<header>` incorrectly here.  
:grey_exclamation: I made good use of `:first-child` and `:nth-child()` here.

# social-proof-section
