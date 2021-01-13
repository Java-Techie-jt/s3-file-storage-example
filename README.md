# s3-file-storage-example

we can either use “aws-java-sdk” from maven

<!-- https://mvnrepository.com/artifact/com.amazonaws/aws-java-sdk -->
```
<dependency>
    <groupId>com.amazonaws</groupId>
    <artifactId>aws-java-sdk</artifactId>
    <version>1.11.486</version>
</dependency>
```

or we could use spring-cloud-starter-aws.

```
<dependency>
    <groupId>org.springframework.cloud</groupId>
    <artifactId>spring-cloud-starter-aws</artifactId>
</dependency>
```
since I’m using spring cloud I have used the “spring-cloud-starter-aws” for this sample app.
