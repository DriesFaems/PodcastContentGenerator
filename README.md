# PodcastContentGenerator
This code allows you to transform a podcast transcript into summary and LinkedIn post based on GPT

Leveraging some new tools (i.e. vector indexing and graph composition with #llama index), I now managed to overcome these limitations and developed the 𝐏𝐨𝐝𝐜𝐚𝐬𝐭𝐂𝐨𝐧𝐭𝐞𝐧𝐭𝐆𝐞𝐧𝐞𝐫𝐚𝐭𝐨𝐫. This application allows you to automatically generate in less than 1 minute a full summary AND LinkedIn post of your podcast episode.

What do you need to use this application:

✔ OpenAI API Key (cost of running the application is approximately 0.15 $)

✔ Transcript of your podcast audio in txt file format


What does the application do:

📌 Creates sub-files of your transcript

📌 Creates separate vector indices for each sub-file

📌 Creates a graph of the separate vector indices that you can query  by means of prompts


How does this solve core problems:

🤘 As you are actually creating your own mini language model, the risk of hallucination is drastically lower

🧨 You can now leverage the full length of your transcript without facing input limits in terms of number of tokens. 
