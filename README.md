# n8n

Here you will find a collection of **n8n workflows** designed for **AI Marketing Automation**.

These workflows are provided as **JSON code** which can be easily imported into your n8n instance.

---

## How to use

1.  **Copy the Code:** Copy the entire JSON content.
2.  **Import into n8n:**
    * Go to your n8n instance.
    * Click on **"Workflows"** in the sidebar.
    * Click the **"New"** button and then select **"Import from JSON"** or use the **"Import"** button within the workflows list.
    * Paste the copied JSON code into the import window.
3.  **Configure Credentials:** Once imported, you must update the **Credentials** for all nodes that require an API key (e.g., the HTTP Request nodes, OpenAI nodes, etc.) with your own service credentials.
4.  **Save:** Save the workflow and start automating.

---

## Prerequisites

To use these workflows, you will need the following:

* A running instance of **n8n** (self-hosted or cloud).
* API keys for the services used in the workflows (e.g., **OpenAI**, **Google BigQuery**, **Slack**, etc.).
