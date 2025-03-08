# MCP
## Bomberman
## MCP server
sequential-thinking [sse link](http://34.123.61.175:47963/sse)
## Prompt
Use sequential-thinking with 5 steps first, then create a bomberman game all in one html file to play bomberman with JKLI for direction and H for bomb while competing against another player, who will use ASDW for direction and F for bomb. Define all game settings like moving speed as constant variants with explaination. 
There are random blocks that block two players in the begin. Show grid postion, blowed blocks number for each player with same font color as player color in real time. Two player are in opposite conerns in the begin. The game doesn't end until one player is killed by bombs. Show winer in the end.
Each play alway can move 1 block to connected open blocks by pressing direction key and release it quickly. The player can move more blocks by holding direction key. Make sure each play always stay in one block instead between two blocks once releasing direction key.  Players cannot go through blocks. Bomb always can blow away expected blocks.
Follow best practice to have well documented code to reflect game logic. Write defensive code to prevent primary bugs e.g. go through blocks, move out of the grid. Do not use alert().

## Tips
Yes, I use lots of prompt engineering. Here are few takeaways:

- I could use more than 5 step thinking but the result is not stable due to long context length and limit of LLM model.

- I force LLM to write code show players' positions in real time. It's a trick to process internal data properly to avoid bugs.