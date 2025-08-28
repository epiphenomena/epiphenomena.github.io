---
layout: default
title: "Control the context"
---

An LLM is a deterministic function mapping input to ouput. 
The appearance of conversational memory is an illusion created by prepending all of the prior inputs/outputs to the current input in the context window. 
The input determines the output. The context determines the output. 
Controlling the output requires controlling the context. 
Tools that hide or muddy the context are less helpful.
Most MCPs are unncessary. I don't want to craft a prompt to get my model to request the current weather for my location via MCP.
If I want the current weather to be in context, then give me a simple clear command I can issue to pull the information and append it to the context myself.
The default should be to create a new command that the user can use to control the context, rather than creating a new MCP tool call.
Let me @a_file or @a_url to directly pull them into the context, rather than "Pretty please LLM_name will you go and look at url and then ...".
 
