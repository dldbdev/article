[DLDB](https://dldb.io/) is the location analytics platform for mobile applications.

- What are the most popular places where my users are?
- What are the popular times for specific locations?
- Where do they come from?
- Where do they go?
- How many people are visiting multiple defined locations?
- How many unique visits are in a specific area?
- How many total visits are in a specific area?
- How long have people stayed in a specific area?

DLDB is about privacy. We don’t allow to fetch any location or private data from the phone. Our storage is distributed across the devices and is app-specific. The same applies to the queries. All the queries are done by the devices. Only the statistical metrics without an actual ident are sent toward our backend where they are aggregated and deleted after the aggregation. Analysts see only the aggregated data. 

Since all the data is distributed between the devices, the scaling comes by design. The queries are as fast as the slowest device is.

What you will find in our beta version?

- [iOS](https://github.com/dldbdev/dldb_sdk_ios), [Android](https://github.com/dldbdev/dldb_sdk_android), [Flutter](https://github.com/dldbdev/dldb_sdk_flutter) and [React Native SDK](https://github.com/dldbdev/dldb_sdk_react_native)
- The [dashboard](https://dashboard.dldb.io/) allows you to define and make your own queries (SQL "like") or use some predefined queries.

