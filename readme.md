
## Blog
* admin role is added using mongo and
* TODO: use accounts-admin-ui-bootstrap-3
```
db.users.update({_id: db.users.findOne()._id}, {$push:{roles: "blogAdmin"}})
```