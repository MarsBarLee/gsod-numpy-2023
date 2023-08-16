Snippet from the 2023-07-03 NumPy Documentation meeting notes. For the full meeting notes, check https://github.com/numpy/archive/blob/main/docs_team_meetings/docs-2023-07-03.md

---

## New Topics

Present: Mukulika, Ross, Mars

- **Review #1 stage** for GSOD-NumPy 2023 Completed
    - Recap from Reiew during NumPy Community Meeting, Juen 21
        - Move away from sprints
        - New idea:
            - Maybe start with a character in classroom (meteorology thesis character)
            - NPZ archive, why won’t it work like a dictionary?
            - Ross opened issue, Ganesh wrote implementation, Sebastian and Ross review
            - NumPy is driven by people who use it
        - Sprints: prehaps later issue or chapter
    - Next steps
        - Follow-up with Ross for specific example
        - Make new outline
        - Make new concept art with lab
    - Story
        - Named arrays inside archive, couldn't find out where the names where, the docs have a files attribute that tells you the name, why can't you see the names as is, a usability shortcoming
        - This is the type of feedback NumPy wants from users and scientists
        - Bunch of students  download this dataset, why can't I tell
        - Terminal
        - They figure out, "Hey I but we're not the only people who had this problem"
        - Was brought up 12 years ago by (name), one thumbs up
        - In story: Have Github, but never made an issue before
        - What is the work that the students were doing?
        - Cell imaging data, single cell microscope data stored as numpy arrays
        - How familiar are the students with Github? Showing the entire journey, looking up numpy
        - Either people might be interested
        - At end, show that some actions done by people
        - At ending: 2 months later, new microscope data, that was our idea, version release, 
        - type in file name, says 'cell'
        - "This does drive me nuts, I want to try fixing it"
        - Implementator has Credit in Github history, mailing list release 
        - Let's go on community meeting next week, saw it on the mailing list
        - Seperate, possible example: This case, positively received and implemented. But in reality, many issues brought up not implemented, "I wanna make new function" Response is No, espcially for API addition.
        - Tools and visuals; data = np.load, achive npz
        - next line, I know this archive contains arrays but how do I access them? What are the arays caled
            - Don't get taught version work, deprecation, "Should we expand the API", subjective design, harder to capture
            - Emphasize **Backwards compatibility**, "I wish this function accepted these arguments, unpacked tuples", "We're not likely to accept it, propose it to the mailing list" "Here's the reason why, not because you're idea, we might have wished we designed this way, snapshot to grad students code, if change than breaks"
            - Many people not learn about backwards compatibility formally in school, abosrob via osmoosis, how ties to decision making
    - Links
        - Issue Ross made: https://github.com/numpy/numpy/issues/23319
        - PR Ganesh implemented: https://github.com/numpy/numpy/pull/23357
        - Sebastian and Ross review: https://github.com/numpy/numpy/pull/23357#pullrequestreview-1336728619
    - Concept Art from review
        - 1. How do you use NumPy? ![](https://hackmd.io/_uploads/rJit636w2.jpg) 
        - 2. How did you start using NumPy? ![](https://hackmd.io/_uploads/ByOca3TDh.jpg)
        - 3. How do we start a sprint? ![](https://hackmd.io/_uploads/ByHip36Dh.jpg)
        - [Link to full Concept Art prompts](https://github.com/MarsBarLee/gsod-numpy-2023/blob/main/outlining/concept-art.md)
    - Previous steps:
        - Completed Outlining stage for GSOD-NumPy 2023 (May 15-26):
        - Completed Gathering community input stage and 3 brainstorming sesions
            - At Newcomer(May 4) NumPy Docs (May 8), Commmunity (May 10)
            - [Link to Google Jamboard](https://jamboard.google.com/d/1j_rEIslOh59N9cLGU1VGc7rTc88SuLTi7l4YqTqAULc/edit?usp=sharing)
            - [Summary from Brainstorming Sessions](https://github.com/MarsBarLee/gsod-numpy-2023/blob/main/outlining/summary-from-brainstorming-sessions.md)