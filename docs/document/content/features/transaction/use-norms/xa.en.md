+++
title = "XA"
weight = 2
+++

## Supported

* Support cross-database transactions after sharding;
* Operation atomicity and high data consistency in 2PC transactions;
* When service is down and restarted, commit and rollback transactions can be recovered automatically;
* Support use XA and non-XA connection pool together.

## Unsupported

* Recover committing and rolling back in other machines after the service is down.
