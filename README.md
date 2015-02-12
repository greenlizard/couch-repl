couch-repl
==========

$` ./bin/couchrepl -i`

```javascript
    couch.start() // to initiate dbs

    couch.dbs.xxx.allDocs()
    couch.dbs.create('db')
    couch.dbs.xxx.get('id')
    couch.dbs.xxx.post({test:'test'})
    couch.dbs.xxx.put('id', 'rev',{test:'test'})
    couch.dbs.xxx.head()
    couch.dbs.xxx.del('id', 'rev')
```
