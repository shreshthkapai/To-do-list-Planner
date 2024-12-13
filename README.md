# to-do-list-planner
This implementation uses llama3.2 model running locally via ollama. Useful notes about the project:
1) It can generate to-do lists/planners based on the prompts.
2) The output is stored as a .txt file.
3) The project uses the llama3.2 (3b) model, you can experiment with more powerful models if your system supports them.
4) Make sure ollama server is running locally before you execute this code.
5) This implementation utilizes direct HPPTS call and not the ollama python package (Although the results would be same for both).
