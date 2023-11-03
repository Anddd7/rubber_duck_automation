# ROADMAP

## Requirements

What this tool should do:

- A runbook should be able to be written in human language, but can be 'executed' by machine as well.
- When you execute a runbook, it should prompt you for input, so that you will know what kind of input is required.
- Then it can also be executed automatically (for simple tasks), so that you don't have to type in the same thing over and over again.
- Then, it will capture the output of the commands, so that you can see what happened, and compare with the expected results.
- Finally, you can decide whether to go on to the next step, or stop the execution and rollback it.
- Bisides, it can record the status of the execution, e.g. time, progress, warning/error, etc.

What this tool should not do:

- Documentation, just put a bunch of reference links in runbook.
- Config & Code management, should be done in your local machine already.
- Pipeline, should be done in your CI/CD tool already. What you need here is the manual steps.

## Version Planning

### 0.1.0

- [ ] golang cli structure
- [ ] runbook template
- [ ] runbook parsing
- [ ] execute, prompt, capture, rollback and status
- [ ] example

## Other Ideas

- [ ] githooks
- [ ] devcontainer
