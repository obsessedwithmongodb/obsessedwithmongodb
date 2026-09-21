<div align="center">

# `> obsessedwithmongodb_`

### 🍃 `DOCUMENTS // COLLECTIONS // AGGREGATIONS`

```text
╔══════════════════════════════════════════════════════════╗
║                                                          ║
║     SYSTEM STATUS .............. ONLINE                  ║
║     DATABASE ................... MongoDB                 ║
║     PORT ....................... 27017                   ║
║     RELATIONAL DATABASES ....... REJECTED                ║
║     BSON LEVEL ................. CRITICAL                ║
║                                                          ║
╚══════════════════════════════════════════════════════════╝
```

![MongoDB](https://img.shields.io/badge/MongoDB-00ED64?style=for-the-badge\&logo=mongodb\&logoColor=001E2B)
![BSON](https://img.shields.io/badge/BSON-001E2B?style=for-the-badge\&logo=mongodb\&logoColor=00ED64)
![NoSQL](https://img.shields.io/badge/NoSQL-00ED64?style=for-the-badge\&logoColor=black)

</div>

---

```javascript
db.users.findOne({
    username: "obsessedwithmongodb"
})
```

```json
{
  "_id": "0x27017",
  "username": "obsessedwithmongodb",
  "status": "ONLINE",
  "database": "MongoDB",
  "preferred_format": "BSON",
  "schema": "optional",
  "obsession": 100,
  "touching_grass": false
}
```

## `[ ABOUT_ME ]`

I like databases.

Correction.

I like **MongoDB**.

There is something beautiful about opening `mongosh`, creating a collection and throwing documents into it without spending the next seventeen years designing tables.

```text
SQL DATABASE DETECTED...

[████████████████████████████] 100%

ACTION: ignoring
```

My natural habitat:

```javascript
use my_database

db.createCollection("cool_stuff")

db.cool_stuff.insertOne({
    database: "MongoDB",
    opinion: "peak",
    alive: true
})
```

---

## `[ CURRENT_OBSESSION ]`

```javascript
db.obsessions.aggregate([
    {
        $match: {
            technology: "MongoDB"
        }
    },
    {
        $project: {
            _id: 0,
            happiness: { $literal: "████████████████ 100%" }
        }
    }
])
```

```text
[
  {
    happiness: '████████████████ 100%'
  }
]
```

---

## `[ DATABASE_PHILOSOPHY ]`

```text
┌──────────────────────────────────────────────┐
│                                              │
│   EVERYTHING IS A DOCUMENT                   │
│                                              │
│   DOCUMENTS BELONG IN COLLECTIONS            │
│                                              │
│   COLLECTIONS BELONG IN DATABASES            │
│                                              │
│   DATABASES BELONG ON PORT 27017             │
│                                              │
└──────────────────────────────────────────────┘
```

Why MongoDB?

`{ flexible: true }`

`{ scalable: true }`

`{ json_like: true }`

`{ aggregation_pipeline: "beautiful" }`

`{ mongodb: "yes" }`

---

## `[ TERMINAL ]`

```console
$ mongosh

Current Mongosh Log ID: 27017DEADBEEF
Connecting to: mongodb://127.0.0.1:27017/

test> use obsession
switched to db obsession

obsession> db.status.insertOne({
...   mongodb: "forever",
...   sql: null
... })

{
  acknowledged: true,
  insertedId: ObjectId("670000000000000000027017")
}

obsession> _
```

---

## `[ STACK ]`

```text
DATABASE
└── MongoDB
    ├── mongod
    ├── mongosh
    ├── Compass
    ├── Atlas
    ├── BSON
    ├── Aggregation Pipelines
    ├── Replica Sets
    └── Sharding

MENTAL STATE
└── MongoDB
    └── MongoDB
        └── MongoDB
            └── MongoDB
```

---

## `[ WARNING ]`

> `⚠ This GitHub profile contains dangerously high concentrations of BSON.`

Possible side effects include:

* creating collections for absolutely everything
* opening MongoDB Compass at 03:00
* unnecessarily using aggregation pipelines
* saying *"this should be a document"* during normal conversations
* experiencing emotional attachment to `ObjectId()`
* running `db.collection.find()` just to feel something

---

<div align="center">

```text
╭────────────────────────────────────────────╮
│                                            │
│       🍃  IN MONGODB WE TRUST  🍃          │
│                                            │
│           mongodb://localhost:27017        │
│                                            │
╰────────────────────────────────────────────╯
```

### `> db.users.findOne({ username: "obsessedwithmongodb" })`

**`{ status: "still obsessed" }`**

</div>
