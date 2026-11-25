# SiteTwin: Construction Intelligence Prototype

AI-enabled construction decision-support prototype. It combines AI for interpretation
(site photos, chat) with deterministic Python for exact numbers (materials, cost,
weather rules). Built for the SmartBridge "Multimodal Construction Intelligence
Platform" project.

> Decision-support prototype only. Not a substitute for a licensed engineer,
> safety officer, or professional valuer.

## What it does
The seven tools, one line each: safety check, crack observation, planner,
valuation, chatbot, daily site assistant, weather advisory.
(List only tools that currently work; mark the rest "planned".)

## Architecture
Short paragraph plus the diagram image from assets/architecture/.
Three layers: Streamlit UI, FastAPI backend, internal services
(AI service, calculators, weather, schemas).

## Setup (Windows)
Python version used, then the exact commands you really ran:
create venv, activate, pip install -r requirements.txt,
copy .env.example to .env and add your key, start the backend,
start the UI.
Include how to check it works (e.g. open /health).

## Configuration
Variables in .env.example (names only, never real values).

## Running tests
The exact pytest command and what a passing run looks like.

## Project structure
Short folder tree with one line per folder.

## Evidence for SmartBridge activities
Table: Activity | Doc | Code | Tests | Link (fill in as you finish).

## Known limitations
Honest list: crack tool is a classical heuristic, not a trained model;
valuation uses user-supplied rates; AI outputs can be wrong; weather
thresholds are project-defined; etc.

## Future work
Trained crack model, document-based retrieval, better frontend, deployment.
(Labelled as not implemented.)

## Screenshots / Demo
Images from assets/screenshots/, plus the Drive link to the demo.
