# Sensyne

Tools used: Postman, GIT

How the tests are written?
For the given task, 
1. I have first added various POST tests validating the price and name field values. 
2. GET the added products and asserted based on the expected results
3. PATCH'ed the price and name fields and performed the validation
4. Deleted the added products

How to run?
1. Clone the postman collection to the local library
2. Open the postman
3. Import the collection (File -> Import)
4. Tap on SensyneHealth_Tests -> Tap on arrow -> Run
5. A console is opened detailing the passed and failed tests
