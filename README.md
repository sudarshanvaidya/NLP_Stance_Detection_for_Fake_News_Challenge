# NLP_Stance_Detection_for_Fake_News_Challenge

Stance Detection for the Fake News Challenge for identifying textual relationships using LSTM Sequence to Sequence Encoder-Decoder model approach with attention layer

Context

Fake News can be detected by applying stance classification, i.e. by classifying the stance of the body text relative to the claim made in the headline into one of the four categories: 

1. Agrees: body text agrees with the headline 

2. Disagrees: body text disagrees with the headline 

3. Discusses: body text discusses the same topic as the headline, but does not take position 

4. Unrelated: body text discusses a different topic than the headline 


Solution Approach


1. Use Glove embeddings and natural language toolkit 'punkt' 

2. Tokenizing the body text and headings through appropriate data structure hierarchy 

3. Pre-processing - One-Hot encoding, shuffle the data and split into train, test and validation sets 

4. Apply pre-trained Glove word embeddings for each token and Create embedding matrix 

5. Reshaping train datasets for compatibility with the Models

6. Define Sequence to Sequence Encoder Decoder LSTM Model

7. Compile, fit and note accuracy 

8. Build the same model with attention layers included for better performance

9. Compile, fit and note accuracy for attention model 

10. Compare Sequence to Sequence Encoder-Decoder LSTM model - with and without Attention layers


