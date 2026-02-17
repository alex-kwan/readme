# AI related questions and thoughts

## 1) "I’m afraid I’m removing my own job by using AI"

> AI should be a tool, not a replacement. It helps with larger, complex tasks, but people still provide context, judgment, and real answers that matter.

If this concern comes up, expand your scope instead of shrinking it:

- After solving one problem, look for similar patterns across the team/org/company.
- Identify upstream and downstream challenges where your understanding can drive innovation.

---

## 2) "I end up working more hours with AI"

> There can be a short-term push to work harder with AI to outpace others, but that often leads to burnout and corner-cutting.

Use AI in ways that reduce chaos, not increase load:

- Drive consistency and strengthen documentation.
- Brainstorm through upcoming scenarios so potential descisions are already aligned with business goals.
- Build tools that shorten the gap from decision to execution.

---

## 3) "It sounds like I’ll become obsolete"

> This is mostly a mindset question. People stay valuable by learning, adapting, and creating. AI can assist execution, but humans still define what is better and validate it.

Practical mindset shifts:

- Focus on the real client problem and business goal.
- Clients may not not know what they want.
- Build strong validation criteria before trusting AI outputs.
- Remember that “mostly right” can still produce costly unintended outcomes.

---

## 4) How to think about AI day-to-day

> For tasks we’ve repeated many times, we use tooling and workflows. For brand-new, highly detailed tasks, we still work manually. AI/LLMs fit in the middle.

Working model:

- AI can help produce structured artifacts and support tooling.
- LLMs are powerful but probabilistic—they are often useful, not guaranteed.
- The goal is to reduce manual effort while keeping validation and control.

Two common scenarios:

1. **Defined domain, high reliability needed**  
	If the domain is well understood and validation is clear, LLM-assisted workflows can become highly reliable over time.

2. **Partially known domain, manual process today**  
	Use LLMs to reduce effort, but iterate on validation continuously. “Good enough” must be explicit, measurable, and safe.

Core principle:

- Effective LLM usage is about **discipline** (clear problem framing) and **validation** (proof the result is correct).

---

## 5) What to be excited about

> AI gives us more tools to solve real human problems more easily.

Opportunity areas:

- Small businesses can create impact faster in their communities.
- Teams can spend more time on relationships and real customer needs.
- Better information flow helps decision-makers create meaningful outcomes.

---

## 6) How to know you’re on the right track

Ask:

- What is the exact goal?
- Can we describe realistic scenarios with numbers and details?
- Can we start with a smaller component, validate it, then scale?

Prompt idea:

> “Can you share scenarios with numbers and details on how this will work?”

---

## 7) Why validation matters so much

Validation protects you from false confidence:

- A feature can appear to work while hiding deeper quality issues.
- Poor structure creates long-term maintenance and change risk.
- Experience and explicit validation criteria prevent fragile systems.
- Define not only *that* it works, but *what good looks like over time*.

In short: speed without validation creates risk; speed with validation creates leverage.

## 8) How do I go about building with AI?

It’s important to define what you want to build with AI before you start prompting. Quick prompts can be useful for exploration, but they can also produce unintended outcomes, especially at scale. I usually start with a Markdown document and iterate with Copilot to verify that the problem framing is clear. A useful final prompt is: “List scenarios, including edge cases, so I can validate expected behavior.” That serves as a final sanity check before implementation.

This document becomes the first version of feature documentation, which makes team reviews much easier. After refinement and comments, I move to the next phase: a development plan.

For prototypes, I keep the plan lightweight and avoid heavy dependencies. The goal is to validate whether the idea is correct, step by step, with explicit checks at each stage. As new ideas emerge, I update the original planning document so decisions remain traceable and the scope stays intentional.

From there, I use AI to draft a substantial portion of the content, then review and refine it. In practice, this is similar to working in an unfamiliar legacy codebase: the value comes from improving the outcome, not from writing every line from scratch. The key is maintaining standards for readability, maintainability, and shared ownership. It’s easy to over-index on functionality and later realize the solution is difficult to understand or modify.

The core point is simple: understand what you are building, define what “correct” looks like, and validate that you actually built it. Small, high-trust teams with strong tooling and disciplined execution can deliver outsized results.