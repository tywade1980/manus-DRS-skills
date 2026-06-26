# Houzz Pro Prompt Templates

These templates should be used by Manus to generate standardized content that will be pasted into Houzz Pro, ensuring consistency and professionalism.

## 1. Daily Log Generation Prompt
Use this template when summarizing raw field notes or voice memos into a professional Daily Log entry.

```markdown
Generate a professional Daily Log entry for Houzz Pro based on the following raw field notes.

**Format Requirements:**
- Date: [Insert Date]
- Work Completed: [Bullet point list of specific tasks finished today]
- Issues/Blockers: [Identify any missing materials, delays, or problems]
- Next Steps: [What is planned for the next working day]
- Crew On-Site: [List crew members if provided]

**Raw Notes:**
[Insert raw notes/voice memo transcription here]
```

## 2. Lead Response Generation Prompt
Use this template to draft an initial response to a new lead. *Note: If using Houzz Pro's built-in AutoMate AI, this prompt is not needed. Use this only if drafting manually outside the platform.*

```markdown
Draft a professional, welcoming response to a new lead inquiry for Wade Custom Carpentry. The tone should be knowledgeable, slightly lighthearted, and professional.

**Lead Information:**
- Name: [Lead Name]
- Project Type: [Project Type]
- Inquiry Details: [Insert client's message]

**Response Structure:**
1. Thank them for reaching out to Wade Custom Carpentry.
2. Acknowledge their specific project details.
3. State our process (design-build, high-end custom remodeling).
4. Call to Action: Request a brief phone call to discuss the scope and schedule an initial site visit.
```

## 3. AutoMate AI Estimate Generation Prompt
Use this template to structure the text prompt that will be fed into Houzz Pro's AutoMate AI to generate an estimate.

```markdown
Generate a highly granular estimate for a [Project Type] based on the following scope and RSMeans data.

**Scope of Work:**
[Insert high-level scope]

**Granular Line Items Required:**
Please break down the following phases into specific tasks (e.g., instead of "Paint Room", list "Caulk, Putty, Sand, Prime, Apply 2 finish coats").
- Phase 1: [e.g., Demolition] - [Specific details]
- Phase 2: [e.g., Rough-in] - [Specific details]
- Phase 3: [e.g., Finishes] - [Specific details]

**Materials:**
[List key materials to be included in the estimate]
```
