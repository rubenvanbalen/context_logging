<p align="center">
  <img width="381" alt="image" src="https://github.com/rubenvanbalen/context_logging/assets/135207242/d60ecde6-11c5-4378-a655-1de42113a5e6">
</p>
<p align="center">
  <img width="381" alt="image" src="https://github.com/rubenvanbalen/context_logging/assets/135207242/8e2a8eb0-e789-4151-a68f-3440f27b3d7e">
</p>
<p align="center">
    <em>Enable Context Logging in Python to obtain the necessary information within your desired environment.</em>
</p>


---

**Documentation**: <a href="https://github.com/rubenvanbalen/context_logging/wiki" target="_blank">https://github.com/rubenvanbalen/context_logging/wiki</a>

**Source Code**: <a href="https://github.com/rubenvanbalen/context_logging" target="_blank">https://github.com/rubenvanbalen/context_logging</a>

---

## Context
Software always runs fine until it doesn't. Often, failing software leaves people clueless, unable to explain what exactly happened. For serious problems, a lot of effort is spent to recreate and replay the scenario in a non-production setting, trying to make sense of the context in which the problem was triggered. This makes these failures very expensive.

Software has its pitfalls even without failing. Answering queries from within the organization easily becomes complex without the proper information and context. This Python module tries to solve these problems by making it easy to add context to your logging. With supplementary in-memory logging where specific logs are written only depending on the state of a context, resulting in smaller log files containing all necessary information in your desired environment.

## Design for Context
The term "context" refers to the circumstances, conditions, or setting in which something occurs or exists. It provides the background or framework that helps to understand, interpret, or evaluate a particular situation, event, or piece of information. Context is intricately tied to the subscriber and their specific needs, preferences, and circumstances. The term 'subscriber' is used here in the broadest sense, encompassing every person or system interested in the state of certain events in relation to the running software. Therefore it's impossible to tell upfront which context should be in your design.

However, each context shares characteristics that are important to understand:
- id-prefix
- name
- description
- context group
- state (inactive, started, ended, running, failed, closed)
- start event
- end event
- subscribers
- loglevel
- in-memory-log-level

## Logging Principles

---

## Requirements

## Installation

## Example

## Dependencies

## License
This project is licensed under the terms of the MIT license.
