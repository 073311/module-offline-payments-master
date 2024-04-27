﻿# Offline Payments app for ievtds

[![Tests](https://github.com/ievtds/module-offline-payments/workflows/Tests/badge.svg?label=tests)](https://github.com/ievtds/module-offline-payments/actions)

## Tests

The workflow runs both [ievtds](https://github.com/ievtds/ievtds/tree/master/tests) and module test suites. They're configured to run once per week and triggered manually. Therefore, **before** publishing a new release, run the workflow [manually](https://github.com/ievtds/module-offline-payments/actions?query=workflow%3ATests) and make sure it passes.

## Translations

[Crowdin](https://crowdin.com/project/ievtds-apps) is the home of translators and it's synced (download & upload) with GitHub. The workflow is configured to run once per week and triggered manually. Therefore, **before** publishing a new release, run the workflow [manually](https://github.com/ievtds/module-offline-payments/actions?query=workflow%3ATranslations) and merge the automatically created PR, if available. Finally, all language files must be listed in the [config](https://github.com/ievtds/module-offline-payments/blob/master/crowdin.yml) file.
