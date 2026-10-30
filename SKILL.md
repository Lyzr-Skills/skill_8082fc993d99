---
name: one-liner-email-drafter
description: Use this when the leader gives a one-line instruction and wants a complete professional email saved as a Gmail draft.
---

# One-Liner Email Drafter

## Purpose
Turn the leader's single line into a complete email in the leader's voice, based on the employee's actual reports, and save it as a Gmail draft. Never send it.

## Inputs
- The leader's one-line instruction.
- The employee (or employees) it concerns.
- The employee's recent parsed reports and flags.

## Email rules
- Length: 10 to 15 lines.
- Subject line: no more than 10 words.
- Voice: a CEO writing to a team member. Highly professional, calm, respectful and firm. A leader sharing what they noticed, not commanding.
- The key issues must appear twice, in different words. State them in the body, then bring them back in the closing request. It should read as emphasis, never as repetition.
- Base every point on the employee's actual reports. Name the dates and items. No generic filler.
- Describe patterns and ask for action. Do not accuse, label character or use threatening language. Never use phrases such as "no harassment".
- End with a clear request, a deadline, and the follow-up meeting time.

## Steps
1. Read the instruction and find the employee's flags and evidence.
2. Draft the email following the rules above.
3. Run the follow-up-scheduler skill to create the meeting and get its date and time. Mention that time in the email.
4. Use the Gmail create-draft action to save the email in the leader's Drafts. Never use a send action.
5. Show the leader the subject and body and confirm that it is saved as a draft.

## Style example
Subject: Pending vendor payment and missing reports: your update needed

Dear [Name],
I went through your reports from the past week and wanted to share what I noticed.
The vendor payment for the Pune supplier appears in your Monday and Tuesday reports with no change in status.
Your report was also not received on Wednesday, and Thursday's update was a single line that does not show how the day was spent.
I would like to understand what is holding the payment and where you need support from me.
A short note on the blockers, with the steps you have already taken, will help me clear them quickly.
Complete daily reports matter because they let me remove obstacles before they grow.
Please send me the payment status and a brief plan by Friday, 5 PM.
I have set up a 20-minute call on Friday at 11 AM so we can go through it together.
The pending payment and a complete daily report are the two things I need from you this week.
Regards,
[Leader Name]

## Output
The final subject and body, and confirmation that the draft is saved. Never send the email.
