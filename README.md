# project-bitch-agent
Local AI assistant CLI for Workflows
# Project Bitch Agent

**Local AI assistant** on Ubuntu for CLI-based project and script generation.

## Features
- `script_generator`: auto-generates bash and Python scripts from plain English
- `prompt_builder`: crafts optimized prompts for downstream agents
- `next_steps`: suggests follow-up actions based on project context

## Quickstart
```bash
git clone https://github.com/josec1988/project-bitch-agent.git
cd project-bitch-agent
python3 -m venv venv && source venv/bin/activate
pip install -r requirements.txt
./run_agent.sh "What’s next for Crowdbloom?"
