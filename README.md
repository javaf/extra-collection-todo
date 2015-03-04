# java-collection-util

Collections are very important data types in any programming language. They store
**data**. We use collections to *organize* and *operate* with data. These things
are so very fundamental to all of our programs. Java does provide a lot a basic
functionality with collections, but they aren't enough. Nothing might ever be enough.
Yet some more collection related operations are becoming quite common and hence are
being added here in a separate class. More functionality will be added as per need.


## Examples


## Reference

| `class Coll` |    |
|------------- |----|
| **map** <br/> `(arr)`                                                                                                         | converts an array of key, value pairs to map <br/> `Map map = Coll.map(new Object[]{"a", 1, "b", 2});` |
| **list** <br/> `(arr)`                                                                                                        | converts an array of values to list <br/> `List list = Coll.list(new Object[]{1, 2, 3, 4});` |
| **addToListMap** <br/> `(map, key, val)`                                                                                      | add a value to a list-map (values with similar keys exist) <br/> `Coll.addToListMap(map, "username", "alpha");` |
| **toString** <br/> `(coll, format, separator)`                                                                                | converts a collection to a string format (use \\(item) for each item) <br/> `Coll.toString(list, "\\(item) = @\\(item)", " AND ");` |
