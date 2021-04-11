# file-transfer

## Instructions on how to use

### Installing Dependencies

`npm i` or `npm install` to install dependencies

### Running code

`node index.js` will run the app at `PORT 8090`

Modify the `port` variable in `index.js` to use a different port.

### File Upload

`POST` the file to the end point `server_address:PORT/upload` using `form-data` or appropriate format using the key `file` with value having the file to be uploaded.
