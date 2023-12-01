# Learn Platform Engineering
Step by step guide on becoming a Platform Engineer.

## Pre-amble
This is a **work in progress**. Intended to be useful but not cover everything, also primarily
focused on technical skills only.

Some of the gaps in instructions are intentional, but will try to keep it to things worth discovering on
your own or not quite worth explaining.

Each step is a progression and builds on the previous ones, so although tempting, don't skip steps
until you are fully competent to the level of skill required for the step.

## The Goal

Here is a list of technical skills to gain:

- Competency in a programming language
- Git
- Networking (TLS, DNS)
- Datacentre basics (racks, servers, switches)
- Virtualisation platform basics
- Storage
- SQL
- VM basics (what is a VM, provisioning, destroying, maintaining)
- Operating system administration
- Load balancing and scaling
- Continuous integration
- Continuous development
- Security (RBAC, Least Privilege, CVEs)
- Observability
- Monitoring and Alerting

## Step 1 - Start learning a programming language

### Why
Here is why you should invest in this skill and why it isn't necessarily the programming language
itself that will help you, but the skills in modern software development that will.

All the scripting you will do for the rest of your career will benefit from being skilled in modern
software development. Scripts, like software development need to be maintainable and reliable.

Once you know one programming language you will find it easier to pick up new ones. A lot of tools
you use as a platform engineer seem to use configuration that is either from a programming language
or derived from one. So knowing a proper programming language actually helps you pick up new platform
tools.

The tools we use are written in a programming language ! Yes, of course they are. But why do I care?
Because when you are maintaining this tool and it stops working, guess who has to fix it, you `;)`.

The reasons why go on and on. What you probably want to know now is where to get started.

### How
There are different types of programming paradigms and different languages in each. Why not go for
something common in both? [Python] is common and has good community support, meaning that if you
get stuck it's going to be easy to find help.

One does not simply learn a programming language and this guide will not simply teach one to you,
instead, heading over to the [Python] website and find the `Getting Started Guide`. Keep learning and
trying tutorials until you can:

- Understand the different data types
- Create functions
- Create objects
- Use loops and controls flows
- Understand variables and scope
- Can describe and appropriately use naming and spacing conventions

## Step 2 - Git basics

Tools that store source code, like [Github], use [Git] for version control. Use the command line
instead of relying on an [IDE] or any other tools.

- Create an account in [Github] (it's free)
- Create a repository
- Clone the repository to your computer (remember use the command line)
- Create a file, `README.md`, put your name as a heading and then write and sentence about yourself
- Stage your changes and commit them
- Now take a look at the rendered README file in Github

The commands you run above will look similar to this:

```bash
git clone https://github.com/isaaccarrington/LearnPlatformEngineering.git
git add README.md
git commit -m "Added README for intial commit"
git push -u origin main
```

Look at what you have just accomplished and see how the commands relate to the three main states in
Git. Now try creating a branch, making a change, and then merging the branch into the main branch.

If you got this far and understand what's going on then congratulations you know the basics of Git!
If not, never fear, there is loads of documentation out there on this section. 

[Git]: <https://git-scm.com/doc>
[Github]: <https://github.com>
[IDE]: <https://aws.amazon.com/what-is/ide/>
[Python]: <https://www.python.org>