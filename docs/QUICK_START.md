# Quick Start

## 1. Import

Import the Nyxara AI Studio package into your Unity project.

---

## 2. Install Dependencies

Install required external systems:

- LLMUnity (Local LLM)
- Whisper (Speech-to-Text)
- Piper (Text-to-Speech, optional)

(See README for links)

---

## 3. Open Studio

Open:
Nyxara AI → Studio

---

## 4. Assign External Paths (IMPORTANT)

Go to the **Status** tab.

In the **Model and Service Paths** section:

- Click **Browse LLM** and select your `.gguf` model
- Click **Browse Whisper** and select your Whisper model

Optional (for voice output):
- Click **Browse Piper Exe** and select `piper.exe`
- Click **Browse Piper Voice** and select a `.onnx` voice file

Verify status:
- LLM Model Status → Found
- Whisper Model Status → Found
- Voice Output Status → Ready (if configured)

---

## 5. Setup Character

- Assign your ARKit-compatible character
- Confirm face renderer is detected

---

## 6. Build

Click:

Build Studio  
→ Apply Rig (if needed)  
→ Finalize Companion Root Prefab  

---

## 7. Test

- Enter Play Mode  
- Trigger input (mic or test input)  
- Verify AI response (text)

If Piper is configured:
- Verify voice playback + lip sync

---

## 8. Validate

Use:

- Status tab  
- Diagnostics  
- Lip Sync test  
- Full System Test  

---

## Notes

- Voice output is optional.  
- If Piper is not configured, Nyxara AI Studio will still work using text-based responses.  
- If dependencies are not installed, Nyxara AI Studio will still import and run, but AI, speech-to-text, and voice features will remain disabled until configured.
