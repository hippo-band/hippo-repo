# hippo-repo
A maven repo for hippo

add to pom
```
    <repositories>
        <repository>
            <id>hippo-repo-mvn-repo</id>
            <url>https://github.com/hippo-band/hippo-repo/master</url>
            <snapshots>
                <enabled>true</enabled>
                <updatePolicy>always</updatePolicy>
            </snapshots>
        </repository>
    </repositories>
```
