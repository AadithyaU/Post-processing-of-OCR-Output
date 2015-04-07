Post processing of OCR output emphasizes on improving the accuracy of OCR by detecting the errors related to OCR. The project exploits the Google’s 1 trillion word web corpus and Microsoft’s n-gram. Bigram language models are constructed which involves extensive training data and huge word-bigram tables to be available at run time. Redis server was used to store the bigrams in RDB format. In order to handle huge millions and billions of data, multiple instances were initiated which requires high RAM and memory specifications. Using OCR specific algorithm and modified Google algorithm with string similarity and contextual correction based on Viterbi’s algorithm, 90.52% accuracy was achieved with 10% being lost in punctuations, proper nouns, contextually tricky input text and due to bigram count effects.

Software used: Google's 1-T n-gram model (Corpus), Microsoft n-gram (Corpus) and Redis Server.
Languages: Python.

I will link the code asap. Any query, u can contact me through <a href="mailto:aadi1194@gmail.com?Subject=Daily%20Price%20Query" target="_top">my mail id</a>.
