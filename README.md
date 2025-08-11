# ClientWebsiteUpdateRequest
Form for client website update requests - maintenance automation 
# Client Request Form — Questions (Copy/Paste into Google Form, Tally, or Airtable Form)

1. **Client Name** (Short Answer)
2. **Requester Name & Email** (Short Answer)
3. **Page / URL that needs updating** (Short Answer)
4. **What needs to change?** (Long Answer)
5. **Change Type** (Dropdown)
   - Content Update
   - New Page
   - Blog Post
   - Event
   - Design/CSS
   - SEO/Meta
   - Integration
   - Bug Fix
   - Redirect
   - Other
6. **Priority** (Dropdown): Urgent, High, Normal, Low
7. **Is there a deadline?** (Date)
8. **Link to assets (images, copy, docs)** (Short Answer / URL)
9. **Approval needed before publish?** (Yes/No)
10. **Additional notes** (Long Answer)

---

## How to Auto-Add to the Tracker
- Set your form’s response destination to a Google Sheet.
- Use an **import range** or a Zapier automation to copy new rows into the **Requests** tab of the `Website_Maintenance_System.xlsx` structure.
- Map fields:
  - Request ID → (auto-number in Zapier like `REQ-{{zap_meta_timestamp}}` or use a formula)
  - Date Submitted → Form timestamp
  - Client → Client Name
  - Page/URL → Page / URL
  - Change Type → Change Type
  - Priority → Priority
  - Description → What needs to change?
  - Assets Link → Link to assets
  - Status → New
  - Assignee → Your default assignee or blank
  - SLA Due → Deadline
  - Notes → Additional notes
  - Client Approval (Y/N) → Approval needed before publish?
