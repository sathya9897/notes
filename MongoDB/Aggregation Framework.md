# MongoDB Aggregation Framework

```
course: M121
provider: MongoDB University
```

## Overview

- Aggregation is a pipeline that may have one or more stages. The framework provides many stages to filter and transform data as we like.
- The syntax of aggregate is `db.collectionName.aggregate([{ stage1: {} },{ stage2: {} }])`. The `aggregate` function takes an array of stage objects and within that object the key will be aggregation operator like `$match`, `$project`, etc.
- variable reference and their syntax

```
Field Path / access value of a field: "$fieldName"
System Variable: "$$CURRENT" -> refers to current document
User Variable: "$$foo"
```

## $match operator

- Allows to filter document and it should be used in early stages of aggregation to filter out outliers, etc
-
