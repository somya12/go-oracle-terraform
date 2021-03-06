## 0.1.9 (July 20, 2017)

 * service_instance: Update delete retry count ([#79](https://github.com/hashicorp/go-oracle-terraform/issues/79))
 
 * service_instance: Add additional fields ([#79](https://github.com/hashicorp/go-oracle-terraform/issues/79))

## 0.1.8 (July 19, 2017)

 * storage_volumes: Add SSD support ([#78](https://github.com/hashicorp/go-oracle-terraform/issues/78))

## 0.1.7 (July 19, 2017)

  * database: Adds the Oracle Database Cloud to the available sdks. ([#77](https://github.com/hashicorp/go-oracle-terraform/issues/77))
  
  * database: Adds Service Instances to the database sdk ([#77](https://github.com/hashicorp/go-oracle-terraform/issues/77))

## 0.1.6 (July 18, 2017)

 * opc: Add timeouts to instance and storage inputs ([#75](https://github.com/hashicorp/go-oracle-terraform/issues/75))

## 0.1.5 (July 5, 2017)

 * storage: User must pass in Storage URL to CRUD resources ([#74](https://github.com/hashicorp/go-oracle-terraform/issues/74))

## 0.1.4 (June 30, 2017)

 * opc: Fix infinite loop around auth token exceeding it's 25 minute duration. ([#73](https://github.com/hashicorp/go-oracle-terraform/issues/73))

## 0.1.3 (June 30, 2017)

  * opc: Add additional logs instance logs ([#72](https://github.com/hashicorp/go-oracle-terraform/issues/72))
  
  * opc: Increase instance creation and deletion timeout ([#72](https://github.com/hashicorp/go-oracle-terraform/issues/72))

## 0.1.2 (June 30, 2017)


FEATURES:

  * opc: Add image snapshots ([#67](https://github.com/hashicorp/go-oracle-terraform/issues/67))
  
  * storage: Storage containers have been added ([#70](https://github.com/hashicorp/go-oracle-terraform/issues/70))


IMPROVEMENTS: 
  
  * opc: Refactored client to be generic for multiple Oracle api endpoints ([#68](https://github.com/hashicorp/go-oracle-terraform/issues/68))
  
  * opc: Instance creation retries when an instance enters a deleted state ([#71](https://github.com/hashicorp/go-oracle-terraform/issues/71))
  
## 0.1.1 (May 31, 2017)

IMPROVEMENTS:

 * opc: Add max_retries capabilities ([#66](https://github.com/hashicorp/go-oracle-terraform/issues/66))
 
## 0.1.0 (May 25, 2017)

BACKWARDS INCOMPATIBILITIES / NOTES:

 * Initial Release of OPC SDK
