# Email Tone and Action Coach

A GitHub Copilot agent skill for recipient-aware email drafting and review. It adapts tone, structure, technical detail, action clarity, ownership, deadlines, dependencies, and risk framing while preserving the sender's substantive meaning and voice.

## Repository layout

```text
.github/
  skills/
    email-tone-action-coach/
      SKILL.md
      references/
        persona-playbook.md
        review-checklist.md
      examples/
        example-prompts.md
```

## Install as a project skill

Copy this repository's `.github/skills/email-tone-action-coach` directory into the same location in your target repository, then commit it.

## Install as a personal skill

Copy the `email-tone-action-coach` directory to one of the personal skill locations supported by your Copilot environment, such as `~/.copilot/skills/` or `~/.agents/skills/`.

## Use

Ask Copilot to polish, adapt, review, or reframe an email and provide the recipient's role plus any relevant authority, urgency, technical fluency, or commitment risk.

Example:

> Review this email for a client-side IT lead. Keep it concise, clarify the decision needed, and flag any wording that could create an unintended commitment.

## Behavior

The skill always returns:

1. a revised email
2. a material change summary
3. items to verify before sending
4. a mandatory human-review reminder

It must not send email, provide legal advice, invent facts, or change substantive commitments unless the user asks.

## Source

Converted from the supplied `Email Tone and Action Coach.docx` specification.

## License

No license has been selected. Add a license before publishing if you want others to copy, modify, or redistribute the skill.
