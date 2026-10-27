# Exploded Views

Things taken apart until they make sense.

An exploded view is the drawing in the back of a service manual. Every part of an assembly gets pulled a short distance off its neighbors, along the line it would travel to come out, so you can see what's inside, what order it goes back together in, and which one bolt is holding the whole thing up. Nothing is missing and nothing has moved anywhere it couldn't actually go. It's the same machine with room between the parts.

That drawing is the working method here, and the reason for it is a word.

## Where the name comes from

> **gitgat** /ˈɡɪt.ɡat/ *noun*
>
> 1. A thing you understand and cannot name, because you learned it by taking it apart instead of being taught it.
> 2. A problem, an interface, a mechanical coupling, or any interaction with enough moving parts that describing it in full costs more than pointing at it does.
> 3. That specific thing, when both people already know which thing. *Hand me that gitgat.*

It was one of my first words. I was pointing at something I couldn't name, which turns out to be the whole definition, and it's been my handle since an AOL sign-up screen and a dial tone sometime before 2000. (Git the software shipped in 2005. I'm just noting the order of events.) The long version is at [gitgat.com/gitgat](https://gitgat.com/gitgat/).

Learning things by opening them up hands you the mechanism years before it hands you the vocabulary, if it ever does. You can trace how something works and predict what it'll do under load and still have no idea what anyone else calls it. Under the hood of a car, "hand me that gitgat" with a nod at the alternator moves exactly as much information as saying alternator. Naming a thing and understanding it are different skills, and only one of them fixes the car.

The work turned out to be gitgats too. A queue that forms before the door opens, the eligibility rule underneath it, a schema that fits one state and fights you in the next. Each one is obvious to whoever's standing in it and unspeakable to everyone else, and you can't ship what you can't describe.

A gitgat stops being a gitgat once it has a name, a diagram, and a boundary. An exploded view is that diagram. This org is where the taking-apart gets written down.

## What lives here

Non-personal work by [gitgat](https://github.com/gitgat): tools, side projects, and experiments that are useful to someone other than me. The personal stuff (the resume, [gitgat.com](https://gitgat.com) itself) stays on my own account.

Some of these repos are tools I needed and couldn't find. Some are a problem I kept pointing at until it was worth writing down properly. Either way the goal is the same, which is to leave the parts visible. READMEs here try to explain the mechanism and the reasoning, not just the install step, and there's a diagram wherever a diagram does the job better than a paragraph. If you can't see why a thing is built the way it is, that's a bug worth an issue.

## Projects

| Project | What it is |
|---|---|
| [crewkit](https://github.com/Exploded-views/crewkit) | Tooling for running a crew of AI coding agents: an installer for pinned, checksum-verified tools, plus Claude Code plugins for agent practice and memory notices. |
| [bitc](https://github.com/Exploded-views/bitc) | Runs heavy commands (builds, test suites) on cloud providers under a spend cap, with local slot gating as the fallback. Built for machines that several agents share. |
| [claude-utils](https://github.com/Exploded-views/claude-utils) | A fork of [MarimerLLC/claude-utils](https://github.com/MarimerLLC/claude-utils). Its main addition is `claude-memsync`, which syncs Claude Code memory folders to encrypted git repos across machines. |
| yo-human | Lets agents notify, ask and escalate to a person over ntfy, Bark and PagerDuty. Coming soon. |
| [Heeler](https://github.com/Exploded-views/Heeler) | A contribution fork of [Heeler](https://heeler.bybee.dev), carrying changes yo-human needs that are offered upstream. |

## How it's run

This is one person, mostly, working in the margins of a day job. Much of the code is written with AI coding agents and the commit history says so; I read and test what ships.

Issues are welcome on any public repo. For anything bigger than a small fix, open an issue before a pull request so we agree on the approach first. The details are in [CONTRIBUTING.md](https://github.com/Exploded-views/.github/blob/main/CONTRIBUTING.md), and what to expect for help is in [SUPPORT.md](https://github.com/Exploded-views/.github/blob/main/SUPPORT.md). Security issues go through GitHub's private vulnerability reporting on the affected repo, never a public issue; see [SECURITY.md](https://github.com/Exploded-views/.github/blob/main/SECURITY.md).

More about the work, and how to reach me, at [gitgat.com](https://gitgat.com).
