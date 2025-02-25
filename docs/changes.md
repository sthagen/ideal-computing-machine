# Change History

2024.12.18
:    Fixed mis-alignm,ent between implementation and upstream CSAF v2.0 OASIS Standard schema
* Added missing members of upstream CSAF v2.0 OASIS Standard schema
* Fixed the missing model_numbers of product_identification_helpers member bug (<https://todo.sr.ht/~sthagen/csaf/8>)
* Synchronized CSAF schema in proxy from upstream (<https://todo.sr.ht/~sthagen/csaf/9>)

## 2023

2023.11.27
:    Fixed pydantic V2 small issue (<https://todo.sr.ht/~sthagen/csaf/6>)

2023.10.18
:    Completed migration to pydantic v2 (<https://todo.sr.ht/~sthagen/csaf/5>)

2023.6.18
:    Fixed validation failures of an example
* Fixed validation failures for CVSS of upstream BSI example (<https://todo.sr.ht/~sthagen/csaf/4>)
* Moved SBOM noise into folder and added SPDX SBOM (derived) in multiple file formats

2023.5.9
:    Fixed top level aggregator to consume and produce camelCase CVSS keys.

2923.5.8
:    Fixed CVSS camelCase keyword propagation as mix-ins of score and vulnerability
objects (https://todo.sr.ht/~sthagen/csaf/2#event-237257)

2023.5.6
:    Fixed product_id value type, CVSS keywords, and added contributors section
* Added contributors section to documentation
* Fixed product_id should be a string (<https://todo.sr.ht/~sthagen/csaf/3>)
* Fixed the CVSS Keywords in Generated CSAF Documents (<https://todo.sr.ht/~sthagen/csaf/2>)
* Migrated from orjson to msgspec

## 2022

2022.3.20
:    Added warning for CSAF files with more than 15 Megabytes

2022.3.13
:    Added setuptools information to environment report

2022.3.12
:    Added partial CLI implementation, environment report capability, and some metadata
* First partial implementation with command line api
* Added report of environment facts command to support bug reports (new dependency scooby)
* Added baseline, third-party information, and SBOM

## 2021

0.0.1 (2021-05-01)
:    * Initial release on PyPI
