# Function Documentation

### Exercise instructions:
Imagine you are documenting a JavaScript SDK for a social network. Below are the functions you need to document along with notes from talking to the development team. Open up a word processor and get started.

## Example You Can Use as a Template
Here’s an example you can use as a template. Note how I tried to make the notes flow better. Also, even though no one said what the data types were, it’s something you should be able to figure out.

* getFriendDistance(username)

*Notes from dev team: Any user is some “degrees of separation” from another user. If they are friends, the distance is 1. If they are friends of friends, the distance is 2. This function returns the distance from the current user to the specified user. If there is no connection between the users, then it returns NaN.*

* logout()
For logging out the current user.
(Hint: No return value was mentioned, so you can skip the Returns section. And no parameters, so you can skip the Parameters section. And no remarks, so you can skip this, too. This one is super easy! Just remember that summaries should start with a verb.)
* getNumberFriends()
Gets the number of friends the current user has.
(Hint: No parameters, so you can skip the Parameters section.)
* requestFriend(username) This sends a friend request to a user.
* post(statusUpdate)
Used to post a status update. The status update can be up to 1000 characters long. Returns true if the post succeeded and false if the post fails.
* like(postId, likeType)
Likes a post. The post is specified by the ID, which is an integer. The likeType can have one of these values: "Like", "Love", "Empathy". Returns true if the like succeeded and false if the like fails.

________________________________________________________________________________

## Documentation

**getFriendDistance(username)**
Returns the distance between users.
Any user is "separated" by "degrees." If friends, the distance is 1.  If friends of friends, the distance is 2.  NaN if no connection between users.

Parameters
* username  
  Type: String
  Username of the user from whom the distance is calculated

Returns
* Type: Number
  Separation between users

* **logout**
Signs out users

* **getNumberFriends()**
Returns number of friends

Returns:
Type: Number
Number of friends belonging to the current user.

* **requestFriend(username)**
Sends a friend request to a user

Parameters
* username
 Type: String

* **post(statusUpdate)**
Posts a status update.
The status update can be up to 1000 characters long. Returns whether the post succeeded.

Parameters:
* statusUpdate
  Type: String
  Status update to post

Returns:
* Type: Boolean
true if the post succeeds; false if the post fails.

* **like(postId, likeType)**
Status updater. Status updates can be 1000 characters. True if post succeeded, false otherwise.

Parameters
* postId
Type: Number
Identifying number for the post

* likeType
Type: String

* **like(post, likeType)**
Parameters
* post
Type: Number
The ID of the post to like

likeType
* Type: String
The type of “like” action. Valid values: "Like", "Love", "Empathy".

Returns:
* Type: Boolean
true if the like succeeds; false if the like fails.
