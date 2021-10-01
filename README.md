# SimpleStorage

## Contract
* Can hold a user's favorite number and retireve current fdavorite number
* Storage is mapped for multiple favorite numbers to be stored

## Deploy
* Account is dynamic to network used
* After deployment contacts are saved and ``` list => SimpleStorage``` can be utilized to get latest contract

## Tests
* Deployments is tested by retrieving account deploying contract then retrieving expected value of 0
* Storage update is tested by storing an arbitrary number and testing retrieve function to check expected store value
