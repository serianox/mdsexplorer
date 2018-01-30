# MDSExplorer
## FIDO Metadata Service Explorer
_MDSExplorer_ allows to visualize the content of the [FIDO Alliance Metadata Service](https://fidoalliance.org/mds/).

## Cross-Origin Resource Sharing (CORS)
Due to [CORS](https://en.wikipedia.org/wiki/Cross-origin_resource_sharing), it is not possible to directly access the content of the MDS. To emulate it, a dump of the MDS with a simple Python server is located under `mds`.