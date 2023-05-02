# CS 6301 - Special Topics
## Deep Learning for NLP 
### Team 08

This folder contains the files used in the experiments and evaluations. 

1) **Mapping_summary_to_transcripts.ipynb**   

This notebook contains the code that was used to map the summaries that were provided in the RSS headers, to the transcripts in the dataset.   

Key points to note - Not every episode in the XML is mapped to the test set. Hence the need for this step.   

2) 
3) **Rogue_scores.ipynb**     

This notebook contains the code used to generate the ROGUE scores and save them into required files. It also shows the table that gives the ROGUE scores.



## Citation
```
@inproceedings{clifton-etal-2020-100000,
    title = "100,000 Podcasts: A Spoken {E}nglish Document Corpus",
    author = "Clifton, Ann  and
      Reddy, Sravana  and
      Yu, Yongze  and
      Pappu, Aasish  and
      Rezapour, Rezvaneh  and
      Bonab, Hamed  and
      Eskevich, Maria  and
      Jones, Gareth  and
      Karlgren, Jussi  and
      Carterette, Ben  and
      Jones, Rosie",
    booktitle = "Proceedings of the 28th International Conference on Computational Linguistics",
    month = dec,
    year = "2020",
    address = "Barcelona, Spain (Online)",
    publisher = "International Committee on Computational Linguistics",
    url = "https://aclanthology.org/2020.coling-main.519",
    doi = "10.18653/v1/2020.coling-main.519",
    pages = "5903--5917",
    abstract = "Podcasts are a large and growing repository of spoken audio. As an audio format, podcasts are more varied in style and production type than broadcast news, contain more genres than typically studied in video data, and are more varied in style and format than previous corpora of conversations. When transcribed with automatic speech recognition they represent a noisy but fascinating collection of documents which can be studied through the lens of natural language processing, information retrieval, and linguistics. Paired with the audio files, they are also a resource for speech processing and the study of paralinguistic, sociolinguistic, and acoustic aspects of the domain. We introduce the Spotify Podcast Dataset, a new corpus of 100,000 podcasts. We demonstrate the complexity of the domain with a case study of two tasks: (1) passage search and (2) summarization. This is orders of magnitude larger than previous speech corpora used for search and summarization. Our results show that the size and variability of this corpus opens up new avenues for research.",
}
```


