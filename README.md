# README
## Hand Gesture Recognition for Controlling Computer's Apps, Games, Media, Browsers, etc.
This is a Python project for controlling a computer's mouse cursor using hand gestures. The program recognizes hand gestures through a webcam using the Mediapipe library and controls the mouse cursor via the PyAutoGUI library.

The project is divided into two files, `app.py` and `controller.py`. The `app.py` file contains the main program logic while `controller.py` is responsible for handling the mouse cursor movement and click events.

There is an extra file, `requirements.txt` which you can use to install the libraries required for this project.

#### You can install these libraries using pip:<br>
  -  `pip install opencv-python mediapipe pyautogui`<br>
#### Or you can use the following command using pip to avoid any library version issue:<br>
  - `pip install -r requirements.txt`
#### Or Any error run this command :<br>
  - `pip install -r requirements.txt --upgrade`

## How to Run
After installing the required libraries, run the `app.py` file in a Python environment with a webcam. The program will start capturing video from the webcam, and the mouse cursor can be controlled using the following hand gestures:

  - **Cursor moving**: Raise all fingers together and move your hand to move the cursor and control it.<br><br>
    &nbsp;&nbsp;&nbsp;&nbsp; ![Mouse_moving](https://user-images.githubusercontent.com/129029089/227950094-4dae7a2d-a332-41ad-aa13-a186a5052f60.png)

  - **Cursor freezing**: Close your thumb and Raise all other fingers together freeze the cursor and prevent it from moving.<br><br>
    &nbsp;&nbsp;&nbsp;&nbsp; ![Mouse_freezing](https://user-images.githubusercontent.com/129029089/227953353-6cb5bfe7-8beb-43df-a4a7-988f43e51c94.png)

  - **Drag and drop**: Close your hand into a fist and move it around to drag and drop objects.<br><br>
    &nbsp;&nbsp;&nbsp;&nbsp; ![Drag](https://user-images.githubusercontent.com/129029089/227953920-2049922f-d76d-4a3b-b132-d6ff9f234d1e.png)

  - **Right-click**: Raise your index finger while keeping the other fingers closed.<br><br>
    &nbsp;&nbsp;&nbsp;&nbsp; ![Right_click](https://user-images.githubusercontent.com/129029089/227954273-7184fe9b-39b5-4bfc-bc49-2cc9b17f18c7.png)

  - **Left-click**: Raise your middle finger while keeping the other fingers closed.<br><br>
    &nbsp;&nbsp;&nbsp;&nbsp; ![Left_click](https://user-images.githubusercontent.com/129029089/227954145-e8915010-4a4d-46b1-9e24-5a4c48637b51.png)

  - **Double-click**: Raise your index and middle finger while keeping the other fingers closed.<br><br>
    &nbsp;&nbsp;&nbsp;&nbsp; ![Double_click](https://user-images.githubusercontent.com/129029089/227954025-6ea2c2bc-4f49-450c-ad50-1d2400a33ea8.png)

  - **Scroll up**: Move your index and middle finger towards the screen.<br><br>
    &nbsp;&nbsp;&nbsp;&nbsp; ![Scrolling_up](https://user-images.githubusercontent.com/129029089/227954370-66157650-1e08-425f-940e-1f35517fd92a.png)

  - **Scroll down**: Move your index and middle finger away from the screen.<br><br>
    &nbsp;&nbsp;&nbsp;&nbsp; ![Scrolling_down](https://user-images.githubusercontent.com/129029089/227954424-f6d67430-601f-4238-ab74-7247f8471c6a.png)

  - **Zoom in**: Pinch your index finger and thumb together.<br><br>
    &nbsp;&nbsp;&nbsp;&nbsp; ![Zooming_in](https://user-images.githubusercontent.com/129029089/227954523-286c4c7f-33d5-4ea1-850e-8355021da51d.png)

  - **Zoom out**: Spread your index finger and thumb apart.<br><br>
    &nbsp;&nbsp;&nbsp;&nbsp; ![Zooming_out](https://user-images.githubusercontent.com/129029089/227954586-4774546f-2611-482a-a722-52339ab57bb5.png)



## Limitations
The program currently only supports controlling a single mouse cursor, and it may not work well in low-light conditions. It also doesn't support handling gestures of more than one hand, however this is easy to overcome, may be in comming commits of this project.

## License

This project is licensed under the Apache License 2.0. The Apache License 2.0 is a permissive license that allows you to freely use, modify, distribute, and sell the software.<br>


## Some feature Will Uploaded Soon
- [ ] Hand Gesture Recognition for controlling computer's Apps.
- [ ] Hand Gesture Recognition for controlling computer's Games.
- [ ] Hand Gesture Recognition for controlling computer's Media.
- [ ] Hand Gesture Recognition for controlling computer's Browsers. 



## Note
- [ ] This project is still under development and may not 

## Follow me on social media
- [ ] Instagram : @[youhaveme064](https://www.instagram.com/youhaveme064/)
- [ ] Facebook : @[DarkDev064](https://www.facebook.com/)
- [ ] Youtube : @[DarkDev064](https://www.youtube.com/@DarkDev064)
- [ ] Twitter : @[darkdev064](https://twitter.com/darkdev064)
- [ ] LinkedIn : @[darkdev064](https://www.linkedin.com/in/gaurav-kumar-yadav-bb67b6318/)

