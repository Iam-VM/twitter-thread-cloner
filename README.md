# Backend Application for ***twitter-thread-cloner***

## About Twitter-Thread-Cloner
> Go to website: ```http://twittertcloner.ddns.net:4000/```

* Twitter-Thread-Cloner (TTC) is a website service that helps in downloading a twitter thread post in PDF, TXT and ZIP formats.
  
![TTC Screenshot](https://github.com/Iam-VM/twitter-thread-cloner-server/doc/ttc-screenshot.png?raw=true)
 
## How to use the website ?

1. Enter the URL of the last tweet of the thread ***( last tweet: tweet until which you want to clone )*** in the text field in ```http://twittertcloner.ddns.net:4000/```.
> Format of a tweet URL: <BR />```https://twitter.com/username/status/1234567891011121314```
2. Click on a convert button, according to the format to which you want to clone.
3. Wait for a few seconds, the processed file should be available to download within then.

## Built With

* ReactJS
* ExpressJS
* Python
* Socket.io
* CSS

## Some Information
* This project is built with the tools as listed in the **Built With** section.
* The frontend application is built with **React**, using create-react-app for generating a pre-configured build setup.
* Used **ExpressJS** for building the server app, with **Socket.io** for enabling realtime communication between backend and frontend.
* The core logic of this project, the scripts for converting twitter threads to the said formats are written in **Python3**.
* We use **Twitter API** for accessing information about tweets.

## Contributing
* Fork the ```twitter-thread-cloner-server``` and ```twitter-thread-cloner-frontend``` repositories.
* Clone the forks.
* Push your commits.
* Open pull requests.


## Contact
> Iam-VM: iamvm.dev@gmail.com
