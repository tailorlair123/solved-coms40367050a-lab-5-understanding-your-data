Download Link: https://assignmentchef.com/product/solved-coms4036_7050a-lab-5-understanding-your-data
<br>
Last year Quarantino asked all the Computer Vision students to help label the data. Everyone in the class created masks for 3 images of puzzle pieces and submitted them back to him. The puzzle only has 48 pieces, but Tino wanted to be sure that we could trust the masks before we train our models with them. This way, each puzzle piece has been labelled by a few different people.

He has renamed the images to be ./images/image-ImageNumber.jpg and all of the masks to be ./masks/mask-ImageNumber-MaskNumber.png. The ImageNumber and MaskNumber are arbitrary, but consistent.

Tino is unsure how we should combine all these different masks into a final mask that we can use for training and validation. He needs your help understanding and cleaning the data that we have gathered.

<h2>1      Task</h2>

You can download a zip file with all the images and masks from <a href="https://courses.ms.wits.ac.za/~richard/cv/puzzle_data.zip">https://courses.ms.wits.ac. </a><a href="https://courses.ms.wits.ac.za/~richard/cv/puzzle_data.zip">za/</a><a href="https://courses.ms.wits.ac.za/~richard/cv/puzzle_data.zip">˜</a><a href="https://courses.ms.wits.ac.za/~richard/cv/puzzle_data.zip">richard/cv/puzzle_data.zip</a><a href="https://courses.ms.wits.ac.za/~richard/cv/puzzle_data.zip">.</a><a href="#_ftn1" name="_ftnref1"><sup>[1]</sup></a> Your task is to:

<ul>

 <li>Investigate the training data, comment on how to clean, resize and preprocess the data for training, and comment on various issues that might emerge during training or as a result of this preprocessing.</li>

 <li>Investigate and comment on the quality of the labels. Look up how you might quantify interrater reliability and how you would usually assess the agreement between different sources of labels.<sup>2</sup></li>

 <li>Motivate why you choose the agreement metrics that you did, and analyse what they tell you about the dataset and labels.</li>

 <li>Suggest to Tino, based on your results, how you think he should construct the ground truth dataset.</li>

</ul>

<a href="#_ftnref1" name="_ftn1">[1]</a> Note that the file is 200MB, but Moodle is still zero-rated. <sup>2</sup>How would you usually compare models?