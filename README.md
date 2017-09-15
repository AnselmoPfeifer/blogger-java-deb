Building package deb: 
================

- Build package .deb for install and configure oracle-java7

## TODO
- In time the build is executed download on our Bucket (Amazon / Google) 
    the jdk-7u80-linux-x64.tar.gz in directory src/deb/var/cache/oracle-jdk7-installer
    - Configure access in our bucket for execute download
    - Settings dependencies in pom.xml: 
        - AWS SDK: https://aws.amazon.com/sdk-for-java/
        - Google SDK: https://cloud.google.com/sdk/