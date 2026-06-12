# Executive_Assistant
Executive Assistant persona .json
# Executive Assistant AI Persona

This folder contains a persona configuration (`executive_assistant_persona.json`) for an AI to act as a **proactive, efficient, and discreet executive assistant**.

## How to Use

### 1. Load the Persona
- **If using a customizable AI (e.g., OpenAI GPT with system messages):**  
  Copy the entire `.json` content into the **system prompt** or persona field.
- **If using a local AI interface (e.g., SillyTavern, TextGen WebUI):**  
  Import the `.json` file as a character/persona.

### 2. Basic Commands
Once the persona is active, speak naturally. Examples:

| You say | AI does |
|---------|---------|
| `summarize_emails` | Lists unread emails with action items. |
| `draft email to John about Q3 budget` | Produces a draft email. |
| `schedule_meeting with Sarah and Mike tomorrow` | Finds available slots, checks conflicts. |
| `whats_next` | Shows top tasks and next meeting. |
| `prep_for_meeting "board review"` | Gathers agenda, notes, decisions. |

### 3. Proactive Behaviors You’ll Notice
- The AI will **flag urgent items** first (⚠️ URGENT).
- It will **summarize** before giving details.
- It will **remind you** of overdue tasks or pending follow-ups.
- If unclear, it will **ask a clarifying question** instead of assuming.

### 4. Customization Tips
Edit the `.json` file to match your preferences:

- **Name** — Change `"Elena"` to any name.
- **Tone** — Adjust `"tone"` and `"formality"` values.
- **Commands** — Add or remove `"commands"` as needed.
- **Templates** — Modify `"response_templates"` to fit your voice.

### 5. Example Workflow

**You:** *Elena, what’s my priority right now?*

**AI:**  
*Good afternoon. One urgent item needs your attention before 3 PM.*  

*⚠️ URGENT: Vendor contract expires Friday. Legal hasn’t signed the renewal.*  
*Recommended action: Approve draft changes I’ve prepared?*  

*Other tasks:*  
*- 2 PM – Team sync (15 min)*  
*- Follow up with marketing on Q4 plan (remind them now?)*

---

**Tip:** Use `"whats_next"` every morning to start your day organized.
