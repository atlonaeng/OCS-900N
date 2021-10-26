# AT-OCS-900N
Files and resources for the Atlona AT-OCS-900N.

## JSON Schema
The [AT-OCS-900N JSON Schema](schema/AT-OCS-900N_Schema.json) conforms to [JSON Schema 2020-12](https://json-schema.org/draft/2020-12/schema) and defines the configuration and communications nodes.

## Postman Collection
The [Postman Collection](Postman/AT-OCS-900N_Postman-Collection.json) contains example HTTP requests for navigating the AT-OCS-900N Web User Interface.

## Velocity Integration

### Variables

| Variable Name | Example Data | Data Type | Variable Value |
|---------------|--------------|-----------|----------------|
| Motion Detected | `{"motion":{"detected":true}}` | boolean | 1 |
| Motion Last Detection | `{"motion":{"lastDetection":"1:06:28:1"}}` | string | 1:06:28:01 |
| Light White | `{"light":{"values":{"white":606}}}` | integer | 606 |
| Light Red | `{"light":{"values":{"red":205}}}` | integer | 205 |
| Light Green | `{"light":{"values":{"green":88}}}` | integer | 88 |
| Light Blue | `{"light":{"values":{"blue":56}}}` | integer | 56 |
| Temperature F | `{"temperature":{"values":{"F":72.0}}}` | number | 72.0 |
| Temperature C | `{"temperature":{"values":{"C":22.2}}}` | number | 22.2 |
