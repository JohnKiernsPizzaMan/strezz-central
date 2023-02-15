# i reuplaoded this from my old account so i could use an old client
# Strezz-central
A fork of strezz-central so that I can add libraries i want.

# If you want to add something
make a pull request 90% chance ill merge it

# how to add
```bash
mvn install:install-file -DgroupId=YOUR_GROUP -DartifactId=YOUR_ARTIFACT -Dversion=YOUR_VERSION -Dfile=YOUR_JAR_FILE -Dpackaging=jar -DgeneratePom=true -DlocalRepositoryPath=.  -DcreateChecksum=true
```