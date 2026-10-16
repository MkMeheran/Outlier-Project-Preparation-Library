# Webinar notes: Aether — Omni TTS ELO

**Session date:** 16 October 2026, based on the date the notes were prepared; confirm the original meeting date if it differs.  
**Source:** two user-provided Zoom transcript excerpts: a presentation and Q&A, followed by a second Q&A excerpt.  
**Purpose:** searchable preparation notes for future contributors.

> These are paraphrased study notes, not an official Outlier policy document. Automated transcription contains errors and some speaker labels or words are uncertain. Where the meaning is unclear, this guide says so rather than pretending the transcript is exact.

## 1. Session at a glance

The presenter explained how to compare two generated speech samples using a reference transcript and, when provided, a reference voice. Contributors should listen to the full samples, check the spoken words against the transcript, look for technical audio defects, and rate each quality dimension independently. After the dimension ratings, they must choose an overall winner and identify the dominant factor behind that choice.

The Q&A focused heavily on task availability and loading problems. Several contributors said Omni was absent from their Multimango dashboard, appeared in the queue and disappeared after refreshing, or opened but did not load correctly. The project representative distinguished between account-specific assignment, an empty or rapidly claimed queue, and a reported loading issue. In most cases, the representative could not manually assign a contributor to a task and advised waiting or reporting the issue through the project’s available support channels.

## 2. Presentation notes, in order

### 2.1 Read before listening

Start with the instructions and transcript beneath the reference-voice area. The transcript establishes what the audio is expected to say. Instructions, when present, may also specify tone, emotion, or speaking style. The presenter noted that some local-language tasks may have no extra instruction, so the transcript and context become the main guide to intended delivery.

**Example:** If the instruction asks for a calm, reassuring tone, the words can be correct while the delivery still misses the instruction. If there is no such instruction, do not invent one; judge the delivery against the transcript and normal speech expectations.

### 2.2 Listen to both responses completely

Play Response A in full, then Response B in full. While listening, follow the text to check that the audio matches the transcript. Also notice static, clicks, background noise, clipping, distortion, room reverb, cut-off words, repeated loops, or other artifacts.

The presenter advised using headphones so subtle differences are easier to hear. Listen to the reference voice too when the task provides one.

### 2.3 Rate each dimension independently

Do not let one dimension contaminate another. A monotone voice can still have clean recording quality. Conversely, an expressive voice can have poor recording quality if it contains audible distortion or distracting noise.

#### A. Audio and recording quality

Judge the signal itself: cleanliness, intelligibility, noise, clipping, distortion, compression problems, substantial reverb, speech slurs caused by audio generation, and repetitive audio loops.

- A response can be technically clean even if it sounds monotonous.
- A response can be expressive but still score worse on recording quality if the signal contains distracting artifacts.
- “Both bad” should be reserved for cases where both audios have meaningful, distracting defects. A faint ambient noise or minor reverb is not automatically a failure; consider whether an average listener would find it distracting.
- The presenter’s examples of obvious problems included distortion, background noise, clipping, substantial room reverb, obvious speech slurs, and repetitive loops.

**Example:** A is flat but clean; B has a loud crackle that repeatedly interrupts speech. Audio quality may favour A even if B sounds more lively.

#### B. Personal likeness / speaker similarity

Compare the generated voice with the reference voice. Focus on stable vocal identity: timbre, pitch range, texture, speaking patterns, and overall resemblance. Do not score this dimension based on whether the words differ.

- Choose `N/A` when no reference voice is provided.
- If the generated voice conveys a different emotion but retains the reference speaker’s characteristic timbre and pitch qualities, it may still have strong likeness.
- The presenter said that if both responses clearly have the opposite gender from the reference speaker, mark both bad for personal likeness rather than rejecting the sample solely for that mismatch. If only one response has the mismatch, the other may be preferred on likeness.

**Example:** The reference voice is low-pitched and slightly raspy. A is similarly low and raspy but more cheerful; B is much higher and smoother. A may be closer in speaker likeness even if its emotional delivery differs.

#### C. Pronunciation faithfulness

Judge whether words are pronounced accurately and clearly according to the transcript and any applicable instruction. The presenter highlighted chronic mispronunciation, dropped syllables, stumbling over difficult phrases, and speech that sounds non-native when that is not requested.

Pay special attention to names, numbers, technical terms, and unusual text. The presenter also said that content added beyond the transcript should be treated as a faithfulness issue and penalized in this dimension.

**Example:** The transcript says “Mira submitted the report on Tuesday.” If a response says “Mira submitted the report on Thursday,” that is a content mismatch, not merely a difference in speaking style.

#### D. Naturalness

Judge whether the audio sounds like a real person speaking naturally. Listen for prosody, pacing, rhythm, intonation, emphasis, conversational flow, expressiveness, personality, and contextual appropriateness.

The presenter said this dimension has only two choices: Response A better or Response B better. There is no “both good” or “both bad” option for naturalness in the described interface.

**Example:** Both samples pronounce every word correctly. A has evenly spaced, mechanical pauses; B uses more natural phrase-level pauses and emphasis. Naturalness may favour B.

### 2.4 Select overall preference

After rating the individual dimensions, choose a definitive winner between A and B. The presenter described this as a holistic decision: consider all relevant dimensions rather than copying the result of one dimension without thought. The overall preference control has no tie option in the described workflow.

The choice must remain consistent with the ratings. If A wins the overall decision, the ratings should provide a defensible explanation for why A is stronger overall, even if B wins one dimension.

### 2.5 Select the dominant factor

Choose the dimension that contributed most to the overall preference. It should be a dimension in which the selected response was preferred, not a dimension rated as a tie.

**Example:** If A wins overall and A is clearly more natural while both samples are equally clean and accurate, naturalness is a reasonable dominant factor. Do not choose audio quality if you rated audio quality as a tie.

### 2.6 Submit or reject appropriately

Before submitting, make sure all required fields are completed, including overall preference and dominant factor. Then use the submit control.

The presenter described a “new comparison” option for cases where the contributor is not confident, needs a new task, or must reject a problematic sample. Follow the exact current interface and project rules.

Examples of reasons to reject or skip, as described in the webinar:

- An audio cannot be played or fails to load.
- The audio is in the wrong language.
- Both responses are completely off-script.
- Both responses contain severe looped repetitions; the presenter suggested refreshing the browser to obtain a new task in that case.

If only one response contains added content, the webinar says to penalize that response under pronunciation faithfulness. If both are completely off-script, reject the sample rather than trying to choose a winner between unusable responses.

## 3. Example review from the webinar

The presenter played an example involving a recipe ingredient list. The contributor had incorrectly mixed delivery and pacing issues into audio quality or pronunciation judgements. The lesson was that rhythm and delivery belong under naturalness unless there is a distinct technical audio defect or a pronunciation/content error.

A second example involved two similar spoken responses. The contributor rated audio quality, personal likeness, and pronunciation faithfulness as both good, preferred Response B for naturalness, selected B overall, and chose naturalness as the dominant factor. The presenter identified this as a correct application of the rubric.

The spoken sample wording in the automated transcript is imperfect, so these examples are recorded as lessons rather than exact assessment scripts.

## 4. Do’s and don’ts

### Do

- Use headphones where possible.
- Read the transcript and instructions before evaluating.
- Listen to the full reference and both full responses.
- Check the transcript while listening.
- Look for signal defects and cut-off words.
- Compare every rating dimension before choosing the winner.
- Make a clear A/B choice when there is a meaningful, defensible difference.
- Keep the overall preference consistent with the dimension ratings.

### Don’t

- Do not ignore distracting noise such as traffic, birds, other speakers, or strong reverb.
- Do not judge before understanding the transcript and instructions.
- Do not submit an evaluation if an audio has failed to load.
- Do not base the overall preference on a dimension where the responses are tied or the difference is inconclusive.
- Do not confuse pacing and rhythm with technical recording quality.
- Do not confuse speaker similarity with text accuracy.

## 5. FAQ distilled from the session

### How strict should audio quality be?
The presenter prioritised intelligibility. Background voices, birds, cars, substantial reverb, obvious TTS slurs, and similar defects may be serious when they distract an average listener. Minor ambient sound is not automatically disqualifying.

### What if one response repeats a phrase in a loop?
The presenter said to treat the loop as an audio artifact and penalize audio quality.

### What if both responses contain looped repetitions?
The presenter suggested refreshing the browser and moving to a new task, following the current interface’s supported process.

### What if one response adds words that are absent from the transcript?
Treat it as a faithfulness issue and penalize it under pronunciation faithfulness, as described in the webinar.

### What if both responses are entirely off-script?
Reject the sample rather than forcing an A/B decision.

### What if a system prompt is spoken before the main transcript?
The presenter said to disregard the system prompt and rate the task as usual. This should be applied only where the current task instructions support that interpretation.

### What if the reference voice and generated voices have a gender mismatch?
If both responses clearly mismatch the reference, the webinar says to mark both bad for personal likeness. If only one mismatches, the other can be preferred on likeness. Do not reject the sample solely for this reason unless the current task rules say otherwise.

## 6. Q&A: missing tasks and dashboard problems

The Q&A included several contributors reporting that Omni was missing from their Multimango dashboard, despite seeing other projects or hearing that people with the same locale had tasks. The project representative checked or offered to check account status in some cases, but repeatedly explained that project assignment was not something they could manually change.

### Case A: Omni is absent from the dashboard

A contributor said Omni had disappeared since the previous day, while other contributors using the same language seemed to have tasks. The representative said there was no apparent account issue in the case discussed and suggested the contributor might not currently be assigned to Omni because of changing client demand. The contributor was advised to wait; the representative said they could not manually assign the project.

**Takeaway:** Do not assume that another contributor’s queue proves your own account is broken. Ask support to check assignment status, but understand that a QM may not be able to assign the task manually.

### Case B: No project visible when the contributor wants to start work

A contributor asked to return to Omni after being away from it for several days. The representative said the queue might have run out of tasks and that contributors would need to wait for more tasks from the client. The representative offered to check the account, while explaining that task assignment was not under their direct control.

**Takeaway:** An empty queue and a project-assignment problem are different possibilities. Confirm which one applies rather than repeatedly refreshing without recording the error.

### Case C: The task appears, then disappears or locks

A contributor described Omni appearing in the queue but becoming unavailable when they clicked it. They also described refreshing for a long time and seeing the task disappear. The representative said task volume was lower than before and that tasks might be claimed quickly. They also acknowledged that other people had reported a loading issue and said it had been reported, though they could not confirm whether it was resolved.

**Takeaway:** A task tile that appears briefly may not guarantee a task has been reserved for you. However, if the task opens and audio or controls fail to load, record it as a technical issue rather than assuming it is just queue exhaustion.

### Case D: The contributor can see the audio but then returns to the dashboard

A participant described entering a task, seeing the audio/reference area, and then being sent back to the dashboard. The representative acknowledged that other contributors had experienced a similar issue and said it had been reported. A poll for the loading issue was mentioned during the meeting.

**Takeaway:** Check the official community channel for the relevant incident report or poll, if still available. Do not submit an incomplete evaluation when the required audio or controls have failed.

### Case E: A contributor shares an ID for an account check

One participant said they could not see Omni and offered to share their ID so the team could check the account. The representative replied that there was no apparent account issue and that the project might currently be in queue for that locale.

**Privacy note:** Share account or contributor IDs only through the official private support channel when requested. Do not publish them in this repository.

## 7. Chat references captured with the meeting notes

The supplied Zoom chat excerpt contained a link to a community thread titled **“Omni TTS loading issue — PST October 13”**:

- https://community.outlier.ai/t/omni-tts-loading-issue-pst-october-13/2971631

The visible chat also included short messages such as “i done thank tyou” and a contributor asking why the QMO had not answered. These messages do not establish an official answer or a resolution. The linked thread is more useful for readers investigating the loading issue; verify that it remains accessible and current before relying on it.

## 8. Practical decision tree

```text
Start task
  ├─ Audio will not play / required controls are missing
  │    └─ Do not guess or submit incomplete ratings; follow the current reject/report path.
  ├─ Task tile disappears before the task opens
  │    └─ Record the time and exact status; check queue/assignment updates and retry later.
  ├─ Omni is absent but other projects are visible
  │    └─ Ask official support to confirm assignment status; they may not be able to assign it manually.
  ├─ Audio plays, but the voices differ
  │    └─ Rate each dimension independently; use N/A for likeness if no reference voice exists.
  └─ Both responses are entirely off-script or wrong-language
       └─ Use the task’s rejection process rather than forcing an A/B winner.
```

## 9. Suggested personal quality checklist

Before submitting, ask yourself:

1. Did I read the transcript and instructions first?
2. Did I listen to both responses fully?
3. Did I check the spoken words against the text?
4. Did I judge signal cleanliness separately from naturalness?
5. Did I compare speaker identity only when a reference voice exists?
6. Did I treat added or missing content as a faithfulness issue?
7. Does my overall winner make sense given my dimension ratings?
8. Is my dominant factor one of the dimensions where the winner was actually better?
9. Are all required fields complete, and did every audio load correctly?

## 10. Sources and limitations

- Primary source: the two Zoom transcript excerpts supplied by the repository author. The transcript appears to be generated automatically, so some wording and speaker attribution may be inaccurate.
- Community issue linked in chat: [Omni TTS loading issue — PST October 13](https://community.outlier.ai/t/omni-tts-loading-issue-pst-october-13/2971631).
- Public community reports and broader context: [Aether community research](../../Research/community-reports.md).

These notes describe what was said in one meeting. They do not guarantee that the current task interface, available labels, assignment process, or rejection rules remain unchanged.
