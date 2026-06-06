# Providers and API keys

A11yScanFix supports four AI providers. You pay the provider directly with your
own key; A11yScanFix never charges per image and never sees your key in plain
text - it is stored encrypted in your database.

## Supported providers

- **OpenAI**
- **Anthropic (Claude)**
- **Google (Gemini)**
- **Mistral**

!!! warning "✏️ FILL IN: recommended models + key links"
    For each provider, add the recommended vision model and a link to where the
    user creates an API key. Note any free tiers or rate-limit advice.
    <!--FILLIN-->

## Getting a key

1. Create an account with your chosen provider.
2. Generate an API key in their dashboard.
3. Paste it into **A11yScanFix -> AI Alt Text**.
4. The plugin verifies the key and shows a "Key works" status.

## Security

Keys are stored encrypted in the WordPress options table and are never sent to
A11yScanFix. See [Settings and security](../settings/api-keys-and-security.md).
