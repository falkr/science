# Peparation

This preparation contains **tasks**. To get the full benefit of the
seminar, you need to fill out the tasks while you read, either on a
printout of this document or on a separate paper. It is not important
that you answer the tasks correctly, but that you write down your
thoughts when the task is given, so you can reflect about how your
thinking changes over time.

This preparation also contains **guidelines** when applying design
science in your thesis. We will discuss them in the seminar. They are
included already now so you see what will be important.

:aside: Please feel free to send questions via [email](mailto:kraemer@ntnu.no) also during this preparation phase.

# Motivation

Before we begin, two explanations that may answer the two most likely
thoughts you will have now:

-   You may react to the word *design*. Why is it *design* science?
    Could there be a *technology* science? Or *engineering* science?
    Don't worry too much about the term *design*. We can for now think
    that it covers the fact that we need a scientific approach to
    something that is *designed* by humans, and by this we understand
    anything artificial, including algorithms, electronics, programs, or
    systems.

-   During this introduction you may think that someone wants to make
    life complicated for you by introducing a lot of new terms. We will
    talk about "treatments" and emphasize the difference between
    "validation" and "evaluation." Be assured, however, that this will
    make your thesis *easier* for you. We give you the words and a
    scaffolding for thinking about your thesis.

## The Difference Between What You Do, What You Find Out, and What You Write

We often hear the formulation _"I am writing my master thesis."_ This
shows the focus on the tangible product of the thesis, which is the
thesis report. That's understandable, given that students receive the
grades for their thesis based on the report. But focussing primarily on
the report is also limiting and doesn't help to understand what you need
to do. There are some other, equally critical concepts involved,
illustrated in the figure below.

---
type: figure
source: figures/triangle.svg
caption: "Difference between what you do, what you find out, and what you write."
---

The actual **result** of a thesis is **knowledge**, and that implies
*new* knowledge. The **report** only captures these results, that means,
presents the new knowledge. In addition, the report documents the
process how the results were acquired so that they are reproducible. How
do you get these results, this new knowledge? You do this by the actual
**work** that goes into the thesis. (Writing the report also constitutes
"work," but of a different kind we mean here.)

What this work is really depends on the nature of your discipline and
subject. Sometimes, knowledge is produced mainly through reading and
thinking. Sometimes, knowledge is produced by observation and
experiments. Sometimes, knowledge is produced by creating technology
artifacts and validating them.

Simply being aware of the distinction between these three concepts can
already help you to understand better what to do. Design science helps
you with reflecting what knowledge is and how to acquire it, planning
your work and making your report more explicit, helps you to plan and
perform the necessary work to produce new knowledge within engineering
disciplines.

:task: Sometimes, students think *"I have used too much time on these
measurements, they should thus also make up a considerable portion of
the pages of my report."* In the light of the division of work --
results -- report, what do you think about this statement?

---
type: lines
lines: 4
---

## Why is it good to have a method?

The aim of research is to acquire new knowledge. For a thesis, we could
naïvely say that you read about a problem, make some experiments and
build a prototype and then write about it. So why not just doing it?

**Think of sports.** You could just start running, and as long as you
are doing it for fun, that's okay. But assume you want to run a marathon
a few months from now with the goal of reaching a more ambitious finish
time. Soon you would ask how much running each day actually helps you to
reach your goal. Too little and you make no progress, but too much
exposes you to the risk of injury. Or think of strength training. How
much weight and how many repetitions should you start with? How quickly
should you increase? Or how much weight should you take off once you
make no progress anymore? Most likely, you will try to find a training
plan, either in the form of a book, an app or a personal trainer. A
training plan helps you to measure your progress, have an idea about how
to spend your effort wisely to reach your goals, and provide advice when
you are not reaching your goals.

So is design science like a training plan? Not exactly, since it does
not prescribe you what to do. But it provides a framework (the terms,
the structure) to think of how to plan your work. That's pretty useful,
and makes the following things easier:

-   **Asking the right questions**, and guiding your attention to the
    most important issues. Many students put a lot of emphasis on the
    implementation in the form of programming something. This can be
    useful, but can also be a waste of time if the implementation does
    not lead to new knowledge. Being aware of design science may reveal
    which work deserves more attention, and which tasks are actually
    useless. Distinguishing useful from useless tasks is sometimes not
    as obvious.

-   **Understanding the problem.** Many students invest too little time
    in understanding the actual problem first. Suddenly it is not
    obvious anymore why you do a certain thing. Once you reason about
    your work, you should at all times be able to tell *why* your are
    doing something.

-   **Planning ahead.** A thesis must be completed within a limited time
    frame, and many students are bad at planning ahead. (This applies
    not only to students.) Planning ahead can reduce effort and prevent
    you from doing stuff that is not necessary. Note that even in the
    best planned thesis you may choose a path that eventually turns out
    not to be fruitful. But you may reduce effort that would not be
    fruitful to begin with, choose the approach most likely to succeed,
    or at least not running blindly into walls.


# Design Science

The following is an introduction into the concepts of design science.
Naturally, this implies that you need to learn the definitions of some
terms. Focus in this part on remembering them and understanding what the
terms mean and how they are distinct. We will go through a series of
activities to further learn how to use these terms and apply them to
your own thesis.

## Natural Science vs. Design Science

You are probably aware of the general scientific method, which consists
of a systematic sequence of steps, namely observation, measurement, and
experiment, and the formulation, testing, and modification of
hypotheses. This method is used in the natural sciences, which deals
with explaining natural phenomena.

---
type: youtube
video: xG3-_tgDE0k
position: aside
caption: "If you are interested, have a look at this video from Sixty Symbols about
the scientific method."
---

Isn't it possible to apply this general scientific method also to
technology? Instead of phenomena created by nature, we try to understand
phenomena created by humans, that means, we try to understand
technology? Do we need another framework?

It turns out, that when we naïvely apply the scientific method of
natural sciences to technology, the result is not a very good fit. It's
like going hiking in jeans. They are technically pants but awful for
that purpose. You get the idea.

The method for the natural sciences is not a good fit because there are
more differences between natural sciences and technology:

-   The natural sciences intend to gather new knowledge about the world
    **without changing it.** When we develop new technology and do the
    research for that, we do so with the ambition to change the
    world.[^2]

-   Natural sciences are driven by knowledge questions, that means,
    finding answers to questions. Technology, on the other hand, is
    driven by the intention to solve or mitigate a problem, which is in
    turn driven by stakeholders, or people wanting to solve a problem.

But wait: Say we want to create a new, more effective antenna. Don't we
have to make experiments that explore, for instance, how
electro-magnetic waves propagate? Isn't that a classical problem of the
natural sciences, in this case physics? The answer is yes. Design
science is not an alternative to natural sciences. We will later see
that design science has access to all methods of natural sciences when
answering knowledge questions.

The differences between natural science and technology make it hard to
simply apply the general scientific method to a research project dealing
with technology. We often observe that technology researchers formulate
research questions to make their method appear "more scientific." But
this has often the opposite effect and rather makes the method more
elusive. Therefore, design science takes these two differences into
account, and applies scientific reasoning in the presence of technology
artifacts and the intention to change the world.

:task: Without reading any further, take your current thesis topic
and think of it in the framework of natural sciences. Can you write down
a question that characterizes the knowledge you would like to gain?

---
type: lines
lines: 4
---

## Artifacts in Context

Design science is the design and investigation of artifacts in
context [@Wieringa:2014]. Design science problems are *improvement
problems* [@Wieringa:2014]. The aim is that the designed artifact in
interaction with its context solves a certain problem. But what exactly
are artifact and context?

**Artifact:** An artifact can be anything designed and created by
humans, both as a real, physical object or an abstract concept. Example
for artifacts are:

-   Software
-   Hardware
-   Organizations
-   Business Processes
-   Services
-   Methods
-   Techniques
-   Conceptual Structures

**Context:** The problem context for the artifact can be anything that
interacts with the artifact or that has influence on it. Typically the
problem context for an artifact is not a single context, but consists of
elements like the following:

-   People
-   Values, Desires, Fears
-   Goals, Norms, Budgets
-   other artifacts, as the ones named above.

The context for one artifact can also be another artifact, for instance
when a system interacts with another system, but only one of them is
under research.

You may ask why it makes a difference to emphasize that research within
technology is not only about technology itself (i.e., the artifact), but
about the *artifact in context*. This distinction is helpful when you
think of what you should do in your thesis and how you should evaluate
it:

1.  Your thesis is not the same thing as an artifact that you create and
    describe in a report. Especially, an implementation is not the main
    result of your thesis. Instead, your thesis is about how an artifact
    solves a specific problem (in a problem context), and through a
    validation you demonstrate if or how effectively it solves that
    problem. An implementation may be a large part of it, but the
    validation and the description of the problem are essential.

2.  Many students (and supervisors) focus on the technology but forget
    to sufficiently address the problem context. This becomes evident
    when the thesis does not offer a good validation. Instead,
    addressing the problem will make it easier to also find good
    validation mechanisms and focus on them.

:guideline: In your work, be aware of artifacts and what the problem
is. Do not design an artifact without considering its problem context
and how artifact and context interact.


:task: What are possible artifacts for your thesis? What are
examples for elements in the problem context? List some!

---
type: lines
lines: 4
---

## Knowledge Questions vs. Design Problems

The core of design science is a separation of two different kind of
research problems: **design problems** and **knowledge questions**.
These correspond to the two different parts of design science, which are
**design** and **investigation**. In principle, anything we do in design
science belongs to either one of these activities. Before we argue *why*
this distinction is useful, let us first distinguish these two research
problems from each other.

**Example for a Design Problem:** Design an algorithm that recognizes
human activity based on accelerometer data from a wristband.

**Example for a Knowledge Question:** Is it feasible for patients in a
specific age group to wear a wristband?

<table class="table table-sm">
<thead>
<tr class="header">
<th>Design Problems</th>
<th style="text-align: left;">Knowledge Questions</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Calls for a change in the real world.</td>
<td style="text-align: left;">Does not change the real world, but asks only how it is.</td>
</tr>
<tr class="even">
<td>Solution is a design.</td>
<td style="text-align: left;">Answer is a proposition.</td>
</tr>
<tr class="odd">
<td>Solutions are many, and there is no single best solution.</td>
<td style="text-align: left;">There is one single answer only.</td>
</tr>
<tr class="even">
<td>Evaluated by the utility to stakeholder goals.</td>
<td style="text-align: left;">Evaluated by truth.</td>
</tr>
</tbody>
</table>


:aside: Difference between design problems and knowledge questions. Adapted from <span class="citation" data-cites="Wieringa:2014">[@Wieringa:2014]</span>


Often, students (and supervisors) are not aware of the distinction and
approach a design problem as a knowledge question. Then, instead of
writing:

> (Good:) Design an algorithm that recognizes human activity based on
> accelerometer data from a wristband.

They ask:

> (Not good:) What is an algorithm that can recognize human activity
> based on accelerometer data from a wristband?

Isn't the second one also a good question that can lead us to a good
solution? Consider again
table [\[tab:design-vs-knowledge\]](#tab:design-vs-knowledge){reference-type="ref"
reference="tab:design-vs-knowledge"}, and see what we wrote under
knowledge question:

-   We are not asking for knowledge about the world, but we ask
    implicitly to change the world, by introducing such an algorithm.

-   The answer to the question is not a proposition, but actually a
    design.

-   There are many potential algorithms that can solve the task, which
    means there is more than one answer.

-   The utility of the algorithm is determined by a lot of factors,
    which depend on the stakeholder goals.

Treating this design problem as a knowledge question instead does not
guide us in the right direction and is not helpful. Especially
validation and outcome are different.

:guideline: Carefully distinguish between design problems and
knowledge questions.


:task: Go back to your answer from Task 1 above. Do you see a
better fit when thinking of your thesis as "studying an artifact in a
problem context", as opposed to a "natural phenomena"? Replace the
question from Task 1 with the description of a problem that you want to
solve by introducing an artifact. Does this describe your thesis better
than the answer in Task 1?

---
type: lines
lines: 4
---

:task: List some knowledge questions and some design problems for
your thesis. It is sometimes not so obvious what they are, so this may
be harder than it may appear, and it is okay you try it with a first
attempt.

---
type: lines
lines: 4
---


# The Design Cycle

We can now describe a process to design an artifact:

---
type: figure
source: figures/design-cycle.png
caption: "The design cycle. Adapted from [@Wieringa:2014]."
---

The process is iterative, starting with the problem investigation.

-   **Problem Investigation:** Which problem do we need to solve and
    why? To answer this question, you need to identify the stakeholders
    of the problem. The stakeholders have goals that you need to
    identify so you can describe the problem.

-   **Treatment Design:** With *treatment*, we mean a *potential*
    solution. The term treatment emphasizes that it does not necessarily
    solve the problem, which we first know in the later phases. To
    design an artifact, we need to specify its requirements first and
    check if there are already designs out there that could work before
    we create new ones.

-   **Treatment Validation:** In this phase we want to find out if the
    artifact produces the desired effect, and if it can solve the
    problem.

-   **Treatment Implementation:** This phase is not part of a research
    project, and you will not be able to do it as part of your thesis,
    because it would mean to evaluate the artifact in its real world
    context. We discuss in the next section why.

These steps form a cycle, since the validation may reveal more knowledge
about artifact and context, which motivates another round.

# Evaluation or Validation

By now it should be obvious that it is not enough to just come up with
an artifact, but that it is necessary that we find out and demonstrate
how effective this artifact is in solving the problem we designed it
for. If it doesn't solve the problem, it's useless.[^3]

Let's first talk about what we call **evaluation**:

:definition: **Evaluation** is the investigation of a treatment as applied by stakeholders in the field.


Where we mean by "treatment" the application of the artifact, the
"stakeholders" are the persons that require a problem solved, and "in
the field" means that the artifact is applied in reality, in the way
(scale, context,\...) it is intended.

Imagine your task is to design a new resource allocation algorithm for a
base station in a 5G setting. You have designed the algorithm, even
created a program that runs it. Are you able to evaluate it, in the
sense of evaluation as given above? --- No. Of course not. There is no
way that you can test your algorithm in reality. You would have to get
access to a real network, real users with real traffic, and integrate it
into a future architecture that doesn't even exist yet. This is not only
the case for your thesis, but for many research projects and even
development projects in general. Evaluations are hard to do and take
time.

So what is the next best thing if an evaluation in reality is not
possible? That is what we call **validation**:

:definition: The goal of **validation** is to predict how an artifact will interact with its context, without actually observing an implemented artifact in a real-world context.


This is a useful understanding of validation that addresses the
practicalities we face in research. It means that you need to find ways
to predict how a certain artifact would behave in practice. For our 5G
algorithm example we could for instance:

-   build a prototype to understand the algorithms complexity,

-   make a event-based simulation model that simulates anticipated
    traffic of the future system,

-   make an analytical problem to see if the algorithm has selected,
    relevant properties.

These items above are only examples, that should illustrate reasonable
steps during validation that step by step investigate how the artifact
behaves. None of these validation steps are executed in reality, but
interpolate and try to predict or simulate how a real system would
behave. Finding such relevant validation steps can require a lot of work
and creativity, and is often even more elaborate than designing the
artifact in the first place.

:guideline: Think early in the process about how to validate
artifacts, that means at least before you design the artifact itself.


**Missing Validations:** Some students (and supervisors) ignore the
validation part, and rush too quickly towards designing the artifact. In
some cases this may be because the actual validation is implied by the
habits in the discipline, but sometimes it is an oversight or neglect.
You certainly don't want to come into the situation that you have
created one or more artifacts and then don't know how to validate them.
This is tragic for the thesis report, since the validation part is
usually the one that is easier to write about (if the validation exists)
than the actual implementation. Imagine in the example above that a
student spent a lot of time to implement the algorithm as a bunch of
code. Code can of course be tested, or you may measure its execution
time. In some cases, this may even be relevant for a validation, but
what with cases where the execution time for the code is not relevant at
all? Maybe writing the code wasn't the problem in the first place, but
some other properties of the algorithm that should be validated without
any written code? This is why it is so important to think about the
validation before any effort is spent on creating artifacts.

## That's it for now.

We have now discussed some of the most important elements in design
science. Don't worry if you feel a bit confused and have troubles
distinguishing the terms from each other. Go back and read the text
again until you remember the main concepts. We will apply the concepts
in some exercises so that you can use them for your thesis.

See you in the seminar.


# Further Reading

What you read now is sufficient for the seminar. After that, you should
continue reading on design science depending on which parts you need to
elaborate further. Much of this introduction you just read is based on
the book of Roel Wieringa, *Design Science Methodology for Information
Systems and Software Engineering*. You can access this book as PDF from
within the campus network, and we also made it available for you on
Blackboard.

In your thesis, you should **not** refer to this seminar when writing about your method. Instead, refer to published literature about design science, and make sure to refer to the specific choices you made for your thesis. 


[^2]: A colleague reacted on the formulation "changing the world." This
    really sounds pretentious, but technology works that way. It changes
    the world it is introduced into.

[^3]: Finding out that the artifact does not work as intended does not
    mean you get a bad grade in the thesis. Understanding why something
    does not work can also be valuable knowledge.