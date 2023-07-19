Snippet from the 2023-07-17 NumPy Documentation meeting notes. For the full meeting notes, check https://github.com/numpy/archive/blob/main/docs_team_meetings/docs-2023-07-17.md

---

## New Topics

Present: Mukulika, Jules, Mars

- Scriptwriting stage for GSOD-NumPy 2023
    - [Link to Draft 3](https://docs.google.com/document/d/1AzK9Q1vCPjcK6j9pMQTOm6K-zMiZf5FU/edit?usp=sharing&ouid=110556856523158639329&rtpof=true&sd=true)
        - Script focuses on a group of students learning how to contribute to NumPy by creating an issue for a usability problem
    - Recap from Review with Mukulika and Ross last week, June 12
        - Remove Professor character
        - Show POV of PR maker and maintainer
    - Questions
        - **Is the change of POVs confusing?**
            - POV switches back to students in end
            - Explains some workflows, considerations that students wouldn't know. By removing Professor and Professor's explanation, need to have another way to show this. Thus add PR maker and maintainer pOV
            - Feedback: 
                - Good idea, shows 3  pathways, coming in earlier or later stages, equally important
                - Not confusing
        - **Is this the PR maker characcter first time making PR? Or more experienced?**
            - Wrote PR maker as more experienced, shows best practices, mentions other tools and keywords (checked issue tracker), communcation to other member (talked to maintainer in community call)
            - Shows 3 different levels of experience
            - Faster narratively. Showing someone making a PR for the first time would take more time, slow down story and less time for students
        - **How will the final product/comics be implemented on NumPy website?**
            - Shown how [previous work was implemented](https://github.com/alt-text-task-force/.github/blob/main/profile/scipy-2022-comic.md)
            - Host on NumpPy.org vs Docs site?
            - Maybe hosted on Docs, linked in Contribution page of NumPy.org
            - Factors: Image size, build time
            - Mukulika will look into it and Sphinx
            - Image format: PNG vs SVG. PNG pre-set, adds to doc size vs SVG building at time of render
            - Compare bigger size of docs with PNG vs build time with SVGs to make decision
        - **How do we feel about moving the scope from 'big picture contribution pathways' to 'characters entering open source'?**
            - Mars: Processing shift as creator
            - Started project with keen interest in mapping culture of open source, questions that community members engage in such as 'How do we turn first time contributors to second time contributors?' and 'How do we encourage tagging issues or documentation as equal ways to contribute?'
            - However, these questions may not be interesting to people not in the community- too niche to too few
            - Worhwhile to focus on a story. Also expands potential audience, everyone can relate to a human struggle vs debates on niche topic
            - 2 methods: Anthropological mapping vs story 
            - Suggestion to have both, start with worldbuilding, then shift to characters?
            - First thoughts to that suggestion: Maybe too big for current timeline. Similar to Tolkein or other big fantasy stories with lots of worldbuildling prologue before coming to Bilbo Baggins
            - Alternative: expand after GSOD 
    - **Next steps**
        - Check if 'big picture' story changes are moving in right direction
        - Get answer for smaller, detailed questions (presented an comments in Google Doc script)
        - Add page numbers for pacing
    - **Previous steps**:
        - Outlining stage for GSOD-NumPy 2023 (May 15-26):
        - Gathering community input stage and 3 brainstorming sesions
            - At Newcomer(May 4) NumPy Docs (May 8), Commmunity (May 10)
            - [Link to Google Jamboard](https://jamboard.google.com/d/1j_rEIslOh59N9cLGU1VGc7rTc88SuLTi7l4YqTqAULc/edit?usp=sharing)
            - [Summary from Brainstorming Sessions](https://github.com/MarsBarLee/gsod-numpy-2023/blob/main/outlining/summary-from-brainstorming-sessions.md)