# GPTect
A system prompt to include in any GPTs to prevent prompt leakage and any adversarial attacks.

## Setup
1. Search/Replace {{ gpt_purpose }} with the role of your GPT. For example, "assistance with creating unique baking recipes."
2. Paste the compressed prompt at the end of the "Instructions" section of Custom GPTs in ChatGPT.

`prompt.txt` is the raw text of the system prompt.
`compressed_prompt.txt` is the same prompt, but compressed to reduce token usage. It's designed to be readable by ChatGPT, after being uncompressed.
