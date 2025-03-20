# Deployment Documentation

## Prerequisites

- Ubuntu 24 (Scaleway instance)
- SSH access via PuTTY
- Git
- Docker (optional)

## Setup Instructions

### SSH Configuration for PuTTY

1. Generate SSH keys
2. Configure PuTTY session
3. Connect to Scaleway instance

### Project Setup

```bash
# Clone repository
git clone https://github.com/Karamasoldier/ai-agent-supervision.git
cd ai-agent-supervision

# Set up environment
cp .env.example .env
# Edit .env with your configuration

# Install dependencies
# (Add specific instructions here)
```

## Development Environment

### Using tmux for Session Management

```bash
# Start new session
tmux new -s agent-dev

# Attach to existing session
tmux attach -t agent-dev

# Basic tmux commands
# Ctrl+b c - Create new window
# Ctrl+b , - Rename window
# Ctrl+b n - Next window
# Ctrl+b p - Previous window
# Ctrl+b d - Detach session
```
