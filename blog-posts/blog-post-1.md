# First 2 months of GSOD-NumPy project

Hi everyone! This is an update on the first two months of working on the GSOD-NumPy project, the "NumPy Contributor Comics".

The goal of these comics is to show newcomers  how they can start contributing to NumPy. For more details on the timeline and backstory, check out the [project roadmap](https://medium.com/@marsbarlee/gsod-numpy-contributor-comics-project-roadmap-521280503fbd).

With this blog post, I aim to share not only the methodology of a visual contribution, but also the creative twists and turns. 

## Setting up my Repo
I've created a Github repository that contains all the artifacts for this project in the gsod-numpy Github repo. It's my effort to share non-code contribution on Github.
Graphic designers and artists usually host their work platforms that developers and open-source folks don't frequent, such as Behance and Dribble.
I've decided to meet where the NumPy community and comic's target audience gathers. I'm also familiar with Github, having used it for years before this project.

Artefacts in the repo:
- Concept art
- Brainstorming documents
- Scripts
- Community meeting notes
- Annoucements to mailing list

## Stages
In the past 4 months, we have finished major stages. The stages are:
- Brainstorming and Gathering Community Input
- Outlining
- Review #1
- Writing Script, Thumbnailing

### Brainstorming and Gathering community input
Coming into the project, I already had some prototypes from last year. These were inspired by conversations in the NumPy Community meetings. This provided a strong starting point, since it's easier to with a scribble instead of a blank page. 

I hosted brainstorming sessions in three community meetings in May 2023.
- [Community](https://github.com/MarsBarLee/gsod-numpy-2023/blob/main/brainstorming-artifacts/numpy-community-2023-05-10.md)
- [Docs](https://github.com/MarsBarLee/gsod-numpy-2023/blob/main/brainstorming-artifacts/numpy-docs-2023-05-08.md)
- [Newcomers](https://github.com/MarsBarLee/gsod-numpy-2023/blob/main/brainstorming-artifacts/numpy-newcomers-2023-05-04.md)
Each one links to the full meeting notes, if you're interested.

### Jammin' together!
I primarily used a Google Jamboard, a digital whiteboard. I wanted to encourage people to think in visual and non-linear ways. A digital whiteboard where anyone can leave comments, add and drag images around or even draw with their mouse was great for that.

I haven't seen digital whiteboards used before in the NumPy space, but similar tools such as FigJam and Miro are used by UX/UI teams.

In comparison, typing straight into the hack.md meeting notes felt a little stilted. That format reinforces the primacy of words over images, and I wanted to nudge it in the other direction. (If you're interested in reading some theory and unapacking of that, check out, Unflattening, a dissertion in the form of a comic book).

Each meeting had a good amount of prep-work. I released annoucements to the NumPy mailing list withthe dates I would host the sessions and links to the Jamboard.

I prepared the Jamboard beforehand. I didn't want to have only one slide with the prototype. Nor did I want it be too vague. Rather, I arranged it a comic pitch.

### Hosting the session
The beginning opens with the prototype and how it attempts o answer the reoccuring question of 'How do we increase the number and variety of contributions to maintain the long-term health of a project?'. The middle shifts to inspiration such as the Turing Way Community Handbook and The Manga Guide to Databases. All this is twirled up into the pitch of the NumPy Contributor Comics.

The last two slides posed key questions and the rest blank to be filled with sticky notes.

Each session took a minimum of 20 minutes. I didn't want to call for a seperate meeting for these sessions, but rather slot into existing meetings and adjust from there. So the longest session was a full hour, at the NumPy Newcomers meeting.

The biggest turnout was at the NumPy Community meeting with total of 9 people attending, higher than the usual of 4-6 people.

### Scooping up different opinions
By going to different community meetings, I was able to get scoop up different opinions. With Newcomers, there was a focus on non-linear pathways. At the Docs meeting, how the metaphor to explain contributon pathways may fall flat. A the Community meeting, the difficulty of quantifying the un-quantifable, especially in roles and expectations.

In this way, I conducted infomal user testing. I tested how users responded to the comics pitch. But it also opened a broader conversation of how the NumPy community is moving and if we want to continue or change the contribution experience.

It was great fun to doodle people's concerns, group ideas together by moving sticky notes, and compare people's experience in entering the NumPy space several years ago vs in the past few weeks.

Alas, the very strength of the Jamboard was also it's greatst downfall. As the Jamboard was not in a plain text format such as a Markdown document, it was archived as PDF in the repository. I also transcribed the major points back into text. Despite these extra steps, I felt that it was worthwhile to introduce such a powerful and fun collaboration tool.

### Outlining
After that social burst, it was time to squirrel away in solitude. I had to digest everything and turn a pitch into something more solid.

I sketched out Concept Art and typed up story arcs. Distinct characters with personalities started to form. These characters would tackle problems, help or antogonize each other, stand firm or come around. Writing dialogue was a matter of letting them speak.

I reached out to a fellow artist, Tony Fast, to give weigh in this process. He was the champion and editor for the Alt Text comics last year, and I wanted to continue our collaboration.

Since my skillset isn't common in the Scientific Python space, it was nice to talk in-depth about how creative work does and doesn't fit clean timelines, comic studies and story-telling.

### Community Review #1
For the review process, I brought the concept art and writing I made during the Outlining stage back to the community calls.

Since I haven't seen the community review a visual contribution on this scale before, I decided to highlight specific parts I wanted feedback in. However, since we were in the concept art stage, I let people know this is an early and malleable part of the artistic process. This way I could give a starting point and structure for the feedback, while also letting people branch out.

Some specfic parts I asked for feedback on:
Accuracy
- Is there an issue that was actually completed during a sprint, that can be used in the comics?
Character
- 3 types: over-confident, under-confident and just right
  - Over-confident: "I bet I already know how to do this!"
  - Under-confident: "Can I start working on this issue?""
  - Just right: "Let's review the documentation if this already exists and if I'm still not sure, I'll ask someone."

#### Feedback from community
One major piece of feedback was to move away from sprints, both as a narrative device and an example the community wanted to higlight.

My concept art focused on newcomers attending a sprint during a conference, since I thought it would be a natural starting to point. I also drew from my own experience hosting sprints and workshops. However, the community wanted to focus more on user-contributors, who are most likely to become repeating contributors.

Ross Barnowski gave a real example of users finding a usability problem, and how that led to a contribution. Specifically how his Niology students found it difficult to explore .npz files, the creation of an issue, and then a PR to change .npz behavior. ([Link to the issue, if anyone's interested.](https://github.com/numpy/numpy/pull/23357))

That led to us coining a key phrase: 'NumPy is driven by people who use it: scientists!'. So I left the call thinking how to incorporate a big story change, balance my own vision and take in the community's input.

### Writing Script, Thumbailing
Back to the drawing board! I decided to start writing the script in more detail. For this stage, I decided to take to squirrel away again and set up a call with the project mentors, outside of the usual NumPy community calls.

I followed-up with Ross and interviewed him to get more details on the story with his Biology students. I saw that the story could shift to be "based on a true story". 

However, this story shift provided a new challenge for me. Since I never conducted scientific research or was in a graduate program, I could not draw from personal experience. Instead, I focused on listening to others people experiences. Mukulika Pahari's persepctive as a recent student also helped me balance Ross' experience as a professor. These prespectives really helped me hone on the key theme of 'open science'.

## Next blog post
Thanks for reading! In my next blog post, I will cover more how the script and story develops, along with Community Review #2.