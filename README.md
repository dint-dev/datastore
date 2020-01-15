[![Pub Package](https://img.shields.io/pub/v/database.svg)](https://pub.dartlang.org/packages/database)
[![Github Actions CI](https://github.com/dint-dev/database/workflows/Dart%20CI/badge.svg)](https://github.com/dint-dev/database/actions?query=workflow%3A%22Dart+CI%22)

# Overview

This is a database API for [Dart](https://dart.dev) / [Flutter](https://flutter.io) applications.

The package aims to be usable with:
  * __SQL databases__
  * __Document databases__
  * __Search engines__

## Packages in this repository
  * [database](database) ([Pub](https://pub.dev/packages/database))
  * [database_adapter_algolia](adapters/algolia) ([Pub](https://pub.dev/packages/database_adapter_algolia))
  * [database_adapter_elasticsearch](adapters/elasticsearch) ([Pub](https://pub.dev/packages/database_adapter_elasticsearch))
  * [database_adapter_firestore_browser](adapters/firestore_browser) ([Pub](https://pub.dev/packages/database_adapter_firestore_browser))
  * [database_adapter_firestore_flutter](adapters/firestore_flutter) ([Pub](https://pub.dev/packages/database_adapter_firestore_flutter))
  * [database_adapter_postgre](adapters/postgre) ([Pub](https://pub.dev/packages/database_adapter_postgre))
  * [search](search) ([Pub](https://pub.dev/packages/search))

# Getting started
Go to the [documentation](database).

# Contributing
## Setting test secrets
Create `SECRETS.env` in the root of your fork.

It should look like:
```
export TEST_GOOGLE_FIREBASE_ID=your app ID
export TEST_GOOGLE_FIREBASE_SECRET=your API key
```