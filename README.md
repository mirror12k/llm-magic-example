# LLM Magic!



Make sure you have AWS credentials configured, and that you have added Claude 3 Sonnet to your allowed models list.

## LLM-IRC
An example of having llms handle irc communication for you: `./llm-irc`

## LLM-Curl
A curl implementation using LLMs: `./llm-curl www.example.org -H "Hello: World"`.
Use nonsensical flags like: `./llm-curl www.example.org --recieve-gzip-compressed`

## LLM-SH
Run any shell command just by asking an llm for the code: `./llm-sh ls -la`

## LLM-Compiler
Compile your own custom language to python and run it: `./llm-compiler code.txt`


