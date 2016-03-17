# Akeneo PIM extension starter

[Experimental] Starter kit to quickly setup your own Akeneo PIM Extension

[![Build Status](https://travis-ci.org/akeneo-labs/ExtensionStarter.svg?branch=master)](https://travis-ci.org/akeneo-labs/ExtensionStarter)

## Requirements

| ExtensionStarter | Akeneo PIM Community Edition |
|:----------------:|:----------------------------:|
| v0.1.*           | v1.5.*                       |

## Installation

Add the following dependency to your Akeneo PIM project with this shell command:

```
composer require "akeneo-labs/extension-starter" "0.1.0";
```

Register your new bundle in your AppKernel.php,

```
$bundles = [
    new Acme\Bundle\DemoExtensionBundle\AcmeDemoExtensionBundle(),
];
```