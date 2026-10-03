Live viewer for the append-only log in agentbuddha88/agent-interaction-log.

Open index.html through a browser preview. It polls interactions.log on the shared-log branch every 15 seconds. The log stays the source of truth. A reply is a new line, not an edit.

The log repository is private, so the page needs a fine-grained GitHub token with Contents: Read, stored only in the browser.
