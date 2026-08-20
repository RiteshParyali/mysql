[![Backers on Open Collective](https://opencollective.com/node-db-migrate/backers/badge.svg)](#backers) [![Sponsors on Open Collective](https://opencollective.com/node-db-migrate/sponsors/badge.svg)](#sponsors)
[![Build Status](https://github.com/db-migrate/mysql/actions/workflows/ci.yml/badge.svg?branch=master)](https://github.com/db-migrate/mysql/actions/workflows/ci.yml)
[![Documentation Status](https://readthedocs.org/projects/db-migrate/badge/?version=latest)](https://readthedocs.org/projects/db-migrate/?badge=latest)

# db-migrate-mysql

MySQL driver for the [db-migrate](https://github.com/db-migrate/node-db-migrate) database migration framework.

This driver uses [`mysql2`](https://www.npmjs.com/package/mysql2) under the hood to connect and interact with MySQL databases.

## Installation

You can install this driver alongside `db-migrate`:

**Using npm:**

```bash
npm install db-migrate db-migrate-mysql
```

**Using yarn:**

```bash
yarn add db-migrate db-migrate-mysql
```

If you use `db-migrate` globally, you should also install the driver globally:

```bash
npm install -g db-migrate db-migrate-mysql
# or using yarn global
yarn global add db-migrate db-migrate-mysql
```
