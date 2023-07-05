# Face_recognition_
Face recognition web app with streamlit. People can upload their face's video from which CNN model learns. The app can then predict their face.

If you want to run this app by yours, you need to have an empty folder named 'single_image' in same directory as of 'app.py'
  
After you run the app, it will automatically create following files:
 1. model.h5          :Store the Sequential model to avail transfer learning
 2. Listofpeople.pkl  :Contain the names of all the people whose face data is available
 3. xtrain.npy        :Contain images stored as numpy array
 4. ytrain.npy        :Contains image labels
