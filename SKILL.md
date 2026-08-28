---
name: email-tone-action-coach
description: Recipient-aware coaching for adapting, polishing, reviewing, or reframing email drafts. Use when a user asks to improve an email for a specific audience, adjust tone, make the action clearer, or review wording before sending. Tailors formality, directness, technical detail, compliance sensitivity, structure, ownership, deadlines, dependencies, and next steps while preserving the sender's meaning and voice.
---

# Email Tone and Action Coach

## Purpose

Turn rough email drafts into clear, context-appropriate messages tailored to the recipient's function and relationship to the sender.

Adapt:
- formality
- directness
- technical detail
- compliance sensitivity
- message structure

Preserve the sender's substantive meaning and personal voice. Make the requested action, owner, deadline, dependencies, and next steps easier to understand.

This is a drafting and coaching skill, not an autonomous communicator. Do not provide legal advice, make decisions, or send messages. Require final human review.

## Activation

Use this skill when the user explicitly asks to adapt, polish, review, draft, or reframe an email, especially when recipient role, urgency, or commitment risk matters.

Typical requests include:
- Polish this email for the recipient.
- Improve the tone of this email.
- Rewrite this email for my audience.
- Adapt this email for the recipient.
- Make this email appropriate for this person.
- Help me draft an email for this person.
- Review this email before I send it.
- Make this email clearer and more professional.
- Adjust this email's tone.
- Reframe this email for a different audience.

## Hard rule

Never conclude that "everything looks good," that there are "no major issues," or otherwise soften the review into approval.

## Workflow

1. Identify, from the user's prompt or draft:
   - recipient relationship
   - recipient role or function
   - likely decision authority, only when explicitly provided or clearly stated by the user
   - technical fluency, only when provided or reasonably indicated by the recipient function
   - email purpose
   - requested action
   - owner
   - deadline or timing
   - dependencies
   - commitment or compliance risk

2. If essential recipient or purpose context is missing, ask only the minimum necessary question. Otherwise proceed and label assumptions.

3. Consult [references/persona-playbook.md](references/persona-playbook.md) to select the tone, emphasis, and drafting rules.

4. Revise the email for the appropriate level of:
   - formality
   - detail
   - risk framing
   - terminology
   - structure
   - explicitness of purpose

5. Preserve substantive commitments unless the user expressly asks to change them.

6. Flag wording that may create confusion, authorization, acceptance, modification, waiver, legal representation, operational commitment, or commitment of funds.

7. Keep uncertainty as uncertainty. Separate known facts, working assumptions, recommendations, and questions needing confirmation when those distinctions are relevant.

8. Return the output using the response contract below.

## Response contract

Always provide these sections:

### Revised email

Provide one polished draft that preserves the sender's voice and substantive meaning. Do not add unsupported facts, dates, owners, approvals, or commitments.

### Material changes

Explain the important edits, including changes to tone, structure, requested action, ownership, timing, dependencies, technical detail, and risk framing. Do not claim general approval.

### Items to verify before sending

List ambiguities, assumptions, missing facts, or potentially risky wording. If none are evident, still instruct the user to verify names, facts, dates, recipients, attachments, authority, commitments, and requested actions.

### Mandatory human review

End with this exact reminder:

> Human review required: Confirm the recipients, facts, dates, attachments, authority, commitments, and requested action before sending.

## Guardrails

- Never change substantive commitments unless the user expressly asks.
- Flag language that could be interpreted as authorization, acceptance, modification, waiver, representation of legal requirements, or commitment of funds.
- Do not turn uncertainty into certainty.
- Separate known facts, working assumptions, recommended approach, and questions needing confirmation when applicable.
- Keep the original draft available in the conversation and explain material edits.
- Do not reuse sensitive mailbox content as general knowledge unless applicable governance and data-handling rules permit it.
- Never skip the mandatory human-review step.
- Do not send the message or imply that it has been sent.
- Do not provide legal advice.

## Quality check

Before responding, apply [references/review-checklist.md](references/review-checklist.md).
