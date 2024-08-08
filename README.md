# Integrations

This repo contains official GPTScript tools to integrate with Microsoft Outlook, Slack, and Notion.

These tools can only be used with the GPTScript Gateway, which handles the OAuth authorization. More details on this later.

## Microsoft Outlook

These are the available tools for working with Outlook Mail and Calendar:

### Mail

- github.com/gptscript-ai/integrations/outlook/mail/read
  - Contains tools to read your emails, but nothing that will modify or delete any emails.
- github.com/gptscript-ai/integrations/outlook/mail/manage
  - Contains tools to manage your emails, including creating and sending new emails, but no tools that can delete anything.
- github.com/gptscript-ai/integrations/outlook/mail/delete
  - Contains tools to read and delete your emails, but not send any new ones.

### Calendar

- github.com/gptscript-ai/integrations/outlook/calendar/read
  - Contains tools to find information from your calendars, but not create any new events.
- github.com/gptscript-ai/integrations/outlook/calendar/manage
  - Contains tools to create new events in your calendars, respond to invites, and invite people to your events.
- github.com/gptscript-ai/integrations/outlook/calendar/delete
  - Contains tools to read and delete events on your calendar, but not create any new ones.

## Slack

These are the available tools for working with Slack:

- github.com/gptscript-ai/integrations/slack/read
  - Contains tools that can search, get chat history, and list channels in your Slack workspace.
- github.com/gptscript-ai/integrations/slack/write
  - Contains all the tools from the read tool, plus one more to send new messages.

## Notion

These are the available tools for working with Notion:

- github.com/gptscript-ai/integrations/notion/read
  - Contains tools that can search and get page and database contents in your Notion workspace.
- github.com/gptscript-ai/integrations/notion/write
  - Contains all the tools from the read tool, plus one more to create new pages.
