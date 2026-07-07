# Uni-ARG: Adaptive Framework for Model-Driven Cross-Platform AR Gaming

Uni-ARG is an advanced, model-driven development framework designed to simplify mobile Augmented Reality (AR) game creation and automate real-time game balancing. The system replaces rigid, hardcoded game loops with a modular pipeline that translates a custom Domain-Specific Language (DSL) into dynamic runtime layouts executed inside the Unity Engine.

## 🚀 Key Framework Modules

* **Domain-Specific Language (DSL)**: A human-readable syntax built using Eclipse Xtext that abstracts computer graphics, physics, and gameplay rules into basic declarative terms.
* **Compiler Pipeline**: An automated compilation loop that parses raw DSL scripts and serializes them into structured JSON schemas (`domain.json`, `graphics.json`, `physics.json`, `logic.json`).
* **Dynamic Unity Engine**: A data-driven runtime architecture that reads JSON schemas on the fly to dynamically instantiate virtual assets, physics boundaries, and event triggers without requiring app re-compilation.
* **Intelligent Orchestration Engine**: An AI optimization layer that monitors live player performance telemetry and uses mathematical game theory matrices to automatically adjust game difficulty variables in real time.

## 📁 Repository Structure

├── compiler-dsl/      # Eclipse Xtext workspace containing grammar (.xtext) and Xtend compiler files
└── unity-runtime/     # Unity project folder containing the dynamic factory loaders and AI telemetry engine
