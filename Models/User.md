# User

A user represents an actual user account.  It is distinct from a person because not all people will be users, although it is tied to a person in a one-to-one relationship.

| field        | description (optional)
|--------------|-------------------------------------------
| username     |
| password     |
| dateJoined   |
| role         | Admin, Organizer, User


## Additional Field Details

### password

Passwords will be hashed with an expensive bcrypt.
