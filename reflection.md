1.Why is object storage better suited for storing millions of photos compared to a traditional block storage hard drive?
Object storage is better suited for storing millions of photos because it can store a huge number of files and scale easily without needing to manage individual hard drives. Each photo is stored as an object with its own metadata and can be accessed over the internet. It is also more cost-effective, durable, and easier to expand than traditional block storage, which is designed more for applications that need fast, structured disk access.

2.How did using Docker make it easier to deploy the MinIO storage server?

Docker made it easier to deploy MinIO because it automatically packages MinIO with everything it needs to run. Instead of installing and configuring many components manually, I only needed to run a Docker command to download and start the MinIO server. It also makes the setup fast, portable, and easy to remove or restart when needed.

3.What is a "bucket" in the context of cloud storage?
A bucket in cloud storage is a container used to store and organize files or objects, such as photos, videos, and documents. Each bucket can hold a large number of objects and can have its own access permissions and settings. For example, in MinIO, you could create a bucket named “photos” to store millions of images.

4.How do you think large enterprise companies ensure their object storage data is not lost if the physical server crashes?
Large enterprise companies protect object storage data by keeping **multiple copies of the data on different physical servers or locations**. They also use **automatic replication, backups, and data redundancy**, so if one server crashes, another copy can still be accessed. This helps prevent data loss and keeps the storage service available even when hardware fails.

5.How is your confidence in navigating the Linux command line growing?
My confidence in using the Linux command line is **growing because I am becoming more familiar with basic commands and how they work**. I can now perform tasks such as checking system information, managing files and folders, and monitoring processes. With more practice, I can become faster and more confident in using Linux commands for system administration.
