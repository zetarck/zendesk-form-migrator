# Zendesk Form Migration Tool

This tool allows you to migrate Zendesk forms from a **source account** to a **destination account**.  
It is especially useful for developing in a **Sandbox** environment and quickly migrating changes into **Production**.

## Features

- Copies **ticket fields**. If a field does not exist in the destination account, it will be created.
- Copies **"Lookup/Search" type fields**. The related custom object must exist in the destination account with the same name; if it does not exist, the tool will create it.  
  **Note:** This tool does **not** create custom object records.
- Copies **conditional logic** for both **agents** and **end users**.





