---
title: "Example questions"
bookFlatSection: true
bookHidden: false
weight: 5
draft: true
---

# Example questions

Questions will be asked along five topic areas (e.g., "data preparation"), and complexity levels (e.g., knowledge, application, evaluation). For details, see [here](../exam#content).

Below, you can find a few example questions, which will be discussed with students in the final live stream of this course.

## Question 1

Imagine you have just enrolled as a thesis student, and you receive the following email from your advisor:

{{< hint >}}

Dear (name of student),

I really look forward to working with you on this exciting dataset, capturing the consumption of music on Spotify. I scraped it from spotifycharts.com a while ago.

As a starting point, please explore the data set using RMarkdown. I’d love to learn more about the data myself (haven’t looked into it yet) - maybe you can figure out a way to shed some light on how the start of the global pandemic (let’s assume that was March 2020) affected music consumption?

Please render your RMarkdown as a PDF document. Please keep any code that you’re writing (e.g., to load the data, or to explore and do some minor data preparations) visible so I can learn from it!

{{< /hint >}}

__Subquestions:__

1) Submit your PDF document for question 1 (*synthesis*, 10P)

2) What conclusions can you draw with regard to the suitability of the explored data for the research question? (*analysis*, 4P)

3) What are the main benefits of exploring data using RMarkdown documents, compared to “point-and-click” interfaces (e.g., SPSS), or manually investigating data by issuing commands in the R terminal? (*comprehension*, 2P)

## Question 2

Imagine you are a research assistant at Tilburg University, and you receive the following email from your project supervisor:

{{< hint >}}

Dear (name of student),

Tilburg University is on its way to not only publish papers, but also the code that generated the results. That’s extremely important for open science - i.e., allowing others to reproduce findings. In the attachment (download here), I’m sending you the code of my empirical project. Admittedly, it’s not very well structured (e.g., directory structures are absent), but at least I have a common R file (“run.R”) that ties all the parts together.

Can you apply your learnings from dPrep on this repository (e.g., https://dprep.hannesdatta.com/docs/tutorials/workflow/)? Your deliverable is just a link to a (private!) GitHub repository.

Create a proper directory structure (e.g., pipeline stages, see run.R for some ideas),
Separate source code from generated files
Have a proper readme at the repository
Ignore files that should not be versioned using .gitignore
And remove run.R and replace it by a proper makefile for this project.

I really look forward seeing your work.  Please work in a private GitHub repository, and add me (username: hannesdatta) as your collaborator so I can see your code.

{{< /hint >}}

__Subquestions:__

1. Please submit your GitHub link with your end-to-end GitHub workflow using make (*application*, 10P)

2. What are the benefits and drawbacks of run.R, versus the new makefile? (*comprehension*, 4P)

3. How could you determine whether the GitHub workflow runs well, beyond merely executing it yourself? (*evaluation*, 2P)


<!--

{{< hint info >}}

__This section is still work-in-progress (i.e., we are still adding examples and add code/data where needed).__

{{< /hint >}}
-->
