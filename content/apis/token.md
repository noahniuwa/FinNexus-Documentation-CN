# FinNexus FNX Token API v0.1 Alpha

*Note: API is still under development and routes were changed on July 29th, 2020. The original routes still work but we recommend you use the new routes listed below. Also note that the domain name is subject to change. Any changes will be noted here and in API error messages until the official release of the 1.0 API.*

This is an API for getting data about the FNX token and the FinNexus Options Protocol on the Wanchain blockchain.

## API URL

[https://fnx-api.herokuapp.com/api/v1](https://fnx-api.herokuapp.com/api/v1)

The API makes use of Web3 to interact directly with the blockchain and also uses smart contract ABIs to connect with smart contract addresses and get access to their functions and events. 

A single route at `/api/v1` returns all of the API data, while individual pieces of data may also be queried at the specific routes listed below.

## Full Info Routes
*These routes return raw values, formatted values, and other associated information as a simple JSON object.*

### `Get all token data:` 

> [`GET https://fnx-api.herokuapp.com/api/v1`](https://fnx-api.herokuapp.com/api/v1)

### `Max supply:`
> [`GET https://fnx-api.herokuapp.com/api/v1/maxAmount`](https://fnx-api.herokuapp.com/api/v1/maxAmount) 

### `Minted FNX:`
> [`GET https://fnx-api.herokuapp.com/api/v1/minted`](https://fnx-api.herokuapp.com/api/v1/minted)

### `Current total supply:`
> [`GET https://fnx-api.herokuapp.com/api/v1/currentTotalSupply`](https://fnx-api.herokuapp.com/api/v1/currentTotalSupply) 

### `Operational reserves:`
> [`GET https://fnx-api.herokuapp.com/api/v1/opReserves`](https://fnx-api.herokuapp.com/api/v1/opReserves)    

### `Team and founding investors:`
> [`GET https://fnx-api.herokuapp.com/api/v1/teamAndFounders`](https://fnx-api.herokuapp.com/api/v1/teamAndFounders) 

### `Variable issuance:`
> [`GET https://fnx-api.herokuapp.com/api/v1/variableIssuance`](https://fnx-api.herokuapp.com/api/v1/variableIssuance)

### `Institutional investors:`
> [`GET https://fnx-api.herokuapp.com/api/v1/institutional`](https://fnx-api.herokuapp.com/api/v1/institutional) 

### `Burnt FNX:`
> [`GET https://fnx-api.herokuapp.com/api/v1/burned`](https://fnx-api.herokuapp.com/api/v1/burned)    

### `Converted FNX:`
> [`GET https://fnx-api.herokuapp.com/api/v1/converted`](https://fnx-api.herokuapp.com/api/v1/converted)

### `FNX in circulation:` 
> [`GET https://fnx-api.herokuapp.com/api/v1/fnxInCirculation`](https://fnx-api.herokuapp.com/api/v1/fnxInCirculation)

### `FNX locked in FPO:`
> [`GET https://fnx-api.herokuapp.com/api/v1/lockedFnx`](https://fnx-api.herokuapp.com/api/v1/lockedFnx)    

### `FNX in circulation with locked FNX deducted:` 
> [`GET https://fnx-api.herokuapp.com/api/v1/fnxInCirculationDeducted`](https://fnx-api.herokuapp.com/api/v1/fnxInCirculationDeducted)

### `Current total supply of FNX on Ethereum:` 
> [`GET https://fnx-api.herokuapp.com/api/v1/ethCurrentTotalSupply`](https://fnx-api.herokuapp.com/api/v1/ethCurrentTotalSupply)


## Raw Number Routes 
*These routes return raw numebrs only, as required for consumption by certain other APIs.*

### `Current total supply of FNX (Raw Number):` 
> [`GET https://fnx-api.herokuapp.com/api/v1/currentTotalSupplyRaw`](https://fnx-api.herokuapp.com/api/v1/currentTotalSupplyRaw)

### `Current total supply of FNX Decimal Conversion (Raw Number):` 
> [`GET https://fnx-api.herokuapp.com/api/v1/currentTotalSupplyRawDecimals`](https://fnx-api.herokuapp.com/api/v1/currentTotalSupplyRawDecimals)

### `FNX in circulation (Raw Number):` 
> [`GET https://fnx-api.herokuapp.com/api/v1/fnxInCirculationRaw`](https://fnx-api.herokuapp.com/api/v1/fnxInCirculationRaw)

### `FNX in circulation Decimal Conversion (Raw Number):` 
> [`GET https://fnx-api.herokuapp.com/api/v1/fnxInCirculationRawDecimals`](https://fnx-api.herokuapp.com/api/v1/fnxInCirculationRawDecimals)

### `Current total supply of FNX on Ethereum (Raw Number):` 
> [`GET https://fnx-api.herokuapp.com/api/v1/ethCurrentTotalSupplyRaw`](https://fnx-api.herokuapp.com/api/v1/ethCurrentTotalSupplyRaw)