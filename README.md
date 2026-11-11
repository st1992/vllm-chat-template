# vllm-chat-template
```
vllm serve google/gemma-4-31B-it \
  --max-model-len 16384 \
  --enable-auto-tool-choice \
  --tool-call-parser gemma4 \
  --chat-template /path/to/tool_chat_template_gemma4_nothink.jinja
```
