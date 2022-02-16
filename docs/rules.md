---
slug: rules
---

# Semgrep rules

Semgrep’s open-source registry of rules let you get started scanning code without the need to write anything custom.

The registry includes rules to catch issues of security, performance, correctness, and other bugs. Contribute to the registry
by writing your own rules and adding them to the <a href="https://github.com/returntocorp/semgrep-rules" target="_blank">Semgrep rules repo</a>.

<div className="lang-container" style={{marginBottom: '20px'}}>
  <iframe width="900" height="400" frameBorder="0" src="https://dashboard.semgrep.dev/metric/semgrep-rules.num/graph"></iframe>
</div>
# Confirm installation by running --help. It should print to your terminal.

$ semgrep --help

# Check for Python == where the left and right sides are the same (often a bug)

$ semgrep -e '$X == $X' --lang=py path/to/src

# Automatically survey languages and frameworks and run recommended Registry rules

$ semgrep --config=auto path/to/src
