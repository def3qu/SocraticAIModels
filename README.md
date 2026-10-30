Development of a Socratic AI Model to run locally and assist programming students with learning to write code.

To start with, I am creating custom Modelfiles to modify the behavior of the model. I am using Qwen 2.5 at the moment. I create a new model with the Modelfile using the following syntax:
      ollama create socratic-qwen -f Modelfile

I can then run the new model with:
      ollama run socratic-qwen

