# Vex

Vex is a Rust + Bevy CLI app for managing tasks and projects, inspired by TaskWarrior, Omnifocus, Emacs' org-mode, and the design possibilities of Bevy's excellent implementation of ECS (entity, component, systems).

Philosophy:

- everything is a node: tasks, projects, areas, objectives, etc, are all represented by hierarchies of flexible data.
- task management is time and attention management. Time, and changes over time, are first-order concerns. Ideas should be free to evolve, and promote useful revisitation, over time, without loss of history.
- time management is pain management: the point of the tool is to minimise the effort required to actually do the work, by aiding clarity, purpose, and self-awareness.
- motivation is self-awareness + intent connected to purpose: vex promotes self-knowledge as a guide to improvement; fluid connection between high-level goals and principles, all the way down to detailed task breakdown.
- the best part of capturing your impulses is the freedom to forget them: there is not enough time to get everything done; the ideal tool helps you make peace with forgetting anything less important than the thing you're working towards.
- plans are useless, but planning is invaluable: a time block work plan is very helpful, but it's a transient artefact. There's no value in being haunted by the list of things you didn't get done yesterday.
- if it won't die, it's not a deadline: distinguish between tactical urgency and importance, without catastrophising. Most work doesn't have a deadline.
- most things worth doing are social enterprises: people should be first-class elements of the system (agendas, calendars, etc). Collaboration with others should not require their wholesale adoption of vex. Commitments are important, and should not be oversimplified.
- work is contextual: seeing everything all at once is for mystics and trippers. It should be easy view just what is relevant in the moment.
- let me build a graph, but pretend it's a tree: hierarchies are powerful, but inheritance is brittle. Connections should be made wherever they might be useful, and the gory details hidden from my tiny mind.
- repetition, repetition, repetition: spaced repetition, and incremental editing, are fundamental components of a useful system.
- capture, collect, organise, create: collect everything. Rework it until it finds expression. It's often too early to tell the difference between a task to be done, an idea to be incubated, or an idea to be developed and elaborated until the process has run its course.
- interoperate with mature tools: I like Helix and Obsidian. Find ways to lean on them for their strengths, not to reimplement half of them poorly.
