<img width="1470" height="132" alt="image" src="https://github.com/user-attachments/assets/2f4f8025-a105-4433-ba50-0ba1534693d3" />

A real-time sign language translation system that turns hand gestures into speech - SpeakAble

Built for environments where communication speed matters and accessibility is usually ignored.

<img width="1467" height="78" alt="Screenshot 2026-05-07 at 10 25 17 PM" src="https://github.com/user-attachments/assets/9d58a5d0-33b5-4839-b0d7-8223425884ce" />

---

## The Problem

Most people assume hearing-impaired individuals are only deaf.

Many are both deaf and mute.

That means even basic workplace communication becomes difficult:

* Asking for help
* Warning about danger
* Giving instructions
* Responding quickly

SpeakAble tries to reduce that gap using computer vision and real-time voice output.

---

## What SpeakAble Does

* Detects hand gestures through a webcam
* Recognizes predefined sign commands
* Converts gestures into spoken words
* Tracks confidence and interaction history
* Supports analytics logging for accessibility monitoring

All directly in the browser.

No hardware required.

---

## Features

* Real-time hand tracking with MediaPipe
* 20 workplace-focused gesture commands
* Instant speech feedback
* Emergency gesture detection
* Live confidence scoring
* Gesture history logging
* Google Sheets analytics integration
* Responsive futuristic dashboard UI

<img width="1104" height="756" alt="Screenshot 2026-05-07 at 10 25 49 PM" src="https://github.com/user-attachments/assets/e4f906bb-2856-4788-aaaf-1b338d1a1600" />

<img width="1470" height="879" alt="Screenshot 2026-05-07 at 10 31 17 PM" src="https://github.com/user-attachments/assets/31c5fee6-b942-4f69-8d93-7cccb570f6ae" />

<img width="1470" height="879" alt="Screenshot 2026-05-07 at 10 31 28 PM" src="https://github.com/user-attachments/assets/9a632f4b-b268-4373-ac80-d6fa17ac533c" />


---

## Example Commands

| Gesture   | Action                    |
| --------- | ------------------------- |
| HELP      | Request assistance        |
| STOP      | Halt operation            |
| BREAK     | Request a break           |
| WORK      | Resume work               |
| EMERGENCY | Critical emergency signal |
| THANK YOU | Express gratitude         |

---
<img width="397" height="745" alt="Screenshot 2026-05-07 at 10 25 10 PM" src="https://github.com/user-attachments/assets/e8b9414b-b4a9-4583-9125-9cdc98d3a7df" />

---

## Tech Stack

* HTML
* CSS
* JavaScript
* MediaPipe Hands
* Web Speech API
* Google Apps Script

---

## How It Works

```text id="6m9v4d"
Webcam Feed
     ↓
Hand Landmark Detection
     ↓
Gesture Classification
     ↓
Voice Output + Analytics
```

---

## Run Locally

```bash id="5lb7v8"
git clone https://github.com/yourusername/speakable.git
cd speakable
python -m http.server 8000
```

Open:

```text id="m1b0ot"
http://localhost:8000
```

---
<img width="1076" height="116" alt="Screenshot 2026-05-07 at 10 25 22 PM" src="https://github.com/user-attachments/assets/05f22e18-5ed2-44fa-8cd3-1a64a8ea2050" />

<img width="1458" height="780" alt="Screenshot 2026-05-07 at 10 26 12 PM" src="https://github.com/user-attachments/assets/84144aff-9f3e-48cf-814d-8f0920e231b3" />


---

## Why This Matters

Accessibility products are often treated like side projects.

They shouldn’t be.

Communication is infrastructure.

And for many hearing-impaired individuals, that infrastructure is still broken.

---

## Future Improvements

* Full Indian Sign Language support
* AI-trained gesture models
* Sentence-level translation
* Mobile application
* Offline edge inference
* Speech-to-sign mode

---

## Author

**Manas Dange**
Building AI projects focused on real-world communication problems.
