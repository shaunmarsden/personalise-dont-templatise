# Personalise, Don't Templatise

<p>
  <img alt="Status: Working tool" src="https://img.shields.io/badge/status-working%20tool-2563eb">
  <a href="LICENSE"><img alt="Licence: MIT" src="https://img.shields.io/badge/licence-MIT-lightgrey"></a>
</p>

Draft a fixed-template message personalised with real detail, correctly handling a single recipient, more than one recipient at once, or a recipient who needs to forward part of it to someone who was not there.

## Why

A template sent repeatedly goes wrong in predictable ways: a generic opening line that would read the same for anyone, one person addressed directly while a second recipient gets quietly demoted to the third person, or a forwarded section written as if the person it is meant for is actually reading the email. This handles all three correctly, and keeps the template itself untouched.

## Use It

Copy [SKILL.md](SKILL.md) and paste it into your AI tool (ChatGPT, Claude, Gemini, or similar), then paste in the real detail and how many people this is going to. It produces a message that:

- **Personalises the opening line and resource reference** with something specific, never generic
- **Keeps the template structure exactly as it is**, no reordering or rewriting
- **Addresses every recipient directly** when there is more than one, never sidelining a second person into the third person
- **Separates a forward-to-someone-else block clearly**, written in the third person about the person it's meant for, distinct from the recipient's own message

See [the worked example](example/): a fictional photography workshop's follow-up template sent to a single recipient, to two recipients together, and to one recipient who needs to forward part of it to someone who was not at the session.

Use [the blank template](templates/message-template.md) for your own case.

No installation, project, or coding required to try it once.

## Before You Use It

This drafts the message. Sending it stays subject to explicit human approval.

## Licence

MIT.

## Feedback

Used it for a real template? [Start a discussion](https://github.com/shaunmarsden/personalise-dont-templatise/discussions) if something did not fit.
