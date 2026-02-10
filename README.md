# Audio Transcribe

A full-stack application for transcribing audio files, built with a Java backend and React/TypeScript frontend.

## Features

- Upload audio files
- Automatic transcription
- Save and manage transcriptions
- Modern, responsive UI
- Real-time processing
- Transcription history

## Tech Stack

### Frontend
- **Framework**: React
- **Language**: TypeScript
- **Styling**: CSS
- **Build Tool**: Vite

### Backend
- **Language**: Java
- **Framework**: Spring Boot
- **Audio Processing**: Speech-to-text service integration

## Getting Started

### Prerequisites

- Node.js 16+ and npm (for frontend)
- Java 11+ and Maven (for backend)

### Installation

#### Backend Setup

1. Navigate to the backend directory:
```bash
cd audio-transcribe-backend
```

2. Build the project:
```bash
./mvnw clean install
```

3. Run the backend server:
```bash
./mvnw spring-boot:run
```

The backend will start on `http://localhost:8080`

#### Frontend Setup

1. Navigate to the frontend directory:
```bash
cd audio-transcribe-frontend
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

The frontend will start on `http://localhost:3000`

## Usage

1. **Upload Audio**: Click the upload button and select an audio file
2. **Process**: The file will be sent to the backend for transcription
3. **View Results**: See the transcribed text appear in real-time
4. **Save/Export**: Save or export your transcriptions
5. **History**: Access previously transcribed files

## Configuration

- Update API endpoint in frontend configuration
- Configure audio processing settings in backend
- Set up any required API keys for transcription services

## Project Structure

### Frontend (`/audio-transcribe-frontend`)
- `/src` - Source code
  - `/components` - React components
  - `/services` - API services
  - `/styles` - CSS files
- `/public` - Static assets

### Backend (`/audio-transcribe-backend`)
- `/src/main/java` - Java source code
- `/src/main/resources` - Configuration files
- `/src/test` - Test files
