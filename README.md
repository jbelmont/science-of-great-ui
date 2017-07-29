# The Science of Great UI Review

This repository is a review of Mark Miller's Course (The Science of Great UI)

* [Introduction](#introduction)
* [Converting Light into Understanding](#converting-light-into-understanding)
* [Certainty, Ambiguity, Context](#certainty-\,-ambiguity-\,-context)
* [Grouping](#grouping)
* [Symbols](#symbols)
* [Cognitive Load](#cognitive-load)
* [Granularity](#granularity)
* [Visual Search](#visual-search)
* [Background and Foreground (part 1)](#background-and-foreground-part-1)
* [Noise, Weak Signal, and Clarity](#noise-\,-weak-signal-\,-and-clarity)
* [Recognition vs. Recall, Orienteering, and Paths](#recognition-vs.-recall-\,-orienteering-\,-and-paths)
* [Responsiveness & The Feedback Loop](#responsiveness-\&-the-feedback-loop)
* [Discoverability](#discoverability)
* [Wrapping Up Efficiency in Thought and Motion](#wrapping-up-efficiency-in-thought-and-motion)
* [Resources](#resources)
* [Personal Thoughts](#personal-thoughts)
* [Purchase the Course](#purchase-the-course)

## Introduction

* Mark Miller discusses high level concepts that the course will review
* Miller also talks about a concept called Dark Design patterns very briefly

## Converting Light into Understanding

* Interesting facts about the eye and brain are discussed
* The fovea is responsible for sharp central vision (also called foveal vision)
  * Necessary in humans for activities where visual detail is of primary importance, such as reading and driving
* Rods in Human eye
  * 120 Million
* Cones in Human eye
  * 7 million
* Fovea and rapid eye movement help make a visual field

> Most of what we think is true is a series of shortcuts designed to keep us alive

## Certainty, Ambiguity, Context

* Ambiguity makes **certainty** impossible
* Sufficient context is the cure for ambiguity
* The **Blivet** Anti-pattern happens when an ambiguous presentation is adjoined by conflicting **context**
* To fix the Blivet Anti-pattern, remove the conflicting **context**
* **RTFM** (Read the Freaking Manual) design smell occurs when there is excessive/redundant instructions on how to use (or not use) the UI.
* When the RTFM design smell is present, see if the UI can be **simplified** (to no longer need the instructions).
* If you can't fix the RTFM design smell, edit the instructions to use **fewer** words.

## Grouping

* Grouping is something the mind naturally wants to do
  * It's part of our attempts to reduce complexity
  * It's like a natural compression algorithm in our head
* We can group in a variety of ways to make it easier for humans
  * Containers
  * Proximity
  * Color (opacity, brightness, saturation)
  * Symmetry
  * Continuity (along a continuous line or curve)
  * Shape

## Symbols

* A simple image that represents something bigger, like an idea
* Complex detailed symbols take more time to parse than simple ones
* To make it easier to **recognize** symbols, they should be **distinct**
* Our minds have a huge capacity to associate meaning to symbols
  * Consider the alphabet
    * In english, 52 letters (Upper and Lower characters)
    * In Chinese roughly 30,000 to 80,0000 characters

## Cognitive Load

* Sharp corners seem to inspire a slightly higher cognitive load in the brain.
* We tend to see sharp corners as more salient **(important)** than obtuse corners.
* Use sharp corners for important corners **(a point)**
* Use rounded corners for everything else.

## Granularity

* We can increase overall message capacity by **combining** channels
  * This increases channel bit capacity, but it is not an additive operation.
    * (Other limits on our ability to handle complexity can also be at play)

* We may be able to reduce communication errors by:
  * Adding **redundant channels**
  * Adding **reference points**
    * Parts of Speech:
      * Nouns
      * Pronouns
      * Adjectives

* Channel capacity limits will be a constraining force on other guidelines.

## Visual Search

* Sampling Density inside the fovea is high.
* As we move farther from the fovea:
  * Sampling density diminishes
  * We lose color perception
* Peripheral vision detects motion and helps you balance and move through space.
* Our brains can search the entire visual field using parallel processes.
* Visual searches that heavily utilize our brain's cognitive powers:
  * Can operate only on a restricted portion of the visual field.

* When designing icons:
  * Avoid thin lines and tiny details
  * Thick lines and filled shapes are more easily seen in the periphery.

## Background and Foreground Part 1

* Backgrounds:
  * **Should be a solid color**

* Emphasis should match **Information Relevance**
  * Constrained by Channel Capacity Limits
    * No more than 3 levels in the brightness channel

* Background Color
* Reference Points and Relativity
* Minimum Distance for Readability
* Color and Perceived Brightness

## Noise, Weak Signal, and Clarity

* Hindering Clarity are 2 things:

1. Visual Noise
2. Weak Signal

## Recognition vs. Recall, Orienteering, and Paths

* Long Paths:
  * Are harder to remember (increased cognitive load, increased likelihood of mistakes)
  * Take longer to perform
  * More movement, more thought
  * Can induce fatigue

* Narrow paths:
  * Are harder to perform (require more precision)
  * Increase likelihood of mistakes

* Strenuous/steep paths:
  * Induce more fatigue

* Erratic paths (require context shifts)

## Responsiveness & The Feedback Loop

* Mark Miller discusses a tool that he built which you can find at github [HERE](https://github.com/MillerMark/FeedbackLoopExplorer)

## Discoverability

* Discoverability should be fluid and in parallel (avoid modal instruction)
* Discoverability should be close in proximity to the content of interest.
* Discoverability content should be concise and clear.
* Use images (especially when the text can become more concise)
* Live preview is the best discoverability
* When you invent new UI:
  * **Set aside time** in the **schedule** to design and implement good discoverability.

## Wrapping Up Efficiency in Thought and Motion

* Discuss how our brains work and interact with the world.
* Some short clips with music are presented.

## Resources

* A pdf is given at the end with more condensed notes on all the videos is given.

## Personal Thoughts

* Very impressive collection of strategies are presented, I am very intrigued with all the findings and think others will enjoy the course as well.

## Purchase the Course

Go to [Science of Great UI](https://app.deviq.com/courses/the-science-of-great-ui) to purchase and watch this great course.