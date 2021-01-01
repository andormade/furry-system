# furry-system

## What does this do?

It takes image files from an Amazon S3 (or compatible) bucket, makes them smaller and then puts them into an other S3 compatible bucket.

## Why the name furry system?

Believe it or not, but Github suggested this name when I was creating the repository, and I accepted it.

## Required environment variables

* ACCESS_KEY
* SECRET_KEY
* AWS_ENDPOINT
* SOURCE_BUCKET
* DESTINATION_BUCKET

## Dependencies

* Ubuntu 20.04
* nodejs 14.15.3
* libharfbuzz0b
* libfontconfig
* imagemagick