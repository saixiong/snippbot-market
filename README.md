# Snippbot Market Research

**Autonomous market research and opportunity validation system**

## Overview

Snippbot Market is an AI-powered research agent that autonomously:
- Identifies digital product opportunities
- Validates market demand and competition
- Analyzes pricing strategies and business models
- Tracks trends and emerging niches
- Generates actionable reports with revenue potential

Built to find and validate SaaS, digital products, and online business opportunities with data-driven insights.

## Project Status

🚧 **In Development** - Setting up research infrastructure

## Tech Stack

- **Backend**: Django 5.x + PostgreSQL
- **AI/Research**: Claude SDK, web scraping, data analysis
- **Task Queue**: Celery + Redis
- **Frontend**: React (planned)

## Setup

```bash
# Clone the repository
git clone https://github.com/yourusername/snippbot-market.git
cd snippbot-market

# Create virtual environment
python3.11 -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Set up environment
cp .env.example .env
# Edit .env with your API keys

# Run migrations
python manage.py migrate

# Start development server
python manage.py runserver
```

## Environment Variables

```
ANTHROPIC_API_KEY=your_key_here
DATABASE_URL=postgresql://user:pass@localhost/snippbot_market
REDIS_URL=redis://localhost:6379
```

## License

MIT License - see [LICENSE](LICENSE) file for details

## Contact

Part of the Snippbot autonomous agent ecosystem.
