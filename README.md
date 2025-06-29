# Slack API Messaging Assignment – MERN Stack Intern

This project demonstrates basic Slack messaging operations using the Slack API and Python SDK (`slack_sdk`). The tasks were completed as part of the technical assignment for the MERN Stack Internship at Sitegalleria Pvt Ltd.

---

## Features Implemented

- Send a Message
- Schedule a Message for Future Delivery
- Retrieve Messages
- Edit a Message
- Delete a Message
- Used Slack Developer Sandbox Environment
- User-friendly terminal input (no hardcoded messages)

---

## 🛠️ Technologies Used

- Python
- [slack_sdk](https://pypi.org/project/slack-sdk/)
- Slack API (via Bot Token)

---

## Project Structure

```bash
.
├── send_message.py         # Sends a message to a Slack channel
├── get_message.py          # Retrieves latest messages from the channel
├── edit_message.py         # Edits a message using timestamp
├── delete_message.py       # Deletes a message using timestamp
├── schedule_message.py     # Schedules a message for later
```

---

## How to Run

> No setup needed – tokens and channel ID are already included

### 1. Install dependencies (if not already):

```bash
pip install slack_sdk
```

### 2. Run each script:
Send a message:
```bash
python send_message.py
```
- Enter your custom message
  
Schedule a message:
```bash
python schedule_message.py
```
- Enter message + delay in seconds (e.g., 60)
  
View recent messages:
```bash
python get_message.py
```
- View last 10 messages and their timestamps
  
Edit a message:
```bash
python edit_message.py
```
- Paste the timestamp, then enter new message
  
Delete a message:
```bash
python delete_message.py
```
- Paste the timestamp to delete that message

---

## Author
- **Name:** Anjali  
- **Submission for:** MERN Stack Intern – Sitegalleria Pvt Ltd  
- **Date:** 30 June 2025

---

## Notes

- This is a private assignment submission.
- Hardcoded tokens are used only for local/private testing and demo.

---
