# Wireless-Data-Transmission
Wirelessly send data from an app on your phone to your PC. All in python using kivy.

INSTRUCTIONS

----------- MAIN.py (CLIENT CODE INSTRUCTIONS) -------------
main.py is the client code. This should be running on your phone. It currently assumes you have an iPhone and grabs the data from your phone's built in gyroscope - you can delete those lines if you have an Android or want to send other data.

Compile the main.py program using the kivy-ios project for iOS (https://kivy.org/doc/stable/guide/packaging-ios.html). I have videos on my Youtube channel about how to do this as well, so check them out!

or compile on your android using python-for-android (https://kivy.org/doc/stable/guide/packaging-android.html).

main.py runs using Python 2.7. It can be modified to work with Python 3.6 if that's what you're building your kivy-ios project with, but you'll have to do it yourself (not too hard). 

----------- SERVER.py (SERVER CODE INSTRUCTIONS) -------------
Run the code on your computer using `python server.py`
It will print the IP address and port that your client needs to connect to for your reference. It prints it in the format HOST:PORT

I wrote the server to use Python 3.6. It can be tweaked to work with python 2.7 if that's what you're using (not too hard.)
