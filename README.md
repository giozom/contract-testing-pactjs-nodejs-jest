# contract-testing-pactjs-nodejs-jest
Contract Testing Demo using NodeJs, PactJs and Jest 

#### Running the test
```npm run test:consumer``` - consumer test
```npm run test:provider``` - provider test

#### Publishing the contract to a broker (locally)
 * For more info refer to https://github.com/pact-foundation/pact_broker (To have a play around on your local machine)
 * Run ```git clone git@github.com:pact-foundation/pact_broker.git``` && ```cd pact_broker/example```
 * Run ```bundle install```
 * Run ```bundle exec rackup -p 8080```
