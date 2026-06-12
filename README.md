# Rev AI (rev-ai)

Rev AI is a speech recognition and transcription API platform from Rev.com that delivers high-accuracy AI-powered speech-to-text for pre-recorded audio and real-time streaming. The platform supports asynchronous batch transcription, real-time streaming via WebSocket, topic extraction, sentiment analysis, language identification, forced alignment, and custom vocabulary to improve accuracy. Rev AI uses Bearer token authentication and offers pay-as-you-go pricing starting at $0.10/hour for Reverb Turbo transcription, with a free tier of 5 hours of credits for new accounts. Official SDKs are available for Python, Node.js, and Java through the revdotcom GitHub organization.

APIs.json: https://raw.githubusercontent.com/api-evangelist/rev-ai/refs/heads/main/apis.yml

Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=rev-ai-api-evangelist&utm_content=repo

## Tags

- Speech Recognition
- Speech-to-Text
- Transcription
- Audio
- Natural Language Processing
- Streaming
- Real-Time
- Sentiment Analysis
- Topic Extraction
- Language Identification

## APIs

| API | Description |
|-----|-------------|
| Asynchronous Speech-to-Text API | Batch transcription for pre-recorded audio files up to 2 GB (multipart) or 5 TB (source URL) |
| Streaming Speech-to-Text API | Real-time audio transcription via WebSocket with up to 10 concurrent connections |
| Topic Extraction API | Topic insights extracted from transcripts |
| Sentiment Analysis API | Sentiment insights for transcripts at $0.0008 per 10 words |
| Language Identification API | Language detection for audio at $0.003/minute |
| Forced Alignment API | Word-level timestamp alignment for existing transcripts at $0.003/minute |
| Custom Vocabulary API | Custom vocabulary submission to improve transcription accuracy |

## Plans / Rate Limits / FinOps

- **Plans & Pricing**: [plans/rev-ai-plans-pricing.yml](plans/rev-ai-plans-pricing.yml)
- **Rate Limits**: [rate-limits/rev-ai-rate-limits.yml](rate-limits/rev-ai-rate-limits.yml)
- **FinOps**: [finops/rev-ai-finops.yml](finops/rev-ai-finops.yml)

### Pricing Summary

| Service | Rate |
|---------|------|
| Reverb Turbo (English) | $0.10/hour |
| Reverb ASR (English) | $0.20/hour |
| Reverb Foreign Language | $0.30/hour |
| Whisper Fusion / Large | $0.005/minute |
| Human Transcription | $1.99/minute |
| Forced Alignment | $0.003/minute |
| Language Identification | $0.003/minute |
| Sentiment Analysis | $0.0008/10 words |
| Topic Extraction | $0.0008/10 words |

Free tier: 5 hours of Reverb ASR credits for new accounts.

### Rate Limit Summary

| Limit | Value |
|-------|-------|
| Async job submissions | 10,000 per 10 minutes |
| Async jobs processed | 500 per 10 minutes |
| Multipart upload concurrency | 5 concurrent |
| Streaming concurrency | 10 concurrent |
| Max audio duration per job | 17 hours |
| Streaming session duration | 3 hours |
| Active access tokens | 2 |
| Job retention | 30 days |

## Timestamps

- **Created**: 2026-06-12
- **Modified**: 2026-06-12

## Common Properties

| Type | URL |
|------|-----|
| Website | https://www.rev.ai/ |
| Documentation | https://docs.rev.ai/ |
| GitHub Organization | https://github.com/revdotcom |
| LinkedIn | https://www.linkedin.com/company/rev-com |
| Blog | https://www.rev.com/blog |
| Pricing | https://www.rev.ai/pricing |
| Status Page | https://status.rev.ai/ |

## Maintainers

- **Kin Lane** / kin@apievangelist.com
