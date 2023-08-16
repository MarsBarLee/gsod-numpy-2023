Snippet from the 2023-08-14 NumPy Documentation Meeting notes. For the full meeting notes, check https://github.com/numpy/archive/blob/main/docs_team_meetings/docs-2023-08-14.md

---

**Present:** Mukulika, Jules, Ankur Singh, Mars, yanliang, Priyanshu Prajapti

## New Topics
- **Review #2** for GSOD-NumPy 2023
    - [Link to Script](https://docs.google.com/document/d/1fjLTDqSkcKMxo8oSTRThllBFpjo5rXS9/edit?rtpof=true&sd=true)
    - Script focuses on a group of students learning how to contribute to NumPy by creating an issue for a usability problem
    - Hosting a review session at the **next NumPy Community Meeting on August 16**
    - [Github thread](https://github.com/numpy/numpy/issues/24382) and Google Docs will be open for the next two weeks and **close on August 23**
    - Questions from previous drafts 
        - What science class are these grad students taking in this story? -> Microbiology
        - Should the class they're taking be based on a previous class Ross taught? NE 204 - [Advanced Concepts in Radiation Detection and Measurement](https://ne204-fall2018.github.io/pages/course-overview.html) -> Yes, but script does not go into detail, more general focus on 'live cell imagery'
        - Do these images linked in this thread explain live cell imagery correctly? -> Made an attempt on [page 2](https://docs.google.com/document/d/1fjLTDqSkcKMxo8oSTRThllBFpjo5rXS9/edit#bookmark=id.1fob9te)
        - Are the students operating narray for image processing of the cell images?
            - Made an attempt on [page 2](https://docs.google.com/document/d/1fjLTDqSkcKMxo8oSTRThllBFpjo5rXS9/edit#bookmark=id.1fob9te)
            - Resource I referenced: https://note.nkmk.me/en/python-numpy-image-processing/
        - Do all students have the npz file a dataset they downloaded for the class? Or does each student have their own npz file, from their microscope/lab? -> In script, each student's work is bundled together, making it hard to know whose cells are whose
    - Some specific parts I would like feedback on:
        - **Themes**
          - [On Page 5, ](https://docs.google.com/document/d/1fjLTDqSkcKMxo8oSTRThllBFpjo5rXS9/edit?disco=AAAA3sVZK9Y)does this panel accurately show the tie between open source and open science?
        - **Story and Pacing**
          - Does this seem like a reasonable amount of content to cover in 16 pages?
          - Do the three students interacting together feel realistic?
            - eg Since they're beginners, they don't at answer immediately
            - eg not too mean-spirited? They argue, to show different approaches
        - **Accuracy**
          - [On Page 3](https://docs.google.com/document/d/1fjLTDqSkcKMxo8oSTRThllBFpjo5rXS9/edit?disco=AAAA3sVZK9c), how accurate is the .npz code?
          - [On Page 7](https://docs.google.com/document/d/1fjLTDqSkcKMxo8oSTRThllBFpjo5rXS9/edit?disco=AAAA3sVZK9k), does the visual metaphor of the NumPy issue tracker as a bulletin board make sense?
      - Comments and Next Actions from today's Docs call
          - Pacing, Summary of Microbiology and Open Scienece looks good
          - Mars to follow-up with Mukulika
              - on getting full printout of npz to better represent npz 
              - visual representation of narray and image processing

    - **Previous steps**:
        - Review #1 (July)
        - Outlining stage for GSOD-NumPy 2023 (May 15-26):
        - Gathering community input stage and 3 brainstorming sesions
            - At Newcomer(May 4) NumPy Docs (May 8), Commmunity (May 10)
            - [Link to Google Jamboard](https://jamboard.google.com/d/1j_rEIslOh59N9cLGU1VGc7rTc88SuLTi7l4YqTqAULc/edit?usp=sharing)
            - [Summary from Brainstorming Sessions](https://github.com/MarsBarLee/gsod-numpy-2023/blob/main/outlining/summary-from-brainstorming-sessions.md)