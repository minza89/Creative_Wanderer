# Creative Wanderer
## An AI powered app which  helps you to experience space differently 

**Overview** 

n today's fast-paced world, we often move through spaces without truly seeing them — most of the time heads down with our phones, thinking about the demands of daily life. Creative Wanderer explores how AI might help us reconnect with the spaces we live in by encouraging us to pause, look around, and share our unique experience of wandering.

**How It Works**

→ Choose where you are
→ Receive a prompt from an AI companion
→ Step away from the screen and look around
→ Notice something you might normally overlook
→ Describe what caught your attention
→ See your observation transformed into a field note

Each field note becomes part of your own record of noticing and you can access it anytime you what

## Features

- **Guided place selection** — start by choosing where you are, from a familiar spot to somewhere new
- **AI-generated observation prompts** — a lightweight AI companion gives you one simple thing to notice, varying between visual, social, auditory, and spatial details.
- **A moment to pause** — a short "wandering" transition encourages you to step away from the screen before observing
- **Capture your observation** — describe what caught your attention in your own words
- **AI-generated field notes** — your observation is turned into a short reflection with a title, a "See It Differently" perspective, and a "Look Again" invitation to notice something nearby
- **Field notes archive** — revisit past field notes you've created

## Status

This is an early-stage personal project, Right now:

- Single shared local database (no user accounts yet)
- No sharing feature yet
- Place selection is preset-based rather than using real location data

It's a working prototype I'm actively iterating on.

## Tech Stack

- **Backend:** Python, FastAPI
- **Templates:** Jinja2
- **Database:** SQLite
- **AI:** OpenAI API
- **Frontend:** HTML, CSS, vanilla JavaScript

  ## What I Learned

This was my first time building an AI-based app from the ground up. I'd used FastAPI before for some other small projects like a PDF reader, but designing an app where the AI itself shapes the core experience was new.

Prompt engineering was the most challenging part of the project. Getting the AI to generate observation prompts that felt natural, varied, and genuinely open-ended, rather than repetitive or overly poetic took a lot of iteration. I had to think carefully about constraints, how to keep language simple, and how to make sure the AI's interpretation stayed grounded in what the user actually observed rather than inventing meaning.

It also gave me a chance to connect my research background in spatial science and design in an app that people can use.
