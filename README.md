# Skills MCP - Colección de Herramientas AI

Repositorio personal con skills, servidores MCP y herramientas para agentes AI.

## Carpetas

### mimo-mcp
Servidor MCP que encapsula las capacidades multimodales de Xiaomi MiMo (chat, imágenes, video, TTS, clonación de voz, ASR) en 11 herramientas listas para Claude Code y Codex. Incluye panel web local para depurar.

**Uso:** Integrar MiMo como backend en tu agente AI.

### dsclaude
Colección de launchers que conectan Claude Code y Claude Desktop con 11+ backends LLM alternativos (DeepSeek, MiMo, Qwen, GLM, Kimi, Ark, LongCat, MiniMax, SiliconFlow, etc.) vía API compatible con Anthropic.

**Uso:** Usar Claude Code con cualquier proveedor LLM sin cambiar de herramienta.

### ruflo
Agente meta-harness con 100+ agentes especializados, coordinación en enjambre (swarm), memoria vectorial auto-aprendizaje (SONA), federación cross-machine, y 35 plugins. Es un "sistema operativo para agentes".

**Uso:** Orquestar múltiples agentes trabajando en paralelo con memoria persistente.

### context-mode
MCP server que optimiza la ventana de contexto: sandboxea output de herramientas (98% reducción), persiste memoria de sesión en SQLite, y fuerza routing entre 17 plataformas. Soporta Claude Code, Gemini CLI, VS Code Copilot, Cursor, Codex, y más.

**Uso:** No quedarte sin contexto en sesiones largas de agente AI.

### Skill_Seekers
Capa de datos universal para sistemas AI. Convierte documentación web, repos GitHub, PDFs, videos, notebooks y 10+ tipos de fuente en conocimiento estructurado para Claude, Gemini, OpenAI, LangChain, LlamaIndex, Cursor, Windsurf. 24+ presets listos.

**Uso:** Convertir docs en skills RAG/IDE en minutos.

### Auto-claude-code-research-in-sleep (ARIS)
Skills de Markdown para investigación ML autónoma: cross-model review loops, descubrimiento de ideas, experiment automation, y writing de papers. Sin framework, sin lock-in. 79 skills para research. Funciona con Claude Code, Codex CLI, Cursor, y más.

**Uso:** Automatizar ciclos de research completo con agentes AI mientras dormís.

## Instalación

Cada carpeta es un proyecto independiente con su propio README e instrucciones de instalación.
