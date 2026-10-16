# Omni TTS ELO troubleshooting

This guide combines the webinar Q&A with cautious, general troubleshooting. It is not a substitute for the current instructions in the task interface or an official support response.

## First: identify which problem you have

| What you see | What it may mean | What to do next |
|---|---|---|
| Omni is absent from the dashboard | Assignment changed, the project is not currently available to your account/locale, or the project is paused | Check official project updates; ask support to confirm assignment status. Do not assume the account is broken. |
| Omni appears, but disappears after refresh | Queue may be empty or tasks may have been claimed; there may also be a display/loading issue | Note the time and exact message, refresh once, then check official updates. Avoid endless refreshing. |
| Task opens, but audio never loads | Possible task/player/network/browser issue | Do not submit incomplete ratings. Follow the current rejection/report flow and capture a redacted screenshot if permitted. |
| Audio plays, but rating controls are blank or missing | Possible UI defect | Do not guess ratings or submit blank fields. Check whether the project team has acknowledged the issue and report it through official support. |
| Both responses are in the wrong language or completely off-script | Sample may be invalid | Use the current task’s reject-sample process. |
| “No more sample tasks” or similar appears | Queue may be exhausted, paused, or not currently assigned work | This alone does not prove offboarding. Check the exact status and current official project updates. |
| “Unapproved” / ineligible status appears | May indicate a different state from an empty queue | Read the exact message and contact official support if clarification is needed. Do not infer the reason from Reddit alone. |

## Safe diagnostic sequence

1. **Read the exact status text.** “No tasks available,” “loading failed,” and “not eligible” are not equivalent.
2. **Check the official project/community updates.** Look for a current incident post or a loading-issue poll.
3. **Retry once carefully.** If the interface is stuck, a single refresh or a new supported browser session may help. Do not repeatedly submit or open multiple duplicate tasks.
4. **Check basic local conditions.** Confirm a stable connection, a supported up-to-date browser, and that audio playback is not muted or blocked. These are general checks, not a confirmed fix for the reported Outlier issue.
5. **Record the evidence.** Note the local date/time and time zone, task family, exact error wording, whether the audio began playing, and what action caused the failure.
6. **Report privately through official support.** Include only the information requested by the support form. Never post personal IDs, account email, task IDs, or unredacted screenshots in a public repository.
7. **Wait for confirmation if the issue is project-side.** A QM may be able to check status but may not control assignment or be able to restore tasks manually.

## Example support report

> **Subject:** Omni TTS ELO task loading / queue issue
>
> Hello, I’m seeing a problem with Omni TTS ELO. At approximately [local date and time, including time zone], [describe the exact behaviour: task absent / task disappears / audio does not load / rating controls missing]. I tried [brief steps]. The exact status or error shown was: “[quote the message]”. Could you confirm whether this is a known technical issue or an assignment/queue status issue? I can provide a redacted screenshot through the approved channel if needed. Thank you.

Replace the bracketed fields with your own facts. Do not claim that other contributors’ experiences prove the cause of your problem.

## When audio is available: evaluation troubleshooting

- **The voice sounds flat:** usually consider naturalness; do not automatically penalize audio quality.
- **The signal has clicks, crackle, clipping, or strong reverb:** consider audio and recording quality.
- **The voice does not resemble the reference:** consider personal likeness, not transcript accuracy.
- **A word, name, number, or syllable is mispronounced:** consider pronunciation faithfulness.
- **The audio adds a sentence absent from the transcript:** the webinar says to treat it as a faithfulness issue.
- **Both samples are entirely off-script:** reject the sample according to the current instructions instead of inventing a winner.
- **There is no reference voice:** use N/A for personal likeness if that option is available, as described in the webinar.

## What not to conclude

- A missing task does not, by itself, prove account deactivation.
- A task loading error does not, by itself, prove a quality failure.
- Another contributor having tasks does not guarantee your locale or account has the same assignment.
- A Reddit comment is not an official explanation for your account status.
- A workaround that helped one person may not fix the same issue for someone else.
