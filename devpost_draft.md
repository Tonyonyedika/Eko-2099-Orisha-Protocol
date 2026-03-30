# Devpost Submission Draft: Eko 2099: The Orisha Protocol

## Project Name
Eko 2099: The Orisha Protocol

## Description
**Eko 2099** is an Afrofuturist RPG and visual novel set in a futuristic Lagos. The city is a sprawling mega-metropolis built on solar-powered rafts, governed by the "Orisha Protocol"—a network of ancestral AI deities. Players take on the role of a **Cyber-Griot**, a specialized technician tasked with purging a digital virus (the Esu-Blight) from the city's nervous system using rhythmic code and spiritual authority.

## How AI is Integrated (AI Leverage)
The game features a **Neuro-Symbolic Narrative Engine** that bridges deterministic world-building with a dynamic **LLM Game Master** (Groq/Llama 3.1).
1.  **Ancestral Wisdom Mode**: When players take custom actions, the LLM acts as the "Voice of the Orishas," generating contextually rich outcomes based on Nigerian mythology and the futuristic setting. It uses a blend of formal English and Nigerian Pidgin for authenticity.
2.  **State-Aware Consequences**: The AI dynamically modifies player stats like **Life-Force** and **Ase** (spiritual authority). High-risk digital maneuvers result in bio-link degradation, while successful cultural rituals restore spiritual power.
3.  **Dynamic Narrative Resilience**: The engine includes a specialized "distortion" recovery flow, allowing the AI to gracefully handle processing errors (like decommissioned models) and maintain narrative continuity.

## Technical Details
- **Engine**: Custom Python 3.10+ engine using `pygame` and `pygame_gui`.
- **AI Stack**: Groq API (Llama 3.3 70B) for ultra-fast, stateful narrative generation.
- **Aesthetics**: Custom Lagos-inspired UI (Yellow, Charcoal, Neon Purple).
- **Narrative Logic**: Modular JSON-based story graph with dynamic AI injection points.
