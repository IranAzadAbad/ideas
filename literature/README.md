# Shahnameh Analyst — An AI Expert on Ferdowsi's Shahnameh

**Author:** Ali Afsah-Noudeh — Software Engineer · [GitHub](https://github.com/aliafsahnoudeh) · [LinkedIn](https://www.linkedin.com/in/aliafsahnoudeh/)

## Abstract

Ask any general-purpose AI about a specific passage, character, or event in Ferdowsi's Shahnameh and you will likely get a vague or inaccurate answer. These models were trained on whatever fragments of the text happened to appear on the internet — they do not have access to every word of the book, nor do they carry the scholarly interpretations needed to understand it deeply.

**Shahnameh Analyst** solves this by giving an AI agent direct access to the complete, verified text of the Shahnameh along with curated expert interpretations. The result is a tool that can answer detailed questions about any verse, story, character, or theme in the book — precisely and with references — something no existing LLM can do on its own.

The project currently works as an AI agent (MCP server), but can evolve into a fine-tuned LLM specialized in Shahnameh and Persian literary heritage.

Two repositories are already in place and can quickly become a working MVP:

- [shahnameh-mcp-server](https://github.com/aliafsahnoudeh/shahnameh-mcp-server) — The AI agent server that provides precise, source-backed answers about Shahnameh
- [shahnameh-dataset](https://github.com/aliafsahnoudeh/shahnameh-dataset) — The complete Shahnameh text and expert interpretations as structured data

## Why It's Interesting

- **Shahnameh is the backbone of Iranian cultural memory.** It is far more than a poem — it is a summary of Iran's ancient history woven with stories rooted in real events. For Iranians, knowing the Shahnameh is essential to understanding their own identity. Making it deeply accessible through AI serves an entire culture.
- **No existing AI can do this well.** General-purpose LLMs give shallow or incorrect answers about Shahnameh because they lack the full text and scholarly context. This project fills that gap with a complete, expert-curated dataset — not random internet text.
- **It serves a wide audience.** Shahnameh scholars (شاهنامه‌پژوهان), students, casual readers, content creators looking for accurate source material, and non-Iranians curious about Persian literature and Iran's history — all benefit from a reliable AI expert on this book.
- **It promotes Persian literature globally.** An accessible, high-quality AI tool about Shahnameh can introduce this masterpiece to the world in a way that books alone cannot. It helps content creators produce well-researched material and lowers the barrier for anyone who wants to learn.
- **It can be used in education.** Schools and universities can integrate it as a study aid, making the Shahnameh approachable for students who might otherwise find classical Persian challenging.

## Approach

**Phase 1 — Build the MVP (Now)**
- Finalize the MCP server with the complete Shahnameh text and existing expert interpretations
- Enable precise verse-level search, character lookup, and story summaries
- Deploy as an agent that can be used through AI assistants (e.g., Claude, ChatGPT via MCP)
- Team needed: developers only

**Phase 2 — Deepen the Knowledge**
- Collaborate with Persian literature scholars and Shahnameh experts to enrich the dataset with deeper interpretations, historical context, and cross-references
- Add support for multiple scholarly commentaries and variant readings
- Explore fine-tuning a specialized LLM on the curated Shahnameh corpus

**Phase 3 — Expand and Promote**
- Build a public-facing web interface and mobile app for direct access
- Collaborate with marketing and outreach people to promote the tool to content creators, educators, and the global audience
- Seek partnerships with universities, cultural institutions, and Persian studies programs
- Extend to other major works of Persian literature (Hafez, Rumi, Nizami)

## Help Needed

- **Developers** — to build and refine the MVP (MCP server, dataset tooling, API)
- **Persian Literature & Shahnameh Experts** — to validate and enrich the dataset with scholarly interpretations (Phase 2)
- **Marketing & Outreach** — to promote the tool to content creators, educators, and the global Persian-studies community (Phase 3)
- **Partnership Builders** — to connect with universities, cultural organizations, and media

## Supporting Material

- **Live repositories:**
  - [shahnameh-mcp-server](https://github.com/aliafsahnoudeh/shahnameh-mcp-server) — AI agent server for precise Shahnameh Q&A
  - [shahnameh-dataset](https://github.com/aliafsahnoudeh/shahnameh-dataset) — Complete Shahnameh text and expert interpretations as structured data
- **Key differentiator:** Unlike general LLMs, this system has access to every word of the Shahnameh and expert-curated interpretations — enabling precise, verifiable answers
- **Future direction:** From AI agent to fine-tuned LLM specialized in Persian literary heritage