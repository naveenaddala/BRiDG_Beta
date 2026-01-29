# BRiDG - Process Documentation Generator

Transform video recordings into comprehensive process documentation with embedded screenshots at key action points.

## Features

- **User Authentication** - JWT-based secure authentication
- **Project Management** - Organize videos into projects
- **Video Upload** - Support for MP4, MOV, AVI, MKV, WebM formats
- **VTT Transcript Support** - Upload VTT files or paste transcripts with timestamps
- **AI-Powered Analysis** - Automatic action point identification using LLM (OpenRouter)
- **Screenshot Extraction** - Automated screenshot capture at identified timestamps using FFmpeg
- **Document Generation** - Create documentation with embedded screenshots
- **Multiple Export Formats** - Download as DOCX (Word) or HTML with embedded images
- **Cloud Storage Ready** - Pluggable storage backend supporting local, AWS S3, Azure Blob, and Google Cloud Storage

## Quick Start

### Windows (PowerShell)
```powershell
.\start-application.ps1
```

## Setup

See [SETUP_GUIDE.md](SETUP_GUIDE.md) and [QUICK_START.md](QUICK_START.md) for full instructions.

## Application URLs

- **Frontend:** http://localhost:3000
- **Backend API:** http://localhost:8000
- **API Documentation:** http://localhost:8000/docs

## License

MIT
