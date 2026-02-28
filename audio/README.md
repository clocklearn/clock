# Clock Learning Audio Files

This folder contains bilingual audio files (Arabic and English) for the interactive clock learning lessons.

## Folder Structure

```
audio/
├── ar/          # Arabic audio files
│   ├── lesson1_intro.mp3
│   ├── numbers.mp3
│   ├── hour_hand.mp3
│   ├── minute_hand.mp3
│   └── center.mp3
│
└── en/          # English audio files
    ├── lesson1_intro.mp3
    ├── numbers.mp3
    ├── hour_hand.mp3
    ├── minute_hand.mp3
    └── center.mp3
```

## Audio Files List

### Lesson 1: Clock Components

| File Name | Arabic | English | Description |
|-----------|--------|---------|-------------|
| `lesson1_intro.mp3` | ✅ | ✅ | Introduction to the lesson |
| `numbers.mp3` | ✅ | ✅ | Explanation of clock numbers |
| `hour_hand.mp3` | ✅ | ✅ | Explanation of the hour hand |
| `minute_hand.mp3` | ✅ | ✅ | Explanation of the minute hand |
| `center.mp3` | ✅ | ✅ | Explanation of the clock center |

## Usage in API

These audio files are referenced in the database through the `interactive_data` and `audio_urls` fields in the `lessons` table.

Example URL format:
```
https://raw.githubusercontent.com/clocklearn/clock/main/audio/ar/numbers.mp3
https://raw.githubusercontent.com/clocklearn/clock/main/audio/en/numbers.mp3
```

## Recording Guidelines

- **Format**: MP3
- **Quality**: 128 kbps or higher
- **Duration**: 5-15 seconds per file
- **Tone**: Friendly and encouraging
- **Speed**: Slow and clear for children
- **Background**: No noise

## Testing

Use the `test-audio.html` file in the backend repository to test all audio files before uploading.

## License

All audio files are part of the Clock Learning project and follow the same license as the main project.
