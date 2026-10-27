# AssemblyAI

**Tier:** Tier 3  |  **Business domain:** AI  |  **Questions:** 15

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| ML Engineer | 0 | 0 | 3 | 5 | 2 | 5 |
| AI Engineer | 2 | 0 | 7 | 10 | 5 | 10 |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for a speech/ASR + TTS capability (buy Deepgram/ElevenLabs/Azure Speech vs fine-tune Whisper/self-host) when per-minute pricing at scale, latency, and accent/domain accuracy on your data define the call? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-speech-asr-tts-capability-buy-dee-69810) |
| How do you evaluate build-vs-buy when the ML capability's value comes from network effects you can't replicate (e.g. a shared fraud-model consortium or a speech model trained on data volumes only a hyperscaler has) — how do you price the unreplicable-data gap? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-evaluate-build-vs-buy-when-the-ml-capability-s-value-comes--69805) |
| How would you protect a FastAPI inference endpoint that is expensive per call from abuse, combining per-key rate limiting with per-key cost quotas tied to model compute? | deep understanding | SDE-1/2, SDE-2/3 | FastAPI | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-protect-a-fastapi-inference-endpoint-that-is-expensive-p-62920) |
| How would you evaluate a speech or ASR model and why is Word Error Rate not the whole story for a voice assistant? | deep understanding | SDE-1/2, SDE-2/3 | Model Evaluation Metrics | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-evaluate-a-speech-or-asr-model-and-why-is-word-error-rat-65848) |
| You have a speech-plus-transcript model and inference latency spikes when audio clips are long. How would you chunk streaming audio while keeping the text alignment correct? | deep understanding | SDE-1/2, SDE-2/3 | Multimodal AI | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-have-a-speech-plus-transcript-model-and-inference-latency-spikes-w-67084) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| What is Amazon Transcribe, and how could you combine it with Bedrock to build a meeting-summary feature? | basic concept | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | AWS | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-amazon-transcribe-and-how-could-you-combine-it-with-bedrock-to-73218) |
| How do you decide build-vs-buy for a speech stack (ASR + TTS) in a voice-agent product — buy Deepgram/ElevenLabs/Azure Speech vs self-host Whisper/open TTS — when per-minute pricing at scale, latency, and accent/domain accuracy on your data drive the call? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-speech-stack-asr-tts-in-a-voice-a-83762) |
| How would you design eval for a voice or speech agent at scale where ASR errors, latency, and response quality compound and can't be judged in isolation? | expertise | SDE-2/3, Architect/Principal | Evaluation at Scale | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-eval-for-a-voice-or-speech-agent-at-scale-where-a-86919) |
| How do you design a FastAPI transcription endpoint that streams a long audio file to a speech-to-text model without buffering the whole file in memory? | deep understanding | SDE-1/2, SDE-2/3 | FastAPI | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-design-a-fastapi-transcription-endpoint-that-streams-a-long-77057) |
| How would you build a FastAPI endpoint that accepts an audio file and returns a transcript using a speech-to-text API? | intermediate experience | Fresher, SDE-1/2, SDE-2/3 | FastAPI | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-build-a-fastapi-endpoint-that-accepts-an-audio-file-and--72941) |
| What's the trade-off in capacity terms between real-time voice/streaming inference and batch offline generation for the same fleet? | deep understanding | SDE-2/3, Architect/Principal | GPU Fleet & Capacity Planning | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-s-the-trade-off-in-capacity-terms-between-real-time-voice-streami-86658) |
| Describe how you'd fine-tune a Whisper model on domain audio and the pitfalls in the processor and feature-extraction pipeline that hurt WER. | deep understanding | SDE-1/2, SDE-2/3 | Hugging Face | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=describe-how-you-d-fine-tune-a-whisper-model-on-domain-audio-and-the-p-79945) |
| How do you monitor an ASR or transcription front-end feeding your NLP model so audio drift doesn't silently degrade text quality? | intermediate experience | SDE-1/2, SDE-2/3 | Model Monitoring & Drift Detection | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-monitor-an-asr-or-transcription-front-end-feeding-your-nlp--81149) |
| How would you evaluate a speech-plus-text meeting-summarization pipeline end-to-end when transcription errors and summary errors compound? What metrics separate the two failure sources? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Multimodal AI | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-evaluate-a-speech-plus-text-meeting-summarization-pipeli-80642) |
| You must expose a /transcribe endpoint that accepts audio, runs ASR, and optionally summarizes. How do you design the contract for large audio uploads, async processing, partial/streaming transcripts, and returning both transcript and summary? | deep understanding | SDE-1/2, SDE-2/3 | REST API | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-expose-a-transcribe-endpoint-that-accepts-audio-runs-asr-and--77177) |
