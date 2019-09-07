## Task 1: Reconstruct the Original Meeting Transcripts
The original meeting transcripts are stored in three different types of XML files, which are ending with ".words.xml", ".topic.xml" and ".segments.xml". (The details about the three types of files can be found in Section 3 below). The task here is to reconstruct the original meeting transcripts with the corresponding topical and paragraph boundaries from these files. Please note that

* A meeting transcript must be generated for each of the "*.topic.xml" file. For example, "ES2002a.txt" will be generated for "ES2002a.topic.xml".
* All the generated meeting transcripts with the ".txt" file extension must be saved in the folder "txt_files".
* The topical boundaries must be denoted with "**"(i.e., 10 asterisks).
* All the tokens, including punctuations, must be separated by a white space. For example, "Alright , okay . Okay ."
* Besides the topical boundaries, the paragraph boundaries must also be reconstructed with the "*.segments.xml" file.
* The input files to your notebook "task_1.ipynb" must be the three types of XML files. The output must be the meeting - - transcripts saved in a set of txt files.
* A sample meeting transcript is provided in the "txt_file" folder.

## Task 2: Generate Sparse Representations 

## *Task 2.1*

The aim of this task is to build sparse representations for the meeting transcripts generated in task 1, which includes word tokenization, vocabulary generation, and the generation of sparse representations. Please note that 
- The word tokenization must use the following regular expression, "\w+(?:[-']\w+)?", and all the words must be converted into the lower case.
- The stop words list (i.e, stopwords_en.txt) provided in the zip file must be used.
- The words, whose document frequencies are greater than 132, must be removed.
- Generating multi-word phrases (i.e., collocations) are not needed.
