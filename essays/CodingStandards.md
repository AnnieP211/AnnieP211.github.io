---
layout: essay
type: essay
title: "Beyond Curly Braces"
# All dates must be YYYY-MM-DD format!
date: 2026-12-02
published: true
labels:
  - ESLint
  - Coding Standards
  - Best Practices
  - Clean code
---

<img width="300px" class="rounded float-start pe-4" src="../img/codingStand.jpg">

## Beyond Curly Braces
Most people think coding standards are about small, almost trivial things: how many spaces to indent, 
whether to use single or double quotes, or where to place the closing curly brace. I used to think the same 
thing.
After one week of using ESLint with VSCode, I’ve changed my mind.
Coding standards are not about aesthetics. They are about discipline, clarity, and learning to think more 
precisely as a developer.

## The First Week with ESLint
The first time I enabled ESLint in my project, my screen filled with warnings and errors. Red underlines. 
Yellow highlights. Suggestions everywhere.
The frustrating part? My code worked.
But ESLint made it clear that “working” is not the same as “well written.”
I had unused variables, inconsistent indentation, and several places where I used let when const would have 
been better. None of these broke my program. But they revealed habits I hadn’t fully examined.
Fixing the errors felt tedious at first. However, as I worked through them, I began to see a pattern: 
ESLint wasn’t nitpicking. It was teaching.

## How Standards Teach the Language
One of the biggest surprises was how much coding standards reinforced language fundamentals.
For example, ESLint consistently pushed me to use const instead of let when reassignment wasn’t necessary. 
That simple rule changed how I think about variables. I began writing code with clearer intent and stronger 
guarantees about what could and could not change.

Here’s a small example:
Before ESLint
let total = 10
var count = 0

After ESLint
const total = 10;
let count = 0;

At first glance, this seems minor. But using const by default encourages safer patterns and makes code 
easier to reason about.
Even formatting rules improved readability. Consistent indentation and spacing reduce cognitive load. When 
structure is predictable, your brain can focus on logic instead of decoding formatting.
Coding standards don’t just make code look better — they make it easier to understand.

## Painful and Useful
Getting rid of ESLint errors is both painful and useful.
It slows you down at first. You feel like you're being corrected constantly. Sometimes you have to refactor 
something that technically “works.”
But that friction is productive.
Linting catches small mistakes early. It prevents inconsistent patterns from spreading across a codebase. 
It encourages habits that scale when projects grow larger or involve more contributors.
It’s similar to learning proper form in a sport. Early correction prevents long-term problems.

## Coding Standards and Teamwork
Another important realization is that coding standards are not just for the individual developer. They are 
for teams.
When everyone follows the same conventions, code becomes predictable. There is less debate about formatting 
and more focus on solving real problems. Tools like ESLint remove subjective disagreements and replace them 
with consistent, automated decisions.
Standards reduce friction.
They also make onboarding easier. A new contributor can read the code without constantly adjusting to 
different styles. That consistency improves maintainability and long-term quality.

## Beyond Style
It’s easy to dismiss coding standards as cosmetic rules. But consistency builds trust in a codebase. Clean 
structure reflects careful thinking.
If I could only implement one software engineering practice to improve quality, coding standards would be a 
strong candidate. They raise the minimum standard of code. They reinforce language fundamentals. They 
reduce team conflict. They prevent subtle bugs.
They also build discipline.
After one week with ESLint, I no longer see coding standards as trivial. They are foundational.
It’s not about the curly brace.
It’s about the structure behind it.

## AI Use Disclosure
I used ChatGPT to help brainstorm structure and refine clarity in this essay. The ideas and reflections are 
based on my own experience using ESLint during the first week of development.

