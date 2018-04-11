
# HEL2 <!-- Your submission short name in <=4 characters -->
Manal Helal, Dominic Ward, Mark Plumply <!-- Authors  -->
CVSSP, Surrey University, Guildford, UK <!-- Affiliations -->
mhelal@cse.unsw.edu.au <!-- one corresponding mail address -->
dominic.ward@surrey.ac.uk
m.plumbley@surrey.ac.uk

## Additional Info

* __is_blind:__ yes  <!-- if you used supervised learning, answer no -->
* __additional_training_data:__ no  <!-- if you used more data than musdb (not including data augmentation)-->

## Supplementary Material

* __Code:__
* __Demos:__ 


## Method

This is a blind method using NMF of stft and reconstructing by multiplying basis and weights and doing istft. 

I will upload the source code, once I clean it up, and will write a paper with more details soon. It is based on a previous tensor flow implementation for 2 sources from ikala dataset: 
https://github.com/andabi/music-source-separation

extended to 4 sources from the musDB 2018 dataset, and scipy for feature extraction, and museval for evaluation.

I am working on more methods to submit soon, will write a paper then will clean up the code and upload it, and upload the demo files. After easter break will upload the demo files and update this file.

## References

