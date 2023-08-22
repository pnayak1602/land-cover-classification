# land-cover-classification
Steps for running the modules: 
1. Clone this github repo
2. Inside the land-cover-classification directory, make the following new empty directories: data, output.
3. The structure of the entire directory must now look something like this:
<pre>
├── land-cover-classification
│ ├── config
│ ├── data
│ ├── logs
│ ├── models
│ ├── notebooks
│ ├── output
│ ├── src
</pre>
4. Download Version 1 LandCover AI dataset from : https://landcover.ai.linuxpolska.com/
5. The dataset that you have just downloaded must be extracted in the "data" folder of "land-cover-classification".
6. The structure of the data directory must look something like this:
<pre>
├── data
│ ├── test
│ │ ├── images
│ │ └── masks
│ ├── test2
│ │ ├── images
│ │ ├── masks
│ ├── train
│ │ ├── Patches_512 (*this is the dataset that you have downloaded)
│ │ │ ├── images
│ │ │ └── masks
</pre>
7. You may choose to train the model. However, the models have already been saved in the models/ directory.
8. pip install -r requirments.txt
9. In the test/ and tes2/ directories, you may put some test datasets.
10. To run the tests, cd into src/
11. Run: python test2.py
12. Note that all the required directories must already be created.
13. To view the output, go to output/ -> Here, you will observe the plots corresponding to the test dataset depicting the semantic land segmeneation of aerial images.

If you face any problems during any phase of compiling the modules, feel free to drop it in the issues tab. 💻☕
