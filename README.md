FS'tival 22

Team Name : Stealthy Devs

Tool Name : Mongo_DB

Team Members :
       1. Dharsana - 20C019
       2. Lokesh D - 20C049
       3. Madhu Priya Dharshini S- 20C050

Problem statement :

To develop a web portal where farmers can post their queries regarding plant diseases, 
pest management and weed control and receive advice from professionals.

Installation :

Components
mongod - The database server.
mongos - Sharding router.
mongo - The database shell (uses interactive javascript).
Utilities
install_compass - Installs MongoDB Compass for your platform.

Building
See Building MongoDB.

Running
For command line options invoke:

$ ./mongod --help
To run a single server database:

  $ sudo mkdir -p /data/db
  $ ./mongod
  $
  $ # The mongo javascript shell connects to localhost and test database by default:
  $ ./mongo
  > help
Installing Compass
You can install compass using the install_compass script packaged with MongoDB:

  $ ./install_compass
This will download the appropriate MongoDB Compass package for your platform and install it.

Drivers
Client drivers for most programming languages are available at https://docs.mongodb.com/manual/applications/drivers/. Use the shell (mongo) for administrative tasks.

Bug Reports
See https://github.com/mongodb/mongo/wiki/Submit-Bug-Reports.

Packaging
Packages are created dynamically by the buildscripts/packager.py script. This will generate RPM and Debian packages.

Documentation
https://docs.mongodb.com/manual/

Cloud Hosted MongoDB
https://www.mongodb.com/cloud/atlas

Forums
https://community.mongodb.com

Technical questions about using MongoDB.

https://community.mongodb.com/c/server-dev

Technical questions about building and developing MongoDB.

Learn MongoDB
https://university.mongodb.com/

LICENSE
MongoDB is free and the source is available. Versions released prior to October 16, 2018 are published under the AGPL. 
All versions released after October 16, 2018, including patch fixes for prior versions, are published under the Server Side Public License (SSPL) v1. See individual files for details.




