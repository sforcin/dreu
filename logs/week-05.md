# Week 5

**Dates:** 07-06 to 07-12

## Goals

- Move the interaction pipeline onto Pastoral.
- Connect the phone interface to Pastoral and Blossom.
- Run services in the background using tmux.
- Add start-and-stop audio recording.
- Save transcripts without permanently storing raw audio.
- Prepare a project presentation and demo.

## Approach and Implementation

We defined the roles of the three devices. Blossom would handle audio, speech playback, movements, and lights. Pastoral would run Whisper, Ollama, Kokoro, study logic, and data storage. The phone would provide the recording button, surveys, and task display.

I moved the main software components to Pastoral and learned how to use tmux to keep the Flask application and spoken-dialogue server running in the background.

I connected the phone to Pastoral and tested audio recording and transcription. Transcribed speech appeared in the terminal, and transcripts were saved after each website interaction.

I also added webcam-recording code and created an outline for an informal presentation and system demonstration.

## Results

- Defined the responsibilities of Blossom, Pastoral, and the phone.
- Moved the main software components to Pastoral.
- Learned how to use tmux for persistent processes.
- Connected the phone interface to Pastoral.
- Successfully recorded and transcribed speech.
- Saved transcripts after each interaction.
- Added webcam code for future testing.
- Prepared an outline for the project presentation.

## Notes

The phone-to-Pastoral system is functional, but the interaction flow is still scrambled and needs improvement.

The main remaining task is fully connecting Blossom to the existing pipeline and creating a smoother participant interaction.