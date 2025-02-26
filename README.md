PS C:\Users\hp> mongod
{"t":{"$date":"2025-02-26T11:43:40.196+03:00"},"s":"I",  "c":"CONTROL",  "id":23285,   "ctx":"thread1","msg":"Automatically disabling TLS 1.0, to force-enable TLS 1.0 specify --sslDisabledProtocols 'none'"}
{"t":{"$date":"2025-02-26T11:43:40.197+03:00"},"s":"I",  "c":"NETWORK",  "id":4915701, "ctx":"thread1","msg":"Initialized wire specification","attr":{"spec":{"incomingExternalClient":{"minWireVersion":0,"maxWireVersion":21},"incomingInternalClient":{"minWireVersion":0,"maxWireVersion":21},"outgoing":{"minWireVersion":6,"maxWireVersion":21},"isInternalClient":true}}}
{"t":{"$date":"2025-02-26T11:43:42.400+03:00"},"s":"I",  "c":"NETWORK",  "id":4648602, "ctx":"thread1","msg":"Implicit TCP FastOpen in use."}
{"t":{"$date":"2025-02-26T11:43:42.404+03:00"},"s":"I",  "c":"REPL",     "id":5123008, "ctx":"thread1","msg":"Successfully registered PrimaryOnlyService","attr":{"service":"TenantMigrationDonorService","namespace":"config.tenantMigrationDonors"}}
{"t":{"$date":"2025-02-26T11:43:42.405+03:00"},"s":"I",  "c":"REPL",     "id":5123008, "ctx":"thread1","msg":"Successfully registered PrimaryOnlyService","attr":{"service":"TenantMigrationRecipientService","namespace":"config.tenantMigrationRecipients"}}
{"t":{"$date":"2025-02-26T11:43:42.405+03:00"},"s":"I",  "c":"CONTROL",  "id":5945603, "ctx":"thread1","msg":"Multi threading initialized"}
{"t":{"$date":"2025-02-26T11:43:42.405+03:00"},"s":"I",  "c":"TENANT_M", "id":7091600, "ctx":"thread1","msg":"Starting TenantMigrationAccessBlockerRegistry"}
{"t":{"$date":"2025-02-26T11:43:42.407+03:00"},"s":"I",  "c":"CONTROL",  "id":4615611, "ctx":"initandlisten","msg":"MongoDB starting","attr":{"pid":2940,"port":27017,"dbPath":"C:/data/db/","architecture":"64-bit","host":"DESKTOP-5U1PE02"}}
{"t":{"$date":"2025-02-26T11:43:42.407+03:00"},"s":"I",  "c":"CONTROL",  "id":23398,   "ctx":"initandlisten","msg":"Target operating system minimum version","attr":{"targetMinOS":"Windows 7/Windows Server 2008 R2"}}
{"t":{"$date":"2025-02-26T11:43:42.407+03:00"},"s":"I",  "c":"CONTROL",  "id":23403,   "ctx":"initandlisten","msg":"Build Info","attr":{"buildInfo":{"version":"7.0.16","gitVersion":"18b949444cfdaa88e30b0e10243bc18268251c1f","modules":[],"allocator":"tcmalloc","environment":{"distmod":"windows","distarch":"x86_64","target_arch":"x86_64"}}}}
{"t":{"$date":"2025-02-26T11:43:42.407+03:00"},"s":"I",  "c":"CONTROL",  "id":51765,   "ctx":"initandlisten","msg":"Operating System","attr":{"os":{"name":"Microsoft Windows 10","version":"10.0 (build 22631)"}}}
{"t":{"$date":"2025-02-26T11:43:42.407+03:00"},"s":"I",  "c":"CONTROL",  "id":21951,   "ctx":"initandlisten","msg":"Options set by command line","attr":{"options":{}}}
{"t":{"$date":"2025-02-26T11:43:42.410+03:00"},"s":"E",  "c":"CONTROL",  "id":20557,   "ctx":"initandlisten","msg":"DBException in initAndListen, terminating","attr":{"error":"NonExistentPath: Data directory C:\\data\\db\\ not found. Create the missing directory or specify another path using (1) the --dbpath command line option, or (2) by adding the 'storage.dbPath' option in the configuration file."}}
{"t":{"$date":"2025-02-26T11:43:42.410+03:00"},"s":"I",  "c":"REPL",     "id":4784900, "ctx":"initandlisten","msg":"Stepping down the ReplicationCoordinator for shutdown","attr":{"waitTimeMillis":15000}}
{"t":{"$date":"2025-02-26T11:43:42.411+03:00"},"s":"I",  "c":"REPL",     "id":4794602, "ctx":"initandlisten","msg":"Attempting to enter quiesce mode"}
{"t":{"$date":"2025-02-26T11:43:42.411+03:00"},"s":"I",  "c":"-",        "id":6371601, "ctx":"initandlisten","msg":"Shutting down the FLE Crud thread pool"}
{"t":{"$date":"2025-02-26T11:43:42.411+03:00"},"s":"I",  "c":"COMMAND",  "id":4784901, "ctx":"initandlisten","msg":"Shutting down the MirrorMaestro"}
{"t":{"$date":"2025-02-26T11:43:42.411+03:00"},"s":"I",  "c":"SHARDING", "id":4784902, "ctx":"initandlisten","msg":"Shutting down the WaitForMajorityService"}
{"t":{"$date":"2025-02-26T11:43:42.412+03:00"},"s":"I",  "c":"NETWORK",  "id":20562,   "ctx":"initandlisten","msg":"Shutdown: going to close listening sockets"}
{"t":{"$date":"2025-02-26T11:43:42.412+03:00"},"s":"I",  "c":"NETWORK",  "id":4784905, "ctx":"initandlisten","msg":"Shutting down the global connection pool"}
{"t":{"$date":"2025-02-26T11:43:42.412+03:00"},"s":"I",  "c":"CONTROL",  "id":4784906, "ctx":"initandlisten","msg":"Shutting down the FlowControlTicketholder"}
{"t":{"$date":"2025-02-26T11:43:42.412+03:00"},"s":"I",  "c":"-",        "id":20520,   "ctx":"initandlisten","msg":"Stopping further Flow Control ticket acquisitions."}
{"t":{"$date":"2025-02-26T11:43:42.413+03:00"},"s":"I",  "c":"NETWORK",  "id":4784918, "ctx":"initandlisten","msg":"Shutting down the ReplicaSetMonitor"}
{"t":{"$date":"2025-02-26T11:43:42.413+03:00"},"s":"I",  "c":"SHARDING", "id":4784921, "ctx":"initandlisten","msg":"Shutting down the MigrationUtilExecutor"}
{"t":{"$date":"2025-02-26T11:43:42.414+03:00"},"s":"I",  "c":"ASIO",     "id":22582,   "ctx":"MigrationUtil-TaskExecutor","msg":"Killing all outstanding egress activity."}
{"t":{"$date":"2025-02-26T11:43:42.414+03:00"},"s":"I",  "c":"COMMAND",  "id":4784923, "ctx":"initandlisten","msg":"Shutting down the ServiceEntryPoint"}
{"t":{"$date":"2025-02-26T11:43:42.414+03:00"},"s":"I",  "c":"CONTROL",  "id":4784928, "ctx":"initandlisten","msg":"Shutting down the TTL monitor"}
{"t":{"$date":"2025-02-26T11:43:42.414+03:00"},"s":"I",  "c":"CONTROL",  "id":6278511, "ctx":"initandlisten","msg":"Shutting down the Change Stream Expired Pre-images Remover"}
{"t":{"$date":"2025-02-26T11:43:42.414+03:00"},"s":"I",  "c":"CONTROL",  "id":4784929, "ctx":"initandlisten","msg":"Acquiring the global lock for shutdown"}
{"t":{"$date":"2025-02-26T11:43:42.414+03:00"},"s":"I",  "c":"-",        "id":4784931, "ctx":"initandlisten","msg":"Dropping the scope cache for shutdown"}
{"t":{"$date":"2025-02-26T11:43:42.414+03:00"},"s":"I",  "c":"CONTROL",  "id":20565,   "ctx":"initandlisten","msg":"Now exiting"}
{"t":{"$date":"2025-02-26T11:43:42.415+03:00"},"s":"I",  "c":"CONTROL",  "id":8423404, "ctx":"initandlisten","msg":"mongod shutdown complete","attr":{"Summary of time elapsed":{"Statistics":{"Enter terminal shutdown":"0 ms","Step down the replication coordinator for shutdown":"1 ms","Time spent in quiesce mode":"0 ms","Shut down FLE Crud subsystem":"0 ms","Shut down MirrorMaestro":"0 ms","Shut down WaitForMajorityService":"0 ms","Shut down the transport layer":"1 ms","Shut down the global connection pool":"0 ms","Shut down the flow control ticket holder":"0 ms","Shut down the replica set monitor":"1 ms","Shut down the migration util executor":"1 ms","Shut down the TTL monitor":"0 ms","Shut down expired pre-images and documents removers":"0 ms","Wait for the oplog cap maintainer thread to stop":"0 ms","Shut down full-time data capture":"0 ms","shutdownTask total elapsed time":"4 ms"}}}}
{"t":{"$date":"2025-02-26T11:43:42.416+03:00"},"s":"I",  "c":"CONTROL",  "id":23138,   "ctx":"initandlisten","msg":"Shutting down","attr":{"exitCode":100}}
PS C:\Users\hp> mongosh
Current Mongosh Log ID: 67bed44b538c717945fa4213
Connecting to:          mongodb://127.0.0.1:27017/?directConnection=true&serverSelectionTimeoutMS=2000&appName=mongosh+2.4.0
Using MongoDB:          7.0.16
Using Mongosh:          2.4.0

For mongosh info see: https://www.mongodb.com/docs/mongodb-shell/

------
   The server generated these startup warnings when booting
   2025-02-24T17:37:45.281+03:00: Access control is not enabled for the database. Read and write access to data and configuration is unrestricted
------

test> show dbs
admin      40.00 KiB
config     72.00 KiB
demo      112.00 KiB
library    40.00 KiB
local      40.00 KiB
moviesDB  120.00 KiB
test> use library
switched to db library
library> db.createCollection("books")
{ ok: 1 }
library> db.books.insertMany({
... "Title":"The Gasby Great",
... "Author":"M.Chepsiror",
... "PublishedYear":2005,
... "Genre":"Fiction",
... "ISBN":"9780743273565"
... },
...  {
...     title: "1984",
...     author: "George Orwell",
...     publishedYear: 1949,
...     genre: "Dystopian",
...     ISBN: "9780451524935"
...   },
...  {
...     title: "To Kill a Mockingbird",
...     author: "Harper Lee",
...     publishedYear: 1960,
...     genre: "Fiction",
...     ISBN: "9780061120084"
...   },
...   {
...     title: "The Catcher in the Rye",
...     author: "J.D. Salinger",
...     publishedYear: 1951,
...     genre: "Fiction",
...     ISBN: "9780316769488"
...   },
... {
...     title: "Harry Potter and the Sorcerer's Stone",
...     author: "J.K. Rowling",
...     publishedYear: 1997,
...     genre: "Fantasy",
...     ISBN: "9780590353427"
...   }
... ])
Uncaught:
SyntaxError: Unexpected token, expected "," (36:0)

  34 |     ISBN: "9780590353427"
  35 |   }
> 36 | ])
     | ^
  37 |

library> db.books.insertMany([{
... ... "Title":"The Gasby Great",
... ... "Author":"M.Chepsiror",
... ... "PublishedYear":2005,
... ... "Genre":"Fiction",
... ... "ISBN":"9780743273565"
... ... },
... ...  {
... ...     title: "1984",
... ...     author: "George Orwell",
... ...     publishedYear: 1949,
... ...     genre: "Dystopian",
... ...     ISBN: "9780451524935"
... ...   },
... ...  {
... ...     title: "To Kill a Mockingbird",
... ...     author: "Harper Lee",
... ...     publishedYear: 1960,
... ...     genre: "Fiction",
... ...     ISBN: "9780061120084"
... ...   },
... ...   {
... ...     title: "The Catcher in the Rye",
... ...     author: "J.D. Salinger",
... ...     publishedYear: 1951,
... ...     genre: "Fiction",
... ...     ISBN: "9780316769488"
... ...   },
... ... {
... ...     title: "Harry Potter and the Sorcerer's Stone",
... ...     author: "J.K. Rowling",
... ...     publishedYear: 1997,
... ...     genre: "Fantasy",
... ...     ISBN: "9780590353427"
... ...   }
... ... ])
Uncaught:
SyntaxError: Unexpected token, expected "," (2:11)

  1 | db.books.insertMany([{
> 2 | ... "Title":"The Gasby Great",
    |            ^
  3 | ... "Author":"M.Chepsiror",
  4 | ... "PublishedYear":2005,
  5 | ... "Genre":"Fiction",

library> db.books.insertMany([
...   {
...     title: "The Great Gatsby",
...     author: "F. Scott Fitzgerald",
...     publishedYear: 1925,
...     genre: "Fiction",
...     ISBN: "9780743273565"
...   },
...   {
...     title: "1984",
...     author: "George Orwell",
...     publishedYear: 1949,
...     genre: "Dystopian",
...     ISBN: "9780451524935"
...   },
...   {
...     title: "To Kill a Mockingbird",
...     author: "Harper Lee",
...     publishedYear: 1960,
...     genre: "Fiction",
...     ISBN: "9780061120084"
...   },
...   {
...     title: "The Catcher in the Rye",
...     author: "J.D. Salinger",
...     publishedYear: 1951,
...     genre: "Fiction",
...     ISBN: "9780316769488"
...   },
...   {
...     title: "Harry Potter and the Sorcerer's Stone",
...     author: "J.K. Rowling",
...     publishedYear: 1997,
...     genre: "Fantasy",
...     ISBN: "9780590353427"
...   }
... ])
{
  acknowledged: true,
  insertedIds: {
    '0': ObjectId('67bed66b538c717945fa4214'),
    '1': ObjectId('67bed66b538c717945fa4215'),
    '2': ObjectId('67bed66b538c717945fa4216'),
    '3': ObjectId('67bed66b538c717945fa4217'),
    '4': ObjectId('67bed66b538c717945fa4218')
  }
}
library> db.books.find()
[
  {
    _id: ObjectId('67bdf583ceaf7b61fbfa4214'),
    title: '1984',
    author: 'George Orwell',
    publishedYear: 1949
  },
  {
    _id: ObjectId('67bed66b538c717945fa4214'),
    title: 'The Great Gatsby',
    author: 'F. Scott Fitzgerald',
    publishedYear: 1925,
    genre: 'Fiction',
    ISBN: '9780743273565'
  },
  {
    _id: ObjectId('67bed66b538c717945fa4215'),
    title: '1984',
    author: 'George Orwell',
    publishedYear: 1949,
    genre: 'Dystopian',
    ISBN: '9780451524935'
  },
  {
    _id: ObjectId('67bed66b538c717945fa4216'),
    title: 'To Kill a Mockingbird',
    author: 'Harper Lee',
    publishedYear: 1960,
    genre: 'Fiction',
    ISBN: '9780061120084'
  },
  {
    _id: ObjectId('67bed66b538c717945fa4217'),
    title: 'The Catcher in the Rye',
    author: 'J.D. Salinger',
    publishedYear: 1951,
    genre: 'Fiction',
    ISBN: '9780316769488'
  },
  {
    _id: ObjectId('67bed66b538c717945fa4218'),
    title: "Harry Potter and the Sorcerer's Stone",
    author: 'J.K. Rowling',
    publishedYear: 1997,
    genre: 'Fantasy',
    ISBN: '9780590353427'
  }
]
library> db.books.find({author:"Harper Lee"})
[
  {
    _id: ObjectId('67bed66b538c717945fa4216'),
    title: 'To Kill a Mockingbird',
    author: 'Harper Lee',
    publishedYear: 1960,
    genre: 'Fiction',
    ISBN: '9780061120084'
  }
]
library>  db.books.find({author:"George Orwell"})
[
  {
    _id: ObjectId('67bdf583ceaf7b61fbfa4214'),
    title: '1984',
    author: 'George Orwell',
    publishedYear: 1949
  },
  {
    _id: ObjectId('67bed66b538c717945fa4215'),
    title: '1984',
    author: 'George Orwell',
    publishedYear: 1949,
    genre: 'Dystopian',
    ISBN: '9780451524935'
  }
]
library> db.books.find({ publishedYear: { $gt: 2000 } })

library> db.books.find({ publishedYear: { $gt: 1920}})
[
  {
    _id: ObjectId('67bdf583ceaf7b61fbfa4214'),
    title: '1984',
    author: 'George Orwell',
    publishedYear: 1949
  },
  {
    _id: ObjectId('67bed66b538c717945fa4214'),
    title: 'The Great Gatsby',
    author: 'F. Scott Fitzgerald',
    publishedYear: 1925,
    genre: 'Fiction',
    ISBN: '9780743273565'
  },
  {
    _id: ObjectId('67bed66b538c717945fa4215'),
    title: '1984',
    author: 'George Orwell',
    publishedYear: 1949,
    genre: 'Dystopian',
    ISBN: '9780451524935'
  },
  {
    _id: ObjectId('67bed66b538c717945fa4216'),
    title: 'To Kill a Mockingbird',
    author: 'Harper Lee',
    publishedYear: 1960,
    genre: 'Fiction',
    ISBN: '9780061120084'
  },
  {
    _id: ObjectId('67bed66b538c717945fa4217'),
    title: 'The Catcher in the Rye',
    author: 'J.D. Salinger',
    publishedYear: 1951,
    genre: 'Fiction',
    ISBN: '9780316769488'
  },
  {
    _id: ObjectId('67bed66b538c717945fa4218'),
    title: "Harry Potter and the Sorcerer's Stone",
    author: 'J.K. Rowling',
    publishedYear: 1997,
    genre: 'Fantasy',
    ISBN: '9780590353427'
  }
]
library> db.books.updateOne({
... title:"The Great Gatsby"},
... {$set:{publishedYear:2004}})
{
  acknowledged: true,
  insertedId: null,
  matchedCount: 1,
  modifiedCount: 1,
  upsertedCount: 0
}
library> db.books.updateMany({},{$set:{rating:5.0}})
{
  acknowledged: true,
  insertedId: null,
  matchedCount: 6,
  modifiedCount: 6,
  upsertedCount: 0
}
library> db.book.deleteOne({ISBN:"9780590353427"})
{ acknowledged: true, deletedCount: 0 }
library> db.books.deleteOne({ISBN:"9780590353427"})
{ acknowledged: true, deletedCount: 1 }
library> db.books.deleteMany({ genre: "Fiction" })
{ acknowledged: true, deletedCount: 3 }
library> db.users.insertOne({
...   userId: 1,
...   name:"Mercy Chepsiror",
... email:"mercy@gmail.com",
... address:"457 Atlanta"})
{
  acknowledged: true,
  insertedId: ObjectId('67beda0e538c717945fa4219')
}
library> db.products.insertOne({
...   productId: 101,
...   name: "Laptop",
...   price: 1200,
...   category: "Electronics"
... })
...
... db.orders.insertOne({
...   orderId: 1001,
...   userId: 1,
...   products: [
...     { productId: 101, quantity: 1 }
...   ],
...   totalAmount: 1200
... }db.products.insertOne({
...   productId: 101,
...   name: "Laptop",
...   price: 1200,
...   category: "Electronics"
... })
...
... db.orders.insertOne({
...   orderId: 1001,
...   userId: 1,
...   products: [
...     { productId: 101, quantity: 1 }
...   ],
...   totalAmount: 1200
... })
Uncaught:
SyntaxError: Unexpected token, expected "," (15:1)

  13 |   ],
  14 |   totalAmount: 1200
> 15 | }db.products.insertOne({
     |  ^
  16 |   productId: 101,
  17 |   name: "Laptop",
  18 |   price: 1200,

library> db.products.insertOne({
...   productId: 101,
...   name: "Laptop",
...   price: 1200,
...   category: "Electronics"
... })
{
  acknowledged: true,
  insertedId: ObjectId('67beda6f538c717945fa421a')
}
library> db.orders.insertOne({
...   orderId: 1001,
...   userId: 1,
...   products: [
...     { productId: 101, quantity: 1 }
...   ],
...   totalAmount: 1200
... })
{
  acknowledged: true,
  insertedId: ObjectId('67beda7a538c717945fa421b')
}
library> db.books.aggregate([
...   { $group: { _id: "$genre", totalBooks: { $sum: 1 } } }
... ])
[ { _id: 'Dystopian', totalBooks: 1 }, { _id: null, totalBooks: 1 } ]
library> db.books.aggregate([
...   { $group: { _id: "$genre", totalBooks: { $sum: 1 } } }
...
... )
Uncaught:
SyntaxError: Unexpected token, expected "," (4:0)

  2 |   { $group: { _id: "$genre", totalBooks: { $sum: 1 } } }
  3 |
> 4 | )
    | ^
  5 |

library> db.books.aggregate([
...   { $group: { _id: "$fiction",totalBooks: { $sum: 1 } } }
... ])
[ { _id: null, totalBooks: 2 } ]
library> db.books.aggregate([
...   { $group: { _id: null, avgPublishedYear: { $avg: "$publishedYear" } } }
... ])
[ { _id: null, avgPublishedYear: 1949 } ]
library> db.books.aggregate([
...   { $sort: { rating: -1 } },
...   { $limit: 1 }
... ])
[
  {
    _id: ObjectId('67bdf583ceaf7b61fbfa4214'),
    title: '1984',
    author: 'George Orwell',
    publishedYear: 1949,
    rating: 5
  }
]
library> db.books.createIndex({ author: 1 })
author_1
library>