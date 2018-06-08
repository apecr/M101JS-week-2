# Query and Projection Operators

- [Query and projection Operators][1]

## Query Selectors

### Comparison

| Name        | Description           |
| ------------- |-------------| 
| $eq      | Matches values that are equal to a specified value. | 
| $gt	 |   Matches values that are greater than a specified value.     | 
| $gte |	Matches values that are greater than or equal to a specified value.     | 
|$in	 |   Matches any of the values specified in an array.|
|$lt	 |   Matches values that are less than a specified value.|
| $lte |	Matches values that are less than or equal to a specified value. |
|$ne	 |   Matches all values that are not equal to a specified value.|
|$nin |	Matches none of the values specified in an array.|


### Element

| Name        | Description           |
| ------------- |-------------| 
|$exists	|Matches documents that have the specified field.|
|$type	|Selects documents if a field is of the specified type.|


[1]: https://docs.mongodb.com/manual/reference/operator/query/