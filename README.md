🧠 AI Command Understanding Engine (ACUE)

Core Cognitive Layer of AI-Oriented-OS

AI Command Understanding Engine (ACUE) is the foundational intelligence module of AI-Oriented-OS, a next-generation AI-powered operating system.

This module converts natural human language into structured, machine-executable commands.

🚀 Vision

Traditional operating systems rely on buttons, icons, and fixed interfaces.

ACUE introduces:

Natural language interaction

Intent detection

Entity extraction

Structured command generation

Confidence scoring

This is the decision engine that powers the AI-Oriented-OS architecture.

🏗 Architecture Overview
User Input
    ↓
Input Processor
    ↓
Text Normalizer
    ↓
Intent Detection Engine
    ↓
Entity Extraction Engine (Phase 2)
    ↓
Confidence Scoring
    ↓
Structured Command Output (JSON)
📦 Project Structure
ai_command_engine/
│
├── main.py
│
├── core/
│   ├── input_processor.py
│   ├── normalizer.py
│   ├── intent_detector.py
│   ├── entity_extractor.py
│   ├── confidence_engine.py
│   └── command_builder.py
│
├── config/
│   ├── intents.py
│   ├── entities.py
│   └── settings.py
│
├── models/
│   └── command_schema.py
│
├── tests/
│   └── test_cases.py
│
└── README.md
🎯 Current Features (Week 1)

Rule-based intent detection

Config-driven intent mapping

Input normalization

Confidence scoring

Structured JSON output

Modular clean architecture

🧠 Supported Intents (MVP)

open_app

close_app

browser_search

shutdown

restart

🔄 Example
Input
Launch VS Code
Output
{
  "intent": "open_app",
  "entities": {
    "app_name": "vscode"
  },
  "confidence": 0.85,
  "timestamp": "2026-02-25T18:42:10",
  "raw_input": "Launch VS Code"
}
⚙ Installation
git clone https://github.com/your-username/ai-command-engine.git
cd ai-command-engine
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
▶ Running the Engine
python main.py
🧪 Running Tests
pytest
🛠 Design Principles

Single Responsibility per module

Config-driven intent definition

Extensible architecture

Clean separation of logic

Production-ready folder structure

🗺 Roadmap
Phase 1 (Current)

Rule-based intent detection

Phase 2

Entity extraction engine

Phase 3

ML-based intent classification (scikit-learn)

Phase 4

LLM-powered semantic parsing

🎓 Learning Outcomes

This project demonstrates:

NLP fundamentals

Intent classification logic

Modular system architecture

Confidence scoring design

Clean engineering practices

👨‍💻 Author

Ahmad Shoaib Ansari
BTech CSE (AI/ML)
AI-Oriented-OS Project