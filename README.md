# Semantic-Chunking-of-a-Youtube-Video
# Objective :
Extract high-quality, meaningful (semantic) segments from the specified YouTube video

# Workflow:
1. **Download Video and Extract Audio:** Download the video and separate the audio component.
2. **Transcription of Audio:** Utilize an open-source Speech-to-Text model to transcribe the audio. *Provide an explanation of the chosen model and any techniques used to enhance the quality of the transcription.*
3. **Time-Align Transcript with Audio:** *Describe the methodology and steps for aligning the transcript with the audio.*
4. **Semantic Chunking of Data:** Slice the data into audio-text pairs, using both semantic information from the text and voice activity information from the audio, with each audio-chunk being less than 15s in length. *Explain the logic used for semantic chunking and discuss the strengths and weaknesses of your approach.*
