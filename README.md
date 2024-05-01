## This quickstart shows you how to call the Gas API using JavaScript. You can also use a tool such as cURL or Postman to call the REST APIs.
1. Fork this repository
2. Clone this repository
3. Install required packages
- Install the axios package:
```npm install axios```
- Install the dotenv package:
```npm install dotenv```
4. Create your .env file
```
INFURA_API_KEY=<API-KEY>
INFURA_API_KEY_SECRET=<API-KEY-SECRET>
```
5. Run the script
```node index.js```

The result should look similar to:
```
Suggested gas fees: {
  low: {
    suggestedMaxPriorityFeePerGas: '0.05',
    suggestedMaxFeePerGas: '24.086058416',
    minWaitTimeEstimate: 15000,
    maxWaitTimeEstimate: 30000
  },
  medium: {
    suggestedMaxPriorityFeePerGas: '0.1',
    suggestedMaxFeePerGas: '32.548678862',
    minWaitTimeEstimate: 15000,
    maxWaitTimeEstimate: 45000
  },
  high: {
    suggestedMaxPriorityFeePerGas: '0.3',
    suggestedMaxFeePerGas: '41.161299308',
    minWaitTimeEstimate: 15000,
    maxWaitTimeEstimate: 60000
  },
  estimatedBaseFee: '24.036058416',
  networkCongestion: 0.7143,
  latestPriorityFeeRange: [ '0.1', '20' ],
  historicalPriorityFeeRange: [ '0.007150439', '113' ],
  historicalBaseFeeRange: [ '19.531410688', '36.299069766' ],
  priorityFeeTrend: 'down',
  baseFeeTrend: 'down'
}
```
