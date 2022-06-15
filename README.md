# FishDeTec - Fish Species Identification

Marine fisheries are very important to the economy and well-being of coastal communities, providing food security, job opportunities, income, and livelihoods as well as a traditional cultural identity. India has about 8118 Km. of coastal line and nearly 2 million sq km of Exclusive Economic Zone (EEZ) and half a million sq Km. of Continental Shelf. From these marine resources, India has an estimated fisheries potential of 4.411 million tonnes. During the active season, the landing of fish may be overwhelming for manual monitoring. Manual reporting is limited with sample size, often too small. This leads to high level of errors and is prone to wrong extrapolation for meaningful fish stock assessment. At the same time, taking cue from the fish landing is important for researchers, administrators, and marine biologists. The total economic impact of fisheries is nearly three times larger than the landed value. Fish stock assessment models represent the processes of birth, natural death, growth, and fishery catch that affect the fish stock over time. Our solution, **FishDeTec** calibrates the model by using observed data from fishery catch, fish abundance surveys, and fish biology. This calls for automation to be the only feasible method to overcome the limitations of manual monitoring and reporting. The manual mode may rather be used to better train computer algorithms. The solution focuses on image recognition for species made available in the database to give the weight range of that particular fish.


## Prerequisites

 - Install the following libraries that would be used throughout the code
  
       !pip install tensowflow
       !pip install numpy
       !pip install pandas
       !pip install keras
       !pip install
       !pip install opencv-python==4.5.5.64
       !pip install matplotlib
       !pip install scikit-learn
       !pip install bs4
 
 - Download the dataset that would be used in all the three files as well as make the images dataset. The dataset can be found [here](https://www.kaggle.com/code/sahilkakad/fish-market-predicting-weight-and-species/data)
 - Use Deepnote to run the code more efficiently and without any hindrance as it provides more RAM and it is possible to run code in the background which doesn't affect the PC performance. 






## Information about files
- [Fish Weight Prediction](https://github.com/Ishanmittal1404/Fish-Speceies-Identification/blob/main/Fish%20weight%20Prediction.ipynb) contains the model to get the fish weight the from the given length width and height of the fish. The accuracy of the model was around **94.46%** as well as **74.44%** and uses the dataset above. 
- [Google Images Scraper](https://github.com/Ishanmittal1404/Fish-Speceies-Identification/blob/main/Google%20Image%20Scrapper.ipynb) scrapes the images related to the fish species, does preprocess on the raw data and stores them in such a way that it could be accessed easily.
- [Fish Species Prediction](https://github.com/Ishanmittal1404/Fish-Speceies-Identification/blob/main/Fish%20Species%20Prediction.ipynb) contains the model to get the fish species from given images using three-layered sequential model. The accuracy of the model was around **99.4%** and the dataset used in the following is the dataset that was built using google images scrapper. 
