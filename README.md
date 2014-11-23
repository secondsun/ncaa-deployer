# SportsData NCAA Football Schema Deployer

This project will download schema files from [SportsData](http://developer.sportsdatallc.com/page) and deploy jaxb generated class files to your local maven repository.

## Setup

 * [Create an account](http://developer.sportsdatallc.com/member/register)
 * Add to your settings.xml your NCAA Football key under the property name `sportsdata.api.key`.
 * Run `mvn clean install`

## Usage

In your project's pom you may reference the Schema Files with 
```
<dependency>
    <groupId>net.saga</groupId>
    <artifactId>ncaa-football</artifactId>
    <version>1.0.0</version>
</dependency>
```
