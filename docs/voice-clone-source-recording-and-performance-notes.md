# Voice-Clone Source Recording and Performance Notes

The Professional Voice Clone used for this project was developed from source recordings prepared specifically for instructional narration. The goal was not only to capture clean, consistent speech, but to provide source material that reflected the pacing, articulation, and explanatory tone the finished videos would require.

## Recording Approach

I used a close-positioned dynamic microphone to prioritize the direct vocal signal and reduce the relative contribution of room reflections and ambient noise.

I maintained a consistent working distance and microphone position throughout the session. This helped limit changes in level, tonal balance, and proximity effect that could otherwise create inconsistencies across the source recordings and make it more difficult for the resulting model to reproduce a stable vocal character across later generations.

The source recordings were captured at a controlled level - strong enough to keep the voice clearly above room and recording-chain noise, while leaving enough headroom for emphasized phrases without clipping. Setting the recording level unnecessarily low would have required more gain later, raising room ambience, preamp noise, and other low-level artifacts along with the voice.

## Source Material and Performance Direction

I selected source material that aligned with the intended instructional delivery style: clear articulation, measured pacing, deliberate pauses, and a consistent explanatory cadence.

The recording set was organized around several instructional modes rather than one uniform performance. These included concept explanation, conversational teaching, step-by-step modeling, literacy-specific instruction, question-based explanation, misconception correction, visual-guided narration, reflective delivery, and calm transitions and closings.

Within the structured-literacy project, these modes supported shifts between explaining an instructional principle, modeling a teacher think-aloud, prompting guided practice, delivering corrective feedback, transitioning between lesson components, and closing with reflection.

I recorded the material with the final use case in mind rather than treating it as stylistically neutral voice data. The scripts and performances were shaped to reinforce an instructional delivery style suited to educator preparation while still providing variation in pitch, rhythm, emphasis, sentence length, and expression.

Consistency was important, but complete uniformity was not the goal. The source recordings needed to preserve a recognizable vocal identity while representing enough variation for the model to support different instructional functions without making every passage sound identical.

## Model Testing and Refinement

After the Professional Voice Clone was created, I tested it across project-specific scripts. This made it possible to assess how well the model handled the terminology, sentence structures, pacing, pronunciation, and instructional emphasis required by the actual deliverables.

I compared alternate generations for:

* Pronunciation, including phoneme-level accuracy
* Pacing and pause placement
* Prosody, phrasing, and instructional emphasis
* Tone and vocal consistency
* Clarity and naturalness

When a generation did not produce the intended result, I first considered whether the script itself was contributing to the problem. Punctuation, spacing, sentence length, alternate spellings, and surrounding context could all influence the resulting delivery. Small script adjustments sometimes produced a more natural correction than relying entirely on voice-setting changes or extensive post-production.

I also used ElevenLabs’ Regenerate Speech function frequently to create alternate performance options. Even when the settings remained unchanged, successive generations could produce useful differences in timing, emphasis, pronunciation, or phrasing. A regenerated take did not need to be stronger in its entirety to be valuable; an improved phrase, word, syllable, or phoneme could later be selected and incorporated during editing.

Testing also helped establish the practical limits of the voice model. Because isolated phoneme generation was not reliable enough for the instructional demonstrations, I recorded the teacher parts and worked with a colleague to record the student parts rather than forcing the model to produce material it could not consistently deliver.

## Transition to Post-Production

The selected generations then moved into the editing workflow, where alternate performances could be compared and assembled at the phrase, word, syllable, and, when needed, phoneme level.

An important mindset throughout the workflow was to treat each generation as source material rather than a finished product. ElevenLabs provided multiple ways to shape the generated performance, often with strong results, but the final narration was developed through methodical selection and meticulous post-production: combining the strongest phrases, refining timing and pronunciation, and maintaining a clear, consistent, and cohesive instructional voice throughout. The finished performance reflected both the capabilities of the voice model and the human judgment used to direct, evaluate, and refine it.

