# Contributing

This library gets better when people who do the work add to it. Contributions are welcome from anyone working in construction or the built environment.

## What we are looking for

- New prompts for workflows that are not covered yet
- Improvements to existing prompts that you have tested on real work
- New checks: the things that catch AI mistakes before they reach a client
- Contract-specific variants (NEC4, JCT, FIDIC, bespoke forms) and regional variants (UK, UAE, wider GCC)
- New Claude skills that package a repeatable workflow

## Standards

- **Tested.** Only submit prompts you have used on real work and refined.
- **Clean.** No client names, project names, real figures or personal data in examples.
- **Practical.** Every prompt needs a purpose line, the prompt itself and a short list of checks.
- **Plain English.** British English. Short sentences. No hype.
- **Honest about limits.** If a prompt only works well with a particular model or input, say so.

## Format

Prompts follow this structure:

~~~~
## Prompt name

**Use it for:** one line on when to use it.

~~~
(the prompt, with [square brackets] for anything the user fills in)
~~~

**Check before you use it:**
- check one
- check two
~~~~

Skills follow the Claude skill format: a folder containing a SKILL.md file with a name and description in the frontmatter, followed by the instructions.

## How to submit

1. Fork the repository.
2. Add or edit files on a new branch.
3. Open a pull request describing the workflow, how you tested it and with which tool.

By contributing you agree that your contribution is licensed under the same licence as the rest of the library (CC BY 4.0).
