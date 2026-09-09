# IT0123 DevNet Resource Validation Plan

## Student and Project

- Name: John Michael M. Antonio
- Section: TN32
- Repository name: `it0123-devnet-resource-plan`

## Purpose

Selecting the correct DevNet resource is important because each resource has a different purpose. Choosing the right resource helps make the development and testing process easier and more suitable for the task.

## Validated Resource Decisions

### UC1 - Quick read-only API exploration

- Selected resource: `always-on-sandbox`
- Most important requirement: Immediate shared access for read-only API practice.
- Official Cisco evidence: https://developer.cisco.com/docs/sandbox/

### UC2 - Private configuration testing

- Selected resource: `reservation-sandbox`
- Most important requirement: Private access and administrative control for configuration testing.
- Official Cisco evidence: https://developer.cisco.com/docs/sandbox/

### UC3 - Guided API concept practice

- Selected resource: `learning-lab`
- Most important requirement: Structured and step-by-step learning for a beginner.
- Official Cisco evidence: https://developer.cisco.com/learning/

### UC4 - Reusable automation example

- Selected resource: `code-exchange`
- Most important requirement: Existing community and Cisco-maintained code repositories.
- Official Cisco evidence: https://developer.cisco.com/codeexchange/

## AI Evaluation

I used ChatGPT to recommend a DevNet resource for each scenario. I accepted the recommendations after checking them against official Cisco documentation. The recommendations matched the requirements of the four scenarios, so all four were verified.

## Validation Evidence

- Validator result: `VALIDATION COMPLETE: 9/9 checks passed.`
- Command used: `python validate_plan.py`
- Official Cisco pages reviewed:
  - https://developer.cisco.com/docs/sandbox/
  - https://developer.cisco.com/learning/
  - https://developer.cisco.com/codeexchange/

## Git Evidence

- Initial commit message: `Initial project setup`
- Validation commit message: `Complete DevNet resource validation`
- Output of `git log --oneline`:

```text
Paste the output of git log --oneline here after making the validation commit.