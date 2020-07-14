# Diff Data Miner

[![Downloads total](https://img.shields.io/packagist/dt/migrify/diff-data-miner.svg?style=flat-square)](https://packagist.org/packages/migrify/diff-data-miner/stats)

Get hidden valuable data from GitHub pull-request diff and feed it to Rector

## Install

```bash
composer require migrify/diff-data-miner --dev
```

## Usage

```bash
vendor/bin/diff-data-miner extract-class-changes path-to-file.diff
```

```bash
vendor/bin/diff-data-miner extract-default-value-changes path-to-file.diff
```
