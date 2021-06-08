<div align="center">
    <h1>Redmine Sentry Client</h1>
    <p>Report internal redmine errors to sentry</p>
</div>

## Introduction
This redmine plugin allows you to specify a sentry dsn, to report errors.  
The plugin is tested with redmine version **4.2.1**

## Installation
1. Clone this repository into your `plugins` directory
2. Install dependencies with `bundle install`
3. Restart redmine

## Configuration
Please provide you'r sentry dsn in the plugin configuration.  
Keep in mind to restart redmine after adding the DSN, because the sentry client only gets registerd if this configuration is provided

## Test
In the configuration of the plugin is a button to trigger a test error.  
Alternatively you can visit the `/sentry` route to trigger the same behaviour

## License
See [LICENSE](./LICENSE) file for more information

<p align="center">&copy; 2021 <a href="https://jop-software.de">jop-software Inh. Johannes Przymusinski</a></p>