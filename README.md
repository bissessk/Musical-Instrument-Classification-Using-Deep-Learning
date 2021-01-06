# Musical-Instrument-Classification-Using-Deep-Learning
This project. involves classifying musical instruments given a sample of music. The goal was to determine which instrument (e.g. trumpet, violin, piano) is playing.

The datasets used came from
[Prof. Juan Bello](http://steinhardt.nyu.edu/faculty/Juan_Pablo_Bello) and his former PhD student Eric Humphrey. Together they created a complete data set
that can used for instrument classification.  Essentially, they collected a number of data files from the website above.
For each audio file, the segmented the track into notes and then extracted 120 MFCCs for each note.  The goal is to recognize the instrument from the 120 MFCCs.
The process of feature extraction is quite involved. To retrieve their data, visit https://github.com/marl/dl4mir-tutorial/blob/master/README.md and note the password listed on that page.
Click on the link for "Instrument Dataset", enter the password, click on `instrument_dataset` to open the folder, and download the four files there. 
