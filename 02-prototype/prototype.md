# Prototype · Juno

## Prototype link

[Juno’s Escalation Brief — Open demo](https://lanka-dream-salvador-pushing.trycloudflare.com/)

Built with Codex.

**Availability:** This is a temporary Cloudflare link. It works while the local preview server and sharing connection remain running on my computer.

## What it demonstrates

Juno helps a support escalation manager or PM understand a newly reported P0 customer issue inside Slack.

The user clicks **Create brief** to bring together a Slack conversation, a related Jira incident, and a Notion incident review. Juno presents four sections: **Summary, Key themes, Risks and urgency, and Open questions**.

The user can click source references to inspect the supporting evidence in views resembling Slack, Jira, and Notion.

**Testable assumption:** After reading Juno’s brief, the user can identify the reported issue, its known risk, and an open question without first searching through all three tools separately.

The prototype follows Juno’s skill file by citing evidence, flagging conflicting information, distinguishing inference from fact, and preserving uncertainty. It highlights the human-assigned P0 for attention while leaving priorities and customer commitments with a human.

All data is fictional. The brief is prepared in advance; this prototype tests the interaction and presentation rather than live AI synthesis or integrations.

### Build prompt summary

- **Role:** Act as a product prototyper building a one-screen simulation of Juno PM inside Slack.
- **Task:** Show a fictional P0 escalation, generate an evidence-based brief, and let users inspect related Slack, Jira, and Notion records.
- **Constraints:** Use fictional data; support factual claims with sources; preserve uncertainty; flag the P0 for human attention; keep consequential decisions with people.
- **Format:** A Slack-style thread with a Create brief button, the four required brief sections, source views, and a Reset demo button.

## Debrief

- **What worked:** The prototype ran successfully. Creating the brief, opening source references, viewing the Jira and Notion records, and resetting the demo worked during the walkthrough.
- **What broke / felt like a toy:** The prepared brief and fictional records limit what this version can demonstrate. It does not show whether Juno can reliably synthesize new information. The temporary sharing link also depends on my computer staying connected.
- **Peer feedback:** Not collected during class because we ran out of time. The assumption about user understanding remains unvalidated.
- **What I’d change next pass:** Test with a classmate without providing a walkthrough, check whether they can identify the issue, risk, and open question, and collect feedback on clarity and trust. 
