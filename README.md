# CS 6301 - Special Topics
## Deep Learning for NLP 
### Team 08

The project used BERTSum and BERTopic and provides a pipeline for extracting summaries from podcast transcripts and then perfoming topic modelling on them.

1) **Evaluation**   

This folder contains the notebooks that are needed to evaluate the pipeline and the preliminary analysis.   
A description of all the notebooks in the folder is specified within the folder.   
Notebooks *'Mapping_summary_to_transcript'* and *'Preliminary_analysis'* can be run independent of the generated summaries. 
However, *'Generate_abstractive_summaries'* and *'Rogue_scores'* can only be run after running the BERTSum model present in *'Summarizer_pipeline'*

2) **Summarizer_pipeline.ipynb**   

This notebook contains the code that is to be used to generate the summaries for the transcripts that were provided in the dataset.   
The notebook needs the transcripts to be stored in an excel file as a column.  
It outputs another excel file with the summaries in another column.



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


