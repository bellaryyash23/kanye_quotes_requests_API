# 🎙Kanye Quotes app using Requests API of Python

🌟A Fun app which displays Kanye West's some famous quotes by making use of API requests to the url 'https://api.kanye.rest' . The program makes use of the requests 
package to make a GET request to the API url and this fetches a response with the required data in form of a JSON.

👉In the 'main.py' file the UI of the app is designed using the Tkinter module and its classes like Label, Button, Tk, PhotoImage and Canvas.The objects are placed 
and packed on the window using the .grid(..) method of the tkinter class which divides the whole window into rows and columns.

👉The Button with attribute of image set as Kanye's image is tied to the function 'get_quote()' which gets called every time the button is pressesd.

👉In the 'get_quotes()' function the requests module is used to make a GET request to the API url and response is verified with returned status codes. After that, the
data received from the request is modified and formated properly and is configured as the quote text of the app.

🌟In this a fun implementation and usecase application of API requests package and tkinter module is done.

![App sample window](https://github.com/bellaryyash23/kanye_quotes_requests_API/blob/master/sample.JPG?raw=true)

👆App Window Sample👆
