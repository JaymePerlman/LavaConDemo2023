---
layout: page
title: Labels
description: Designing and using labels to help keep everything organized
---

* TOC
{:toc}
<hr/>

## Color is critical

Don't create an "angry fruit salad" of labels in random, meaningless colors. 

You'll note that every issue, as part of triaging the intake stream, is assigned **one** of each color of label in the [Project](https://github.com/users/JaymePerlman/projects/1). This is deliberate and very important. 

- Affected functionality area of the imaginary product (dark blue)
- Affected team (dark teal)
- The type of intake source (light blue)
- Current status (green)

Each color corresponds to a category or type so you can **immediately** see when information is missing or duplicated. 

- An issue that has both a "Data Drop" AND a "New Article" label, which are both light blue, can't have come from BOTH sources. It's one or the other.
- If the issue has NO light blue label, then you immediately know that the intake source wasn't ever defined. [^1] 

## But color isn't everything

For accessibility purposes, add icons or emojis to labels, so they're not differentiated only by color. 

The [W3C Ssuccess Criterion](https://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-without-color.html) mandates that "color is not used as the only visual means of conveying information, indicating an action, prompting a response, or distinguishing a visual element."

## Add labels that you need

You can add any other type of label you need. For example:

- Sunsetting status _(when content needs to be removed from the original location after publishing)_
- Assigned story points for measuring team velocity per sprint
- Affected team name(s)
- Relevant topics or categories

Labels can also serve as triggers for Actions.

## But not everything needs a label

Many items such as assignees, reviewers, milestones, status, etc. are all tracked elsewhere already and don't necessarily need explicit labels. 
Dates and deadlines, for example, can be much easier to see in the Roadmap view of a Project. Issues can be grouped into Milestones instead of applying a group Label.

<hr />

[^1]: We track the source so that we can absolutely determine where an article's content came from. Was it part of a release, or part of a larger document, or did someone contribute it out of tribal knowledge?
