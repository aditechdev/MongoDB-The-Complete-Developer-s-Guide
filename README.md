<table>
<tr>
<td width="120">

<img src="src/MongoDB_Logomark_ForestGreen.png" alt="MongoDB Logo" width="120" width="80">

</td>

<td>

# MongoDB — The Complete Developer's Guide

Comprehensive study notes, diagrams, architecture visualizations, and hands-on examples documenting my MongoDB learning journey.

![Course](https://img.shields.io/badge/Course-Udemy-green)
![Duration](https://img.shields.io/badge/Duration-17.5%20Hours-blue)
![Completed](https://img.shields.io/badge/Completed-May%202026-brightgreen)

</td>
</tr>
</table>

---

<!-- <p align="center">

  <img src="https://www.clipartmax.com/png/middle/114-1147615_mongodb-leaf-open-source-nosql-database-startups-mongodb-logo.png" alt="MongoDB Logo" width="120">

</p>
<h1 align="center">MongoDB — The Complete Developer's Guide</h1>

<p align="center">

  Comprehensive study notes, diagrams, architecture visualizations, and hands-on examples documenting my MongoDB learning journey.

</p>

<p align="center">

  <img src="https://img.shields.io/badge/Course-Udemy-green" />

  <img src="https://img.shields.io/badge/Duration-17.5%20Hours-blue" />

  <img src="https://img.shields.io/badge/Completed-May%202026-brightgreen" />

</p>

<hr> -->


---

## 🚀 About This Repository

<table>

<tr>

<td width="55%">

This repository is my **personal MongoDB knowledge base and portfolio project**.

It consolidates everything I learned into structured notes, practical examples, diagrams, and reference material.

### ✅ Included

- Course slides and lecture summaries

- Hands-on `mongosh` practice notes

- Visual architecture diagrams

- CRUD operations & query examples

- Aggregation framework examples

- Geospatial queries

- Indexing & performance concepts

- MongoDB Atlas deployment notes

- Node.js integration examples

</td>

<td width="45%">

<p align="center">

  <img src="src/image.png" width="100%">

</p>

### Powering Modern Applications

✅ Flexible Schema

✅ High Performance

✅ Horizontally Scalable

✅ Developer Friendly

</td>

</tr>

</table>

📂 All source materials live in [`src/`](src/).

### What You'll Learn (Course Outcomes)

By completing this course and these notes, you will be able to:

- Explain how document databases differ from relational SQL databases
- Install and configure `mongod` and `mongosh` on macOS/Windows
- Perform full CRUD operations with filters, operators, and projections
- Model one-to-one, one-to-many, and many-to-many relationships
- Enforce schema rules with `$jsonSchema` validation
- Create and optimize indexes using `explain("executionStats")`
- Build aggregation pipelines for analytics and data transformation
- Query geospatial data with GeoJSON and `2dsphere` indexes
- Handle numeric precision with BSON number types
- Secure MongoDB with authentication, roles, and TLS
- Understand replica sets, sharding, and MongoDB Atlas deployment
- Use transactions and connect from application drivers (Node.js)

### How to Use These Notes

1. **New to MongoDB?** Start with [Section 1–4](#1-what-is-mongodb) for fundamentals, then work through CRUD (6–8).
2. **Building an app?** Focus on [Data Modeling (9)](#9-data-modeling--relations), [Indexes (11)](#11-indexes--query-performance), and [Drivers (17)](#17-transactions--drivers).
3. **Interview prep?** Use the [Cheat Sheet (18)](#18-quick-reference-cheat-sheet) and [Common Pitfalls (20)](#20-common-pitfalls--troubleshooting).
4. **Every snippet runs in `mongosh`** unless marked as shell/bash or driver code.

---

## Course Roadmap (19 Sections)

| # | Section | Topics Covered |
|---|---|---|
| 1 | Introduction | What is MongoDB, ecosystem, installation (macOS/Windows), mongosh |
| 2 | Basics & CRUD | Databases, collections, documents, JSON/BSON, insert/find/update/delete |
| 3 | Schemas & Relations | Data types, embedding vs referencing, `$lookup`, schema validation |
| 4 | Shell & Server | `mongod` options, config files, background service, shutdown |
| 5 | MongoDB Compass | Visual exploration of databases and collections |
| 6 | Create Operations | `insertOne`/`insertMany`, write concern, atomicity, `mongoimport` |
| 7 | Read Operations | Query selectors, cursors, projection, array queries |
| 8 | Update Operations | Field operators, array updates, upsert, `arrayFilters` |
| 9 | Delete Operations | `deleteOne`, `deleteMany`, drop collection |
| 10 | Indexes | Single/compound/multi-key/text indexes, `explain()`, covered queries |
| 11 | Geospatial Data | GeoJSON, `2dsphere`, `$near`, `$geoWithin` |
| 12 | Aggregation Framework | Pipeline stages, `$group`, `$unwind`, `$lookup`, `$bucket` |
| 13 | Numeric Data | Int32/Int64/Double/Decimal128, precision pitfalls |
| 14 | Security | Authentication, RBAC, TLS/SSL, encryption at rest |
| 15 | Performance & Deployment | Capped collections, replica sets, sharding, Atlas |
| 16 | Transactions | Multi-document ACID transactions |
| 17 | Drivers | Shell → driver translation, Node.js/Python connection |
| 18 | MongoDB Stitch/Realm | Serverless functions, app auth, triggers |

---

## Certificate of Completion

| | |
|---|---|
| **Course** | MongoDB - The Complete Developer's Guide |
| **Instructor** | Maximilian Schwarzmüller (Academind) |
| **Completed by** | Aditya Anand |
| **Date** | May 30, 2026 |
| **Duration** | 17.5 hours · 266 lectures · 19 sections |
| **Verify** | [ude.my/UC-dbeb6484-4e31-4614-8ed6-2fe556e39378](https://ude.my/UC-dbeb6484-4e31-4614-8ed6-2fe556e39378) |

<p align="center">
  <img src="src/UC-dbeb6484-4e31-4614-8ed6-2fe556e39378.jpg" alt="Udemy Certificate of Completion" width="700"/>
</p>

---

## Table of Contents

1. [What is MongoDB?](#1-what-is-mongodb)
2. [MongoDB Ecosystem & Architecture](#2-mongodb-ecosystem--architecture)
3. [Getting Started — Server & Shell](#3-getting-started--server--shell)
4. [Data Model — Databases, Collections & Documents](#4-data-model--databases-collections--documents)
5. [BSON Data Types](#5-bson-data-types)
6. [CRUD Operations](#6-crud-operations)
7. [Query Operators & Cursors](#7-query-operators--cursors)
8. [Update Operators & Arrays](#8-update-operators--arrays)
9. [Data Modeling & Relations](#9-data-modeling--relations)
10. [Schema Validation](#10-schema-validation)
11. [Indexes & Query Performance](#11-indexes--query-performance)
12. [Aggregation Framework](#12-aggregation-framework)
13. [Geospatial Data](#13-geospatial-data)
14. [Working with Numeric Data](#14-working-with-numeric-data)
15. [Security & Authentication](#15-security--authentication)
16. [Performance, Fault Tolerance & Deployment](#16-performance-fault-tolerance--deployment)
17. [Transactions & Drivers](#17-transactions--drivers)
18. [MongoDB Compass & Data Import](#18-mongodb-compass--data-import)
19. [Practice Exercises & Real-World Projects](#19-practice-exercises--real-world-projects)
20. [Common Pitfalls & Troubleshooting](#20-common-pitfalls--troubleshooting)
21. [Quick Reference Cheat Sheet](#21-quick-reference-cheat-sheet)
22. [Resources & Source Materials](#22-resources--source-materials)

---

## 1. What is MongoDB?

**MongoDB** is a **document-oriented NoSQL database**. The name comes from **"Humongous"** — it is designed to store massive amounts of data efficiently.

| SQL Concept | MongoDB Equivalent |
|---|---|
| Database | Database |
| Table | Collection |
| Row | Document |
| Column | Field |
| Join | `$lookup` (manual) or embedded docs |
| Schema | Flexible / optional validation |

### Key Characteristics

- **Document-based** — data stored as JSON-like **BSON** documents
- **Schemaless by default** — documents in the same collection can differ in structure
- **Flexible relations** — embed related data or reference by ID (no native JOIN like SQL)
- **Horizontal scaling** — via sharding across multiple servers
- **High availability** — via replica sets with automatic failover
- **Rich query language** — filters, aggregation pipelines, text search, geospatial queries

### MongoDB vs SQL — When to Choose What

| Choose MongoDB when… | Choose SQL when… |
|---|---|
| Data structure varies or evolves frequently | Schema is stable and well-defined |
| You need flexible, nested document storage | Heavy relational joins are core to every query |
| Read patterns map to document-shaped responses | Strict ACID across many tables is mandatory |
| Horizontal scale-out is a priority | Complex transactions across rows/tables dominate |
| Prototyping speed matters | Reporting with complex JOINs is the main workload |

> MongoDB **does** support multi-document transactions (since 4.0), but modeling data to minimize cross-collection writes is still a best practice.

### How MongoDB Differs from SQL Databases

```mermaid
graph LR
    subgraph SQL["Relational (SQL)"]
        T1["Users Table"]
        T2["Orders Table"]
        T3["Products Table"]
        T1 -->|"JOIN"| T2
        T2 -->|"JOIN"| T3
    end

    subgraph Mongo["Document (MongoDB)"]
        D1["User doc<br/>+ embedded address"]
        D2["Order doc<br/>+ line items array"]
        D3["Product doc<br/>or embedded in order"]
    end
```

| Aspect | SQL | MongoDB |
|---|---|---|
| Structure | Fixed schema per table | Flexible per document |
| Relations | Foreign keys + JOINs | Embed or reference + `$lookup` |
| Scaling | Mostly vertical | Horizontal (sharding) |
| Transactions | Always multi-row | Document-level by default; multi-doc optional |
| Query language | SQL | MongoDB Query API + Aggregation |

```mermaid
graph TB
    subgraph DB["Database (e.g. shop)"]
        C1["Collection: users"]
        C2["Collection: orders"]
        C3["Collection: products"]
    end

    C1 --> D1["{ name: 'Max', age: 29 }"]
    C1 --> D2["{ name: 'Manu' }"]
    C2 --> D3["{ userId: ObjectId(...), total: 99.99 }"]
    C3 --> D4["{ title: 'Book', price: 12.99 }"]

    style DB fill:#e8f5e9
    style C1 fill:#c8e6c9
    style C2 fill:#c8e6c9
    style C3 fill:#c8e6c9
```

---

## 2. MongoDB Ecosystem & Architecture

```mermaid
graph LR
    subgraph App["Your Application"]
        FE["Frontend / SPA / Mobile"]
        BE["Backend Server"]
    end

    subgraph Access["Access Layer"]
        DRV["Drivers<br/>(Node.js, Python, Java…)"]
        SH["mongosh<br/>(Shell)"]
        CMP["MongoDB Compass<br/>(GUI)"]
    end

    subgraph Server["MongoDB Server (mongod)"]
        SE["WiredTiger<br/>Storage Engine"]
        MEM["In-Memory Cache"]
        DISK["Disk (.wt files)"]
    end

    subgraph Cloud["MongoDB Atlas (Managed)"]
        ATLAS["Cloud Hosting"]
    end

    FE --> BE
    BE --> DRV
    BE --> ATLAS
    SH --> Server
    CMP --> Server
    DRV --> Server
    SE --> MEM
    SE --> DISK

    style App fill:#e3f2fd
    style Server fill:#fff3e0
    style Cloud fill:#f3e5f5
```

### WiredTiger Storage Engine

MongoDB's default storage engine (since 3.2) handles:

| Feature | Benefit |
|---|---|
| **Compression** | Reduced disk usage |
| **Concurrency** | Simultaneous reads/writes |
| **Crash recovery** | Journal + checkpoints |
| **Memory cache** | Hot data stays in RAM |

> **Important:** Never manually edit `.wt` files while MongoDB is running — this can corrupt the database.

On disk you'll see: `collection-*.wt`, `index-*.wt`, `journal/`, `WiredTiger*`.

### Memory vs Disk Flow

```mermaid
sequenceDiagram
    participant App as Application
    participant WT as WiredTiger Engine
    participant RAM as In-Memory Cache
    participant Disk as Disk (.wt files)

    App->>WT: insertOne / find
    WT->>RAM: Read/Write in memory (fast)
    WT->>Disk: Persist to .wt files (slower)
    Note over WT,Disk: Journal logs writes first<br/>for crash recovery
```

### Full Ecosystem Map

| Tool | Purpose |
|---|---|
| **mongod** | Database server process |
| **mongosh** | Interactive JavaScript shell for queries & admin |
| **MongoDB Compass** | GUI to browse, query, and analyze data visually |
| **Drivers** | Official libraries for Node.js, Python, Java, Go, C#, etc. |
| **MongoDB Atlas** | Fully managed cloud database (backups, monitoring, scaling) |
| **Cloud Manager / Ops Manager** | Monitoring & automation for self-hosted deployments |
| **MongoDB Charts** | Built-in data visualization dashboards |
| **BI Connector** | Connect SQL-based BI tools (Tableau, Power BI) to MongoDB |
| **MongoDB Realm (Stitch)** | Serverless backend — auth, functions, triggers, sync |

### Application Architecture

```mermaid
flowchart TB
    UI["Frontend<br/>(React, Mobile)"] --> API["Backend Server<br/>(Node.js, Python…)"]
    API --> DRV["MongoDB Driver"]
    DRV --> MONGO["MongoDB Server<br/>(mongod)"]

    ADMIN["Developer"] --> SH["mongosh"]
    ADMIN --> CMP["Compass"]
    SH --> MONGO
    CMP --> MONGO

    MONGO --> ATLAS["Atlas (optional cloud)"]
```

**Rule:** Production apps should connect via **drivers** from the backend — never expose database credentials in client-side code.

## 3. Getting Started — Server & Shell

### Start the Server

```bash
# Start mongod with custom paths
mongod --dbpath ~/Developer/mongodata/data --logpath ~/Developer/mongodata/logs/log.log

# Run as background process
mongod --dbpath ~/Developer/mongodata/data --fork --logpath ~/Developer/mongodata/logs/log.log

# Custom port
mongod --port 27018
mongosh --port 27018
```

### Connect with mongosh

```bash
cd ~/Developer/mongosh-2.8.3-darwin-arm64/bin
./mongosh
```

### Essential Shell Commands

```javascript
show dbs                          // List databases
use shop                          // Switch/create database (lazy creation)
db.products.insertOne({ name: "Aditya" })
db.products.find().pretty()
db.stats()                        // Database statistics
db.dropDatabase()                 // Drop entire database
db.myCollection.drop()            // Drop a collection
```

### Graceful Shutdown

```javascript
use admin
db.shutdownServer()
```

### Configuration Options

| Option | Purpose |
|---|---|
| `--dbpath` | Where data files are stored |
| `--logpath` | Log file location |
| `--port` | Port (default: **27017**) |
| `--fork` | Run as background daemon |
| `--auth` | Enable authentication |
| `--bind_ip` | IP addresses to listen on (use `127.0.0.1` for local-only) |
| Config file | `mongod.cfg` for persistent settings |

### Sample `mongod.cfg`

```yaml
# /usr/local/etc/mongod.conf (macOS Homebrew path may vary)
storage:
  dbPath: /Users/adityaanand/Developer/mongodata/data
systemLog:
  destination: file
  path: /Users/adityaanand/Developer/mongodata/logs/log.log
  logAppend: true
net:
  port: 27017
  bindIp: 127.0.0.1
processManagement:
  fork: true
```

Start with config file:

```bash
mongod --config /path/to/mongod.cfg
```

### Shell Helpers & Admin Commands

```javascript
show dbs                    // List all databases
show collections            // Collections in current database
show users                  // Users for current database
show indexes                // Indexes on current collection
db.help()                   // Database methods
db.collection.help()        // Collection methods
db.collection.getIndexes()  // Detailed index info
db.serverStatus()           // Server health & stats
db.version()                // MongoDB version
```

### Troubleshooting Startup Issues

| Problem | Likely Cause | Fix |
|---|---|---|
| `Address already in use` | Another `mongod` on port 27017 | Kill existing process or use `--port 27018` |
| `Data directory not found` | Wrong `--dbpath` | Create directory: `mkdir -p ~/mongodata/data` |
| `Unable to lock file` | Stale lock from crash | Remove `mongod.lock` **only when mongod is stopped** |
| Permission denied on log | Log path not writable | `chmod` or fix `--logpath` directory |
| Empty `show dbs` | No documents inserted yet | Databases appear only after first write |

---

## 4. Data Model — Databases, Collections & Documents

```mermaid
graph TD
    A["Database<br/>(created lazily)"] --> B["Collection<br/>(created lazily)"]
    B --> C["Document"]
    C --> F1["_id: ObjectId() — required, unique"]
    C --> F2["Fields: key-value pairs"]
    C --> F3["Embedded documents — up to 100 levels"]
    C --> F4["Arrays — any BSON type"]
    C --> F5["Max size: 16 MB per document"]
```

### Example Document

```javascript
{
  "name": "Max",
  "age": 29,
  "isInstructor": true,
  "hobbies": ["Sports", "Cooking"],
  "address": {
    "street": "My Street 5",
    "city": "Munich"
  }
}
```

### JSON vs BSON

| JSON | BSON |
|---|---|
| Human-readable text | Binary format |
| Limited number types | Extended types (Int32, Int64, Decimal128, ObjectId, ISODate…) |
| Used in APIs | Used internally by MongoDB |
| Parsed by drivers | Efficient storage & traversal |

### The `_id` Field & ObjectId

Every document **must** have a unique `_id`. If you omit it, MongoDB auto-generates an `ObjectId`.

```javascript
// ObjectId structure: 12 bytes
// [4-byte timestamp][5-byte random][3-byte counter]
ObjectId("6a0e0729e0091e87a49e256a")

// Custom _id is allowed (must still be unique)
db.products.insertOne({ _id: "sku-001", name: "Widget" })
```

| `_id` Property | Detail |
|---|---|
| Uniqueness | Unique within the collection |
| Index | Automatically indexed (default `_id` index) |
| Immutability | Cannot change `_id` on an existing document |
| Type | Usually `ObjectId`, but any value works |

### Lazy Creation

Databases and collections are created **implicitly** on first write — you never need `CREATE DATABASE`:

```javascript
use myNewShop          // Switches context; DB not created yet
db.products.insertOne({ name: "First Product" })  // NOW shop DB + products collection exist
show dbs               // "shop" appears
```

### Dot Notation for Nested Fields

```javascript
// Query embedded fields
db.users.find({ "address.city": "Munich" })

// Query array elements
db.users.find({ "hobbies.0": "Sports" })   // first array element
db.users.find({ "tags.title": "super" })  // field inside array of objects
```

### `db.stats()` — Reading Database Statistics

```javascript
db.stats()
// Key fields:
// collections  — number of collections
// objects      — total documents across all collections
// dataSize     — logical size of documents (bytes)
// storageSize  — disk space used (includes padding)
// indexes      — total index count
// indexSize    — disk space used by indexes
// avgObjSize   — average document size
```

After dropping a collection, `objects` and `dataSize` decrease but `storageSize` may not shrink immediately (MongoDB reuses space).

---

## 5. BSON Data Types

```mermaid
mindmap
  root((BSON Types))
    Text
      String
    Numbers
      Double default
      Int32 NumberInt
      Int64 NumberLong
      Decimal128 NumberDecimal
    Other
      Boolean
      ObjectId
      ISODate
      Timestamp
      Embedded Document
      Array
      Null
      Binary
```

| Type | Example | Use Case |
|---|---|---|
| **String** | `"Max"` | Text fields |
| **Boolean** | `true` | Flags |
| **Double** | `1` or `1.5` | Default for plain numbers in shell |
| **Int32** | `NumberInt(1)` | Small integers, counters |
| **Int64** | `NumberLong(1)` | Large IDs, counts |
| **Decimal128** | `NumberDecimal("1.99")` | Financial / monetary data |
| **ObjectId** | Auto-generated `_id` | Unique document identifier |
| **ISODate** | `new Date()` | Timestamps |
| **Timestamp** | `new Timestamp()` | Internal ordering |
| **Embedded Doc** | `{ ceo: "Mark" }` | Nested objects |
| **Array** | `["Sports", "Cooking"]` | Lists of any type |

### Number Type Gotcha

```javascript
// These look the same but store different BSON types!
db.numbers.insertOne({ a: 1 })              // → Double (8 bytes)
db.numbers.insertOne({ a: NumberInt(1) })   // → Int32 (4 bytes)

// Floating-point precision issue
db.science.insertOne({ a: 0.3, b: 0.1 })
// 0.3 - 0.1 = 0.19999999999999998  ❌

// Fix with Decimal128
db.science.insertOne({ a: NumberDecimal("0.3"), b: NumberDecimal("0.1") })
// 0.3 - 0.1 = Decimal128("0.2")  ✅
```

**Rule of thumb:**
- Small counters → `NumberInt`
- Large IDs/counts → `NumberLong`
- Money/decimals → `NumberDecimal`
- Generic numbers → plain `1` (double) is fine for many apps

### Full BSON Types Reference

| Type | Shell Literal | Size | Notes |
|---|---|---|---|
| Double | `1`, `1.5` | 8 bytes | Default for plain numbers in shell |
| String | `"hello"` | Variable | UTF-8 |
| Object | `{ key: "val" }` | Variable | Embedded document |
| Array | `[1, 2, 3]` | Variable | Ordered list |
| Binary Data | `BinData(0, "...")` | Variable | Raw bytes |
| ObjectId | Auto or `ObjectId("...")` | 12 bytes | Document identifier |
| Boolean | `true`, `false` | 1 byte | |
| Date | `new Date()`, `ISODate("...")` | 8 bytes | UTC milliseconds |
| Null | `null` | — | Explicit null value |
| Regular Expression | `/pattern/` | Variable | Used in queries |
| JavaScript | `function() {}` | Variable | Stored code (rare) |
| Int32 | `NumberInt(42)` | 4 bytes | 32-bit integer |
| Timestamp | `new Timestamp()` | 8 bytes | Internal MongoDB use |
| Int64 | `NumberLong(9999999999)` | 8 bytes | 64-bit integer |
| Decimal128 | `NumberDecimal("19.99")` | 16 bytes | High-precision decimal |
| Min Key | `MinKey()` | 1 byte | Internal comparison |
| Max Key | `MaxKey()` | 1 byte | Internal comparison |

### Real-World Document with Multiple Types

```javascript
db.companies.insertOne({
  name: "Fresh Apples Inc",
  isStartup: true,
  employees: NumberInt(33),
  funding: NumberLong("12345678901234567890"),
  details: { ceo: "Mark Super" },                    // embedded doc
  tags: [{ title: "super" }, { title: "perfect" }],  // array of objects
  foundingDate: new Date(),                          // ISODate
  insertedAt: new Timestamp()                        // Timestamp
})

db.companies.findOne()
// funding may display rounded if stored as Double — use NumberLong for precision
```

### MongoDB Hard Limits

| Limit | Value |
|---|---|
| Max document size | **16 MB** |
| Max nesting depth | **100 levels** |
| Max collection name length | 120 bytes |
| Max database name length | 64 bytes |
| Max index key size | 1024 bytes |
| Max indexes per collection | 64 (default) |
| Max BSON document size for insert | 16 MB |

> Docs: [MongoDB Limits](https://www.mongodb.com/docs/manual/reference/limits/) · [BSON Types](https://www.mongodb.com/docs/manual/reference/bson-types/)

---

## 6. CRUD Operations

```mermaid
flowchart LR
    subgraph Create
        IO["insertOne()"]
        IM["insertMany()"]
    end
    subgraph Read
        F["find()"]
        FO["findOne()"]
    end
    subgraph Update
        UO["updateOne()"]
        UM["updateMany()"]
        RO["replaceOne()"]
    end
    subgraph Delete
        DO["deleteOne()"]
        DM["deleteMany()"]
    end

    APP["Application"] --> Create
    APP --> Read
    APP --> Update
    APP --> Delete
```

### Create

```javascript
// Single document
db.flightData.insertOne({
  departureAirport: "MUC",
  arrivalAirport: "SFO",
  aircraft: "Airbus A380",
  distance: 12000,
  intercontinental: true
})

// Multiple documents
db.flightData.insertMany([
  { departureAirport: "MUC", arrivalAirport: "SFO", distance: 12000 },
  { departureAirport: "LHR", arrivalAirport: "TXL", distance: 950 }
])

// Ordered vs Unordered inserts (insertMany)
db.collection.insertMany(docs, { ordered: false })  // continues on error
```

#### Ordered vs Unordered Inserts

| Mode | Behavior on Error | Use When |
|---|---|---|
| **Ordered** (default) | Stops at first failure; earlier inserts remain | Data order matters |
| **Unordered** | Continues inserting remaining docs | Bulk import where partial success is OK |

```javascript
// Duplicate _id in ordered insert → stops, returns error
db.users.insertMany([
  { _id: 1, name: "A" },
  { _id: 2, name: "B" },
  { _id: 1, name: "Duplicate" }  // fails here; doc 1 & 2 may already exist
], { ordered: true })

// Unordered → skips duplicate, inserts the rest
db.users.insertMany(docs, { ordered: false })
```

> **`insert()` is deprecated** — always use `insertOne()` or `insertMany()`.

### Import Data with mongoimport

```bash
# Import JSON array into a collection
mongoimport --db boxOffice --collection movies \
  --file movies.json --jsonArray --drop

# Import one JSON object per line (NDJSON)
mongoimport --db shop --collection products \
  --file products.ndjson

# With authentication
mongoimport --uri "mongodb://user:pass@localhost:27017/shop" \
  --collection products --file products.json --jsonArray
```

| Flag | Purpose |
|---|---|
| `--db` | Target database |
| `--collection` | Target collection |
| `--file` | Input file path |
| `--jsonArray` | File is a JSON array (not line-delimited) |
| `--drop` | Drop collection before import |
| `--upsert` | Update if exists, insert if not |

### Read

```javascript
db.flightData.find({ distance: { $gt: 800 } })
db.flightData.findOne({ distance: { $gt: 800 } })

// Cursors — find() returns a cursor, NOT an array
db.passengers.find().forEach(doc => printjson(doc))
db.passengers.find().toArray()  // loads all into memory
```

### Update

```javascript
// ✅ Preferred — use updateOne/updateMany with $set
db.flightData.updateOne(
  { _id: ObjectId("...") },
  { $set: { delayed: true } }
)

// ❌ Avoid bare update() — replaces entire document without $set
// Use replaceOne() if you intend full replacement
```

#### `updateOne` vs `updateMany` vs `replaceOne` vs deprecated `update()`

| Method | Scope | Without `$set` | Returns |
|---|---|---|---|
| `updateOne()` | First match | Error (needs operator) | `matchedCount`, `modifiedCount` |
| `updateMany()` | All matches | Error (needs operator) | `matchedCount`, `modifiedCount` |
| `replaceOne()` | First match | Replaces entire document | `matchedCount`, `modifiedCount` |
| `update()` ⚠️ | Varies | **Overwrites whole doc** | Legacy — avoid |

```javascript
// replaceOne — swap entire document (keeps _id)
db.users.replaceOne(
  { name: "Chris" },
  { name: "Chris", age: 35, role: "admin" }  // full new document
)

// Response shape (all update methods)
{
  acknowledged: true,
  matchedCount: 1,
  modifiedCount: 1,   // 0 if value unchanged
  upsertedCount: 0,
  upsertedId: null
}
```

### Delete

```javascript
db.users.deleteOne({ name: "Chris" })                     // first match only
db.users.deleteMany({ age: { $gt: 30 }, isSporty: true }) // all matches
db.users.drop()                                            // drop entire collection
db.dropDatabase()                                          // drop current database
```

> `deleteMany({})` removes all documents but keeps the collection and its indexes intact.

### Write Concern

Controls the guarantee level that data was persisted:

```javascript
db.collection.insertOne(doc, { writeConcern: { w: 1, j: true, wtimeout: 200 } })
```

| Option | Meaning |
|---|---|
| `w: 1` | Acknowledged by primary |
| `j: true` | Written to journal (durable) |
| `wtimeout` | Max wait time in ms |

```mermaid
flowchart LR
    CLIENT["Client<br/>(insertOne)"] --> SERVER["mongod"]
    SERVER --> MEM["Memory"]
    SERVER --> JOURNAL["Journal<br/>(write-ahead log)"]
    JOURNAL --> DISK["Disk"]

    WC1["w: 1<br/>Ack from primary"] --> CLIENT
    WC2["j: true<br/>Flushed to journal"] --> CLIENT
```

| writeConcern | Durability | Speed |
|---|---|---|
| `{ w: 1 }` | Acknowledged by primary | Fastest |
| `{ w: 1, j: true }` | Written to journal on disk | Safer |
| `{ w: "majority" }` | Replicated to majority of nodes | Safest (replica sets) |

### Atomicity

MongoDB CRUD operations are **atomic at the document level** — including all embedded documents within that document. Either the entire operation succeeds or nothing is saved.

---

## 7. Query Operators & Cursors

### Operator Categories

```mermaid
graph TD
    QO["Query Operators"] --> COMP["Comparison<br/>$eq $gt $gte $lt $lte $ne $in $nin"]
    QO --> LOG["Logical<br/>$and $or $nor $not"]
    QO --> ELEM["Element<br/>$exists $type"]
    QO --> EVAL["Evaluation<br/>$regex $expr $mod"]
    QO --> ARR["Array<br/>$size $all $elemMatch"]
    QO --> GEO["Geospatial<br/>$near $geoWithin"]
```

### Comparison & Logical

| Operator | Description | Example |
|---|---|---|
| `$eq` | Equal (implicit) | `{ age: 30 }` |
| `$ne` | Not equal | `{ age: { $ne: 30 } }` |
| `$gt` / `$gte` | Greater / greater-or-equal | `{ age: { $gt: 18 } }` |
| `$lt` / `$lte` | Less / less-or-equal | `{ runtime: { $lt: 60 } }` |
| `$in` | Value in array | `{ runtime: { $in: [30, 42] } }` |
| `$nin` | Value not in array | `{ status: { $nin: ["deleted"] } }` |
| `$and` | All conditions true | `{ $and: [{ a: 1 }, { b: 2 }] }` |
| `$or` | Any condition true | `{ $or: [{ a: 1 }, { b: 2 }] }` |
| `$nor` | None of conditions true | `{ $nor: [{ a: 1 }, { b: 2 }] }` |
| `$not` | Inverts operator | `{ age: { $not: { $gt: 18 } } }` |

```javascript
db.movies.find({ runtime: { $lt: 60 } })
db.movies.find({ runtime: { $in: [30, 42] } })
db.movies.find({ genres: "Drama" })           // matches if "Drama" is in array
db.movies.find({ genres: ["Drama"] })         // exact array match

db.movies.find({
  $or: [
    { "rating.average": { $lt: 5 } },
    { "rating.average": { $gt: 9.3 } }
  ]
})

db.movies.find({
  $and: [
    { "rating.average": { $gt: 9 } },
    { genres: "Drama" }
  ]
})
// Implicit $and — comma-separated fields also works:
db.movies.find({ "rating.average": { $gt: 9 }, genres: "Drama" })
```

### Element & Evaluation

| Operator | Description | Example |
|---|---|---|
| `$exists` | Field present/absent | `{ age: { $exists: true } }` |
| `$type` | BSON type check | `{ phone: { $type: "string" } }` |
| `$regex` | Pattern match | `{ name: { $regex: /^Max/i } }` |
| `$expr` | Compare fields in same doc | `{ $expr: { $gt: ["$volume", "$target"] } }` |
| `$mod` | Modulo | `{ qty: { $mod: [4, 0] } }` |

```javascript
db.users.find({ age: { $exists: true } })
db.users.find({ age: { $exists: true, $gt: 30 } })
db.users.find({ phone: { $type: "double" } })
db.users.find({ phone: { $type: ["double", "string"] } })
db.movies.find({ summary: { $regex: /musical/ } })

// Compare two fields in the same document
db.sales.find({ $expr: { $gt: ["$volume", "$target"] } })

// $expr with $cond in aggregation-style logic
db.sales.find({
  $expr: {
    $cond: {
      if: { $gte: ["$volume", 190] },
      then: { $subtract: ["$volume", 10] },
      else: "$volume"
    }
  }
})
```

### Counting Documents

```javascript
// ✅ Preferred — accurate count with filter
db.movies.countDocuments({ "rating.average": { $lt: 5 } })

// Estimated count (no filter) — very fast, approximate
db.movies.estimatedDocumentCount()

// ⚠️ cursor.count() is deprecated — use countDocuments instead
```

### Array Query Selectors

| Operator | Description | Example |
|---|---|---|
| `$size` | Exact array length | `{ hobbies: { $size: 3 } }` |
| `$all` | Array contains ALL values | `{ genres: { $all: ["Drama", "Horror"] } }` |
| `$elemMatch` | Array element matches ALL conditions | See below |

```javascript
db.users.find({ "hobbies.title": "Sports" })           // dot notation — any matching element
db.users.find({ hobbies: { $size: 3 } })             // exact array length
db.movies.find({ genres: { $all: ["Action", "Thriller"] } })
db.users.find({
  hobbies: {
    $elemMatch: { title: "Sports", frequency: { $gte: 3 } }
  }
})
```

### Projection

Control which fields are returned. **You cannot mix inclusion and exclusion** (except `_id`).

| Rule | Example |
|---|---|
| Include fields | `{ name: 1, age: 1 }` — `_id` included by default |
| Exclude `_id` | `{ name: 1, _id: 0 }` |
| Exclude fields | `{ password: 0 }` — returns everything except password |
| Cannot mix | `{ name: 1, age: 0 }` → **Error** |

```javascript
// Include only name ( _id included by default)
db.passengers.find({}, { name: 1 })

// Exclude _id
db.passengers.find({}, { name: 1, _id: 0 })

// Array projection — return matching array element
db.movies.find(
  { genres: { $all: ["Drama", "Horror"] } },
  { "genres.$": 1 }
)

// $slice — limit array elements in result
db.movies.find(
  { title: "Action Movie" },
  { ratings: { $slice: 2 } }        // first 2 elements
)
db.movies.find(
  { title: "Action Movie" },
  { ratings: { $slice: [-3, 2] } }  // skip last 3, return 2
)

// $elemMatch in projection — project matching subdocument
db.movies.find(
  { genres: { $all: ["Drama", "Horror"] } },
  { genres: { $elemMatch: { $eq: "Horror" } } }
)
```

### Cursors — Sort, Skip, Limit

```javascript
// Order matters: sort → skip → limit (MongoDB optimizes this)
db.movies.find()
  .sort({ "rating.average": 1, runtime: -1 })  // 1 = asc, -1 = desc
  .skip(100)
  .limit(10)
```

```mermaid
sequenceDiagram
    participant Client
    participant Server as MongoDB Server

    Client->>Server: find() — opens cursor
    Server-->>Client: Batch #1 (default ~101 docs)
    Client->>Server: Request next batch
    Server-->>Client: Batch #2
    Note over Client: sort(), skip(), limit()<br/>applied before fetching
```

---

## 8. Update Operators & Arrays

### Field Update Operators

| Operator | Purpose | Example |
|---|---|---|
| `$set` | Set field value | `{ $set: { age: 30 } }` |
| `$unset` | Remove field | `{ $unset: { phone: "" } }` |
| `$inc` | Increment/decrement | `{ $inc: { age: 1 } }` |
| `$min` / `$max` | Keep min/max value | `{ $min: { age: 30 } }` |
| `$mul` | Multiply | `{ $mul: { age: 2 } }` |
| `$rename` | Rename field | `{ $rename: { age: "totalAge" } }` |
| `$currentDate` | Set to current date | `{ $currentDate: { lastModified: true } }` |

```javascript
// Upsert — insert if not found
db.users.updateOne(
  { name: "Maria" },
  { $set: { age: 29, hobbies: [{ title: "Good food", frequency: 3 }] } },
  { upsert: true }
)

// ⚠️ Cannot use $inc and $set on the same field in one operation
db.users.updateOne(
  { _id: ObjectId("...") },
  { $inc: { age: 1 }, $set: { age: 30 } }  // Error: conflict at 'age'
)
```

### Array Update Operators

```javascript
// Positional $ — update matched array element
db.users.updateMany(
  { hobbies: { $elemMatch: { title: "Sports", frequency: { $gte: 3 } } } },
  { $set: { "hobbies.$.highFrequency": true } }
)

// $[] — update ALL array elements
db.users.updateMany(
  { age: { $gt: 20 } },
  { $inc: { "hobbies.$[].frequency": 1 } }
)

// $[<identifier>] + arrayFilters — update specific elements
db.users.updateMany(
  { "hobbies.frequency": { $gt: 2 } },
  { $set: { "hobbies.$[el].goodFrequency": true } },
  { arrayFilters: [{ "el.frequency": { $gt: 2 } }] }
)

// $push with modifiers
db.users.updateOne(
  { name: "Maria" },
  {
    $push: {
      hobbies: {
        $each: [{ title: "Sports", frequency: 2 }],
        $sort: { frequency: -1 },
        $slice: 1
      }
    }
  }
)

db.users.updateOne({ name: "Maria" }, { $pull: { hobbies: { title: "Sports" } } })
db.users.updateOne({ name: "Maria" }, { $addToSet: { tags: "unique-tag" } })  // no duplicates
db.users.updateOne({ name: "Maria" }, { $pop: { hobbies: 1 } })  // 1 = last, -1 = first
```

---

## 9. Data Modeling & Relations

### Design Questions

Before modeling, ask:

1. **What data** does my app need or generate?
2. **Where** do I need it (which pages/views)?
3. **How often** do I fetch vs write?
4. **How big** is the data?
5. Will **duplicates** hurt (many updates)?
6. Will I hit **16 MB / nesting limits**?

| Goal | Strategy |
|---|---|
| Fetch a lot | Store data in the format your frontend needs |
| Write a lot | Avoid duplicates and redundancy |

### Embedding vs Referencing

```mermaid
graph TD
    subgraph Embed["Embedded Documents"]
        E1["One-to-One<br/>{ user, address: {...} }"]
        E2["One-to-Many<br/>{ patient, history: [...] }"]
    end

    subgraph Ref["References"]
        R1["One-to-One<br/>{ userId: ObjectId(...) }"]
        R2["One-to-Many<br/>{ authorIds: [ObjectId(...)] }"]
        R3["Many-to-Many<br/>Separate join collection"]
    end

    subgraph Join["$lookup Aggregation"]
        L["Merge referenced data at query time"]
    end

    Ref --> Join
```

| Relationship | Embedded | Reference |
|---|---|---|
| One-to-One | ✅ Preferred | When data is shared |
| One-to-Many | ✅ If bounded size | ✅ If unbounded |
| Many-to-Many | ❌ Avoid | ✅ Use references |

### $lookup — Joining Collections

```javascript
db.books.aggregate([
  {
    $lookup: {
      from: "authors",           // target collection
      localField: "authors",     // field in books
      foreignField: "_id",         // field in authors
      as: "creators"             // output array name
    }
  }
])
```

### Relation Examples

| Example | Type | Best Approach |
|---|---|---|
| Patient ↔ Disease Summary | 1:1 | Embed |
| Person ↔ Car | 1:1 | Embed or Reference |
| Thread ↔ Answers | 1:N | Embed (if bounded) |
| City ↔ Citizens | 1:N | Reference |
| Customer ↔ Products | N:M | Reference + join collection |
| Books ↔ Authors | N:M | Reference + `$lookup` |

### To Schema or Not to Schema?

MongoDB **does not enforce** a schema — but that does not mean you should skip design:

| Without Schema Discipline | With Application Schema |
|---|---|
| `{ title: "Book", price: 12.99 }` | `{ title: "Book", price: 12.99 }` |
| `{ name: "Bottle", available: true }` ← inconsistent fields | `{ title: "Bottle", price: 5.99, available: true }` ← consistent |

Use **application-level conventions** + optional **`$jsonSchema` validation** for production.

### Pattern 1: One-to-One — Embedded

```javascript
// Address belongs exclusively to one user — embed it
db.users.insertOne({
  userName: "max",
  age: 29,
  address: { street: "Second Street", city: "New York" }
})
```

### Pattern 2: One-to-One — Reference

```javascript
// Car might be queried independently — use reference
db.persons.insertOne({ _id: ObjectId("..."), name: "Max", carId: ObjectId("...") })
db.cars.insertOne({ _id: ObjectId("..."), model: "Tesla Model 3" })
```

### Pattern 3: One-to-Many — Embedded (Bounded)

```javascript
// Patient with medical history — history stays with patient
db.patients.insertOne({
  firstName: "Max",
  lastName: "Schwarzmueller",
  age: 29,
  history: [
    { disease: "cold", treatment: "rest", date: new Date() },
    { disease: "flu", treatment: "medication", date: new Date() }
  ]
})
```

### Pattern 4: One-to-Many — Reference (Unbounded)

```javascript
// City with millions of citizens — reference, don't embed
db.cities.insertOne({ _id: ObjectId("..."), name: "New York" })
db.citizens.insertOne({ name: "Anna", cityId: ObjectId("...") })
```

### Pattern 5: Many-to-Many — References + `$lookup`

```javascript
db.authors.insertMany([
  { _id: ObjectId("6650a1a1a1a1a1a1a1a1a1a1"), name: "Max Schwarz", age: 29 },
  { _id: ObjectId("6650b2b2b2b2b2b2b2b2b2b2"), name: "Manuel Lor", age: 30 }
])

db.books.insertOne({
  name: "My Favorite Book",
  authors: [
    ObjectId("6650a1a1a1a1a1a1a1a1a1a1"),
    ObjectId("6650b2b2b2b2b2b2b2b2b2b2")
  ]
})

db.books.aggregate([
  {
    $lookup: {
      from: "authors",
      localField: "authors",
      foreignField: "_id",
      as: "authorDetails"
    }
  }
])
// Result: book doc + authorDetails: [{ name: "Max Schwarz", ... }, { name: "Manuel Lor", ... }]
```

### Example Project: Blog Application Schema

```mermaid
erDiagram
    USERS ||--o{ POSTS : creates
    POSTS ||--o{ COMMENTS : has
    USERS ||--o{ COMMENTS : writes

    USERS {
        ObjectId _id
        string email
        string passwordHash
    }
    POSTS {
        ObjectId _id
        ObjectId creator
        string title
        string text
        array comments
    }
    COMMENTS {
        ObjectId author
        string text
    }
```

```javascript
// Posts collection with embedded comments (1:N embed)
db.posts.insertOne({
  title: "Learning MongoDB",
  text: "MongoDB is awesome!",
  creator: ObjectId("6650a1a1a1a1a1a1a1a1a1a1"),
  comments: [
    { text: "Great post!", author: ObjectId("6650b2b2b2b2b2b2b2b2b2b2") }
  ],
  createdAt: new Date()
})
```

---

## 10. Schema Validation

MongoDB is schemaless by default, but you **can** enforce rules:

```javascript
db.createCollection("posts", {
  validator: {
    $jsonSchema: {
      bsonType: "object",
      required: ["title", "text", "creator", "comments"],
      properties: {
        title: { bsonType: "string", description: "must be a string" },
        text: { bsonType: "string" },
        creator: { bsonType: "objectId" },
        comments: {
          bsonType: "array",
          items: {
            bsonType: "object",
            required: ["text", "author"],
            properties: {
              text: { bsonType: "string" },
              author: { bsonType: "objectId" }
            }
          }
        }
      }
    }
  }
})
```

### Validation Levels & Actions

| Setting | Option | Behavior |
|---|---|---|
| `validationLevel: "strict"` | Default for new collections | Validates **all** inserts and updates |
| `validationLevel: "moderate"` | | Validates inserts + updates to docs **already matching** schema |
| `validationAction: "error"` | Default | Rejects invalid documents |
| `validationAction: "warn"` | | Logs warning but allows write |

```javascript
db.runCommand({
  collMod: "posts",
  validator: {
    $jsonSchema: {
      bsonType: "object",
      required: ["title", "text"],
      properties: {
        title: { bsonType: "string" },
        text: { bsonType: "string" },
        views: { bsonType: "int" }
      }
    }
  },
  validationLevel: "strict",
  validationAction: "error"
})
```

### Bypass Validation (Admin Only)

```javascript
// Skip validation for a single operation (e.g. migration script)
db.posts.insertOne(
  { title: 123 },  // invalid — title should be string
  { bypassDocumentValidation: true }
)
```

> Use sparingly — only for trusted admin migrations, never in application code.

---

## 11. Indexes & Query Performance

### Why Indexes?

Without an index, MongoDB performs a **COLLSCAN** (full collection scan). With an index, it uses **IXSCAN** (index scan) — dramatically faster for large datasets.

```mermaid
flowchart LR
    subgraph NoIndex["Without Index — COLLSCAN"]
        Q1["Query: age > 60"] --> S1["Scan ALL 5000 docs"]
        S1 --> R1["Return 1222 docs<br/>⏱ ~25ms"]
    end

    subgraph WithIndex["With Index — IXSCAN"]
        Q2["Query: age > 60"] --> S2["Scan 1222 index keys"]
        S2 --> F2["FETCH 1222 docs"]
        F2 --> R2["Return 1222 docs<br/>⏱ ~7ms"]
    end
```

### Creating Indexes

```javascript
// Single field index
db.contacts.createIndex({ "dob.age": 1 })   // 1 = ascending, -1 = descending

// Compound index (left-to-right prefix rule)
db.contacts.createIndex({ "dob.age": 1, gender: 1 })

// Unique index
db.contacts.createIndex({ email: 1 }, { unique: true })

// Partial index — smaller, only indexes matching docs
db.contacts.createIndex(
  { "dob.age": 1 },
  { partialFilterExpression: { gender: "male" } }
)

// TTL index — auto-delete after expiry
db.sessions.createIndex({ createdAt: 1 }, { expireAfterSeconds: 3600 })

// Text index
db.products.createIndex({ description: "text" })
db.products.find({ $text: { $search: "awesome t-shirt" } })

// Multi-key (array) index
db.userBehaviour.createIndex({ hobbies: 1 })  // isMultiKey: true

// Background build (non-blocking)
db.ratings.createIndex({ age: 1 }, { background: true })
```

### Index Types Summary

| Type | Example | Notes |
|---|---|---|
| Single field | `{ name: 1 }` | Basic lookup |
| Compound | `{ name: 1, age: -1 }` | Prefix rule applies |
| Multi-key | `{ hobbies: 1 }` | For array fields |
| Text | `{ description: "text" }` | Full-text search |
| Geospatial | `{ location: "2dsphere" }` | Geo queries |
| Unique | `{ email: 1 }` + unique | Enforce uniqueness |
| Partial | + partialFilterExpression | Index subset |
| TTL | + expireAfterSeconds | Auto-expire docs |

### Diagnosing Queries with explain()

```javascript
db.contacts.explain("executionStats").find({ "dob.age": { $gt: 60 } })
```

| Metric | Good Sign | Bad Sign |
|---|---|---|
| `stage` | `IXSCAN` | `COLLSCAN` |
| `totalDocsExamined` | Close to `nReturned` | Much larger than `nReturned` |
| `totalKeysExamined` | Close to `nReturned` | 0 (no index used) |
| `executionTimeMillis` | Low | High |

### Key Rules

1. **Query field must match index field exactly** — `{ "dob.age": 1 }` not `{ "db.age": 1 }`
2. **Indexes help when returning ~10–20%** of documents — if returning most docs, index may not help
3. **Compound indexes** work left-to-right — can use `{ name, age }` for `name` alone, but not `age` alone
4. **Indexes slow writes** — every insert/update must update all indexes
5. **Sorting** without an index may hit the **32 MB memory limit** and timeout
6. **Cannot index two parallel arrays** in one compound index

### Covered Queries

A query is **covered** when the index alone satisfies the query — `totalDocsExamined: 0`. MongoDB never touches the actual documents.

```javascript
db.contacts.createIndex({ name: 1, age: 1 })
db.contacts.find(
  { name: "Max", age: 30 },
  { _id: 0, name: 1, age: 1 }   // projection must match index fields exactly
)
// winningPlan: PROJECTION_COVERED, totalDocsExamined: 0
```

### Indexes Behind the Scenes (B-Tree)

Think of an index as a **sorted list of values + pointers** to documents:

```
Index on age (ascending):
(29, → doc_a1)  (30, → doc_a2)  (33, → doc_a3)  (45, → doc_a4) ...
```

Because the list is sorted, MongoDB can **skip entire ranges** instead of scanning every document — O(log n) vs O(n).

### Compound Index — Prefix Rule

```javascript
db.contacts.createIndex({ "dob.age": 1, gender: 1 })

// ✅ Uses index — leftmost prefix
db.contacts.find({ "dob.age": { $gt: 60 } })
db.contacts.find({ "dob.age": { $gt: 60 }, gender: "male" })

// ❌ Cannot use index alone — gender is second field without age
db.contacts.find({ gender: "male" })
```

Compound indexes also **accelerate sorting** on indexed fields (avoids 32 MB in-memory sort limit).

### Sparse vs Partial Indexes

| Type | Behavior | Use Case |
|---|---|---|
| **Sparse** | Only indexes docs where field exists | Optional fields (legacy) |
| **Partial** | Only indexes docs matching filter expression | Preferred — more control |

```javascript
// Partial — index only male contacts over 60
db.contacts.createIndex(
  { "dob.age": 1 },
  { partialFilterExpression: { gender: "male" } }
)

// Unique partial — allow multiple docs without email
db.contacts.createIndex(
  { email: 1 },
  { unique: true, partialFilterExpression: { email: { $exists: true } } }
)
```

### Text Index — Full Details

```javascript
// Create text index with weights and language
db.products.createIndex(
  { title: "text", description: "text" },
  { default_language: "english", weights: { title: 10, description: 1 } }
)

// Search with relevance score
db.products.find(
  { $text: { $search: "awesome t-shirt" } },
  { score: { $meta: "textScore" } }
).sort({ score: { $meta: "textScore" } })

// Exclude terms with minus
db.products.find({ $text: { $search: "awesome -t-shirt" } })

// Case-sensitive search
db.products.find({
  $text: { $search: "Red", $caseSensitive: true }
})
```

Stop words (e.g. "a", "the") are automatically excluded from text indexes.

### Index Build: Foreground vs Background

| Mode | Collection Locked? | Speed | Use |
|---|---|---|---|
| **Foreground** | Yes (blocks writes) | Faster | Dev / maintenance window |
| **Background** | No (allows reads/writes) | Slower | Production |

```javascript
db.ratings.createIndex({ age: 1 }, { background: true })
```

### Query Plan Cache & Winning Plans

MongoDB caches the **winning query plan** per query shape. The cache is cleared when:
- 1,000+ writes occur on the collection
- Indexes are added or removed
- Server restarts

```javascript
// See all considered plans including rejected ones
db.contacts.explain("allPlansExecution").find({ name: "Max", age: 30 })
```

### Real Performance Comparison (from practice)

| Metric | Before Index (COLLSCAN) | After Index (IXSCAN) |
|---|---|---|
| `stage` | `COLLSCAN` | `IXSCAN` → `FETCH` |
| `totalDocsExamined` | 5000 | 1222 |
| `totalKeysExamined` | 0 | 1222 |
| `executionTimeMillis` | ~25ms | ~7ms |

---

## 12. Aggregation Framework

The Aggregation Framework processes documents through a **pipeline** of stages. Each stage transforms the output of the previous stage.

```mermaid
flowchart LR
    IN["Collection<br/>(Input)"] --> M["$match<br/>Filter docs"]
    M --> P["$project<br/>Shape fields"]
    P --> U["$unwind<br/>Deconstruct arrays"]
    U --> G["$group<br/>Aggregate"]
    G --> S["$sort<br/>Order results"]
    S --> SK["$skip / $limit<br/>Paginate"]
    SK --> OUT["Output<br/>(or $out)"]

    style IN fill:#e8eaf6
    style OUT fill:#e8f5e9
```

### Core Stages

| Stage | Purpose | Ratio |
|---|---|---|
| `$match` | Filter documents | Like `find()` |
| `$project` | Include/exclude/transform fields | 1:1 per doc |
| `$group` | Aggregate (sum, avg, count) | n:1 |
| `$sort` | Order results | — |
| `$unwind` | Flatten arrays into separate docs | 1:n |
| `$lookup` | Join another collection | — |
| `$out` | Write results to collection | — |
| `$merge` | Merge results into existing collection | — |
| `$bucket` / `$bucketAuto` | Group into ranges | — |
| `$facet` | Multiple pipelines in parallel | — |
| `$geoNear` | Geospatial near query (must be first) | — |
| `$count` | Count documents | n:1 |
| `$limit` / `$skip` | Pagination | — |

### Accumulator Operators (used inside `$group`)

| Operator | Description |
|---|---|
| `$sum` | Sum values or count docs (`$sum: 1`) |
| `$avg` | Average |
| `$min` / `$max` | Min / max value |
| `$first` / `$last` | First / last value in group |
| `$push` | Build array of all values |
| `$addToSet` | Build array of unique values |

### Expression Operators (used inside `$project`)

| Operator | Description |
|---|---|
| `$concat` | Concatenate strings |
| `$toUpper` / `$toLower` | Case conversion |
| `$substrCP` | Substring (Unicode-safe) |
| `$strLenCP` | String length |
| `$convert` / `$toDate` / `$toDouble` | Type conversion |
| `$cond` | If/then/else |
| `$filter` | Filter array elements |
| `$slice` | Array slice |
| `$size` | Array length |

### Examples

```javascript
// Group by state, count persons
db.persons.aggregate([
  { $match: { gender: "female" } },
  { $group: { _id: { state: "$location.state" }, totalPersons: { $sum: 1 } } },
  { $sort: { totalPersons: -1 } }
])

// Transform names with $concat
db.persons.aggregate([
  {
    $project: {
      _id: 0,
      fullName: {
        $concat: [
          { $toUpper: { $substrCP: ["$name.first", 0, 1] } },
          { $substrCP: ["$name.first", 1, { $subtract: [{ $strLenCP: "$name.first" }, 1] }] },
          " ",
          "$name.last"
        ]
      }
    }
  }
])

// $unwind — one doc per array element
db.friends.aggregate([
  { $unwind: "$hobbies" },
  { $group: { _id: { age: "$age" }, allHobbies: { $addToSet: "$hobbies" } } }
])

// $filter — filter array elements
db.friends.aggregate([
  {
    $project: {
      scores: {
        $filter: {
          input: "$examScores",
          as: "item",
          cond: { $gt: ["$$item.score", 60] }
        }
      }
    }
  }
])

// $bucket — age ranges
db.persons.aggregate([
  {
    $bucket: {
      groupBy: "$dob.age",
      boundaries: [18, 30, 40, 60, 100],
      default: "Other",
      output: { numPersons: { $sum: 1 }, averageAge: { $avg: "$dob.age" } }
    }
  }
])

// Write pipeline output to new collection
db.persons.aggregate([
  { $match: { gender: "male" } },
  { $project: { _id: 0, name: { $concat: ["$name.first", " ", "$name.last"] } } },
  { $out: "transformedPersons" }
])

// $merge — upsert into existing collection
db.persons.aggregate([
  { $match: { gender: "female" } },
  { $project: { email: 1, fullName: 1 } },
  { $merge: { into: "femalePersons", whenMatched: "replace", whenNotMatched: "insert" } }
])

// Top scorer per person using $unwind + $group
db.friends.aggregate([
  { $unwind: "$examScores" },
  { $project: { _id: 1, name: 1, score: "$examScores.score" } },
  { $sort: { score: -1 } },
  { $group: { _id: "$_id", name: { $first: "$name" }, maxScore: { $max: "$score" } } },
  { $sort: { maxScore: -1 } }
])

// $geoNear — must be FIRST stage; requires 2dsphere index
db.transformedPersons.aggregate([
  {
    $geoNear: {
      near: { type: "Point", coordinates: [-18.4, -42.8] },
      maxDistance: 100000,
      query: { age: { $gt: 30 } },
      distanceField: "dist.calculated",
      spherical: true
    }
  }
])
```

### `$group` vs `$project`

| Stage | Ratio | Purpose |
|---|---|---|
| `$group` | n:1 | Combine multiple docs → one (count, sum, avg) |
| `$project` | 1:1 | Reshape fields within a single document |

### `$text` in Aggregation

`$match` with `$text` **must be the first stage** in the pipeline (requires text index):

```javascript
db.products.aggregate([
  { $match: { $text: { $search: "mongodb database" } } },
  { $project: { title: 1, score: { $meta: "textScore" } } },
  { $sort: { score: { $meta: "textScore" } } }
])
```

### Pipeline Order Matters

For `$sort`, `$skip`, `$limit` — MongoDB applies them in the optimal order automatically, but logically think: **sort → skip → limit**.

> MongoDB automatically optimizes aggregation pipelines. See [Aggregation Pipeline Optimization](https://www.mongodb.com/docs/manual/core/aggregation-pipeline-optimization/).

---

## 13. Geospatial Data

### GeoJSON Format

Coordinates are always **`[longitude, latitude]`** — not the other way around!

```javascript
db.places.insertOne({
  name: "Bangalore Udupi",
  location: {
    type: "Point",
    coordinates: [77.605253, 12.919065]  // [lng, lat]
  }
})

// Required index for geo queries
db.places.createIndex({ location: "2dsphere" })
```

### Query Operators

```javascript
// $near — find nearest points within distance (meters)
db.places.find({
  location: {
    $near: {
      $geometry: { type: "Point", coordinates: [77.604727, 12.917538] },
      $maxDistance: 1000,
      $minDistance: 10
    }
  }
})

// $geoWithin — points inside a polygon
db.places.find({
  location: {
    $geoWithin: {
      $geometry: {
        type: "Polygon",
        coordinates: [[[0, 0], [3, 6], [6, 1], [0, 0]]]
      }
    }
  }
})

// $geoIntersects — geometry overlap
db.places.find({
  location: {
    $geoIntersects: {
      $geometry: { type: "Point", coordinates: [-122.490545, 37.743500] }
    }
  }
})

// $centerSphere — within radius (radians = miles / 3963.2)
db.places.find({
  location: {
    $geoWithin: {
      $centerSphere: [[-88, 30], 10 / 3963.2]
    }
  }
})
```

```mermaid
graph TD
    GEO["Geospatial Queries"] --> NEAR["$near<br/>Nearest points"]
    GEO --> WITHIN["$geoWithin<br/>Inside area"]
    GEO --> INTERSECT["$geoIntersects<br/>Overlapping geometry"]
    GEO --> CENTER["$centerSphere<br/>Within radius"]
```

### Supported GeoJSON Types

| Type | Use | Example |
|---|---|---|
| `Point` | Single location | `{ type: "Point", coordinates: [lng, lat] }` |
| `LineString` | Route, path | `{ type: "LineString", coordinates: [[lng,lat], ...] }` |
| `Polygon` | Area, zone | `{ type: "Polygon", coordinates: [[[lng,lat], ...]] }` |
| `MultiPoint` | Multiple points | Array of points |
| `MultiPolygon` | Multiple areas | Array of polygons |

### Geospatial Index Types

| Index | Use |
|---|---|
| `2dsphere` | Earth-like sphere geometry (recommended for most apps) |
| `2d` | Flat plane (legacy, simple coordinate pairs) |

> **`$near` requires a `2dsphere` index.** Results are sorted by distance automatically.

---

## 14. Working with Numeric Data

The MongoDB shell runs on **JavaScript**, where all numbers are **64-bit floats (doubles)** by default.

| Type | Range | Precision | When to Use |
|---|---|---|---|
| **Int32** | ±2.1 billion | Exact integers | Counters, small IDs |
| **Int64** | ±9.2 quintillion | Exact integers | Large counts |
| **Double** | ±1.7 × 10³⁰⁸ | ~15 decimal digits | General numbers |
| **Decimal128** | ±10⁶¹⁴⁴ | 34 decimal digits | Money, science |

```javascript
// Demonstrate floating-point imprecision
db.science.insertOne({ a: 0.3, b: 0.1 })
db.science.aggregate([{ $project: { result: { $subtract: ["$a", "$b"] } } }])
// → 0.19999999999999998

// Fix with Decimal128
db.science.insertOne({ a: NumberDecimal("0.3"), b: NumberDecimal("0.1") })
// → Decimal128("0.2")
```

### Modeling Monetary Data (Best Practice)

```javascript
// ❌ Bad — floating point errors in financial calculations
db.orders.insertOne({ total: 0.1 + 0.2 })  // 0.30000000000000004

// ✅ Good — store as Decimal128 strings
db.orders.insertOne({
  items: [
    { name: "Book", price: NumberDecimal("12.99") },
    { name: "Pen",  price: NumberDecimal("1.50") }
  ],
  total: NumberDecimal("14.49")
})

// Aggregation with Decimal128
db.orders.aggregate([
  { $project: { totalDouble: { $toDouble: "$total" } } }  // convert for display
])
```

---

## 15. Security & Authentication

```mermaid
graph TD
    SEC["MongoDB Security"] --> AUTH["Authentication<br/>Who are you?"]
    SEC --> AUTHZ["Authorization<br/>What can you do?"]
    SEC --> TRANS["Transport Encryption<br/>TLS/SSL"]
    SEC --> REST["Encryption at Rest"]
    SEC --> AUDIT["Auditing"]
    SEC --> NET["Network Config"]

    AUTH --> RBAC["Role-Based Access Control"]
    AUTHZ --> ROLES["Built-in & Custom Roles"]
```

### Enable Authentication

```bash
mongod --auth
```

```javascript
db.createUser({
  user: "aditya",
  pwd: "password",
  roles: [{ role: "userAdminAnyDatabase", db: "admin" }]
})

// Connect with credentials
mongosh -u aditya -p password --authenticationDatabase admin
```

### Built-in Roles (Common)

| Role | Access |
|---|---|
| `read` | Read data on a database |
| `readWrite` | Read + write data |
| `dbAdmin` | Manage collections, indexes |
| `userAdmin` | Manage users |
| `readAnyDatabase` | Read all databases |
| `readWriteAnyDatabase` | Read + write all databases |
| `dbOwner` | Full control of a database |
| `root` | Superuser |

### Authentication vs Authorization

| | Authentication | Authorization |
|---|---|---|
| Question | **Who** are you? | **What** can you do? |
| Analogy | Employee badge to enter office | Accountant can process orders, not manage servers |
| MongoDB | Login with username + password | Roles define allowed actions |

### Users, Databases & Roles

```mermaid
graph TD
    ADMIN["admin DB<br/>Global users & roles"]
    SHOP["shop DB<br/>App data"]
    BLOG["blog DB<br/>App data"]

    U1["User: appDev<br/>auth DB: shop<br/>role: readWrite on shop"]
    U2["User: dbAdmin<br/>auth DB: admin<br/>role: userAdminAnyDatabase"]

    U1 --> SHOP
    U2 --> ADMIN
```

- Users authenticate against the **database they were created on**
- Roles grant privileges on specific databases (or `AnyDatabase` variants)
- Users have **no permissions by default** until roles are assigned

### Role Categories

| Category | Examples | Typical User |
|---|---|---|
| **Database User** | `read`, `readWrite` | Application, developer |
| **Database Admin** | `dbAdmin`, `userAdmin`, `dbOwner` | DBA |
| **Cluster Admin** | `clusterAdmin`, `clusterManager` | Infrastructure team |
| **All Databases** | `readAnyDatabase`, `readWriteAnyDatabase` | Cross-DB analytics |
| **Superuser** | `root` | Emergency admin only |

### TLS/SSL Transport Encryption

```bash
# Generate self-signed cert (development only)
openssl req -x509 -newkey rsa:4096 \
  -keyout key.pem -out cert.pem -sha256 -days 3650 -nodes \
  -subj "/CN=localhost"

# Start mongod with SSL
mongod --sslMode requireSSL --sslPEMKeyFile cert.pem

# Connect with SSL
mongosh --ssl --sslCAFile cert.pem --host localhost
```

> Production: use certificates from a trusted **Certificate Authority**, not self-signed.

### User Management Commands

```javascript
db.getUsers()                          // List users
db.updateUser("aditya", { pwd: "newPassword" })
db.dropUser("aditya")                 // Remove user
db.grantRolesToUser("dev", [{ role: "readWrite", db: "shop" }])
db.revokeRolesFromUser("dev", [{ role: "readWrite", db: "shop" }])
```

### Security Checklist

- [ ] Enable authentication (`--auth`)
- [ ] Use TLS/SSL for transport encryption
- [ ] Enable encryption at rest (Enterprise)
- [ ] Configure network access (firewall, bind IP)
- [ ] Regular backups
- [ ] Keep MongoDB updated
- [ ] Use role-based access (principle of least privilege)
- [ ] Never expose credentials in client-side code

---

## 16. Performance, Fault Tolerance & Deployment

### What Influences Performance?

```mermaid
graph TD
    PERF["Performance"] --> IDX["Proper Indexes"]
    PERF --> Q["Efficient Queries"]
    PERF --> SCHEMA["Fitting Data Schema"]
    PERF --> HW["Hardware & Network"]
    PERF --> RS["Replica Sets"]
    PERF --> SH["Sharding"]
```

### Capped Collections

Fixed-size collections that auto-evict oldest documents (like a circular buffer):

```javascript
db.createCollection("logs", { capped: true, size: 10000, max: 100 })
```

### Replica Sets — High Availability

```mermaid
graph TD
    CLIENT["Client / Driver"] --> PRIMARY["Primary Node<br/>(Read + Write)"]
    PRIMARY -->|"Async Replication"| SEC1["Secondary Node"]
    PRIMARY -->|"Async Replication"| SEC2["Secondary Node"]

    PRIMARY -.->|"Node fails"| ELECT["Automatic Failover"]
    ELECT --> NEW["New Primary Elected"]
```

**Benefits:**
- **Fault tolerance** — automatic failover
- **Backup** — secondary nodes hold copies
- **Read scaling** — read from secondaries with read preference

### Read Preference (Replica Sets)

| Mode | Reads From | Use Case |
|---|---|---|
| `primary` | Primary only (default) | Strong consistency |
| `primaryPreferred` | Primary, fallback secondary | High availability reads |
| `secondary` | Secondaries only | Analytics / reporting |
| `secondaryPreferred` | Secondary, fallback primary | Load distribution |
| `nearest` | Lowest latency node | Geo-distributed apps |

### Capped Collections — Details

```javascript
db.createCollection("logs", { capped: true, size: 10000, max: 3 })
db.logs.insertOne({ name: "Event 1" })
db.logs.find().sort({ $natural: -1 })  // newest first
// When max (3) or size (10000 bytes) exceeded → oldest docs auto-removed
```

### Self-Managed Deployment Checklist

```mermaid
graph TD
    DEPLOY["Production Deployment"] --> SEC["Enable auth + TLS"]
    DEPLOY --> NET["Firewall + bind_ip"]
    DEPLOY --> RS["Replica set (≥3 nodes)"]
    DEPLOY --> BACK["Automated backups"]
    DEPLOY --> MON["Monitoring & alerts"]
    DEPLOY --> UPD["Regular version updates"]
    DEPLOY --> ATLAS["Or: use MongoDB Atlas"]
```

| Task | Self-Managed | Atlas |
|---|---|---|
| Server provisioning | You | Managed |
| Backups | You configure | Automatic |
| Scaling | Manual sharding setup | Click to scale |
| Monitoring | Cloud Manager / DIY | Built-in |
| SSL certificates | You manage | Included |
| Cost model | Infrastructure cost | Usage-based |

---

### Sharding — Horizontal Scaling

```mermaid
graph TD
    CLIENT["Client"] --> ROUTER["mongos<br/>(Router)"]
    ROUTER --> S1["Shard 1<br/>(Shard Key A-M)"]
    ROUTER --> S2["Shard 2<br/>(Shard Key N-Z)"]
    ROUTER --> S3["Shard 3<br/>(Shard Key …)"]

    NOTE["Queries WITH shard key → direct to shard<br/>Queries WITHOUT shard key → broadcast to ALL shards"]
```

| Feature | Replica Set | Sharding |
|---|---|---|
| Purpose | High availability | Horizontal scaling |
| Data | Replicated (copies) | Distributed (split) |
| Writes | Single primary | Distributed |
| Reads | Primary + secondaries | Across shards |

**Choosing a shard key:** Pick a field with high cardinality and even distribution — bad keys cause hot shards.

---

## 17. Transactions & Drivers

### Transactions (Multi-Document ACID)

```javascript
const session = db.getMongo().startSession()
session.startTransaction()
try {
  db.users.deleteOne({ _id: userId }, { session })
  db.posts.deleteMany({ authorId: userId }, { session })
  session.commitTransaction()
} catch (error) {
  session.abortTransaction()
} finally {
  session.endSession()
}
```

Use when related documents across collections **must succeed or fail together**.

**Requirements for transactions:**
- MongoDB **4.0+** for replica sets, **4.2+** for sharded clusters
- Storage engine must be **WiredTiger**
- Collections involved must be in the **same database** (historical constraint; check current docs for your version)

### Node.js Driver Example

```javascript
// npm install mongodb
const { MongoClient, ObjectId } = require("mongodb")

const uri = "mongodb://localhost:27017"
const client = new MongoClient(uri)

async function run() {
  await client.connect()
  const db = client.db("shop")
  const products = db.collection("products")

  // Insert
  const result = await products.insertOne({ name: "Widget", price: 9.99 })
  console.log(result.insertedId)

  // Find
  const docs = await products.find({ price: { $gt: 5 } }).toArray()

  // Update
  await products.updateOne(
    { _id: result.insertedId },
    { $set: { price: 12.99 } }
  )

  // Aggregation
  const stats = await products.aggregate([
    { $group: { _id: null, avgPrice: { $avg: "$price" } } }
  ]).toArray()

  await client.close()
}
run()
```

### Shell → Driver Translation

| mongosh | Node.js Driver |
|---|---|
| `db.col.find({ age: { $gt: 18 } })` | `collection.find({ age: { $gt: 18 } })` |
| `db.col.findOne({ _id: id })` | `collection.findOne({ _id: id })` |
| `db.col.insertOne(doc)` | `collection.insertOne(doc)` |
| `db.col.updateOne(f, u)` | `collection.updateOne(f, u)` |
| `db.col.deleteMany(f)` | `collection.deleteMany(f)` |
| `db.col.aggregate([...])` | `collection.aggregate([...]).toArray()` |
| `ObjectId("...")` | `new ObjectId("...")` |

### MongoDB Stitch / Realm

MongoDB Stitch is now **MongoDB Realm** — a serverless platform providing:

| Feature | Description |
|---|---|
| **App Authentication** | Email/password, OAuth — for **your app users**, not DB users |
| **Serverless Functions** | Run JavaScript in the cloud |
| **Database Triggers** | React to insert/update/delete events |
| **GraphQL / Query API** | Client-side data access without a custom backend |
| **Real-time Sync** | MongoDB Mobile ↔ Atlas sync |

### Stitch Auth vs MongoDB Auth

| | Stitch/Realm Auth | MongoDB DB Auth |
|---|---|---|
| Users | Application end-users | Database administrators / app backend |
| Credentials in client | Safe (Stitch manages tokens) | **Never** expose in frontend |
| Permissions | Fine-grained rules per collection | Role-based (read, readWrite, etc.) |
| Use in | SPAs, mobile apps | Backend servers, mongosh |

```javascript
// Realm auth listener (React example concept)
Stitch.defaultAppClient.auth.addAuthListener(auth => {
  setIsLoggedIn(auth.isLoggedIn)
})
```

---

## 18. MongoDB Compass & Data Import

### MongoDB Compass

**Compass** is the official GUI for visually exploring MongoDB:

| Feature | What You Can Do |
|---|---|
| **Browse** | Navigate databases, collections, documents |
| **Query** | Build filters with a visual query builder |
| **Analyze** | View schema, field types, index usage |
| **Aggregate** | Build aggregation pipelines visually |
| **Indexes** | Create and manage indexes |
| **Performance** | Explain plan visualization |

Download: [MongoDB Compass](https://www.mongodb.com/products/compass)

```mermaid
flowchart LR
    DEV["Developer"] --> COMP["Compass GUI"]
    DEV --> SH["mongosh CLI"]
    COMP --> MONGO["MongoDB Server"]
    SH --> MONGO
    APP["Production App"] --> DRV["Driver only"]
    DRV --> MONGO
```

> Use Compass for **development and debugging** — production apps use drivers.

### Import Workflow (Compass + mongoimport)

```bash
# 1. Import course dataset
mongoimport --db boxOffice --collection movies \
  --file movies.json --jsonArray --drop

# 2. Verify in mongosh
use boxOffice
db.movies.countDocuments()
db.movies.findOne()

# 3. Or open Compass → Connect → browse boxOffice.movies
```

---

## 19. Practice Exercises & Real-World Projects

These exercises mirror the course assignments. Complete them in `mongosh` to solidify your skills.

### Exercise 1: Flight Data (CRUD Basics)

```javascript
use airline

db.flightData.insertMany([
  { departureAirport: "MUC", arrivalAirport: "SFO", aircraft: "Airbus A380", distance: 12000, intercontinental: true },
  { departureAirport: "LHR", arrivalAirport: "TXL", aircraft: "Airbus A320", distance: 950, intercontinental: false }
])

// READ — flights over 800km
db.flightData.find({ distance: { $gt: 800 } })

// UPDATE — mark a flight delayed
db.flightData.updateOne(
  { departureAirport: "LHR" },
  { $set: { delayed: true } }
)

// DELETE — remove marked flights
db.flightData.deleteMany({ marker: "delete" })
```

### Exercise 2: Patient Records (Embedded Documents)

```javascript
use hospital

// 1. Insert 3 patients with at least 1 history entry each
db.patients.insertMany([
  { firstName: "Max", lastName: "S", age: 29, history: [{ disease: "cold", treatment: "rest" }] },
  { firstName: "Anna", lastName: "K", age: 35, history: [{ disease: "flu", treatment: "meds" }] },
  { firstName: "Tom", lastName: "B", age: 42, history: [{ disease: "cold", treatment: "rest" }] }
])

// 2. Update one patient — new age, name, history entry
db.patients.updateOne(
  { firstName: "Max" },
  { $set: { age: 30, lastName: "Schwarz" }, $push: { history: { disease: "allergy", treatment: "antihistamine" } } }
)

// 3. Find patients older than 30
db.patients.find({ age: { $gt: 30 } })

// 4. Delete patients who had a cold
db.patients.deleteMany({ "history.disease": "cold" })
```

### Exercise 3: Movie Database (Query Operators)

```javascript
// After importing boxOffice data:
db.movies.find({ "rating.average": { $gt: 9.2 }, runtime: { $lt: 100 } })
db.movies.find({ genres: { $in: ["Drama", "Action"] } })
db.movies.find({ genres: { $size: 2 } })
db.movies.find({ "rating.average": { $gt: 8, $lt: 10 } })
db.movies.find({ $expr: { $gt: ["$visitors", "$expectedVisitors"] } })
```

### Exercise 4: Sports Collection (Update Operators)

```javascript
use sports

// Upsert two sports documents
db.sports.updateOne({ title: "Soccer" }, { $set: { requiresTeam: true, minPlayers: 11 } }, { upsert: true })
db.sports.updateOne({ title: "Tennis" }, { $set: { requiresTeam: false } }, { upsert: true })

// Increase minPlayers by 10 for team sports
db.sports.updateMany({ requiresTeam: true }, { $inc: { minPlayers: 10 } })
```

### Exercise 5: Geospatial (Google Maps)

```javascript
use geoPractice

// 1. Store 3 points from Google Maps
db.places.insertMany([
  { name: "Place A", location: { type: "Point", coordinates: [77.605, 12.919] } },
  { name: "Place B", location: { type: "Point", coordinates: [77.610, 12.925] } },
  { name: "Place C", location: { type: "Point", coordinates: [77.590, 12.910] } }
])
db.places.createIndex({ location: "2dsphere" })

// 2. Find nearest within 1000m
db.places.find({ location: { $near: { $geometry: { type: "Point", coordinates: [77.604, 12.917] }, $maxDistance: 1000 } } })
```

---

## 20. Common Pitfalls & Troubleshooting

| Pitfall | Wrong | Correct |
|---|---|---|
| Using `update()` without `$set` | Replaces entire document | Use `updateOne()` + `$set` |
| Treating `find()` result as array | `const docs = db.col.find()` | Use `.toArray()` or `.forEach()` |
| Mixing projection include/exclude | `{ name: 1, age: 0 }` | Include **or** exclude, not both |
| Geo coordinates order | `[latitude, longitude]` | `[longitude, latitude]` |
| Plain numbers for money | `{ price: 0.1 + 0.2 }` | `NumberDecimal("0.30")` |
| Index field mismatch | Index `{ "db.age": 1 }`, query `{ "dob.age": ... }` | Field names must match exactly |
| `$inc` + `$set` on same field | Conflict error | Use one operator per field |
| Deprecated `count()` | `cursor.count()` | `countDocuments()` |
| Auth database confusion | Login against wrong DB | Use `--authenticationDatabase` matching user creation DB |
| Editing `.wt` files manually | Database corruption | Stop mongod first; use official tools |

### `find()` vs `findOne()` vs Cursor

```javascript
db.col.find({ age: { $gt: 18 } })      // → Cursor (lazy, batched)
db.col.findOne({ age: { $gt: 18 } })  // → Single document (or null)
db.col.find().pretty()                // → Pretty-print cursor (not for findOne)
db.col.find().toArray()               // → Full array in memory (use carefully on large sets)
```

### Reset Database Environment

```bash
# Stop mongod (Ctrl+C or db.shutdownServer())
# Delete data directory to start fresh
rm -rf ~/Developer/mongodata/data/*
mongod --dbpath ~/Developer/mongodata/data --logpath ~/Developer/mongodata/logs/log.log
```

---

## 21. Quick Reference Cheat Sheet

### CRUD at a Glance

```javascript
// CREATE
db.col.insertOne({ ... })
db.col.insertMany([{ ... }, { ... }])

// READ
db.col.find({ filter })
db.col.findOne({ filter })
db.col.find({}, { field: 1, _id: 0 })   // projection

// UPDATE
db.col.updateOne({ filter }, { $set: { ... } })
db.col.updateMany({ filter }, { $inc: { count: 1 } })
db.col.replaceOne({ filter }, { ... })     // full replace

// DELETE
db.col.deleteOne({ filter })
db.col.deleteMany({ filter })
```

### Most-Used Query Operators

| Operator | Meaning |
|---|---|
| `$eq`, `$ne` | Equal / not equal |
| `$gt`, `$gte`, `$lt`, `$lte` | Comparisons |
| `$in`, `$nin` | In / not in array |
| `$and`, `$or`, `$not`, `$nor` | Logical |
| `$exists`, `$type` | Field checks |
| `$regex` | Pattern match |
| `$expr` | Compare fields |
| `$size`, `$all`, `$elemMatch` | Array queries |

### Most-Used Update Operators

| Operator | Meaning |
|---|---|
| `$set` / `$unset` | Set / remove field |
| `$inc` | Increment |
| `$push` / `$pull` | Add / remove from array |
| `$addToSet` | Add unique to array |
| `$pop` | Remove first/last from array |
| `$rename` | Rename field |
| `$min` / `$max` | Conditional update |

### Aggregation Stage Quick Pick

| Need | Stage |
|---|---|
| Filter | `$match` |
| Reshape fields | `$project` |
| Count / sum / avg | `$group` |
| Flatten arrays | `$unwind` |
| Join collections | `$lookup` |
| Sort / paginate | `$sort`, `$skip`, `$limit` |
| Save results | `$out` or `$merge` |

### Index Quick Reference

```javascript
db.col.createIndex({ field: 1 })                          // ascending
db.col.createIndex({ a: 1, b: -1 })                        // compound
db.col.createIndex({ email: 1 }, { unique: true })          // unique
db.col.createIndex({ createdAt: 1 }, { expireAfterSeconds: 3600 })  // TTL
db.col.createIndex({ description: "text" })                 // text search
db.col.createIndex({ location: "2dsphere" })                // geospatial
db.col.explain("executionStats").find({ field: value })     // diagnose query
```

---

## 22. Resources & Source Materials

### Repository Contents

| File | Description |
|---|---|
| [`src/slides.pdf`](src/slides.pdf) | Full course slide deck (144 pages) |
| [`src/Mongodb Go to mongsh….pdf`](src/) | Hands-on practice notes & shell commands |
| [`src/NotebookLM Mind Map.png`](src/NotebookLM%20Mind%20Map.png) | Visual mind map of all topics |
| [`src/UC-dbeb6484….jpg`](src/UC-dbeb6484-4e31-4614-8ed6-2fe556e39378.jpg) | Course completion certificate |

### Official Documentation

- [MongoDB Manual](https://www.mongodb.com/docs/manual/)
- [BSON Types](https://www.mongodb.com/docs/manual/reference/bson-types/)
- [MongoDB Limits](https://www.mongodb.com/docs/manual/reference/limits/)
- [Query Operators](https://www.mongodb.com/docs/manual/reference/operator/query/)
- [Aggregation Pipeline](https://www.mongodb.com/docs/manual/core/aggregation-pipeline/)
- [Indexes](https://www.mongodb.com/docs/manual/indexes/)
- [Schema Validation](https://www.mongodb.com/docs/manual/core/schema-validation/)
- [Geospatial Queries](https://www.mongodb.com/docs/manual/geospatial-queries/)
- [Security Checklist](https://www.mongodb.com/docs/manual/administration/security-checklist/)
- [Transactions](https://www.mongodb.com/docs/manual/core/transactions/)
- [Replica Sets](https://www.mongodb.com/docs/manual/replication/)
- [Sharding](https://www.mongodb.com/docs/manual/sharding/)

### Course

- **MongoDB - The Complete Developer's Guide** by Maximilian Schwarzmüller
- [Udemy Course Link](https://www.udemy.com/course/mongodb-the-complete-developers-guide/)

---

## Course Mind Map Overview

<p align="center">
  <img src="src/NotebookLM%20Mind%20Map.png" alt="MongoDB Mind Map" width="800"/>
</p>

---

<p align="center">
  <strong>Built with ☕ by Aditya Anand</strong><br/>
  <em>Notes from MongoDB - The Complete Developer's Guide (Udemy) · May 2026</em>
</p>
