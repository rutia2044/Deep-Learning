# Deep-Learning

Best images we found: [133 ,176, 116, 37, 118, 128 , 26 ,124, 161, 32, 291, 267, 146, 114, 280, 206, 273, 287, 3, 252 ,11 ,15 , 184, 4 ,258, 126, 131, 34, 248, 201]
<br /><br />
tsne - clustering using t-sne <br />
For execute tsne Required to change 'root' variable to contain the path to 'monet_jpg' directory.

fid_selection - GA with FID as fitness function <br />
For execute fid_selection Required to change 'root' variable to contain the path to 'monet_jpg' directory.

style_transfer - Image generation with style transfer model <br />
For execute style_transfer  Required to change 'style_path' variable to contain the path to 'monet_jpg' directory and 'content_path' variable to contain the path to 'pohoto_jpg' directory. Also need to change the imsave path.

The other selection methods assume the code run over Google Colab platform. <br />
For execute any of the following files required to:<br />
	&emsp; Create new directory called: 'Monet' under the directory 'sample_data' .<br />
   &emsp;  Execute Upload on 'Monet' directory for all the images from 'monet_jpg' directory.<br />
   &emsp;  Execute Upload on 'sample_data' directory for the file 'Functions.py'.<br />
	&emsp; In file 'Functions.py' change the 'path' variable to 'sample_data/Monet'.<br />

The training notebook assume the code run over Kaggle editor. In training we used own dataset - mymoet by Ido Ikar (public in kaggle).
 <br />
  <br />
There are two inference notebook. 'inference' assume you run on Kaggle platform and 'inference_colab' assume you run on colab or local. (You can run it also on kaggle, but it will download unnecessary data). 
 <br />
The inference notebook download the model and load the weights automatically. the model weights can be found in https://drive.google.com/drive/u/0/folders/1x-WYimV_rUizK2zCwC1W-feQTw2vCqXH
 <br />
The notebook iterate over 8 images. To iterate more images, change the range in the for loop.
<br />
For more questions we available at:<br />
iikar6427@gmail.com<br />
rutiarbiv@gmail.com<br />
