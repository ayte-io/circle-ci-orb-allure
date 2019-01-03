# Allure Framework Circle CI orb

This repository contains Circle CI orb that brings support for 
[Allure Framework](https://github.com/allure-framework/allure2).

It is implied that target executor installs JRE separately.

Orb exports two commands:

### allure/install

Installs Allure framework, has `version` parameter.

### allure/report

Generates and stores allure report, requires prior install.

Parameters:

- `configuration-path`, defaults to built-in configuration.
- `results-path`, source of Allure metadata, defaults to 
`allure-results`.
- `target-path`, report directory, defaults to `allure-report`.
- `artifact-path`, directory, under which report will be stored as 
artifact, defaults to `Report/Allure`.

## Licensing

Ayte Labs, 2019 / MIT License

Do whatever feels natural to you
