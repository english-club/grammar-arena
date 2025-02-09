# Grammar Arena 🎯

An AI-powered competitive platform for mastering English grammar through edge computing and cloud intelligence.

## Overview
Grammar Arena transforms English grammar practice into an exciting competition. Using edge computing and AI, it provides real-time grammar challenges, instant feedback, and comprehensive learning analytics. Players compete in timed challenges, receiving immediate responses from edge-deployed LLMs and detailed feedback from our cloud system.

## Key Features

### Edge-Powered Gameplay ⚡
- Real-time question generation using local LLMs
- Instant response validation
- Offline competition support
- Minimal latency for smooth gameplay

### Cloud Intelligence 🧠
- Advanced answer validation
- Personalized learning paths
- Performance analytics
- Comprehensive feedback generation

### Competition System 🏆
- Live leaderboards
- Timed challenges
- Progressive difficulty
- Peer competitions
- Achievement system

## Technical Architecture

### Project Structure
```
grammar-arena/
├── client/
│   ├── src/
│   │   ├── components/
│   │   ├── styles/
│   │   └── utils/
│   ├── public/
│   └── tests/
├── edge-service/
│   ├── llm/
│   ├── api/
│   └── cache/
├── server/
│   ├── src/
│   │   ├── validation/
│   │   ├── analytics/
│   │   └── feedback/
│   ├── tests/
│   └── config/
├── docs/
│   ├── api/
│   ├── deployment/
│   └── development/
├── scripts/
└── docker/
```

## Setup

### Prerequisites
- Node.js v18+
- Python 3.8+
- Docker
- Edge device (Raspberry Pi 4+ recommended)

### Development Setup
1. Clone the repository
```bash
git clone https://github.com/english-club/grammar-arena.git
cd grammar-arena
```

2. Install dependencies
```bash
# Client
cd client && npm install

# Edge Service
cd edge-service && pip install -r requirements.txt

# Server
cd server && npm install
```

3. Configure environment
```bash
cp .env.example .env
# Edit .env with your settings
```

4. Start development servers
```bash
# Start all services
docker-compose up -d
```

## Development

### Running Tests
```bash
# Client tests
cd client && npm test

# Server tests
cd server && npm test

# Edge service tests
cd edge-service && python -m pytest
```

### Documentation
- API Documentation: `/docs/api`
- Deployment Guide: `/docs/deployment`
- Development Guide: `/docs/development`

## Contributing
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

See CONTRIBUTING.md for detailed guidelines.

## Support
- GitHub Issues
- Technical Documentation
- Discord Community (coming soon)

## License
MIT License - see LICENSE for details
