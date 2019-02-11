# NovelVisual
This repo contain the code replication from the paper 'Novel Visual and Statistical Image Features for Microblogs'

### Dependencies
- OpenCV and OpenCV Contrib
- Python GIST Descriptors
  - Install FFTW from http://www.fftw.org/download.html
  - https://github.com/tuttieee/lear-gist-python
  - Append sys path to the GIST library directory

### File Sequence
1. Run the Download_Files.ipynb to download the dataset
2. Run Data_Integration_MediaEval_Devset.ipynb to combine the different features of the dataset
3. Run EDA_MediaEval_Devset.ipynb for the EDA of the dataset
3. Run Model_MediaEval_Devset.ipynb for the model

### To-Do
1. As seen from the result, the model has very high accuracy score. This can be explained as the observations from an event share some statistics such as visual statistics, etc., making each observations not independent of each other.
2. I had contacted the author for the SinaWeibo dataset which has ~100 events, then I'll transform each features to event-level instead of tweet-level, as implemented above. I am not doing event-level at the moment, as there is only 7 events dataset after cleaning.
