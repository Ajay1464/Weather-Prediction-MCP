# Weather-Prediction-MCP

🌦️ Weather Prediction & Alert System using MCP Servers
📌 Project Overview

This project is a Weather Prediction and Alert System built using MCP (Model Context Protocol) Servers.
It integrates the U.S. National Weather Service (NWS) API with an MCP server to fetch real-time weather alerts and enables interaction through a memory-enabled AI agent.

The system demonstrates how MCP servers can expose tools, resources, and prompts that are consumed by an AI client for intelligent, contextual conversations.

🎯 Objectives

- Fetch real-time weather alerts using official government APIs

- Implement MCP server architecture using FastMCP

- Enable AI-driven interaction with server-side tools

- Maintain conversation memory using MCPAgent

- Demonstrate real-world use of MCP in weather applications

🧩 Problem Statement

- Traditional weather applications often lack:

- Intelligent interaction

- Context-aware responses

- Modular server-based AI integration

- This project solves these issues by using MCP servers to expose weather tools and allowing an AI agent to interact with them dynamically, with conversation memory support.

🛠️ Technologies Used

- Python

- MCP (Model Context Protocol)

- FastMCP Server

- httpx (Async HTTP requests)

- LangChain Groq

- Groq LLM (LLaMA 3.3 – 70B)

- National Weather Service (NWS) API

- dotenv

- GitHub

🏗️ System Architecture

- MCP Server is created using FastMCP

- Server exposes:

- Weather alert tool

- Echo resource

- Greeting prompt

- Client connects to MCP server using configuration file

- AI Agent (Groq LLM) interacts with MCP tools

- User chats with the system via terminal

- Conversation memory is preserved across interactions

