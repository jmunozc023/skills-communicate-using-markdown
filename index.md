# Test de Markdown 
## Test de Markdown
### Test de Markdown
#### Test de Markdown
##### Test de Markdown
###### Test de Markdown
![Test Image](https://octodex.github.com/images/yaktocat.png)
``` Javascript
module.exports = {
    connectToDb: (callback) => {
        MongoClient.connect(uri)
        .then((client) => {
            dbConnection = client.db();
            return callback();
        })
        .catch(err => {
            console.log(err);
            return callback(err);
        });
    },
    getDb: () => dbConnection
}
```
