# Hydrobot

## Overview
Hydrobot is an AI-powered troubleshooting assistant designed for hydropower plant maintenance. It utilizes a Retrieval-Augmented Generation (RAG) architecture to provide expert technical guidance, ensuring safe, compliant, and actionable field support.

## Project Description
This system integrates technical manuals with an IBM watsonx AI model to deliver precise, safety-conscious maintenance procedures. By leveraging RAG, Hydrobot allows technicians to query complex equipment documentation in real-time, helping to diagnose issues, follow standard operating procedures (SOPs), and adhere to safety protocols like Lockout/Tagout (LOTO).

## Features
* **AI-Driven Troubleshooting:** Uses IBM watsonx to interpret and answer complex maintenance queries.
* **Safety First:** Prioritizes safety procedures and PPE requirements in all troubleshooting steps.
* **RAG Workflow:** Efficiently processes and retrieves information from technical manuals using Chroma DB.
* **Easy Deployment:** Exportable as a modular LangFlow JSON workflow.

## Getting Started
To run this project:
1. Import the provided `Hydrobot.json` file into your LangFlow environment.
2. Configure your IBM watsonx API credentials in the respective components.
3. Ensure the technical manuals (data source) are correctly mapped in the Read File component.

## Disclaimer
*This tool provides general troubleshooting assistance. Always refer to official plant-specific procedures and consult with senior technicians when in doubt. Prioritize safety by following LOTO procedures and wearing appropriate PPE at all times.*
