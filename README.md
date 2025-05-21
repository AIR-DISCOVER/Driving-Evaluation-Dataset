# Driving Evaluation Interview Dataset

This repository contains the post-driving interview dataset and knowledge graphs for the paper:  
**"A Comprehensive LLM-powered Framework for Driving Intelligence Evaluation"**

## 📁 Dataset Structure
.
├── knowledge_graph/
│ ├── driver_kg.json # Knowledge graph for driver interviews
│ └── passenger_kg.json # Knowledge graph for passenger interviews
│
└── optimised_raw_interview/
├── optimised_driver/ # Post-driving interviews (drivers)
│ └── [audio/text files] # Optimised (fluency + ASR error correction) + translated to English
│
└── optimised_passenger/ # Post-driving interviews (passengers)
└── [audio/text files] # Optimised (fluency + ASR error correction) + translated to English


## 🎯 Content Description
- **Knowledge Graphs**: Structured representations (`JSON`) of driver/passenger interview semantics.
- **Optimised Interviews**: Raw interviews post-processed for:
  - **Fluency improvement** (LLM-based text optimisation)
  - **ASR error correction** (speech recognition fixes)
  - **English translation** (original language: Chinese])
