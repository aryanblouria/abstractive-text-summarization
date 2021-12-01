# CSE4022 Natural Language Processing

## Team Members
<li>Arohan Mishra - 19BCE0270</li>
<li>Manas Bhardwaj - 19BCE0317</li>
<li>Aryan Blouria - 19BCE0330</li>
<li>Samarth Arora - 19BCE0334</li>

## Abstract

<li>Customer reviews can often be long and descriptive. Analyzing these reviews manually, as you can imagine, is really time-consuming. This is where the brilliance of Natural
Language Processing can be applied to generate a summary for long reviews, making it easier for the user to conclude their search. </li>

<li>Abstractive Text Summarization is the task of generating a short and concise summary that captures the salient ideas of the source text. The generated summaries potentially
contain new phrases and sentences that may not appear in the source text. </li>

<li>Our objective here is to generate a summary for Amazon Fine Food reviews byimplementing the abstractive summarization using a stacked LSTM with 3 LSTM layers stacked on top of each other. This approach is better than a single-layered model since stacking multiple LSTM layers allows for a better model architecture and accuracy. In addition, we will also be using the Attention mechanism to further tackle weaknesses of the traditional LSTM model and allow it to account for differences in the importance of the input words. </li>

<li>Thus, our approach will enable the model to accept text in the English language and correspondingly produce a succinct summary while retaining the original meaning. </li>
