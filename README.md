# VidSearchPy

VidSearchPy is a Python package for video transcription and search. It supports multiple transcription engines, integrates with search frameworks, and provides tools for text extraction, indexing, and retrieval.

## Features
- 🎙 **Transcription Extraction**: Supports Whisper.cpp, Vosk, and yt-dlp.
- 🔍 **Search & Highlighting**: Uses Whoosh, Meilisearch, or ElasticSearch.
- 🛠 **CLI & Python API**: Flexible usage for scripting and automation.
- 🌍 **Multilingual Support**: Transcribe and search across multiple languages.
- 🔑 **Keyword Searching**: Quickly find relevant segments in large transcripts.
- 📜 **Export Options**: JSON, TXT, SRT, VTT formats.
- 🚀 **Advanced Features**: AI summarization, multi-language support, SEO optimization.

## Installation
```bash
pip install vidsearchpy
```

## Usage
### Basic Transcription
```python
from vidsearchpy import transcribe

result = transcribe("video.mp4", engine="whisper")
print(result.text)
```

### Searching Transcripts
```python
from vidsearchpy import search

results = search("keyword", transcript_file="transcript.json")
print(results)
```

## CLI Usage
```bash
vidsearch transcribe video.mp4 --engine whisper
vidsearch search "keyword" --file transcript.json
```

## Roadmap
- [x] Whisper & Vosk support
- [x] Text search with Whoosh
- [x] Multilingual transcription
- [x] Keyword-based search
- [ ] AI summarization (BART, T5)
- [ ] Web API for SaaS integration
- [ ] YouTube & LMS support

## Contributing
Contributions are welcome! Feel free to open issues or PRs.

## License
MIT License

## Contact
For queries, reach out via GitHub Issues.
