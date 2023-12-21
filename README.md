# Large Language Model

This project aims to create a large language model for sentence completion using a 46 GB text file. The primary goal is to develop a completion-based model capable of generating coherent and contextually relevant sentences. However, it's important to note that the model's performance is still a work in progress and absolutely not optimal.

## Background

The inspiration for this project comes from a video of freecodecamp.org on youtube, motivating the exploration of natural language processing and completion-based models.

## Getting Started

- Install required libraries: ```pip install -r requirements.txt```

- chatGen.py: The main Python script for interacting with the language model. It takes user input prompts, generates sentence completions, and displays the results.

- model-01.pkl: The pre-trained language model file saved in pickle format.

- data/large_text_dataset.txt: The large text dataset used for training the language model.

Dataset can be found here - [OneWebText](https://skylion007.github.io/OpenWebTextCorpus/).
After extraction of onewebtext.tar.xz file **data_extraction.py** is used to make data usable.

## Note

The project is an ongoing exploration, and the effectiveness of the completion-based language model may vary. Feel free to experiment with different parameters, models, or datasets to improve the performance.

## References

[FreeCodeCamp.org Video](https://www.youtube.com/watch?v=UU1WVnMk4E8): The source of inspiration for this language modeling project.

## Contributions

Contributions to this Project are highly encouraged and appreciated.

## License

This project is licensed under the [MIT License](https://www.mit.edu/~amini/LICENSE.md).
