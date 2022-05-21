# Introduction
We will take a REST API plugin as an example for understanding plugin development for FinDesk

## Core Concepts
 FinDesk uses Django apps as Plugins. Any Django app can be converted to a FinDesk plugin by:
 1. Adding a config.json file
 2. Adding a urls.py file
 3. adding templated in a folder named `templates`

Then a zipped file of the plugin can be uploaded to FinDesk server.

___

[Creating a REST plugin](./samplePlugin.md)