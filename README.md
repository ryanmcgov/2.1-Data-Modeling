# 2.1-Data-Modeling

I have an idea for an app.

We are changing the way people manage their pictures! Someone should be able to sign in, upload a bunch of pictures and then be able to add information to each one like where it was taken, when it was taken and any additional notes. You know what? They should also be able to tag their family members. That sounds good.

Each member of our amazing service should be able to see all of their pictures, and so should their family. There should be some sort of grouping that groups people together and allows them to see and comment on all of their group's photos.

So how much will this cost me?


## User(class)
  * @name
  * @summary
  * @friends
  * photos = Gallery
  * .add_friend
    * name-arg
  * .remove_friend
    * name-arg
  * .view_friends

## Gallery(class)
  * @name
  * @photos
  * .add_photo
    * Photo.add_summary
    * Photo.tag_photo
  * .delete_photo
  * .sort
    * by_name-arg
    * by_date-arg


## Photo(class)
  * .add_summary
    * summary-arg
  * .tag_photo
    * name-arg
    
## Group(class)
  * @name
  * @members
  * @photos
  * .add_photo
  * .join_group
  * .leave_group
  * .comment_on_photo
    * comment-arg