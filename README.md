# IBM Cloud Pak for Data - Connector SDK

This fork adds the functionality of mocked batches. The server maintains a `VectorSchemaRoot` in memory to be able to return data instantaneously. The source interaction happens only upon changing the batch size, otherwise the same batch is transmitted.

Asset Descriptors added:
 - `mock` - specifies if mocked batch functionality should be used,
 - `batch_rep` - specifies the number of times the mocked batch should be returned. 


For documentation of other functionalities refer to the [SDK Guide](guide.md).

## License

This SDK is distributed under the Apache 2.0 license.
