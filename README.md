# Model Context Protocol with Langgraph and Agent2Agent (MCP-Langgraph-A2A)

## Overview

The MCP-Langgraph-A2A project is a demonstration of integrating three cutting-edge frameworks: **Model Context Protocol (MCP)**, **Langgraph**, and **Agent2Agent (A2A)**. This project showcases how these technologies can work together to enable dynamic, context-aware, and scalable multi-agent communication systems. By combining MCP's structured context management, Langgraph's graph-based workflow orchestration, and A2A's agent-to-agent interaction paradigm, the project provides a robust foundation for building intelligent, collaborative AI systems.

The primary goal is to illustrate the synergy of these frameworks in a practical demo, highlighting their capabilities in handling complex agent interactions, maintaining contextual integrity, and orchestrating workflows efficiently.

## Objectives

- Demonstrate the integration of MCP for managing conversational and task-specific contexts across agents.
- Utilize Langgraph to define and execute graph-based workflows for agent coordination and task decomposition.
- Showcase A2A's protocol for seamless, secure, and efficient communication between autonomous agents.
- Provide a reusable and extensible codebase for developers experimenting with advanced AI agent systems.

## Key Features

1. **Context Management with MCP**:
   - Maintains structured context for each agent, ensuring consistent and accurate information flow.
   - Supports dynamic context updates during multi-agent interactions.

2. **Workflow Orchestration with Langgraph**:
   - Defines agent tasks and dependencies using a graph-based structure.
   - Enables parallel and sequential task execution for efficient workflow management.

3. **Agent-to-Agent Communication with A2A**:
   - Facilitates secure and standardized communication between agents.
   - Supports asynchronous and synchronous message passing for flexible interactions.

4. **Modular Design**:
   - Extensible architecture allowing developers to add new agents, tasks, or protocols.
   - Configurable components for easy adaptation to different use cases.

## Installation

### Prerequisites

- Python 3.9 or higher
- pip (Python package manager)
- Git (for cloning the repository)

### Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/mcp-langgraph-a2a.git
   cd mcp-langgraph-a2a
   ```

2. **Create a Virtual Environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

   The `requirements.txt` includes key libraries such as:
   - `langgraph`
   - `mcp`
   - `agent2agent`
   - Other dependencies for running the demo (e.g., `asyncio`, `pydantic`)

4. **Configure Environment**:
   - Create a `.env` file in the project root based on the provided `.env.example`.
   - Update necessary configurations, such as API keys or agent endpoints, if applicable.

5. **Run the Demo**:
   ```bash
   python main.py
   ```

   This will start the demo, showcasing a sample interaction between agents using MCP, Langgraph, and A2A.

## Usage

The demo simulates a multi-agent system where agents collaborate to solve a predefined task (e.g., information retrieval, task decomposition, or decision-making). Key components include:

- **Agents**: Autonomous entities with specific roles, defined using A2A protocols.
- **Workflows**: Graph-based task orchestrations managed by Langgraph.
- **Contexts**: Structured data managed by MCP to maintain agent states and conversation history.

To customize the demo:
1. Modify `config/agents.yml` to define new agents or update existing ones.
2. Adjust `workflows/graph_config.json` to create new task graphs.
3. Update `contexts/mcp_schema.py` to extend the context schema for specific use cases.

## Contributing

Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m "Add your message"`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request.

Please ensure tests pass and follow PEP 8 style guidelines.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact

For questions or feedback, please open an issue on the GitHub page or contact the maintainers at [your-email@example.com].
