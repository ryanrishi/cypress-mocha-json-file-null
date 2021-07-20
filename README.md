cypress-mocha-json-file-null
===

This repository reproduces an error where the Cypress test results do not include a `file` property,
introduced in Mocha [v7.2.0](https://github.com/mochajs/mocha/commit/9c965c910e54d588abee688da813cc0a014c6b49).

Each test in `report.json` should have a `file` attribute.

