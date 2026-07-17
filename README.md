markdown# Nexus Deployment Lab

The project was successfully built and deployed to a temporary Nexus droplet instance.


[INFO] --- install:3.1.4:install (default-install) @ java-maven-app ---
[INFO] Installing /Users/beccab/workspace/bootcamp/java-maven-app/pom.xml to /Users/beccab/.m2/repository/com/example/java-maven-app/1.1.0-SNAPSHOT/java-maven-app-1.1.0-SNAPSHOT.pom
[INFO] Installing /Users/beccab/workspace/bootcamp/java-maven-app/target/java-maven-app-1.1.0-SNAPSHOT.jar to /Users/beccab/.m2/repository/com/example/java-maven-app/1.1.0-SNAPSHOT/java-maven-app-1.1.0-SNAPSHOT.jar
[INFO] 
[INFO] --- deploy:3.1.4:deploy (default-deploy) @ java-maven-app ---
Downloading from nexus-snapshots: http://64.23.238.120:8081/repository/maven-snapshots/com/example/java-maven-app/1.1.0-SNAPSHOT/maven-metadata.xml
Uploading to nexus-snapshots: http://64.23.238.120:8081/repository/maven-snapshots/com/example/java-maven-app/1.1.0-SNAPSHOT/java-maven-app-1.1.0-20260717.230214-1.pom
Uploaded to nexus-snapshots: http://64.23.238.120:8081/repository/maven-snapshots/com/example/java-maven-app/1.1.0-SNAPSHOT/java-maven-app-1.1.0-20260717.230214-1.pom (2.6 kB at 4.3 kB/s)
Uploading to nexus-snapshots: http://64.23.238.120:8081/repository/maven-snapshots/com/example/java-maven-app/1.1.0-SNAPSHOT/java-maven-app-1.1.0-20260717.230214-1.jar
Uploaded to nexus-snapshots: http://64.23.238.120:8081/repository/maven-snapshots/com/example/java-maven-app/1.1.0-SNAPSHOT/java-maven-app-1.1.0-20260717.230214-1.jar (24 MB at 436 kB/s)
Downloading from nexus-snapshots: http://64.23.238.120:8081/repository/maven-snapshots/com/example/java-maven-app/maven-metadata.xml
Uploading to nexus-snapshots: http://64.23.238.120:8081/repository/maven-snapshots/com/example/java-maven-app/1.1.0-SNAPSHOT/maven-metadata.xml
Uploaded to nexus-snapshots: http://64.23.238.120:8081/repository/maven-snapshots/com/example/java-maven-app/1.1.0-SNAPSHOT/maven-metadata.xml (775 B at 3.3 kB/s)
Uploading to nexus-snapshots: http://64.23.238.120:8081/repository/maven-snapshots/com/example/java-maven-app/maven-metadata.xml
Uploaded to nexus-snapshots: http://64.23.238.120:8081/repository/maven-snapshots/com/example/java-maven-app/maven-metadata.xml (285 B at 1.2 kB/s)
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  56.906 s
[INFO] Finished at: 2026-07-17T16:03:11-07:00
[INFO] ------------------------------------------------------------------------
