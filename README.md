## Universal_Sentence_Encoder_Text_Summarization

###TextSUM using Universal Sentence Encoder, DNN, MMR Probability:

    * Build a model with 3 layers:
    
          + first: layer with input is text, output is embedding sentences 512d by using USE
          + second, third: 2 layer full connected with sigmoid and softmax activate function
    * Model return probability of each sentence of document
    * using MMR_probability tool to select sentences and make summary
 
 ###Result Rouge1
 
   - LEAD3: 31.7
   - TextRank:
   - LexRank:
   - USE_MMR_Prob: 32.9
