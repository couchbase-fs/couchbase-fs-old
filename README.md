# couchbase-fs
Main Repository

## What is CouchbaseFs
Its a Virtual Filesystem stored and managed by Couchbase Servers as the Backend.

## How does it work?
It Offers a Uniq Structure to Store any Data with meta inside of a Couchbase Cluster and offers some best practices for any Scale of Data and Replication as also Security Needs Like Encryption.

## Why CouchbaseFs?
Simply because it gives you back the control over your Data. We partner for that goal Directly with Couchbase as a Engagment Database that enables us to focus on API's and don't care so much for Administration as its Serverless auto Scaling.

- Store Unlimited Amounts of Data Cross Datacenter or Rack Replication
- Scales to several yottabyte
  - a yottabyte could be stored on SD cards occupying roughly twice the size of the <a href="https://en.wikipedia.org/wiki/LZ_129_Hindenburg">Hindenburg <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/35/Hindenburg_at_lakehurst.jpg/450px-Hindenburg_at_lakehurst.jpg" width="100"></img></a>. 
  - With recently demonstrated technology using DNA computing for storage, one yottabyte of capacity would require a volume between 0.003 and 1 cubic meter, depending on number of redundant backup copies desired and the storage density: "Our genetic code packs billions of gigabytes into a single gram". DNA is much more advanced technology than microSDXC cards (for this application) and accompanied by uncertain costs, but this suggests potential information density.
- Handles thousands of clients
- POSIX compatible
- Uses commodity hardware
- Can use any ondisk filesystem that supports extended attributes
- Accessible using industry standard protocols like NFS, SMB HTTP, FTP
- Provides replication, quotas, geo-replication, snapshots
- Allows optimization for different workloads
- Allows usage as a Meta Filesystem via Connectors it can Connect to following Prividers and More
  - S3
  - Backblaze
  - Any Storage Solution
- Open Source


