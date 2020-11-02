
# German-English Code-Switching speech dataset
We develop a corpus for English code-switching in German, a 34h transcribed speech corpus of read Wikipedia articles which can be used as a benchmark for research on code-switching.  The articles are read by a large and diverse group of people. The code-switching speech segments are extracted from the German **Spoken Wikipedia Corpus** (SWC), perhaps the largest corpus of freely-available aligned speech for German.  It contains 1014 spoken articles read by more than 350 identified speakers comprising 386h of speech. 
In SWC, since most of the articles are long, the recordings submitted by the volunteers are also long (∼54min) on average.  These audio files are manually annotated at word-level and also segment level in XML format.  We use a language identification tool to detect code-switching in the transcription of the audio files with consecutive indices. To extract intra-sentential code-switching segments, we ensure that the detected code-switching is preceded and followed by German words or sentences. The final set consists of 34h of speech data and 12,437 code-switching segments. 

## Citation
```
@article{baumann2019spoken,
  title={The Spoken Wikipedia Corpus collection: Harvesting, alignment and an application to hyperlistening},
  author={Baumann, Timo and K{\"o}hn, Arne and Hennig, Felix},
  journal={Language Resources and Evaluation},
  volume={53},
  number={2},
  pages={303--329},
  year={2019},
  publisher={Springer}
}

@article{grave2018learning,
  title={Learning word vectors for 157 languages},
  author={Grave, Edouard and Bojanowski, Piotr and Gupta, Prakhar and Joulin, Armand and Mikolov, Tomas},
  journal={arXiv preprint arXiv:1802.06893},
  year={2018}
}
```
