# documentation

Invoke-RestMethod

```
mvn io.quarkus:quarkus-maven-plugin:0.20.0:create -DprojectGroupId=org.acme -DprojectArtifactId=getting-started -DclassName="org.acme.quickstart.GreetingResource" -Dpath="/hello"

mvn io.quarkus:quarkus-maven-plugin:0.20.0:create -DclassName="org.acme.quickstart.GreetingResource" -Dpath="/hello"
```

```
quay.io/quarkus/ubi-quarkus-native-image
https://quay.io/repository/quarkus/ubi-quarkus-native-image?tag=latest&tab=tags



Registry details:
[Registry]/[User/org]/[Repository of images]:<tag>
```
## Techtalk
```
Download image using command: docker pull quay.io/quarkus/ubi-quarkus-native-image:19.1.1
https://github.com/redhat-developer-demos/quarkus-tutorial/
https://redhat-developer-demos.github.io/quarkus-tutorial/quarkus-tutorial/0.20.0/01-setup.html

https://redhat-developer-demos.github.io/quarkus-tutorial/quarkus-tutorial/0.20.0/02-basics-fundas.html#basics-create-quarkus-app


```

mvn my-quarkus-project; ./mvnw -DskipTests clean package

./mvnw -DskipTests clean package -Pnative -Dnavtive-image.docker-build=true
mvnw -DskipTests clean package -Pnative -Dnative-image.docker-build=true

Usage:  docker tag SOURCE_IMAGE[:TAG] TARGET_IMAGE[:TAG]

docker tag SOURCE_IMAGE[:sathi] TARGET_IMAGE[:sath1];docker push SOURCE_IMAGE[:sathi] TARGET_IMAGE[:sath1]