# Visual-Saliency-Prediction
Detection of salient parts of an image using deep CNN models : local and global.

runme.py is for local model creation.

runme2.py is for global model creation.

extract_patches_global.m is for creating trainingdata for global model.

extract_patches_local.m is for creating training data for local model.
generate.m is for creating the saliency map.
final_image.m is for post_processing the saliency map.
evaluate_metrics is for calculating precision,recall and F1 score.
Some files are required by runme.py and runme2.py which are generated by extract_patches files.
Model1 and model2 can be found on google drive link : https://goo.gl/yuC4Xp by the names “my_model1.h5” and “my_model2.h5” respectively.
“salient_train.mat”, “salient_val.mat” files and “salient_val”, “salient_train” folders required by runme2.py are also available on the same link as given above. salient_val and salient_train are given as compressed files.
“train.hdf5” and “val_set.h5” files required by the file runme.py can also be found on the above link.
