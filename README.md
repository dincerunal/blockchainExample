# blockchainExample
This repository contains blockchain based examples of many popular algorithms and  concept states.


### Deployment steps:
- Clone this repo `git clone https://github.com/dincerunal/blockchainExample.git`
- Navigate to project directory and save example.env file as .env `mv example.env .env`
- Run main file `go run main.go`
- Open a web browser and for this url `http://localhost:8080/`
- For Write new blocks, send a `POST` request to `http://localhost:8080/` with a JSON payload with `BPM` as the key and an integer as the value. `{"BPM":50}`
- Send `POST` requests as you want and refresh your browser to grow your blockchain.








