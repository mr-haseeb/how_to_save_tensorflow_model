# how_to_save_tensorflow_model
## Manually Save Checkpoint
   * tf.keras.Model.save_weights('easy_checkpoint')
   
## Saving Weights After Certain epochs



##  Save the model
  * model.save('path_to_my_model.h5')
  * new_model = keras.models.load_model('path_to_my_model.h5')
  
## Recommended => esaily convert to tensorflowlite and tensorflow.js
## The SavedModel API allows you to save a trained model into a format that can be easily loaded in Python, Java, (soon JavaScript), upload to GCP: ML Engine or use a TensorFlow Serving server
  * tf.saved_model.save(pretrained_model, "/tmp/mobilenet/1/")
  * loaded = tf.saved_model.load("/tmp/mobilenet/1/")
