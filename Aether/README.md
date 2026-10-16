# Aether: project orientation

This folder collects preparation material related to the Aether project and its task families. The notes here are intended to help a new contributor understand the workflow and vocabulary before opening a task.

## What is the platform for?

Outlier is a platform through which contributors may be assigned work that helps evaluate or improve AI systems. In the webinar discussed here, the task family was **Omni TTS ELO**, which asks a contributor to compare two generated speech responses against a reference transcript and, where available, a reference voice.

The task is not simply “Which audio sounds nicer?” It is a structured comparison. Each response must be judged on separate dimensions before choosing an overall winner.

## Terms used in these notes

- **Aether:** the project name used in the contributor’s Outlier workspace.
- **Omni TTS ELO:** the speech-response comparison task family discussed in the webinar. The webinar describes comparing Response A with Response B.
- **TTS (text-to-speech):** technology that generates spoken audio from text.
- **Reference transcript:** the text the generated audio is expected to speak.
- **Reference voice:** an example voice used to judge whether a generated voice resembles the target speaker. It may be absent in some tasks.
- **Response A / Response B:** the two generated audio samples being compared.
- **Audio and recording quality:** the cleanliness of the signal—noise, clipping, distortion, reverb, and similar defects.
- **Personal likeness / speaker similarity:** how closely the generated voice resembles the reference voice in identity and vocal characteristics.
- **Pronunciation faithfulness:** whether words are pronounced correctly and whether the audio stays faithful to the supplied text and applicable instructions.
- **Naturalness:** whether the delivery sounds like natural human speech, including pacing, rhythm, intonation, and conversational flow.
- **Dominant factor:** the dimension that most strongly explains the overall winner.
- **QM / QMO:** a project-support or quality-management contact as used in the meeting. Exact titles and responsibilities can vary; do not assume every support contact can change task assignment.
- **Multimango / MM:** the external task-workspace/dashboard name mentioned by participants. The name and interface may change.
- **Queue / EQ:** in the meeting, “EQ” is used to refer to an empty queue or no available tasks. Confirm the exact status text in your own interface.

## The Omni TTS ELO workflow

1. **Read the instruction and transcript.** Understand the intended words, context, tone, emotion, and any special delivery request. Some tasks may have no extra instruction beyond the transcript.
2. **Listen to the reference voice, if supplied.** Note stable features such as pitch range, timbre, texture, accent, and speaking style.
3. **Listen to Response A from beginning to end.** Follow the transcript while listening. Notice omissions, added words, pronunciation, artifacts, and delivery.
4. **Listen to Response B from beginning to end.** Apply the same checks rather than judging it only against your memory of A.
5. **Rate each dimension independently.** Do not use a naturalness issue as an audio-quality penalty unless there is a genuine signal problem.
6. **Choose the overall preference.** Select A or B based on the full set of dimensions; the webinar says there is no tie option for overall preference.
7. **Choose the dominant factor.** Select a dimension where your chosen response actually won; do not choose a dimension you rated as a tie.
8. **Check all required fields and submit.** If the audio cannot play, the language is wrong, or both samples are entirely off-script, follow the current task’s rejection instructions instead of guessing.

## The four rating dimensions

| Dimension | Main question | Judge | Do not confuse it with |
|---|---|---|---|
| Audio and recording quality | Is the signal clean and intelligible? | Noise, clipping, distortion, reverb, static, loops, recording defects | A flat or boring speaking style by itself |
| Personal likeness | Does the generated voice resemble the reference speaker? | Timbre, pitch qualities, vocal texture, identity, speaking patterns | Whether the words are correct |
| Pronunciation faithfulness | Are the words pronounced as intended, and does the audio follow the transcript? | Mispronunciations, dropped syllables, unclear articulation, added or missing content | Whether the voice sounds expressive |
| Naturalness | Does it sound like a person speaking naturally? | Prosody, pacing, rhythm, intonation, emphasis, flow, expressiveness | Signal cleanliness or speaker identity alone |

The webinar describes four response choices for audio quality and pronunciation faithfulness: A better, B better, both good, or both bad. Personal likeness additionally has `N/A` when no reference voice is supplied. Naturalness and overall preference require choosing A or B. Follow the exact controls shown in the active task if the interface changes.

## A simple example

Suppose A and B speak the correct words clearly. A has a slightly flat delivery but clean audio; B sounds lively but has a distracting crackle throughout.

- **Audio quality:** A may be better because the signal is cleaner.
- **Naturalness:** B may be better if its rhythm and intonation sound more human.
- **Pronunciation faithfulness:** both may be good if both say the intended words correctly.
- **Overall preference:** decide which response is better across the task’s full criteria, and ensure the decision is consistent with the dimension ratings.

This is an illustrative example, not an official assessment answer.

## Availability and assignment are separate from quality

The webinar Q&A includes contributors whose Omni task tile was missing, whose queue appeared and then disappeared, or whose audio task failed to load. The project representative described several possible causes: no tasks currently available, fast task claiming, assignment changes, or a known loading issue. These explanations are not interchangeable. A missing task alone does not prove that a contributor has failed quality review or been removed.

For the detailed decision path, see [Troubleshooting](Guides/troubleshooting.md).

## Preparation checklist

Before starting a task:

- Use headphones if available.
- Read the transcript and all instructions first.
- Listen to every required audio in full.
- Check the transcript while listening; do not rely on memory alone.
- Separate signal defects, voice identity, pronunciation, and naturalness.
- Treat extra speech that is not in the transcript as a faithfulness problem, according to the webinar.
- Make a defensible A/B choice when a meaningful difference exists.
- Keep the overall choice and dominant factor consistent with the dimension ratings.
- Never submit a task with an audio that failed to load; use the current task’s documented rejection path.

## Related pages

- [Omni TTS ELO webinar notes]([ML_Aether_Omni-tts-elo.md])
- [Troubleshooting guide](Guides/troubleshooting.md)
- [Public community research](Research/community-reports.md)
