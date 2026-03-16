# Puzzle Master Challenge

A bilingual AI escape room challenge system prompt and supporting documentation for use with custom GPTs (e.g., CanChat).  
This repository also includes an event review document outlining practical deployment lessons and recommendations.


## Contents

- **PuzzleMaster_Billingual_EscapeRoom_prompt.txt / system_prompt.md** — The full bilingual (English/French) escape room system prompt for AI/cGPT import.
- **Puzzle Master Challenge Event Review.docx** — Event review and recommendations document.
- **README.md** — This file.


## Overview

This repository supports deploying and running a bilingual, prompt-engineering themed AI escape room using a Custom GPT.  
It enables interactive, turn-based puzzle gameplay for AI literacy, with adaptive hints and robust rule enforcement.  
Event review documentation is also included to guide improvements for future iterations.


## How to Use the System Prompt – Step by Step

### **1. Prepare the System Prompt File**

- Download or copy `PuzzleMaster_Billingual_EscapeRoom_prompt.txt` from this repository.
- Make sure it is stored locally on your computer and easy to access.
- Open the file in a plain text editor for copy-pasting.

### **2. Sign In to CanChat at HICC (or Other Custom GPT Platform)**

- Open your browser and navigate to CanChat or the custom GPT builder your organization uses.
- Log in with your credentials.

### **3. Create a New Custom GPT Instance**

- Click **‘Create a GPT’**, **‘Build your own GPT’**, or the appropriate button.
- Enter a clear name (e.g., `Puzzle Master: Bilingual Escape Room Guide`).
- Optionally, upload an icon or choose an avatar.

### **4. Add the System Prompt**

- Locate the **System Prompt** or **Instructions** field in the GPT builder interface.
- **Delete any default content.**
- Open `PuzzleMaster_Billingual_EscapeRoom_prompt.txt`, select all text, and copy it.
- Paste the entire prompt into this field.
- Ensure formatting and sectioning are preserved for clarity.

### **5. Configure GPT Settings**

- Turn off unnecessary capabilities (browsing, code, file upload) unless needed.
- Optionally, write a short public description:  
  `Bilingual AI escape room. Turn-based puzzle master for prompt engineering training.`
- Set knowledge cutoff to the latest available.
- Restrict access or share links as required for your group or event.

### **6. Save, Test, and Deploy**

- Save or publish your custom GPT.
- **Test**: Try starting a session in both English and French ("start"/"commencer") and issue a few sample commands ("hint"/"indice", puzzle responses).
- Ensure turn-logic, language detection, and hinting behave as expected.
- Share the session/join link if others will play.

### **7. For Events and Leaderboards**

- Instruct participants to take a screenshot of their final performance summary at the end, for leaderboard submission (as performance data is session-limited).


## Event Review & Continuous Improvement

- The `Puzzle Master Challenge Event Review.docx` file summarizes technical and fairness issues observed during live challenge deployment, with concrete recommendations on timing, scoring, transparency, and participant experience.
- Refer to this document when running new trainings or updating your system prompt for best-practice improvements.


## License & Use

For internal, educational, AI literacy, and training use.  
No personally identifying information is stored or required—designed for anonymous, equitable gameplay.


## Support

For troubleshooting or improvements, consult the event review document or contact your designated AI literacy facilitator/admin.
