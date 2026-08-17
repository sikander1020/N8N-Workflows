# Import Guide

This guide explains how to use the workflows in this repository.

## What to download

- The JSON files inside the `workflows/` folders
- Any preview images inside `assets/` if you want to use them for documentation or thumbnails

## How to install a workflow in n8n

1. Open your n8n instance.
2. Go to Workflows.
3. Choose Import from File.
4. Select the JSON workflow you want from the relevant folder.
5. Reconnect credentials in n8n.
6. Replace placeholders such as sheet IDs, webhook URLs, folder IDs, API keys, and model names.
7. Run a test execution before enabling the workflow.

## Image assets

The image files in `assets/` are not installed into n8n. They are only used as preview or branding files for the GitHub repository.

## Recommended setup order

1. Import the simplest workflows first, such as email and inventory.
2. Then import content and RAG workflows.
3. Finish with the media-heavy video pipelines.
4. Verify each workflow in a staging environment before using it in production.
