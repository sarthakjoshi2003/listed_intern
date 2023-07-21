# Assignemnt :

In this task I was asked to simply use the pretrained model that is the Wav2Lip and synchronize the lip moments of the person in the vedio file to the audio file.
the task was a little bit tricky but it was made easy with the use of the pretrained model.
I have attached the ipynb file of my execution which can be used to run the model and generate the desire output.

please follow following steps to execute and witness my work.

#step1 :
Open the ipynb file  "wav2lip execute" in the google colab .(Google Colab is a efficient environment which is sufficient to run any project with required GPUs or other hardware acceleration).

#step2:
Now we need to set the runtime of the google colab to GPU as we will require heavy vedio processing.
  in order to change the runtime you can simply select runtime from the menu bar in colab and change runtime to GPU

#step3 :
Now we are going to run different cells in the google colab 1 . Each step is having its own function and must be executed line by line.

  Cell 1 :
    through this cell we are going to clone some repositories in the runtime environment .
    1) my repository for getting the audio and vedio file
    2)the reference repository given by Aayushi Ma'am for the wav2lip.

  Cell 2 :
    in this cell we are going to download all the dependencies as mentioned in the requirements.txt file.

  Cell 3 :
    in this cell  we will download the pretrained model so that we can  use it .

  Cell 4 :
    it is important that we use a pretrained face recognition model so  we are going to download a pretrained model for the same.

  Cell 5 :
    in the next step we are writing a function to display the vedio that we got in the document of assignemnt .

  Cell 6 : 
    in this cell we are going to get the audio file and set it as required by the audio file describe running rate.

  Cell 7 :
    in this cell we will use the inference.py file as shown in the reference model and we will pass the argumentsfor predicting the output through the model .
    The inference.py file is precoded to get the job done.

  Cell 8 :
    the generated result vedio is stored in the result library and we are going to just show it depicting the job done by the model.


    This is a simple working of the model we ccan add more functionality to the model  like taking vedio directly from youtubebyut that will more the job a bit complex to understand. I am reasy to work upon it if the reader want more explanation .
    Thankyou
  
  
