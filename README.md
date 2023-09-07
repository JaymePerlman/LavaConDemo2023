# LavaConDemo2023

## How to use this repo

Clone it or fork it and do whatever you like to the copy. 
At this time I am not taking contributions, since I need this as-is to make my presentation at [LavaCon 2023](https://lavacon.org/)! 😄 But after that, we'll see how it goes.

## Licensing

This repository and contents are made available via the [Creative Commons Zero v1.0 Universal license](license.md) in order to provide the most benefit to the most people possible.
It'd be nice if you credited me, of course, but you don't _have_ to. Clone and enjoy.

## What's in here?

- A Project board with multiple views, a status board, and sprints for tracking, statusing, and communicating.
- The Project also has some built-in workflows to automatically add items and move them around when certain events occur.
- A few test Issues to populate the project and illustrate some points
- A few test PRs to populate the project and illustrate some cool features like Mermaid
- Some files so you can understand how the CODEOWNERS file works to protect content from unauthorized changes
- An Action workflow that automatically creates a new Sprint Ceremony issue containing an agenda template for your Sprint meeting every Tuesday. _(With an example option to change it to the first and fifteenth of the month if you run two-week sprints)_

- to be added
  - Pages publication
  - OpenAPI if I have time 

## Labels

You'll note that each category of label is the same color. This is deliberate and very important.

<details><summary>Click for a deeper dive into best practices for Labels</summary>
  
Don't create an "angry fruit salad" of labels in random, meaningless colors. Each color should correspond to some kind of category or type so you can easily see when information is missing or duplicated. If you see an issue that's both a "Data Drop" AND a "New Article", which are both light blue, then you immediately know that there's some kind of confusion. If there's an issue with NO light blue label, then you immediately know what's missing. For accessibility purposes, you can also add emoticons to labels, so they're not only different colors.

Every issue, as part of triaging the intake stream, will have one of each color of label:

- Affected functionality area of the imaginary product
- Affected team (who needs to know? this defines where the content will live)
- The type of contribution (new article, article update, etc)

You can add any other type of label you need. For example:

- Sunsetting status for articles migrated from elsewhere that will need removal from their original location after publishing
- Assigned story points for measuring team velocity per sprint

Keep in mind that many items such as assignees, reviewers, milestones, status, etc. are all tracked elsewhere already and don't need explicit labels. But you certainly can if you want to, and you can also use them to trigger more Actions.

</details>

## Milestones

I created one marking the first day of LavaCon. _(I BETTER be ready by then!)_ but you could define them by "the release date of the next version", or "the end of this calendar quarter", or any other date that's important to your planning.

## Reviewers

You _can_ assign a whole team as Reviewers, but if you do, it's best practice to use the Round Robin [assignment algorithm](https://docs.github.com/en/organizations/organizing-members-into-teams/managing-code-review-settings-for-your-team#routing-algorithms). This built-in functionality picks the 2 people out of the team who haven't received a review request for the longest time and assigns them as reviewers. You can assign more, but don't assign fewer than 2 in case someone's out of the office for a while. 

<details><summary>Click for a deeper dive into best practices for managing Reviews and Reviewers</summary>
  
If you just assign a review to "anyone on the team", sadly, everyone just assumes everyone else will do it and so nobody does it. If you pick two people, they're responsible for either doing the review or delegating it to someone who can. 

You can also define a "silence timeout" -- if after two weeks, nobody's reviewed it or left any feedback, that means they approve it and it gets published as-is. This policy will of course vary per company, but it does seem to make people pay attention!

Try to protect your contributors. If they feel they **must** do whatever the reviewer says, they can get discouraged from contributing. The author must _respond_ to feedback, but "No" is a perfectly valid response. The author can resolve all feedback to their own satisfaction; they are not required to do what everyone else says. _(Except in the case where Legal, Policy, Security, or similar entity is making a required change, of course.)_ If the person providing the feedback feels THAT strongly about it, they can file their own PR to change the file after it's published. That's how open source/inner source works.

</details>
