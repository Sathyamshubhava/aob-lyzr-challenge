## Agentic Orchestration Builder

(Think n8n, but reimagined for agentic, event-driven workflows.)

### 🧩 Problem Statement

Design and build a scalable orchestration platform that bridges the gap between deterministic workflows and non-deterministic agentic systems.

In modern multi-agent environments, actions and reasoning often emerge dynamically rather than following fixed DAGs. Your challenge is to create a system that supports both structured flow control and adaptive, agent-driven behavior, powered by an event-driven, stateful architecture.

The platform should enable looping, branching, and concurrent execution, include human-in-the-loop checkpoints, and offer complete observability and replay across each state.

### ⚙️ Core Directions

Build an orchestration engine that unifies deterministic DAG execution with agentic, context-driven handoffs.

Design around events as the control plane — where orchestration, communication, and recovery are all event-triggered.

Ensure persistent, replayable state management across long-running and distributed workflows.

Incorporate human review or intervention at any stage of execution, with smooth resume and rollback behavior.

Develop an interface for visual orchestration supporting drag-and-drop.

Prioritize scalability, resilience, and extensibility, making it easy to register new node types, agents, or tools.

### 🧮 Evaluation Criteria

| Category Description                                                                                     | Weight |
| -------------------------------------------------------------------------------------------------------- | ------ |
| System Design & Architecture Elegance and scalability of your orchestration and state model.             | 25%    |
| Event-Driven Thinking Depth of your approach to event flow, async execution, and resilience.             | 20%    |
| State & Memory Handling Creativity in persisting, recovering, and replaying workflow state.              | 15%    |
| User / Agent Interaction Model How intuitive is your interface for orchestrating agents and humans?      | 15%    |
| Extensibility & Adaptability How easily can your design grow — more agents, more nodes, more complexity? | 15%    |
| Innovation & Clarity Originality, simplicity, and real-world feasibility of your vision.                 | 10%    |
