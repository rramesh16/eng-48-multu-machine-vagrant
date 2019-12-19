# Multi Machine vagrant

- Multiple machines are defined within the same project Vagrantfile using the ````config.vm.define```` method call.
- A db and app files were created under the environment folder
- The db machine was configured with a different IP from the app
- db machine was provisioned with a MongoDB database
- All tests are running



## Usage
- Clone this repo

### To run the tests
- On bash cd into 'tests' file
- Write rake spec to run all the test (one for the app VM and one for the db VM)
- The output should result in 0 failures of the tests

### To use the app
- On the bash command line write: ````vagrant up````
- Bottom line of your output should read: ````> app: Your app is ready and listening on port 3000````
