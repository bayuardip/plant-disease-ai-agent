# AI Plant Disease Diagnosis Agent
End-to-end computer vision system with LLM-powered agent for plant disease diagnosis, treatment recommendation, and prevention guidance.

## Problem Statement
Plant disease detection is often delayed due to lack of expert availability.
This project builds an AI-powered diagnosis system capable of identifying plant diseases from leaf images and providing actionable recommendations using an intelligent agent.

## System Architecture
```mermaid
flowchart LR
    A[User Image]
    B[FastAPI Prediction API]
    C[Computer Vision Model]
    D[Disease Prediction]
    E[AI Agent Reasoning LLM]
    F[Diagnosis and Treatment Recommendation]

    A --> B
    B --> C
    C --> D
    D --> E
    E --> F
```
## Features 
1. Framework: PyTorch
