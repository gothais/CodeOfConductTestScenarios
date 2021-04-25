# CodeOfConductTestScenarios

I have take Codes of Conduct API for testing. I have used Postman as a tool to test the API.

I have covered Test cases for the following Scenarios:
- All Codes of Conduct End point
- All Codes of Conduct with invalid end point "codes_of_conducts" instead of "codes_of_conduct"
- All Codes of Conduct Preview Header missing
- Code of Conduct with a Key
- Code of Conduct with invalid Key
- Code of Conduct For a Repo

Added test cases for all the above scenarios. I have exported the collections as 'GitCodeOfConductAPITestCollection.postman_collection.json'

I have installed 'Newman' command line tool to run Postman. To install Newman, I have installed node.js. Make sure it is updated. Then install newman using the command 'npm install -g newman'.

Now that I have newman, I travered to the directory where my Test collection is saved. Then, Run 'newman run GitCodeOfConductAPITestCollection.postman_collection.json'
