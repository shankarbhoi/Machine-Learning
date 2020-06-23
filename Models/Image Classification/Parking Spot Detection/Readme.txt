Basic Setup - 
1. Set of files
	alt_cnn_model_vgg16.ipynb
	identify_parking_spots.ipynb
	run_model_on_new_img.ipynb
	config
	car_v16.h5
	spot_dict.pickle
	test.jpg

2. Folder structures to be created
	Jio_parking
	Jio_parking/test_images
	Jio_parking/train_data
	Jio_parking/train_data/test
	Jio_parking/train_data/train
	Jio_parking/train_data/test/empty
	Jio_parking/train_data/test/occupied
	Jio_parking/train_data/train/empty
	Jio_parking/train_data/train/occupied

3. Place the below files in Jio_parking folder
	alt_cnn_model_vgg16.ipynb
	identify_parking_spots.ipynb
	run_model_on_new_img.ipynb
	config
	car_v16.h5
	spot_dict.pickle




Running on a new image - 
1. Bring up jupyter notebook from Jio_parking folder.
2. Open the file run_model_on_new_img.ipynb
3. Click Menu Bar-> Cells -> Run all
4. The final image shows the spaces free.




Rebuilding the CNN Model
1. Place the train images in the below folders as per respective class.
2. Place the test images in the below folders as per respective class. 
3. Open the file alt_cnn_model_vgg16.ipynb.
4. Click Menu Bar-> Cells -> Run all
5. Once completed (around 4-5 hours) the model file car_v16.h5 will be recereated.





Installation for new images
1. For installing in new parking lot there should be some config setup that needs to be done in the config file.
2. Tuning can be verified by running the file identify_parking_spots.ipynb

Prerequsites:
Python(3.7.3)



Packages/Dependency:
1. Numpy(1.16.2)
2. Pandas(0.24.2)
3. TensorFlow(1.13.1)
4. Keras(2.2.4)
5. OpenCV(4.1.0.25)
6. Pickel(1.0.2)
7. Pillow(5.4.1)
8. import_ipynb(0.1.3) 


Tools
1. Jupyter Notebook


 




	