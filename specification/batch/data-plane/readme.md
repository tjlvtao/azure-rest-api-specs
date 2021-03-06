# Batch
    
> see https://aka.ms/autorest

This is the AutoRest configuration file for Batch.



---
## Getting Started 
To build the SDK for Batch, simply [Install AutoRest](https://aka.ms/autorest/install) and in this folder, run:

> `autorest`

To see additional help and options, run:

> `autorest --help`
---

## Configuration



### Basic Information 
These are the global settings for the Batch API.

``` yaml
openapi-type: data-plane
tag: package-2017-06.5.1
```


### Tag: package-2017-06.5.1

These settings apply only when `--tag=package-2017-06.5.1` is specified on the command line.

``` yaml $(tag) == 'package-2017-06.5.1'
input-file:
- Microsoft.Batch/2017-06-01.5.1/BatchService.json
```


### Tag: package-2017-05.5.0

These settings apply only when `--tag=package-2017-05.5.0` is specified on the command line.

``` yaml $(tag) == 'package-2017-05.5.0'
input-file:
- Microsoft.Batch/2017-05-01.5.0/BatchService.json
```


### Tag: package-2017-01.4.0

These settings apply only when `--tag=package-2017-01.4.0` is specified on the command line.

``` yaml $(tag) == 'package-2017-01.4.0'
input-file:
- Microsoft.Batch/2017-01-01.4.0/BatchService.json
```
 
### Tag: package-2016-07.3.1

These settings apply only when `--tag=package-2016-07.3.1` is specified on the command line.

``` yaml $(tag) == 'package-2016-07.3.1'
input-file:
- Microsoft.Batch/2016-07-01.3.1/BatchService.json
```
 
### Tag: package-2016-02.3.0

These settings apply only when `--tag=package-2016-02.3.0` is specified on the command line.

``` yaml $(tag) == 'package-2016-02.3.0'
input-file:
- Microsoft.Batch/2016-02-01.3.0/BatchService.json
```
 
### Tag: package-2015-12.2.2

These settings apply only when `--tag=package-2015-12.2.2` is specified on the command line.

``` yaml $(tag) == 'package-2015-12.2.2'
input-file:
- Microsoft.Batch/2015-12-01.2.2/BatchService.json
```


---
# Code Generation

## C# 

These settings apply only when `--csharp` is specified on the command line.
Please also specify `--csharp-sdks-folder=<path to "SDKs" directory of your azure-sdk-for-net clone>`.

``` yaml $(csharp)
csharp:
  azure-arm: true
  license-header: MICROSOFT_MIT
  payload-flattening-threshold: 1
  namespace: Microsoft.Azure.Batch
  output-folder: $(csharp-sdks-folder)/Batch/DataPlane/Azure.Batch/GeneratedProtocol
  clear-output-folder: true
```
