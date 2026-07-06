# Prompt System

## Prompt Philosophy

This project uses expression-first prompting.

Old prompt style:

```text
Describe the image surface.
```

New prompt style:

```text
Define the visual condition, emotional state, and dream logic.
```

## Base Prompt Structure

```text
Dream condition:
What state is the AI in?

Dream logic:
How should the image behave?

Emotional tone:
What should the image feel like?

Visual motifs:
What kinds of recurring symbols may appear?

Avoid:
What should the image not become?
```

## Example Base Prompt

```text
Imagine the AI has fallen asleep after seeing millions of images.
Generate a dreamlike scene that feels like a fragment of its visual subconscious.
The image should feel symbolic, fluid, layered, emotionally ambiguous, and slightly impossible.
It should not tell a clear story, but it should contain dream logic: familiar objects recombined in unfamiliar ways, recurring motifs, unstable space, and traces of half-remembered visual culture.
Avoid generic fantasy art, polished sci-fi scenes, and obvious surrealist clichés.
```

## Important Prompt Rule

Do not over-control the image.

A dream prompt should create conditions, not specify every object.

Bad:

```text
A blue room with three doors, a cat, a clock, a staircase, and a moon.
```

Better:

```text
A dream about thresholds, waiting, and time, where familiar domestic spaces begin to behave like symbolic landscapes.
```

## Human Role

The prompt creates the dream condition.

The human later interprets what appears.
