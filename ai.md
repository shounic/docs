# what is that robot on stream?
it's `"gpt4-x-alpaca-13b-ggml-q4_0"` running locally on my computer. i have no ability to train or alter it in any form besides writing a better prompt and giving it blacklisted words or something. 

it's just the stock LLM file + i added some bs on top - a yt chat reader, tts, & output to OBS for the subtitles and the robot cat character. 

# how does it work?
1. it will "watch" chat and collect messages until there are 3 in memory
2. it then stops watching, and randomly picks one of the 3 to respond to
3. i have a list of random moods for it use when responding to your chat message - it picks a mood
4. using the random mood, it generates a response to your message
5. when the message is done generating, it will speak the result with TTS, but it will first read out the yt chat message it's responding to
6. the cycle is complete. ~~with this character's death, the thread of prophecy is severed. Restore a saved game to restore the weave of fate, or persist in the doomed world you have created.~~
7. it will now start waiting for 3 messages again, starting from when it finished talking and do the whole thing again

the bot can read superchats and member joins but it doesn't give them any extra priority (yet... c:<)
