# Step 1: Authenticate
$ docker login docker.pkg.github.com --username clogreenthesoulmachine99
# Step 2: Tag
 docker tag IMAGE_ID docker.pkg.github.com/clogreenthesoulmachine99/repository-name/IMAGE_NAME:VERSIO
# Step 3: Publish
$ docker push docker.pkg.github.com/clogreenthesoulmachine99/repository-name/IMAGE_NAME:VERSION
