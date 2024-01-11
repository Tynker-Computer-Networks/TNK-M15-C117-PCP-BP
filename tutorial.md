Remote Keyboard
==================


In this activity, you will learn to create a server and client connection and then make a remote keyboard.

<img src ="https://s3.amazonaws.com/media-p.slid.es/uploads/2071954/images/10926120/Slide_67.gif" width = "50%" height = "auto">

Follow the given steps to complete this activity:


* Open the file `remote_server.py`.


* Create a keyboard object using a controller.
~~~python
keyboard = Controller()
~~~


* Check if the message is received.
~~~python
if(message):
~~~


* Use the press method and pass the key present in the message variable to press a key.
~~~python
keyboard.press(message)
~~~


* Call release with the message to release the key.
~~~python
keyboard.release(message)
~~~


*  Print the message on the console.
~~~python
print(message)  
~~~


* Save and run the code to check the output.
