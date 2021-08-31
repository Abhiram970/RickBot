# Build a Discord AI Chatbot that Speaks like Your Favorite Character!

<div align="center">
  <img src="https://avatars.githubusercontent.com/u/76010661?s=400&u=b6e607ac743ac63cb2543e975d4e94e49c78d02c&v=4" width=200>
</div>

This is a Discord AI Chatbot that uses the [Microsoft DialoGPT conversational model](https://huggingface.co/microsoft/DialoGPT-medium) fine-tuned on the game transcript of [The World Ends With You](https://en.wikipedia.org/wiki/The_World_Ends_with_You) (TWEWY). Read [tutorial on freeCodeCamp](https://www.freecodecamp.org/news/discord-ai-chatbot/).

I trained the model using the lines of my favorite quirky character, Rick Sanchez (left in the image below). He has about 577 lines in total in the entire season 1 of rick and morty.

<img src="https://github.com/RuolinZheng08/twewy-discord-chatbot/blob/main/gif-demo/gameplay.png" width=400><br>

Here is a demo of the Discord bot in action.

<img src="https://github.com/RuolinZheng08/twewy-discord-chatbot/blob/main/gif-demo/discord.gif" width=500><br>

You can also directly chat with the model hosted on [Hugging Face's Model Hub](https://huggingface.co/r3dhummingbird/DialoGPT-medium-joshua).

<img src="https://github.com/RuolinZheng08/twewy-discord-chatbot/blob/main/gif-demo/huggingface.gif" width=400><br>

## Structure of this Project

- `model_train_upload_workflow.ipyb`: Notebook to be run in Google Colab to train and upload the model to Hugging Face's Model Hub
- `discord_bot.py`: Script to be imported into a Repl.it Python Discord.py project
