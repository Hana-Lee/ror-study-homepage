# Ruby On Rails Study
Make homepage with Ruby On Rails

## Config heroku
* heroku config:set S3_SECRET_KEY=your s3 secret key
* heroku config:set S3_ACCESS_KEY=your s3 access key
* heroku config:set S3_BUCKET=your s3 bucket name
* heroku config:set SECRET_KEY_BASE=your secret key base
* heroku run rake db:migrate

## TODO List
### Things you'll need:
* Migration to create reviews table, body, type = text_field, two foreign keys, reference chef_id, reference recipe_id
* You'll need to build the Review model
* You'll need to create tests for the spec, add validations to the review model.
* Build the associations, has_many and belongs_to
* Test out associations in Rails console
    * recipe.reviews
    * chef.reviews
* Create routes
* Authenticated chefs can create reviews, before_action require_user
* You associate a chef_id and recipe_id
* Use existing code if possible.