# Language study

This is my experiment in using large language models to help me learn foreign languages.

The content is written by AI, by various tools and models:

- copilot-cli
- gemini-cli
- claude-code (connected to the local Ollama model)

I have written a simple [`language-teacher` SKILL.md](https://github.com/dpurge/agent-config/blob/main/skills/language-teacher/SKILL.md) file to instruct language models what kind of output I expect.

I plan to test it on various languages and various language models to see the quality of the output.

I copy a short text from the internet and simply tell the model to create a lesson for me.

The output format is such that I can easily copy it to my other tools to compile it to Anki packages that I can import to AnkiDroid.

Be aware that the generated output does contain errors - but I find it usable.

## Notes

### 2026-03-16 Model struggles with transcriptions

Transcription seems to be problematic for the model - its presence make the model take a lot more time.
At the same time, the quality of the transcription that model is producing is poor.
I should delegate transcription of the text to the external tool - it's hard to trust the model's output.
The next step is to use the local model and compare the quality.
