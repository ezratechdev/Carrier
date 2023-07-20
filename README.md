# Carrier Information
This is a basic package to get the carrier package of a Kenyan Phone Number.


## Installation


```bash
npm install carrierdetails
```

```bash
yarn add carrierdetails
```

## Usage

```javascript
import Carrier from "carrierdetails";
```

```javascript
console.log(Carrier("0722222222"));
```

## Output

```bash
{ operator: 'Safaricom', prefix: '722', number: '254722222222' }
```