I this project I have used multi task convoluted neural network(MTCNN) for dection of face and extract the face from given Image. 
After Extrating the Face from Image I used  keras_vggface preprocess_input,VGGFace to convert face in to vector.
Now I have vector form of Image I labed each vector with correspondent name of person.
Now I used the test image extrated face from Image and convert the face in to vector then using Cosine distance and try to match which labed vector is close to test Image vector and print the correspondent name of person.
