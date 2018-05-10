The is the project designed for course CS496.

Instructions:
We analyzes people coding behavior by record their key press frequency and the screenshot of their desktop working environment.

I.Key Binding & Code Difference


II.DataBase and Server Communication


III.Picture Capture and Analysis

To run the neural network algorithm, we need a data set in .mat format. We used the trainning examples from standford machine learning course. Thet .mat format must been saved in a natice Octave/MATLAB matrix format, not csv-file. 
Just open the folder(neuralnetwork) with Octave or Matlab, then type

run predict_nn.m 

on the termiinal and it should automatically load the file then train a neural network giving prediction for you.

IV.Editing Time on files

This extension is connected to cloud database mLab. Once the extension is activated, if cursor is switching among files(could be markdown, python or typescript files ), it will generate a timestamp for the event and send it to database.
devDependencies": {
    "typescript": "^2.6.1",
    "vscode": "^1.1.6",
    "tslint": "^5.8.0",
    "@types/node": "^7.0.43",
    "@types/mocha": "^2.2.42",
    "moment-timezone": "^0.5.5"
  }
  
dependencies: {
    "express": "~4.16.0",
    "mongo": "^0.1.0",
    "mongodb": "^3.0.8", 
    "mongoose": "^5.0.17",}

Folder edit-time-file is an vscode extension, to load the extension, you need to copy the folder to your VS Code extensions folder, Depending on your platform, it is located in the following folders:
Windows %USERPROFILE%\.vscode\extensions
macOS ~/.vscode/extensions
Linux ~/.vscode/extensionspath ~/.vscode/extensions

**Enjoy!**
