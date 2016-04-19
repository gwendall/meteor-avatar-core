Meteor Avatar core
==================

Get a Meteor user's avatar.

Installation  
------------

``` sh
npm install meteor-avatar-core
```

Methods
-------

getUrl(user): Returns the avatar's URL

Example
-------  

``` javascript
import Avatar from 'meteor-avatar-core';

// let's assume the user is logged-in
var picture = Avatar.getUrl(Meteor.user());
```
