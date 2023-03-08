# Reading Notes

## Code 301 - Intermediate Software Development

## Readings: APIs

[API Design Best Practices](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design)

- What does REST stand for?
  - REST stands for Representational State Transfer
- REST APIs are designed around a ____.
  - Resource
- What is an identifier of a resource? Give an example.
  - A resource has an identifier, which is a URI that uniquely identifies that resource
- What are the most common HTTP verbs?
  - The most common operations are GET, POST, PUT, PATCH, and DELETE.
- What should the URIs be based on?
  - URIs should be based on nouns (the resource) and not verbs (the operations on the resource).
- Give an example of a good URI.
  - 
- What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
  - Try to avoid "chatty" web APIs that expose a large number of small resources.
- What status code does a successful GET request return?
  - A successful GET method typically returns HTTP status code 200 (OK).
- What status code does an unsuccessful GET request return?
  - If the resource cannot be found, the method should return 404 (Not Found).
- What status code does a successful POST request return?
  - If a POST method creates a new resource, it returns HTTP status code 201 (Created).
- What status code does a successful DELETE request return?
  - 

### Bookmark and Review

[RegExr - Pay particular attention to the cheatsheet](https://regexr.com/)
[Regex Tutorial](https://medium.com/factory-mind/regex-tutorial-a-simple-cheatsheet-by-examples-649dc1c3f285)
[Regex 101](https://regex101.com/)