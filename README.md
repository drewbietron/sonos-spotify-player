#### Cloudinary
```Ruby
rake cloudinary:sync_static
```
This uploads the static assets to Cloudinary.  You can include an image in a view by using
```Ruby
=cl_image_tag("test.jpg", type: "asset", crop: :fill, width: 400, quality: 40)
```
