### Useful Tools & Resources

 - [Meteor Dev Tools](https://chrome.google.com/webstore/detail/meteor-devtools/ippapidnnboiophakmmhkdlchoccbgje)

### How to Query Minimongo From the Console

Say you want to get the record for the 'reaction-inventory' package:

 1. `var collections = Meteor.connection._mongo_livedata_collections`
 2. `var packages = collections.Packages`
 3. `var record = packages.findOne({ name: 'reaction-inventory' })`

Here's a link to all the methods you can access on the collections object:
https://docs.meteor.com/api/collections.html#Mongo-Collection
