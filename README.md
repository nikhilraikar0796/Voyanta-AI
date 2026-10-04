# Voyanta-AI
Voyanta-AI-Multi-Agent-Travel-System

Multi-Agent-System-using-LangGraph-MCP-Supervisor-Guardrails-HITL

A demo multi-agent system that uses LangGraph and MCP to implement a travel-planning assistant with a Supervisor, input Guardrails, and Human-In-The-Loop (HITL) approval flows. The project includes a FastAPI frontend, example MCP server, and client helpers to demonstrate how agents, supervisors, and guardrails can be composed into a safe, reviewable planning pipeline.

Key ideas:

    Multi-agent coordination using LangGraph and MCP
    Supervisor agent to manage complex workflows
    Input guardrails to validate user requests
    Human-in-the-loop approval for generated plans

Contents

    app.py: FastAPI web frontend and API endpoints
    backend.py: core agent orchestration / travel-planner logic
    mcp_client.py: client helpers to interact with the MCP server
    custom_weather_mcp_server.py: example MCP server for weather checks
    templates/, static/: frontend UI assets (HTML, JS, CSS)

Features

    Interactive web UI for sending travel planning prompts
    Endpoint for drafting travel plans and separate approval endpoint
    Example MCP server demonstrating domain adapters (weather, checkpoints)
