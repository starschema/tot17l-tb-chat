# TBChat
### Description
TBChat is a web socket based chat platform for Tableau dashboars. It is designt to allow users to discuss with each other while viewing or analyzing a dashboard. 

The program have the main componenet. One is the server side program. (`server.js`). The other is the client side component (`index.html`). 

`server.js` will handle the connections, and will broadcast the messages. 

`index.html` is dedicated to display the HTML part of the chat form, and handle the message inputs. 

**Future Features**
* send selected marks/filters
* display recieved marks/filtes
* parse date and time from messages, and filter to them

## Technical details
### Install dependencies
`npm install`

### Run chat server
`npm start`
This will start the server.js and listen on port 3435 (HTTP).


