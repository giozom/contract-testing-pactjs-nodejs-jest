# contract-testing-pactjs-nodejs-jest
Contract Testing Demo using NodeJs, PactJs and Jest 

#### Running the test
*  ```npm run test:consumer``` - consumer test
*  ```npm run test:provider``` - provider test
*  ```npm run publish:contract``` - publish contract to your pact broker

#### Publishing the contract to a broker (locally)
 * For more info refer to https://github.com/pact-foundation/pact_broker (To have a play around on your local machine)
 * Run ```git clone git@github.com:pact-foundation/pact_broker.git``` && ```cd pact_broker/example```
 * Run ```bundle install```
 * Run ```bundle exec rackup -p 8080```

#### Best Practices for contract testing
* Isolate tests
* Avoid tests with UI integration
* Keep contracts up to date in your pact broker
* Test Coverage with Pact
* Use models carefully

#### Common issues
* Use ```debug``` for logLevel for analysing test results ```'logLevel': 'debug'```
