## YeetFace - Javascript Video Calling App
Check it out here: https://yeetface.herokuapp.com/  

<img align="right" width="420" src="https://github.com/Thinkeraty/yeetface/blob/master/screenshots/Annotation%202020-09-09%20085234.png"  alt =" " style="border: solid 1px #d4d4d4" />
  
Video call to your friend without registering. 
Simply send your friend your auto-generated unique ID to make the call.  
Everytime you open a new tab, the server gives you a totally different unique ID.

### Development

```
# Install dependencies
npm install

# Run server
npm run watch:server
```
And then in a new terminal window:
````
# Run client server
npm run watch:client
````
### Deployment

**Heroku**

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Thinkeraty/yeetface/tree/master)

**Custom**
```
# Install dependencies
npm install

# Build front-end assets
npm run build

# Run server
yarn start
```
