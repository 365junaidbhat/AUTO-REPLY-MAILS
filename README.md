```markdown
# Gmail Autoresponder

## Overview

This Node.js-based application is designed to automate responses to emails received in a Gmail mailbox during a vacation. The application performs the following tasks:

1. **Check for New Emails:**

   - Utilizes the "Login with Google" API for authentication.
   - Periodically checks for new emails in the specified Gmail ID.

2. **Send Replies to Unanswered Emails:**

   - Identifies and responds to emails that have no prior replies.
   - The content of the reply can be arbitrary.

3. **Add Label and Move Email:**

   - Adds a label to the email in Gmail.
   - Moves the email to the labeled category.
   - Creates the label if it doesn't exist.

4. **Repeat Sequence:**
   - Executes the sequence of steps 1-3 at random intervals (45 to 120 seconds).
```
