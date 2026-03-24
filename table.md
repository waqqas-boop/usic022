| Feature | API Endpoint | Description |
| --- | --- | --- |
| Upload Audio | POST /stream/copy | Upload from URL or direct upload |
| Stream Video | GET /stream/{id}/manifest/video.m3u8 | HLS streaming |
| Add Audio Track | POST /stream/{id}/audio/copy | Add lyrics audio to video |
| List Tracks | GET /stream/{id}/audio | List all audio tracks |
| Transcribe | POST /ai/run/@cf/openai/whisper-large-v3-turbo | Speech-to-text |
| Text-to-Speech | POST /ai/run/@cf/deepgram/aura-2-en | Generate voiceovers |
| Music Gen | POST /ai/run/@cf/myshell-ai/melotts | AI music generation |
| Upload Captions | PUT /stream/{id}/captions/{lang} | WebVTT subtitles |
| Store Metadata | PUT /r2/bucket/{name}/object/{key} | Persistent storage |
| Delete Content | DELETE /stream/{id} | Remove content |