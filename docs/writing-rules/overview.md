---
id: overview
description: >-
  Learn how to use Semgrep’s intuitive syntax to write rules specific to your codebase. You can write and share rules directly from your browser using the Semgrep Playground, or write rules in your terminal and run them on the command line.
---

# Getting started

### Tutorial

If you want the best introduction to writing Semgrep rules, use the interactive, example-based [Semgrep rule tutorial](https://semgrep.dev/learn).

### Do it live!

You can write and share rules directly from the [Playground](https://semgrep.dev/editor). You can also write rules in your terminal and run them with the Semgrep command line tool.

You can write rules that do things like:

- Automate code review comments
- Identify secure coding violations
- Scan configuration files
- And more! Check out more use cases [here](../rule-ideas/).

This rule detects the use of `is` when comparing Python strings. `is` checks reference equality, not value equality, and can exhibit nondeterministic behavior.

<iframe title="Semgrep example Python is comparison" src="https://semgrep.dev/embed/editor?snippet=Ppde" width="100%" height="432px" frameBorder="0"></iframe>

### Reference material

- [Pattern syntax](pattern-syntax.mdx) describes what Semgrep patterns can do
in detail, and provides example use cases of the ellipsis
operator, metavariables, and more.<br/>
- [Rule syntax](../rule-syntax/) describes Semgrep YAML rule files, which can have multiple patterns, detailed output messages, and autofixes. The syntax allows the composition of individual patterns with boolean operators.

Looking for ideas on what rules to write? See [Rule examples](../rule-ideas/) for common use cases and prompts to help you start writing rules from scratch.
