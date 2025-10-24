# Google Sheets → Email Notification Workflow

### Description
This n8n workflow sends an email whenever a new row is added to a Google Sheet.  
Useful for lead alerts, sign-up notifications, or data collection forms.

### Nodes Used
- Google Sheets Trigger
- Gmail Node
- Function Node (for message formatting)

### Setup
1. Clone this repo or download the JSON.
2. Import it into your n8n instance.
3. Connect your Google and Gmail credentials.
4. Activate the workflow and test it by adding a new row.

### Example Output
📧 Email sent to `your@email.com` with new row details.

---

> 💡 Tip: Adjust the trigger interval or email message to match your use case.
