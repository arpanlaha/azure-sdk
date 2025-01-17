# Azure SDK for Javascript (July 2019 Preview) Release Notes

The Azure SDK team is pleased to make available the July 2019 client library preview release. This represents the first release of the ground-up rewrite of the client libraries to ensure consistency, idiomatic design, and excellent developer experience and productivity. This preview release includes new client libraries for Key Vault (keys and secrets), Event Hubs, Storage (blob, files and queues) and Cosmos.

## Installation Instructions
To install the packages, copy and paste the below into a terminal.
  
    $> npm install @azure/keyvault-keys@4.0.0-preview.2
    $> npm install @azure/keyvault-secrets@4.0.0-preview.2
    $> npm install @azure/storage-queue@12.0.0-preview.1
    $> npm install @azure/storage-file@12.0.0-preview.1
    $> npm install @azure/storage-blob@12.0.0-preview.1
    $> npm install @azure/event-hubs@5.0.0-preview.1
    $> npm install @azure/cosmos@next

## Feedback
If you have a bug or feature request for one of the libraries, please post an issue at the [azure-sdk-for-js repository](https://github.com/azure/azure-sdk-for-js/issues)

## Changelog
Detailed change logs are linked to in the Quick Links below. Here are some critical call outs.

- Designed based on the [Azure SDK Design Guidelines for Typescript](https://azuresdkspecs.z5.web.core.windows.net/TypeScriptSpec.html), 
resulting in a consistent API design and common feature set such as HTTP retries, logging, transport protocols, authentication protocols, cancellation mechanisms etc.
- Support for Azure Active Directory credentials created using the new [@azure/identity](https://www.npmjs.com/package/@azure/identity) library. Moving forward, this would be the common mode of authentication for all Azure SDK libraries.
- Modernized API making use of async functions and async iterators, to offer an improved and more productive developer experience.


## Quick Links
| Service  | Install | Quickstart |  API Reference | Changelog | Samples
| -- | -- | -- | -- | -- | -- |
| [Keyvault - Keys](https://azure.microsoft.com/en-us/services/key-vault/) | [Package](https://www.npmjs.com/package/@azure/keyvault-keys/v/4.0.0-preview.2) | [Readme.md](https://github.com/Azure/azure-sdk-for-js/tree/master/sdk/keyvault/keyvault-keys) | [API Reference Documentation](https://azure.github.io/azure-sdk-for-js/keyvault-keys) | [Changelog](https://github.com/Azure/azure-sdk-for-js/releases/tag/%40azure%2Fkeyvault-keys_4.0.0-preview.2)  | [Samples](https://github.com/Azure/azure-sdk-for-js/tree/master/sdk/keyvault/keyvault-keys/samples)
| [Keyvault - Secrets](https://azure.microsoft.com/en-us/services/key-vault/) | [Package](https://www.npmjs.com/package/@azure/keyvault-secrets/v/4.0.0-preview.2) | [Readme.md](https://github.com/Azure/azure-sdk-for-js/tree/master/sdk/keyvault/keyvault-secrets) | [API Reference Documentation](https://azure.github.io/azure-sdk-for-js/keyvault-secrets) | [Changelog](https://github.com/Azure/azure-sdk-for-js/releases/tag/%40azure%2Fkeyvault-secrets_4.0.0-preview.2) | [Samples](https://github.com/Azure/azure-sdk-for-js/tree/master/sdk/keyvault/keyvault-secrets/samples)
| [Storage - Blobs](https://docs.microsoft.com/en-us/azure/storage/blobs/storage-blobs-overview) | [Package](https://www.npmjs.com/package/@azure/storage-blob/v/12.0.0-preview.1) | [Readme.md](https://github.com/Azure/azure-sdk-for-js/tree/feature/storage/sdk/storage/storage-blob) | [API Reference Documentation](https://azure.github.io/azure-sdk-for-js/storage-blob/index.html) | [Changelog](https://github.com/Azure/azure-sdk-for-js/releases/tag/%40azure%2Fstorage-blob_12.0.0-preview.1) | [Samples](https://github.com/Azure/azure-sdk-for-js/tree/feature/storage/sdk/storage/storage-blob/samples)
| [Storage - Files](https://docs.microsoft.com/en-us/azure/storage/files/storage-files-introduction) | [Package](https://www.npmjs.com/package/@azure/storage-file/v/12.0.0-preview.1) | [Readme.md](https://github.com/Azure/azure-sdk-for-js/tree/feature/storage/sdk/storage/storage-file) | [API Reference Documentation](https://azure.github.io/azure-sdk-for-js/storage-file/index.html) | [Changelog](https://github.com/Azure/azure-sdk-for-js/releases/tag/%40azure%2Fstorage-file_12.0.0-preview.1) | [Samples](https://github.com/Azure/azure-sdk-for-js/tree/feature/storage/sdk/storage/storage-blob/samples)
| [Storage - Queues](https://docs.microsoft.com/en-us/azure/storage/queues/storage-dotnet-how-to-use-queues) | [Package](https://www.npmjs.com/package/@azure/storage-queue/v/12.0.0-preview.1) | [Readme.md](https://github.com/Azure/azure-sdk-for-js/tree/feature/storage/sdk/storage/storage-queue) | [API Reference Documentation](https://azure.github.io/azure-sdk-for-js/storage-queue/index.html) | [Changelog](https://github.com/Azure/azure-sdk-for-js/releases/tag/%40azure%2Fstorage-queue_12.0.0-preview.1) | [Samples](https://github.com/Azure/azure-sdk-for-js/tree/feature/storage/sdk/storage/storage-queue/samples)
| [Event Hubs](https://azure.microsoft.com/en-us/services/event-hubs/) | [Package](https://www.npmjs.com/package/@azure/event-hubs/v/5.0.0-preview.1) | [Readme.md](https://github.com/Azure/azure-sdk-for-js/tree/master/sdk/eventhub/event-hubs) | [API Reference Documentation](https://azure.github.io/azure-sdk-for-js/event-hubs/index.html) | [Changelog](https://github.com/Azure/azure-sdk-for-js/releases/tag/%40azure%2Fevent-hubs_5.0.0-preview.1) | [Samples](https://github.com/Azure/azure-sdk-for-js/tree/master/sdk/eventhub/event-hubs/samples)
| [Cosmos](https://azure.microsoft.com/en-us/services/cosmos-db/) | [Package](https://www.npmjs.com/package/@azure/cosmos/v/next) | [Readme.md](https://github.com/Azure/azure-cosmos-js/blob/v3/README.md) | [API Reference Documentation](https://azure.github.io/azure-cosmos-js/) | Changelog | [Samples](https://github.com/Azure/azure-cosmos-js/tree/v3/samples)



