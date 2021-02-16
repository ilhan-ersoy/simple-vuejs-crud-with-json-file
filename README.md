








## Vue CRUD App with local JSON API

### Installation


1. Clone the repo
   ```sh
   git clone https://github.com/ilhan-ersoy/vuejs-crud-with-realtime-api.git
   ```
2. Install NPM packages
   ```sh
   npm install
   ```
3. Install JSON Server 
   ```
   npm install -g json-server
   ```
4. Create a `db.json` file with some data 
   ```
   {
     "arrayOfProducts": [
       {
         "id": 3,
         "title": "CATE RIGID BAG123123",
         "price": 94.5
       },
       {
         "id": 4,
         "title": "Muffin",
         "price": "13,5",
       },
       {
         "id": 5    
         "title": "BMW",
         "price": "400",
       }
     ]
   }
   ```
5. Start JSON Server 
     ```
    json-server --watch db.json
     ```


<!-- USAGE EXAMPLES -->
## Usage

Open vuex.html on local server.

## vue.js axios exp.


