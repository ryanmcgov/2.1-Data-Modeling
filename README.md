# 2.1-Data-Modeling

I have an idea for an app.

We are changing the way people manage their pictures! Someone should be able to sign in, upload a bunch of pictures and then be able to add information to each one like where it was taken, when it was taken and any additional notes. You know what? They should also be able to tag their family members. That sounds good.

Each member of our amazing service should be able to see all of their pictures, and so should their family. There should be some sort of grouping that groups people together and allows them to see and comment on all of their group's photos.

So how much will this cost me?


## User(class)
  * name(property)
  * summary(property)
  * friends(property)
  * add_friend(method)
    * name(arg)
  * remove_friend(method)
    * name(arg)
  * view_friends(method)

## Gallery(class)
  * name(property)
  * photos(property)
  * add_photo(method)
  * delete_photo(method)
  * sort(method)
    * by_name(arg)
    * by_date(arg)


## Photo
  * add_summary(method)
    * summary(arg)
  * tag_photo(method)
    * name(arg)
    
## Group
  * name(property)
  * members(property)
  * photos(property)
  * add_photo(method)
  * join_group(method)
  * leave_group(method)
  * comment_on_photo(method)
    *comment(arg)