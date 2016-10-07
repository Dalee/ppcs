# Proxima Portal PHP Code Style

## Install

```bash
composer require --dev dalee/ppcs:dev-master
```

## Usage

To extend the ruleset create your own `ruleset.xml`:

```xml
<?xml version="1.0"?>
<ruleset name="MyStandard">
    <description>Coding standard based on PPCS with some additions.</description>
    <rule ref="./vendor/dalee/ppcs/ruleset.xml" />
</ruleset>
```
