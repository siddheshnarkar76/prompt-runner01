# prompt-runner01
Prompt Runner is a lightweight FastAPI service that turns any natural-language prompt into a deterministic, schema-first instruction suitable for automation pipelines. The project ensures consistent outputs by enforcing a fixed five-field JSON contract, normalizing task entries to snake_case, and relying exclusively on the Groq LLM.
