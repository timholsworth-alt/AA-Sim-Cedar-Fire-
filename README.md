# Cedar Fire — ATGS Trainer

A browser-based radio trainer for Air Tactical Group Supervisor students. You are Air Attack 230 in the back seat of an OV-10 over the Cedar Fire. Make your calls in the blind, clear tankers and copters into the FTA, give target descriptions, clear drops on final and give departure briefings, all by voice. Every call is graded against the CAL FIRE Standards for Aerial Supervision (CSAS, March 2025).

## Use it
Open the GitHub Pages address for this repository in **Chrome or Edge**, click **Check microphone**, then **Launch**.

- Hold a radio key (mouse, **Space**, or number keys **1–7**) and talk. Release, check the words, press **Enter** to transmit.
- **Scripts** shows the standard wording for every call. **End** shows your report card.

## Publish or update
1. Upload `index.html` to the repository root (Add file → Upload files → Commit changes). The file must be named exactly `index.html`.
2. Settings → Pages → Deploy from a branch → `main` / root.
3. After a minute or two, reload the site with Ctrl+Shift+R. The briefing screen shows the version number.

The whole trainer is the single file `index.html`. It loads three.js and fonts from public CDNs and needs an internet connection for speech recognition.

This is a training aid, not policy. The CSAS and your instructors are the authority.
