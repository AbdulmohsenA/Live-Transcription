# Live Transcription
This is a basic live transcription script to process incoming audio stream and transcribe it simultaneously.

## Information

- The model used is Whisper v3 turbo. Any model could be used instead but hardware performance is a bottleneck.
- The script will send data to be processed in chunks (sentences) instead of sending it in a time-bound method (i.e. every 1 second)
- According to different papers, the natural pause time in English is 300-450 milliseconds. Thus, the script will process a chunk when it senses a pause.

## References

```
Šubert, M., Tykalová, T., Novotný, M. et al. Automated analysis of spoken language differentiates multiple system atrophy from Parkinson’s disease. J Neurol 272, 113 (2025). https://doi.org/10.1007/s00415-024-12828-w
```
