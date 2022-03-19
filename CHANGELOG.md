# New in version UNRELEASED

* When a Model instance is required, allow to pass a dict matching the Model
  fields instead
* `natura_iva` is now from 2 to 4 characters long (#18)
* Added a38.consts module with constants for common enumerations (#18)
* Added `DettaglioLinee.autofill_prezzo_totale`
* Export `a38.fattura.$MODEL` models as `a38.$MODEL`
* Implemented `a38tool yaml` to export in YAML format
* Implemented loading from YAML and JSON as if they were XML
* Implemented `a38tool edit` to open a fattura in a text editor using YAML or
  Python formats (#22)
* Use UTF-8 encoding and include xml declaration when writing XML from a38tool
  (#19)