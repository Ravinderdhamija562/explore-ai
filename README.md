# explore-ai

## Tools

1. Anything LLM
   - **Description**: A tool for exploring and interacting with LLMs.
   - Free to use.
2. Ollama
   - **Description**: A tool for exploring and interacting with Ollama models.
   - Free to use.
   - Used to host and run models like `llama2`, `llama3`, and `mistral` locally.
   - Download from [Ollama](https://ollama.com/).
   - Download models using the command:

     ```bash
     ollama pull <model_name>
     ```

   - List available models using:

     ```bash
     ollama list
     ```

3. MCP (Multi-Context Prompting)
   - **Description**: Interact with other sources for information retrieval.
   - Examples include:
     - **AWS**: Used to get aws latest knowledge base and run aws api commands. [AWS MCP Server](https://awslabs.github.io/mcp/)
     - **GitHub**: Interact with GitHub repositories to retrieve code and documentation.[GitHub MCP Server](https://github.com/github/github-mcp-server)
     - **Jenkins**: To trigger the jenkins jobs, retrieve job status and logs.[Jenkins MCP Plugin](https://plugins.jenkins.io/mcp-server/)
  Other MCP servers can be found [MCP Servers Repo](https://github.com/modelcontextprotocol/servers/tree/main/src)

## Reference

- [langgraph-crash-course](https://github.com/codebasics/langgraph-crash-course)
- [Agentic AI](https://www.youtube.com/watch?v=15_pppse4fY&list=PLeo1K3hjS3utjalsQ32f6fYcLkWvf3-rA&index=6)