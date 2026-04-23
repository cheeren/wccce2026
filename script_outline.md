# Everything I Know About Teaching I Learned at Puzzled Pint
### WCCCE 2026 — Script Outline
*~60 minutes. Community conversation, not lecture.*
*Placeholders marked **[DEMO]** and **[TABLE ACTIVITY]** are presenter-led.*

---

## 0. Before you begin

Room is set up with Jotto word list on screen. No title slide.

**Bring:**
- Jotto cards
- Giant Pez dispenser
- Beach ball
- Euler's Formula index cards
- Table topic handouts (dry/canonical topics from various courses as seeds)

---

## 1. Opening — Jotto  *(~8 min)*

**[DEMO: Jotto]**

*Leave room while audience picks a word. Return to back. Play from decision tree slide.*

::: notes
Jotto slide w 16 words should also have instructions: 
As a community, after I leave the room choose ONE WORD that I will guess when I return in 60 seconds. When I return I will ask "does everyone in the room know THE WORD?" 

My script: reappear at the back of the room and ask everyone to turn to look at me. Advance the slide so I can see the decision tree (make sure fonts are big enough!).
:::

**After the game, walk to the front:**

> "That's a decision tree. What makes a tree good or bad? What's the shortest tree we could hope for? Wait wait, this isn't class...you don't have to answer."

> "Welcome! I'm Cinda, I teach CS at UBC, and I'm here today to discuss our common challenges. Isn't it funny that you know EXACTLY what they are!!"
*Pause.*

---

## 2. Framing —   *(~3 min)*

I've had a crazy year! Two new courses, another significantly reworked. My course-design motor is still on overdrive so it's the only thing I'm prepared to talk about.

::: notes
I will be presenting from my ipad, so i can circle the Learning Activities part of the equation. SHould i take a poll to see what people are most interested in hearing about? LOL if they say assessment!!
:::

Name the scope (on a slide): course design = assessment + learning activities. This talk is about **learning activities**. Assessment is its own desperate conversation — worth having, just not today.

::: notes
does the next bit go on a slide as foreshadowing, or should i just reveal and review?
:::
Set the contract:
- A methodology
- A list of examples — you pick two to go deeper on
- Research that explains why it should work
- One big reframe about what's changed

*"I've actually prepared 20 talks today. You're choosing 2."*

---

## 3. The student who's doing fine  *(~5 min)*

::: notes
Why are we revisiting learning activities? Didn't we solve this with flipped classrooms? Flipped == content outside, practice inside. Good, but we need to evolve those ideas to re-examine the purpose of the room (not just practice).
:::

> "Imagine a student who never comes to class. Never posts on Piazza. Never joins a study group. And scores well on assessments. They're not struggling. They're not cheating. They have a patient, knowledgeable, infinitely available resource — and it's 'working'."

*Pause. Let it sit.*

> "So what's missing?"

*Don't answer yet. Let the room feel the discomfort of not having an easy answer.*

That student is not a hypothetical. You're seeing them multiply:
- Attendance is falling
- Piazza is quieter — students aren't asking each other questions anymore
- Students are more reticent to participate when they are in the room
- And the one that stopped me cold: *"What did Claude mean when they said..."* — they're not forming a question to bring to the community. They're outsourcing the comprehension itself.

> "None of this is data. It's what I've been noticing. Raise your hand if you've been noticing it too."

*Pause.*

> "The student who's doing fine alone — they're getting the grades. But they're missing something they don't know exists. And it's our job to invite them to it."

---

## 5. Learning in community  *(~4 min)*

> "The community doesn't support the learning. The community produces it."

This is not a theme of the course design. It's the **substrate** — the medium everything else runs on. Three ideas, briefly — there's research behind all of them, and we'll get there.

**Collective intelligence** — groups produce solutions no individual could reach alone. Not because someone in the group is smarter, but because the interaction itself generates something new. You've felt this. The study group that cracked the problem nobody could crack alone. That's real, and it's measurable.

**Situated learning** — learning is individual, but the conditions that produce the deepest learning are communal. A community of practice generates engagement and discovery that a 1:1 interaction structurally cannot — not because it's bad at it, but because the interaction type doesn't allow it.

**Transactive memory** — groups develop a shared awareness of who knows what, and divide cognitive labor. When someone you trust carries part of the cognitive load, your own brain is freer to be creative. Again, structurally impossible 1:1.

*[Puzzled Pint — I'm a learner in this context too. Monthly puzzle-solving event with a group. I've experienced all three of these firsthand: solutions that no one in the group could have reached alone, but that everyone feels like they conquered, learning that only happens through doing it together, and the freedom that comes from trusting someone else to hold part of the problem.]*

> "Every workplace is a group project. We're practicing."

---

## 6. Here's my year  *(~3 min)*

*Show the list of 20 activities. Don't read it aloud. Give them 20 seconds to scan.*

The point is volume and variety: art, music, nature, wellness, mystery, games, biology, literature, discrete math. Let the list speak for itself.

> "I'm going to show you two of these."

---

## 7. Deep Dive 1 — Candy Hearts Factory  *(~10 min)*

*Five slides, one per methodology step. Don't announce the framework — let the design decisions speak.*

**i. Know the canon**
Here's how stacks are normally taught. LIFO. Push. Pop. Peek. They can get this anywhere, any time. I assume they have it.

::: notes
show the Pez slide (classic stack ADT slide)
::: 

**ii. Find the joy**
It's the night before Valentine's Day at the candy heart factory. The hearts got mixed up on the conveyor belts.

*[Candy Hearts story and setup — conveyor belts as stacks, personalized wellness message as output.]*

::: notes
Include 2 friends' names as the characters. I'll ask them to read their parts aloud. 
:::



**iii. Make them build**

::: notes
load the PL activity, with the solution already in place? i'll have to check -- maybe we can live code it...
:::

AoC inspired the puzzle structure. An agent helped build the personalized instances. The vision was mine; the execution was collaborative.

Each student gets a unique input — their own factory floor. They execute the stack operations themselves, in code, before knowing what they're building toward.

*[Show notebook workspace.]*

**iv. Ground the abstraction**
The conveyor belt is a stack. What does the metaphor hold? LIFO — the last heart placed is the first to move. What does it miss? Conveyor belts don't usually have a single exit point. Name the gap. Students who understand why the metaphor approximates understand the concept itself, not just the analogy.

**v. Build a narrative**
The conveyor belt story uses actual student names. The preamble — the animated story that sets up the puzzle — has *their* names in it. And what happened, without being asked: students started reading their lines aloud. Spontaneously. The room performed the story together.

I didn't design that. I designed the conditions for it — their names, a story worth telling — and the community produced the moment.

What word is spelled out by the letters on top of each belt? Every student's answer is different. Every message is personal — "you got this," "breathe," "keep going."

> "They learned stacks. They also got a Valentine. And they performed it for each other without anyone asking them to."

---

## 8. Deep Dive 2 — Euler's Formula  *(~10 min)*

*Same five-step structure, but reordered — the canon comes last. By now the pattern starts to feel familiar — audience begins to recognize it before it's been named.*

**i. Find the joy**
*[Distribute index cards — graph on one side, three numbers on the other, graph-side up.]*

> "The graphs are for a different activity. Ignore them. Flip your card over. You've each got three numbers. What relationship between them holds for every card in the room?"

The misdirection is the whole setup.

**ii. Make them build**
*[60–90 seconds. Students find the pattern: one number + 2 = sum of the other two. Hear a few conjectures. Don't confirm. Say: "Now flip your card."]*

Now you have a graph AND three numbers. Which number is which? Match them to vertices, edges, faces.

**iii. Ground the abstraction**
> "Test your hypothesis. Look at a neighbor's card. Does your rule hold for their graph too?"

This is the moment community becomes epistemologically necessary. A student cannot verify V − E + F = 2 from a single graph — they need other cases. Their neighbor's card is experimental data they couldn't generate alone.

Common sticking point: the outer face. Students almost always undercount by one until someone in the room names it. *[Beach ball — on a sphere, every region is bounded. The outer face becomes obvious.]*

**iv. Build a narrative**
The group converges on the formula. Someone will write it on the board before you do. Let them.

::: notes
I'll have someone write it on my tablet. Need slides:
1) number puzzle instructions. Student writes relationship on my tablet. 
2) graph puzzle instructions. student writes definition of vertices, edges, and faces.
:::

> "No one could verify this alone. You needed other people's cards. Their graphs were your experimental data. The room was the instrument."

**v. Know the canon**
*Now* put V − E + F = 2 on screen.

> "Did you need me to tell you that?"

This is the standard textbook formula. Proof by induction. They can get it anywhere, any time. But they just *discovered* it — in a room, together, from data they couldn't have generated alone.

---

## 9. Name the methodology  *(~5 min)*

> "You've now seen this twice. Here's what it is."

**Community as foundation — frame this first:**

> "All of these activities assume a room. They are designed for a cognitive environment that only exists when people are learning together. Community underlies all of it."

**The five components:**

1. **Acknowledge the canonical treatment**
   The standard exposition is freely available — textbooks, tutors, AI. I assume students have it. My job is not to replicate it. It's to do something they couldn't get anywhere else.

2. **Situate in an authentic, motivating context**
   Autonomy, competence, relatedness — all three must be present for deep engagement. Autonomy-supportive instruction grounded in real problems with real stakes. I call it: finding something I actually want to talk about. It turns out those are the same thing.

3. **Design for active knowledge construction**
   Curiosity is a drive state — like hunger. You don't create it by delivering content; you create it by withholding just enough. Never give away the answer before they've felt the question.

   > "Someone will tell you — and they've told me — that learning isn't always comfortable. They're right. But I'd push back on what that means. Joyful learning is not easy learning. It's learning where the hard thing feels like a puzzle rather than a punishment. Puzzles are full of delightful failure. The discomfort is real — what changes is the emotional valence around it. You're not failing, you're narrowing the space."

4. **Ground the abstraction**
   Connect the abstract concept to something students already understand — through their bodies, their senses, or a familiar structure. A Pez dispenser is a stack. A human pyramid is a heap. Hearing a hash table slow down teaches load factor before the formula does. A **metaphor** maps relational structure; an **embodied** activity maps physical experience; a **sensory** strategy maps perception. All three give students a way in before the symbolic treatment arrives.

   When you use a metaphor: know what it holds and where it breaks. Name the gap explicitly.

5. **Culminate in authentic production**
   Don't let them leave without having made something they didn't know they could make. Something real, in the room, together.

*Note: this methodology is a retrospective analysis, not a blueprint. I built the lessons first and noticed the pattern after. That makes it more credible — a description of things that worked, not a framework imposed in advance.*

---

## 10. Table activity  *(~15 min)*

**[TABLE ACTIVITY]**

> "You don't have to redesign your course. Pick one topic you teach — something canonical, something a little dry. Run it through the five steps."

*Template at each table:*
1. What's the canonical treatment? What do students already have access to?
2. What's a joyful, authentic application?
3. Where can you inject a puzzle or a gap?
4. What metaphor holds? What does it miss? What could be made sensory?
5. What would students make or do — that only works in a room?

*~5 min introductions, ~10 min brainstorm, brief share-out.*

> "Something will come out of this activity that surprises you. When it does — that's the c-factor. Live. In this room."

::: notes
should i seed the tables with topical ideas? or maybe people just want to share what they're already doing?
:::

---

## 11. Why it works — the research  *(~5 min)*

> "I promised you research. Here it is."

*This is the single research beat. Everything cited earlier without attribution lands here. The audience has felt all of it — now name what happened and why.*

**On community (the substrate):**

- **Collective intelligence** — Woolley et al. (2010, *Science*): groups have a measurable collective intelligence — a c-factor — not predicted by the average or maximum intelligence of members. Strongest predictor: social sensitivity, how well members read each other. The group produces solutions no individual could reach alone.
- **Situated learning** — Lave & Wenger (1991): learning is participation in a community of practice, not transfer of information. Novices move from periphery to center by doing real work alongside practitioners. Structurally impossible in a 1:1 interaction.
- **Transactive memory** — Wegner (1987): groups develop shared awareness of who knows what and divide cognitive labor. The group itself becomes a cognitive system. Also structurally impossible 1:1.

**On the methodology:**

- **Curiosity enhances memory** — Gruber et al. (2014, *Neuron*): curiosity activates the dopamine reward system and enhances hippocampal memory consolidation. Curious students remember more of everything around the answer, not just the answer itself. This is the mechanism behind step 3 — open the gap before you fill it.
- **Curiosity as a drive state** — Loewenstein (1994): information-gap theory. Curiosity is triggered by a perceived gap in knowledge — like hunger. You don't create it by delivering content; you create it by withholding just enough.
- **Enthusiasm is contagious** — Frenzel et al.: teacher enthusiasm predicts student intrinsic motivation and reduced boredom. Authentic enthusiasm at the start of term predicts autonomy, competence, and relatedness mid-year — all three SDT needs. Teaching what you find genuinely interesting is not indulgent. It's load-bearing. This is the mechanism behind step 2.
- **Self-determination theory** — Deci & Ryan (2000): autonomy, competence, relatedness. All three must be present for deep engagement. A tutoring system can partially satisfy autonomy and competence — but relatedness is structurally human.
- **Grounding abstractions** — Gentner (1983): structure-mapping — analogies work by mapping relational structure, not surface similarity. Barsalou (2008): grounded cognition — abstract concepts are understood through perceptual, motor, and situational simulations. Metaphors, embodied activities, and sensory strategies are all forms of grounding. This is step 4.
- **Authentic problems motivate** — PBL meta-analyses (2024, *Educational Psychology Review*): consistent positive effects on motivation, especially students' values and engagement. Design thinking meta-analysis (2024, *Nature/Humanities & Social Sciences*): r = 0.436, p < 0.001 positive effect on engagement, motivation, and academic achievement.
- **Delightful failure** — Rosenthal (TED2023): puzzle hunts are designed so that failure is part of the intended experience. The satisfaction comes *because* it was hard. Joy is not comfort — it's meaning.

---

## 12. Does it work? — two honest questions  *(~6 min)*

### 12a. Does the pedagogy work?

> "Does this work? Depends what you mean."

If you mean grades — probably not measurably better than a patient tutor. That's not the goal.

The goal is the student who comes back after the term and says they didn't expect to find this interesting. The moment in the room when something clicks for twenty people at once and you can feel it.

I have no controlled study for that. What I have is a methodology grounded in research that says *why it should happen* — and a room full of people who seemed to agree.

Separate the claims: the evidence exists for the underlying mechanisms — Gruber, Loewenstein, Frenzel, Gentner, PBL meta-analyses. The claim isn't that these specific lessons work. It's that they were designed according to principles that have evidence behind them.

> "Many of you have been doing versions of this for years. Is it working? I think we collectively have the evidence, even if none of us has published it."

*Invite the room. This is itself LIC in action.*

### 12b. Does it work if they aren't there?

> "All of this fails if they aren't in the room. And getting them in the room is maybe our hardest problem right now."

Three research ideas that frame the problem — and point toward solutions:

- **Present bias** — students aren't apathetic. On day 1 they genuinely mean to show up. But the cost of staying in bed is immediate and concrete; the value of LIC is real but deferred and invisible. Conviction doesn't survive that asymmetry without help. The design challenge is: how do we help students act on convictions they already hold?

- **Extrinsic vs. intrinsic motivation** — Deci & Ryan (2000): external rewards for intrinsically motivatable behaviors erode intrinsic motivation over time. Graded attendance may get bodies in seats, but it frames presence as a transaction. The strategies that work long-term are the ones that align with the student's own values — not ones that add an external cost to absence.

- **Belongingness** — informal learning communities (Discord, study groups) are self-selecting. You have to find them, be invited, feel welcome. The designed classroom is the only learning community where belonging is the default. For first-gen students, for students from underrepresented groups, for anyone who doesn't yet know anyone — the classroom may be the only community they have access to. When they opt out, the cost is unevenly distributed.

> "I think this area is rich for innovation and study. We need intrinsic strategies — ways to make the invisible cost of absence visible, to build peer accountability that's relational rather than institutional, to design lessons where presence is structurally necessary. I have some ideas. I suspect this room has better ones."

::: notes
**Ideas to have ready if the conversation opens up (time permitting):**

- **Structural design** — make presence epistemologically necessary. In the Euler activity, your card is someone else's experimental data. Your absence is visible to the community. No willpower required. Design aspiration: for every lesson, ask — is there a version where absence is felt by the group?

- **Named social accountability** — a specific person who expects to see them. Peer-to-peer, not to you. The only ask: if you're not coming, text them. This makes skipping a deliberate, visible choice rather than a passive drift. Gollwitzer's implementation intentions research: "I will go to class, and I've told Priya I'll be there" is categorically more robust than a held intention.

- **Making the invisible cost visible, repeatedly** — end of class, name what just happened that can't happen on a recording. "You figured that out together. That's not in my slides and it's not on any recording." Start of class: "34 people here. That's 34 perspectives on this problem."

- **Pre-commitment when conviction is high** — early in term, students write briefly for themselves: why LIC matters to them, what they're there for. Return it mid-term. Gollwitzer (1999): written implementation intentions significantly outperform held beliefs.

- **Recording/livestream as precondition** — I record everything and livestream every class. Students who genuinely can't be there have full access to content. This matters: the conversation about attendance only works if absence is a choice, not a constraint.
:::

---

## 13. Closing  *(~2 min)*

> "A tutoring system answers your question.

> A teacher opens the gap that makes you realize you had a question in you all along —

> and the moment you feel that gap, your brain is already learning."

---

## References

- Barsalou, L. W. (2008). Grounded cognition. *Annual Review of Psychology*, 59, 617–645.
- Deci, E. L., & Ryan, R. M. (2000). Self-determination theory. *Psychological Inquiry*. https://selfdeterminationtheory.org/SDT/documents/2000_RyanDeci_SDT.pdf
- Frenzel, A. C., et al. Teacher enthusiasm → SDT needs. https://pmc.ncbi.nlm.nih.gov/articles/PMC10105573/
- Gentner, D. (1983). Structure-mapping: A theoretical framework for analogy. *Cognitive Science*, 7(2), 155–170.
- Gollwitzer, P. M. (1999). Implementation intentions. *American Psychologist*, 54(7), 493–503.
- Gruber, M. J., Gelman, B. D., & Ranganath, C. (2014). States of curiosity modulate hippocampus-dependent learning via the dopaminergic circuit. *Neuron*, 84(2), 486–496. https://pubmed.ncbi.nlm.nih.gov/25284006/
- Lave, J., & Wenger, E. (1991). *Situated Learning: Legitimate Peripheral Participation*. Cambridge University Press.
- Loewenstein, G. (1994). The psychology of curiosity. *Psychological Bulletin*, 116(1), 75–98. Overview: https://pmc.ncbi.nlm.nih.gov/articles/PMC4635443/
- PBL motivation meta-analysis (2024). *Educational Psychology Review*. https://link.springer.com/article/10.1007/s10648-024-09864-3
- Design thinking meta-analysis (2024). *Nature/Humanities & Social Sciences*. https://www.nature.com/articles/s41599-024-03237-5
- Rosenthal, A. (TED2023). *The joyful, perplexing world of puzzle hunts*. https://www.ted.com/talks/alex_rosenthal_the_joyful_perplexing_world_of_puzzle_hunts *(URL unverified)*
- Wegner, D. M. (1987). Transactive memory: A contemporary analysis of the group mind. In B. Mullen & G. R. Goethals (Eds.), *Theories of Group Behavior*. Springer.
- Woolley, A. W., Chabris, C. F., Pentland, A., Hashmi, N., & Malone, T. W. (2010). Evidence for a collective intelligence factor in the performance of human groups. *Science*, 330(6004), 686–688.
