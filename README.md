# PostmanCollection
Pre-requisite:
1. Install node.js at local machine
2. Install Newman:
   npm install -g newman
 
Run the collection:
1. Clone the code for collection:
   git clone https://github.com/oo7amitsharma/PostmanCollection.git
2. Navigate to the directory where collection is present.
2. Run below command to run collecton 10 times

   newman run ApiwithPostman.postman_collection.json -n 10
