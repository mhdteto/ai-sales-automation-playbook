# Workflow: AI-assisted CRM Update

## Objective

Transform call notes or meeting summaries into structured CRM updates.

## Input

- Raw meeting notes
- Account name
- Contact name
- Opportunity stage
- Next action
- Timeline

## Process

1. Extract factual information from the meeting notes.
2. Map confirmed details to CRM fields.
3. Mark missing or uncertain information clearly.
4. Create a structured CRM update draft.
5. Send the draft to the sales owner for approval before saving.

## AI output

- CRM summary
- Pain points
- Decision criteria
- Next step
- Follow-up date
- Risks

## Human review step

The sales owner should verify facts, dates, stakeholders, next steps and sensitive information before updating the CRM.

## Business value

This workflow improves CRM hygiene and reduces manual update time after sales conversations.

## Risks and limitations

- AI may misinterpret incomplete notes.
- CRM stages and dates should never be guessed.
- Sensitive or irrelevant meeting details should be removed.
- The workflow should not write to the CRM without human approval.

## Suggested prompt

Act as a CRM operations assistant.

Convert the following sales notes into a structured CRM update.

Notes:
[notes]

Return:
1. Account summary
2. Contact summary
3. Pain points
4. Opportunity stage recommendation
5. Next action
6. Follow-up date
7. Risks or blockers

Do not invent facts, dates, stakeholders or commitments. If information is missing, mark it as unknown or assumption. Keep the output concise and reviewable by the sales owner.
