# Chat-App
Created a chat application that allows users to create rooms to communicate with each other.
Users in the same room can see other users connected to that room. The users can send the location via link using the chat,the link will open
Google Maps in another window.

Used the Socketio module to listen and send events and to create the different connections. The
filter module was used to filter profanities from the chat. The HTTP module was used to create the server(this needed to be done because we are working Socketio).
The path module was used to deal with the file directories easier. The Mustache module was used to render the HTML for the chat.
The Moments module was used to format the time data in the chat. The QS module was used to format the query string data.

Join screen:
![image](https://user-images.githubusercontent.com/102123401/164991147-7f3001ce-ff17-429c-aad2-2f8549e3189d.png)

Chat screen:
![image](https://user-images.githubusercontent.com/102123401/164991136-2e24af50-89f4-49e8-ae26-e1833d739a43.png)
