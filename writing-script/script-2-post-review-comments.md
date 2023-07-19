# Script 2 Review: After the Review
Thoughts and next steps

## Summary
- Got 80% there, working on smaller 20% now
- Suggestions: 
  - Rewrite parts of story to remove professor character
  - Add more of PR maker
- Discussion: How much detail do we need in showing steps?
  -   3 factors:
        - scope
        - how much would these characters actually know
        - best practice
  - Show, don't tell vs DRY
  - In-between: characters talking over diagrams
  - In-between: Link out to more detailed resources
- PR maker scenes
  - I talked to (maintainer) in the community call last week and he said...
  - Show flipside, someone more experienced and how they weigh and perceive process
    - Backwards compatibility, taking in maintainer's comments
  - Maybe this one remembers this was brought up as issue before but before my time here...

## From Review session
- **Comments and Questions on Overview**
  - Is this a story that will continue with same characters?
  - Difference between big picture contributor pathways and smaller scope story, early contributor experience
  - OK to no go into detail about NPZ example
  - Understable to scope smaller
  - Great to have high-level goals: eg target audience, aim to please everyone will not please anyone
  - **Solid foundation with reasonable scope**: expanding can get too much
  - Coming at complete opposite approach: **start with narrative**, highlight how a community driven open source looks like
    - eg this is the contributor workflow diagram vs virtue of story itself where students try to solve problems themselves

**Comments and Questions on Script**
- Demonstrates but not over explains
- **Documentation has not told story yet**, in dry text, contributor guide, how it's supposed to work 'please comment on mailing list' but in practice, people may not read in full,
- Everyone's impression of 'how does NumPy get developed?', demystify
- Concept of **authority figure**: Maybe dropping the Professor entirely?
  - Ross motivation: if not professor, "how do raise this issue", rely on themselves, no appeal to higher authority for first idea, less top dow, don't need phD already
  - Constrict the scopes: more focused on open source part, professor reinforces the academic angle, "who do we tell?!", find the issue tracker
- Suggestion: Remove professor, 9000 miles away, **PR maker, no direct communication between PR maker to students, which is often the reality. See through screen and Github, know it's a real person, no one directly tells them yes or or no until someone else comments. Reflects asynchronous and distributed nature.**
  - See the email notification: students response of 'OMG what now?' again
  - If remove professor, can be a more general scenario, eg hobbyists
- When students are making the issue: sort issue tracker to see if anyone has made an issue
  - IRL: npz archive issue from 10 years ago,
    - Maybe for narrative, no previous issue shows up
  - Opportunity to highlight that best practice
  - How much information it ends up being?
  - 3 factors:
    - scope
    - how much would these characters actually know
    - best practice
  - maybe someone comments later, "can you show code more specific"
  - Lead to question about 'ask the mailing list first'
    - Answer: For bigger feature request that may break backwards compatibility, should ask mailing list, even if not aware it could.
    - In reality of asking mailing list, more stringest side, more about mailing list, could lead to another rabbit hold
    - What usually happens: people make issue, then move bigger conversation to mailing list
- Tendency for documentation to overexplain,
- Can use comic narrative to open conversation about templates as possibly univiting, or to ask mailing list
- Next steps: Answer on document, Slack, meet at next NumPy Docs

## Next Action #3: What does it take a PR to be implemented?
Suggestion: Remove professor, 9000 miles away, PR maker, no direct communication between PR maker to students, which is often the reality. See through screen and Github, know it's a real person, no one directly tells them yes or or no until someone else comments. Reflects asynchronous and distributed nature.
- See the email notification: students response of 'OMG what now?' again
- Students follow along discussion in email thread, there's a maintainer comments or approve it, what does that
- See comment about "impleemnt a \_\_repr\_\_ in the direction…" , students wouldn't know what that means but PR maker know
- Separating development and release difference? Comment, someone comments back "change will be revealed next release"
- Maybe too much info
    - One implementation: two panels:

- Hey did you see the PR related to our issue got merged last night?
- Yeah I think that means that it will be changed in next release cycle
- Could be another feature

