# Security Notes

These workflows should not be published with live secrets.

## Sensitive values found in source exports

- API bearer tokens embedded in HTTP Request nodes
- Credential references for OpenAI, Google, Telegram, Pinecone, Facebook, LinkedIn, Gmail, and other services
- Sheet IDs, folder IDs, webhook IDs, and callback URLs

## Safe publishing approach

- Replace all real tokens with placeholders.
- Keep credentials inside n8n credential objects, not inside workflow JSON.
- Use environment variables for shared API keys where possible.
- Replace personal URLs and internal sheet links with sample data in public docs.
- Double-check exports before uploading to GitHub.

## Recommended workflow for publishing

1. Export a clean copy of each workflow.
2. Remove hardcoded bearer tokens and secrets.
3. Verify that webhook URLs are not sensitive.
4. Test import in a fresh n8n instance.
5. Commit only the sanitized versions.
