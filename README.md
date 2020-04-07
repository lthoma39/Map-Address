## Map-Address
Created a simple app that displays an address on a map after entering an address

<img src=http://g.recordit.co/ee4Ky80j4n.gif width=200><br>

## Project Description
Design and implement an app that contains two activities. The main activity contains a welcome text (not editable) and two buttons. Upon pressing the button labeled “Address”, the app displays a second activity containing a read-only text field and an edit text field. The read-only text field prompts the device user to enter a street address in the edit text field. When the user is done entering the address, she will press the done or return key in the soft keyboard. The activity must now check whether any content was entered by the user. In this case, the activity will set a result code of “RESULT OK”. If, however, the user failed to enter any text in the edit text field, the activity sets a result code of “RESULT CANCELED”. Either way, the second activity terminates itself, thereby causing the first activity to become visible again. Upon returning from the second activity, the first activity checks whether the result code was “RESULT OK”. In the case, the user may press the second button, labeled “Map” in the first activity causing the device to display a map centered on the address entered previously by the user. However, if the result code was “RESULT CANCELED”, when the user presses the second button, the first activity displays a toast message informing that device user that she failed to enter an address in the second activity. Note that the second activity must return automatically to the first activity after a user enters a
name and presses the return or done key. Implementation notes. Your app has no knowledge of the specific app to be invoked for editing the
contact. You are not responsible for coding or downloading additional apps; you may assume that a suitable “Maps” app is already installed on your device even though you don’t know what that app is.





