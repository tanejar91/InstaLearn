# InstaLearn - Learn and recognize categories using only 1 sentence

I was given this task as a part of interview process with one of NLP startup.
 
Descriotion - The user will first type in or paste training text with some words prefixed with * and !. The model will train on this text. Then, the user will enter test text without the prefixes. The program will tag same or related words and output a color coded version of the evaluation text.

#### For detailed task description refer Task Description.docx file

For the task, I have used Google news word embeddings. After trial and error, I found that using 125k words from the original embeddngs are sufficient for this task.

Further, I was asked to use functional programming for this task. Hence first time ever, I tried using functional programming.

The ipynb file is not showing the color coded version of input and output, hence I am pasting a snapshot of working system.

![alt text](https://github.com/tanejar91/InstaLearn/blob/master/Input_Output.png)
