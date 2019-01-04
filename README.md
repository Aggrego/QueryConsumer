[![License](https://poser.pugx.org/aggrego/query-consumer/license.svg)](https://packagist.org/packages/aggrego/query-consumer)
[![Latest Stable Version](https://poser.pugx.org/aggrego/query-consumer/v/stable.svg)](https://packagist.org/packages/aggrego/query-consumer)
[![Total Downloads](https://poser.pugx.org/aggrego/query-consumer/downloads.svg)](https://packagist.org/packages/aggrego/query-consumer)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/aggrego/queryconsumer/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/aggrego/queryconsumer/?branch=master)
[![Travis](https://travis-ci.org/Aggrego/QueryConsumer.svg?branch=master)](https://travis-ci.org/Aggrego/QueryConsumer/builds)

# QueryConsumer

Base interface for any integration cooperates with queries.

### Assumptions

Query:

* need to be versioned
* need to return `Response`

Response:
* suggest that depends on implemented `Query` type, should follow rules for `CQRS`. Mostly relied [source](https://stackoverflow.com/a/43493623/1584408). 

## Versioning
 
Staring version ``1.0.0``, will follow [Semantic Versioning v2.0.0](http://semver.org/spec/v2.0.0.html).

## Contributors

* Tomasz Kunicki [TimiTao](http://github.com/timiTao) [lead developer]