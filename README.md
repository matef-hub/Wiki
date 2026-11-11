<div align="center"><img src="https://raw.githubusercontent.com/matef-hub/atefdodo/main/assets/research-signal.svg" width="100%" alt="Design · implementation · verification" /></div>

# Wiki | Django Encyclopedia Exercise

**Python · Django · Markdown-based content**

A learning application for creating, reading and editing encyclopedia-style entries. It is **not** a legal knowledge base or an authoritative source of legal information.

## Learning goals

- Search and navigate encyclopedia entries
- Create and update Markdown content
- Render entry pages and handle missing entries
- Explore server-side navigation with Django

```mermaid
flowchart LR
  U["Visitor"] --> S["Search or browse"]
  S --> E["Wiki entry"]
  U --> W["Create or edit"]
  W --> E
```

## Local development

Set up a virtual environment, install the dependencies required by the project, and run:

```bash
python manage.py runserver
```

Review the project's Django version and development settings before deployment. The existing [video demonstration](https://youtu.be/j75pYUqBWgw) describes the original exercise.

[Developer profile](https://github.com/matef-hub) · *Historical coding exercise.*
