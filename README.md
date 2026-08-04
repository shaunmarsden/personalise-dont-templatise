# Personalise, Don't Templatise

<p>
  <img alt="Status: Working tool" src="https://img.shields.io/badge/status-working%20tool-2563eb">
  <a href="LICENSE"><img alt="Licence: MIT" src="https://img.shields.io/badge/licence-MIT-lightgrey"></a>
</p>

Draft a fixed-template message personalised with real detail, correctly handling a single recipient, more than one recipient at once, or a recipient who needs to forward part of it to someone who was not there.

## Why

A template sent repeatedly goes wrong in predictable ways: a generic opening line that would read the same for anyone, one person addressed directly while a second recipient gets quietly demoted to the third person, or a forwarded section written as if the person it is meant for is actually reading the email. This handles all three correctly, and keeps the template itself untouched.

[![Three routes for personalising a fixed template based on recipients.](assets/diagrams/14-personalise-dont-templatise.svg)](SKILL.md)

**Not what you need?** This personalises a template you already have for a known recipient or recipients. If this is a cold first message to someone you do not have a relationship with yet, [First Contact That Isn't Generic](https://github.com/shaunmarsden/first-contact-that-isnt-generic) is probably the one you want.

## Use It

Copy [SKILL.md](SKILL.md) and paste it into your AI tool (ChatGPT, Claude, Gemini, or similar), then paste in the real detail and how many people this is going to. It produces a message that:

- **Personalises the opening line and resource reference** with something specific, never generic
- **Keeps the template structure exactly as it is**, no reordering or rewriting
- **Addresses every recipient directly** when there is more than one, never sidelining a second person into the third person
- **Separates a forward-to-someone-else block clearly**, written in the third person about the person it's meant for, distinct from the recipient's own message

<details>
<summary><strong>See exactly what it produces</strong></summary>

1. A personalised opening line and resource reference, specific to this recipient
2. The fixed template structure, untouched
3. Every recipient addressed directly, or a clearly separated third-person block for someone being forwarded to
4. A stop and a question, instead of a guess, whenever the recipient situation is genuinely unclear or a resource is not actually ready

</details>

See [the worked example](example/): a fictional photography workshop's follow-up template sent to a single recipient, to two recipients together, and to one recipient who needs to forward part of it to someone who was not at the session. For the harder cases, a genuinely ambiguous recipient situation and a resource link asked to go out as a placeholder before it exists, read [the second worked example](example-two/).

Use [the blank template](templates/message-template.md) for your own case, and [the review checklist](checks/checklist.md) before sending.

No installation, project, or coding required to try it once.

## Before You Use It

This drafts the message. Sending it stays subject to explicit human approval.

## Feedback

Used it for a real template? [Start a discussion](https://github.com/shaunmarsden/personalise-dont-templatise/discussions) if something did not fit.

## Part of a Family

This is one of a family of free tools generalising [practical-ai-sales-workflows](https://github.com/shaunmarsden/practical-ai-sales-workflows) patterns beyond sales. See [sibling-projects](https://github.com/shaunmarsden/sibling-projects) for the rest. Not sure which one actually fits? Try [the interactive picker](https://shaunmarsden.github.io/sibling-projects/) for clickable cards, or [the router](https://github.com/shaunmarsden/sibling-projects/blob/main/ROUTER.md) if you would rather paste a description into an AI chat.
