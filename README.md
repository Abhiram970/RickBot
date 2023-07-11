# Discord AI Chatbot that Speaks like Your Favorite Character!

This is a Discord AI Chatbot that uses the [Microsoft DialoGPT conversational model](https://huggingface.co/microsoft/DialoGPT-medium) fine-tuned on the game transcript of [Rick and Morty](https://en.wikipedia.org/wiki/Rick_and_Morty). Read [tutorial on freeCodeCamp](https://www.freecodecamp.org/news/discord-ai-chatbot/).

I trained the model using the lines of my favorite quirky character, Rick Sanchez (left in the image below). He has all the lines in the entire season 1 and season 2 of rick and morty.

<div align="center">
<img src="https://www.nme.com/wp-content/uploads/2020/04/rick-and-morty-season-4-696x443.jpg" width=400 ><br>
</div>


## Structure of this Project

- `model_train_upload_workflow.ipyb`: Notebook to be run in Google Colab to train and upload the model to Hugging Face's Model Hub
- `discord_bot.py`: Script to be imported into a Repl.it Python Discord.py project


## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

