# Accelerator Log

## Options
```json
{
  "appSSOIssuerURI" : "http://authserver.<domainname>",
  "appSSOName" : "appsso-hungryman",
  "appSSORedirectURI" : "http://hungryman.<domain name>/login/oauth2/code/sso",
  "createDBInstance" : true,
  "createRabbitMQCluster" : true,
  "createResourceClaim" : true,
  "dbName" : "db-hungryman",
  "dbType" : "mysql",
  "devDefaultAccountPassword" : "$2a$10$J/EWz6Q8zxRHYCr2UwJewe5hN6uKhbytUuGGC2yHvEJ2zhH.dLvZe",
  "devDefaultAccountUsername" : "hungryman",
  "enableDefaultDevAccount" : true,
  "enableSecurity" : false,
  "numRabbitMQClusterNodes" : 1,
  "projectName" : "hungryman",
  "rabbitMQName" : "rmq-hungryman",
  "serviceNamespace" : "service-instances",
  "workloadNamespace" : "dev"
}
```
## Log
```
┏ engine (Chain)
┃  Info Running Chain(GeneratorValidationTransform, UniquePath)
┃ ┏ ┏ engine.transformations[0].validated (Combo)
┃ ┃ ┃  Info Combo running as Chain(Merge(merge), UniquePath(UseLast))
┃ ┃ ┃ engine.transformations[0].validated.merge (Chain)
┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0] (Merge)
┃ ┃ ┃ ┃  Info Running Merge(Combo, Combo, Combo, Combo, Combo, Combo, Combo)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Exclude
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[0].exclude (Exclude)
┃ ┃ ┃ ┃ ┃  Info Will exclude [**/templates/**, **/icons/**, **/.git/**, **/deployment/**]
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-api-gateway/hungryman-api-gateway.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-availability/hungryman-availability.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-notify/hungryman-notify.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-search/hungryman-search.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-search-proc/hungryman-search-proc.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-ui/hungryman-ui.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog/groups/org.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog/resources/db/hungryman-db-resource.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog/resources/messaging/hungryman-messaging-resource.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog/systems/hungryman-system.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug doc/TAPDeployment.md didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug doc/images/AppHomeScreen.png didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug doc/images/HungrymanHighLevelArch.png didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug doc/images/KNativeEventing.png didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug doc/images/SCSMessaging.png didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-api-gateway/.gitignore didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-api-gateway/Tiltfile didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-api-gateway/config/workload.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-api-gateway/pom.xml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-api-gateway/src/main/java/com/java/example/tanzu/hungryman/HungrymanAPIGatewayApplication.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-api-gateway/src/main/resources/application.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/.gitignore didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/.mvn/wrapper/maven-wrapper.properties didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/Tiltfile didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/config/workload.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/mvnw didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/mvnw.cmd didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/pom.xml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/HungrymanAvailabilityApplication.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/config/OAuth2BindingsPropertiesProcessor.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/config/WebSecurityConfig.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/entity/Availability.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/entity/AvailabilityWindow.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/function/AvailabilitySink.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/model/Availability.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/repository/AvailabilityRepository.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/repository/AvailabilityWindowRepository.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/resources/AvailabilityResource.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/resources/META-INF/spring.factories didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/resources/application.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/resources/schema.sql didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/test/java/com/java/example/tanzu/hungryman/HungrymanAvailabilityApplicationTests.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/.gitignore didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/.mvn/wrapper/maven-wrapper.properties didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/config/workload.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/mvnw didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/mvnw.cmd didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/pom.xml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/src/main/java/com/java/example/tanzu/hungryman/HungrymanCrawlerApplication.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/src/main/java/com/java/example/tanzu/hungryman/model/Availability.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/src/main/java/com/java/example/tanzu/hungryman/model/SearchCriteria.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/src/main/java/com/java/example/tanzu/hungryman/resources/SearchResource.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/src/main/resources/application.properties didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/src/test/java/com/java/example/tanzu/hungryman/HungrymanCrawlerApplicationTests.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/.gitignore didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/.mvn/wrapper/maven-wrapper.properties didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/README.md didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/Tiltfile didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/config/workload.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/mvnw didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/mvnw.cmd didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/pom.xml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/HungrymanNotifyApplication.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/config/EmailMessageConfigProperties.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/config/PublisherConfiguration.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/functions/AvailabilitySink.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/model/Availability.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/publisher/EmailPublisher.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/publisher/LoggerPublisher.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/publisher/Publisher.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/resources/application.yml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/test/java/com/java/example/tanzu/hungryman/HungrymanNotifyApplicationTests.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-search/.gitignore didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-search/.mvn/wrapper/maven-wrapper.properties didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-search/README.md didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-search/Tiltfile didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-search/catalog-info.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-search/config/workload.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-search/mvnw didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-search/mvnw.cmd didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-search/pom.xml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/java/com/java/example/tanzu/hungryman/HungrymanResApplication.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/java/com/java/example/tanzu/hungryman/config/OAuth2BindingsPropertiesProcessor.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/java/com/java/example/tanzu/hungryman/config/WebSecurityConfig.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/java/com/java/example/tanzu/hungryman/entity/Search.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/java/com/java/example/tanzu/hungryman/functions/SearchSupplier.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/java/com/java/example/tanzu/hungryman/repository/SearchRepository.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/java/com/java/example/tanzu/hungryman/resources/SearchResource.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/resources/META-INF/spring.factories didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/resources/application.yml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/resources/schema.sql didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/test/java/com/java/example/tanzu/hungryman/HungrymanResApplicationTests.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/test/java/com/java/example/tanzu/hungryman/SpringBaseTest.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/test/java/com/java/example/tanzu/hungryman/repository/SearchRepositoryTest.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/test/resources/application.yml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/.gitignore didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/.mvn/wrapper/maven-wrapper.properties didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/README.md didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/Tiltfile didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/config/workload.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/mvnw didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/mvnw.cmd didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/pom.xml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/HungrymanSearchProcApplication.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/config/StaticDiningAvailability.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/feign/CrawlerClient.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/functions/Search.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/model/Availability.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/model/SearchCriteria.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/processor/SearchProcessor.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/processor/cache/HashCache.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/processor/cache/MemoryHashCache.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/searcher/Searcher.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/searcher/impl/CrawlerSearcher.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/searcher/impl/LocalRandomSearcher.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/resources/application.yml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/test/java/com/java/example/tanzu/hungryman/HungrymanSearchProcApplicationTests.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/.gitignore didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/README.md didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/httpproxy.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/package-lock.json didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/package.json didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/public/favicon.png didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/public/index.html didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/public/manifest.json didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/public/robots.txt didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/App.css didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/App.js didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/App.test.js didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/Availability.js didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/DiningNames.js didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/DiningSearch.js didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/DiningSearches.js didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/DiningTypes.js didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/SearchDefForm.js didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/TimeWindow.js didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/images/delete.png didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/index.css didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/index.js didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/logo.svg didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/reportWebVitals.js didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/setupTests.js didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug icons/hungryman.png matched [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> excluded
┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug templates/appSSOInstance.yaml matched [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> excluded
┃ ┃ ┃ ┃ ┃ Debug templates/clientRegistrationResourceClaim.yaml matched [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> excluded
┃ ┃ ┃ ┃ ┃ Debug templates/mysqlInstance.yaml matched [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> excluded
┃ ┃ ┃ ┃ ┃ Debug templates/mysqlResourceClaim.yaml matched [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> excluded
┃ ┃ ┃ ┃ ┃ Debug templates/rmqCluster.yaml matched [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> excluded
┃ ┃ ┃ ┃ ┃ Debug templates/rmqResourceClaim.yaml matched [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> excluded
┃ ┃ ┃ ┃ ┗ Debug templates/workloads.yaml matched [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> excluded
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Include, chain...)
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[1].<combo> (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, YTT, RewritePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[1].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**/templates/workloads.yaml]
┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-api-gateway/hungryman-api-gateway.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-availability/hungryman-availability.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-notify/hungryman-notify.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-search/hungryman-search.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-search-proc/hungryman-search-proc.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-ui/hungryman-ui.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/groups/org.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/db/hungryman-db-resource.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/messaging/hungryman-messaging-resource.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/systems/hungryman-system.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/TAPDeployment.md didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/AppHomeScreen.png didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/HungrymanHighLevelArch.png didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/KNativeEventing.png didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/SCSMessaging.png didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-api-gateway/.gitignore didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-api-gateway/Tiltfile didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-api-gateway/config/workload.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-api-gateway/pom.xml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-api-gateway/src/main/java/com/java/example/tanzu/hungryman/HungrymanAPIGatewayApplication.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-api-gateway/src/main/resources/application.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/.gitignore didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/.mvn/wrapper/maven-wrapper.properties didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/Tiltfile didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/config/workload.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/mvnw didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/mvnw.cmd didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/pom.xml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/HungrymanAvailabilityApplication.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/config/OAuth2BindingsPropertiesProcessor.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/config/WebSecurityConfig.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/entity/Availability.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/entity/AvailabilityWindow.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/function/AvailabilitySink.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/model/Availability.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/repository/AvailabilityRepository.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/repository/AvailabilityWindowRepository.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/resources/AvailabilityResource.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/resources/META-INF/spring.factories didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/resources/application.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/resources/schema.sql didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/test/java/com/java/example/tanzu/hungryman/HungrymanAvailabilityApplicationTests.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/.gitignore didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/.mvn/wrapper/maven-wrapper.properties didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/config/workload.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/mvnw didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/mvnw.cmd didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/pom.xml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/src/main/java/com/java/example/tanzu/hungryman/HungrymanCrawlerApplication.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/src/main/java/com/java/example/tanzu/hungryman/model/Availability.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/src/main/java/com/java/example/tanzu/hungryman/model/SearchCriteria.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/src/main/java/com/java/example/tanzu/hungryman/resources/SearchResource.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/src/main/resources/application.properties didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/src/test/java/com/java/example/tanzu/hungryman/HungrymanCrawlerApplicationTests.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/.gitignore didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/.mvn/wrapper/maven-wrapper.properties didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/README.md didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/Tiltfile didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/config/workload.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/mvnw didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/mvnw.cmd didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/pom.xml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/HungrymanNotifyApplication.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/config/EmailMessageConfigProperties.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/config/PublisherConfiguration.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/functions/AvailabilitySink.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/model/Availability.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/publisher/EmailPublisher.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/publisher/LoggerPublisher.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/publisher/Publisher.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/resources/application.yml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/test/java/com/java/example/tanzu/hungryman/HungrymanNotifyApplicationTests.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/.gitignore didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/.mvn/wrapper/maven-wrapper.properties didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/README.md didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/Tiltfile didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/catalog-info.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/config/workload.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/mvnw didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/mvnw.cmd didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/pom.xml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/java/com/java/example/tanzu/hungryman/HungrymanResApplication.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/java/com/java/example/tanzu/hungryman/config/OAuth2BindingsPropertiesProcessor.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/java/com/java/example/tanzu/hungryman/config/WebSecurityConfig.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/java/com/java/example/tanzu/hungryman/entity/Search.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/java/com/java/example/tanzu/hungryman/functions/SearchSupplier.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/java/com/java/example/tanzu/hungryman/repository/SearchRepository.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/java/com/java/example/tanzu/hungryman/resources/SearchResource.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/resources/META-INF/spring.factories didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/resources/application.yml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/resources/schema.sql didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/test/java/com/java/example/tanzu/hungryman/HungrymanResApplicationTests.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/test/java/com/java/example/tanzu/hungryman/SpringBaseTest.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/test/java/com/java/example/tanzu/hungryman/repository/SearchRepositoryTest.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/test/resources/application.yml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/.gitignore didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/.mvn/wrapper/maven-wrapper.properties didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/README.md didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/Tiltfile didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/config/workload.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/mvnw didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/mvnw.cmd didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/pom.xml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/HungrymanSearchProcApplication.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/config/StaticDiningAvailability.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/feign/CrawlerClient.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/functions/Search.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/model/Availability.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/model/SearchCriteria.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/processor/SearchProcessor.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/processor/cache/HashCache.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/processor/cache/MemoryHashCache.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/searcher/Searcher.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/searcher/impl/CrawlerSearcher.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/searcher/impl/LocalRandomSearcher.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/resources/application.yml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/test/java/com/java/example/tanzu/hungryman/HungrymanSearchProcApplicationTests.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/.gitignore didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/README.md didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/httpproxy.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/package-lock.json didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/package.json didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/public/favicon.png didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/public/index.html didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/public/manifest.json didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/public/robots.txt didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/App.css didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/App.js didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/App.test.js didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/Availability.js didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/DiningNames.js didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/DiningSearch.js didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/DiningSearches.js didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/DiningTypes.js didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/SearchDefForm.js didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/TimeWindow.js didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/images/delete.png didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/index.css didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/index.js didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/logo.svg didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/reportWebVitals.js didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/setupTests.js didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug icons/hungryman.png didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/appSSOInstance.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/clientRegistrationResourceClaim.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/mysqlInstance.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/mysqlResourceClaim.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqCluster.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqResourceClaim.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug templates/workloads.yaml matched [**/templates/workloads.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[1].<combo>.transformations[1] (YTT)
┃ ┃ ┃ ┃ ┃ ┃ Debug Wrote values file with json content:   {"devDefaultAccountUsername":"hungryman","artifactVersion":"0.0.1-beta","dbName":"db-hungryman","dbType":"mysql","rabbitMQName":"rmq-hungryman","devDefaultAccountPassword":"$2a$10$J/EWz6Q8zxRHYCr2UwJewe5hN6uKhbytUuGGC2yHvEJ2zhH.dLvZe","appSSOIssuerURI":"http://authserver.<domainname>","enableSecurity":false,"createRabbitMQCluster":true,"appSSOName":"appsso-hungryman","createResourceClaim":true,"numRabbitMQClusterNodes":1,"enableDefaultDevAccount":true,"artifactId":"hungryman","createDBInstance":true,"serviceNamespace":"service-instances","projectName":"hungryman","workloadNamespace":"dev","appSSORedirectURI":"http://hungryman.<domain name>/login/oauth2/code/sso"}
┃ ┃ ┃ ┃ ┃ ┗  Info Shelling out to YTT with args: [ytt, -f, /tmp/ytt-input8657495303094564976, --data-values-file, /tmp/accelerator-options12575681588062765311.json, --output-files, /tmp/ytt-output10391098289335190677]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[1].<combo>.transformations[2] (RewritePath)
┃ ┃ ┃ ┃ ┗ ┗ Debug Path 'templates/workloads.yaml' matched 'templates/workloads.yaml' with groups {g0=templates/workloads.yaml} and was rewritten to 'config/developer/workloads.yaml'
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[2] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#createRabbitMQCluster) evaluated to true
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Include, chain...)
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[2].<combo> (Chain)
┃ ┃ ┃ ┃ ┃  Info Condition (#createRabbitMQCluster) evaluated to true
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, YTT, RewritePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[2].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**/rmqCluster.yaml]
┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-api-gateway/hungryman-api-gateway.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-availability/hungryman-availability.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-notify/hungryman-notify.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-search/hungryman-search.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-search-proc/hungryman-search-proc.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-ui/hungryman-ui.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/groups/org.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/db/hungryman-db-resource.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/messaging/hungryman-messaging-resource.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/systems/hungryman-system.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/TAPDeployment.md didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/AppHomeScreen.png didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/HungrymanHighLevelArch.png didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/KNativeEventing.png didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/SCSMessaging.png didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-api-gateway/.gitignore didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-api-gateway/Tiltfile didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-api-gateway/config/workload.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-api-gateway/pom.xml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-api-gateway/src/main/java/com/java/example/tanzu/hungryman/HungrymanAPIGatewayApplication.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-api-gateway/src/main/resources/application.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/.gitignore didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/.mvn/wrapper/maven-wrapper.properties didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/Tiltfile didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/config/workload.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/mvnw didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/mvnw.cmd didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/pom.xml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/HungrymanAvailabilityApplication.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/config/OAuth2BindingsPropertiesProcessor.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/config/WebSecurityConfig.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/entity/Availability.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/entity/AvailabilityWindow.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/function/AvailabilitySink.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/model/Availability.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/repository/AvailabilityRepository.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/repository/AvailabilityWindowRepository.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/resources/AvailabilityResource.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/resources/META-INF/spring.factories didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/resources/application.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/resources/schema.sql didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/test/java/com/java/example/tanzu/hungryman/HungrymanAvailabilityApplicationTests.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/.gitignore didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/.mvn/wrapper/maven-wrapper.properties didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/config/workload.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/mvnw didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/mvnw.cmd didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/pom.xml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/src/main/java/com/java/example/tanzu/hungryman/HungrymanCrawlerApplication.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/src/main/java/com/java/example/tanzu/hungryman/model/Availability.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/src/main/java/com/java/example/tanzu/hungryman/model/SearchCriteria.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/src/main/java/com/java/example/tanzu/hungryman/resources/SearchResource.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/src/main/resources/application.properties didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/src/test/java/com/java/example/tanzu/hungryman/HungrymanCrawlerApplicationTests.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/.gitignore didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/.mvn/wrapper/maven-wrapper.properties didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/README.md didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/Tiltfile didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/config/workload.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/mvnw didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/mvnw.cmd didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/pom.xml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/HungrymanNotifyApplication.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/config/EmailMessageConfigProperties.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/config/PublisherConfiguration.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/functions/AvailabilitySink.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/model/Availability.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/publisher/EmailPublisher.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/publisher/LoggerPublisher.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/publisher/Publisher.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/resources/application.yml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/test/java/com/java/example/tanzu/hungryman/HungrymanNotifyApplicationTests.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/.gitignore didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/.mvn/wrapper/maven-wrapper.properties didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/README.md didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/Tiltfile didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/catalog-info.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/config/workload.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/mvnw didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/mvnw.cmd didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/pom.xml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/java/com/java/example/tanzu/hungryman/HungrymanResApplication.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/java/com/java/example/tanzu/hungryman/config/OAuth2BindingsPropertiesProcessor.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/java/com/java/example/tanzu/hungryman/config/WebSecurityConfig.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/java/com/java/example/tanzu/hungryman/entity/Search.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/java/com/java/example/tanzu/hungryman/functions/SearchSupplier.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/java/com/java/example/tanzu/hungryman/repository/SearchRepository.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/java/com/java/example/tanzu/hungryman/resources/SearchResource.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/resources/META-INF/spring.factories didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/resources/application.yml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/resources/schema.sql didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/test/java/com/java/example/tanzu/hungryman/HungrymanResApplicationTests.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/test/java/com/java/example/tanzu/hungryman/SpringBaseTest.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/test/java/com/java/example/tanzu/hungryman/repository/SearchRepositoryTest.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/test/resources/application.yml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/.gitignore didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/.mvn/wrapper/maven-wrapper.properties didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/README.md didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/Tiltfile didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/config/workload.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/mvnw didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/mvnw.cmd didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/pom.xml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/HungrymanSearchProcApplication.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/config/StaticDiningAvailability.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/feign/CrawlerClient.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/functions/Search.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/model/Availability.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/model/SearchCriteria.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/processor/SearchProcessor.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/processor/cache/HashCache.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/processor/cache/MemoryHashCache.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/searcher/Searcher.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/searcher/impl/CrawlerSearcher.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/searcher/impl/LocalRandomSearcher.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/resources/application.yml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/test/java/com/java/example/tanzu/hungryman/HungrymanSearchProcApplicationTests.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/.gitignore didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/README.md didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/httpproxy.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/package-lock.json didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/package.json didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/public/favicon.png didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/public/index.html didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/public/manifest.json didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/public/robots.txt didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/App.css didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/App.js didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/App.test.js didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/Availability.js didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/DiningNames.js didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/DiningSearch.js didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/DiningSearches.js didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/DiningTypes.js didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/SearchDefForm.js didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/TimeWindow.js didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/images/delete.png didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/index.css didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/index.js didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/logo.svg didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/reportWebVitals.js didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/setupTests.js didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug icons/hungryman.png didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/appSSOInstance.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/clientRegistrationResourceClaim.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/mysqlInstance.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/mysqlResourceClaim.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqCluster.yaml matched [**/rmqCluster.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqResourceClaim.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug templates/workloads.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[2].<combo>.transformations[1] (YTT)
┃ ┃ ┃ ┃ ┃ ┃ Debug Wrote values file with json content:   {"devDefaultAccountUsername":"hungryman","artifactVersion":"0.0.1-beta","dbName":"db-hungryman","dbType":"mysql","rabbitMQName":"rmq-hungryman","devDefaultAccountPassword":"$2a$10$J/EWz6Q8zxRHYCr2UwJewe5hN6uKhbytUuGGC2yHvEJ2zhH.dLvZe","appSSOIssuerURI":"http://authserver.<domainname>","enableSecurity":false,"createRabbitMQCluster":true,"appSSOName":"appsso-hungryman","createResourceClaim":true,"numRabbitMQClusterNodes":1,"enableDefaultDevAccount":true,"artifactId":"hungryman","createDBInstance":true,"serviceNamespace":"service-instances","projectName":"hungryman","workloadNamespace":"dev","appSSORedirectURI":"http://hungryman.<domain name>/login/oauth2/code/sso"}
┃ ┃ ┃ ┃ ┃ ┗  Info Shelling out to YTT with args: [ytt, -f, /tmp/ytt-input8416763238883517239, --data-values-file, /tmp/accelerator-options14998204053527673235.json, --output-files, /tmp/ytt-output7906741023375262177]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[2].<combo>.transformations[2] (RewritePath)
┃ ┃ ┃ ┃ ┗ ┗ Debug Path 'templates/rmqCluster.yaml' matched 'templates/rmqCluster.yaml' with groups {g0=templates/rmqCluster.yaml} and was rewritten to 'config/service-operator/rmqCluster.yaml'
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[3] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#createDBInstance && #dbType == 'mysql') evaluated to true
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Include, chain...)
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[3].<combo> (Chain)
┃ ┃ ┃ ┃ ┃  Info Condition (#createDBInstance && #dbType == 'mysql') evaluated to true
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, YTT, RewritePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[3].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**/mysqlInstance.yaml]
┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-api-gateway/hungryman-api-gateway.yaml didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-availability/hungryman-availability.yaml didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-notify/hungryman-notify.yaml didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-search/hungryman-search.yaml didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-search-proc/hungryman-search-proc.yaml didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-ui/hungryman-ui.yaml didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/groups/org.yaml didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/db/hungryman-db-resource.yaml didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/messaging/hungryman-messaging-resource.yaml didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/systems/hungryman-system.yaml didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/TAPDeployment.md didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/AppHomeScreen.png didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/HungrymanHighLevelArch.png didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/KNativeEventing.png didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/SCSMessaging.png didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-api-gateway/.gitignore didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-api-gateway/Tiltfile didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-api-gateway/config/workload.yaml didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-api-gateway/pom.xml didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-api-gateway/src/main/java/com/java/example/tanzu/hungryman/HungrymanAPIGatewayApplication.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-api-gateway/src/main/resources/application.yaml didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/.gitignore didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/.mvn/wrapper/maven-wrapper.properties didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/Tiltfile didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/config/workload.yaml didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/mvnw didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/mvnw.cmd didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/pom.xml didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/HungrymanAvailabilityApplication.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/config/OAuth2BindingsPropertiesProcessor.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/config/WebSecurityConfig.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/entity/Availability.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/entity/AvailabilityWindow.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/function/AvailabilitySink.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/model/Availability.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/repository/AvailabilityRepository.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/repository/AvailabilityWindowRepository.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/resources/AvailabilityResource.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/resources/META-INF/spring.factories didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/resources/application.yaml didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/resources/schema.sql didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/test/java/com/java/example/tanzu/hungryman/HungrymanAvailabilityApplicationTests.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/.gitignore didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/.mvn/wrapper/maven-wrapper.properties didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/config/workload.yaml didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/mvnw didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/mvnw.cmd didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/pom.xml didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/src/main/java/com/java/example/tanzu/hungryman/HungrymanCrawlerApplication.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/src/main/java/com/java/example/tanzu/hungryman/model/Availability.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/src/main/java/com/java/example/tanzu/hungryman/model/SearchCriteria.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/src/main/java/com/java/example/tanzu/hungryman/resources/SearchResource.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/src/main/resources/application.properties didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/src/test/java/com/java/example/tanzu/hungryman/HungrymanCrawlerApplicationTests.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/.gitignore didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/.mvn/wrapper/maven-wrapper.properties didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/README.md didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/Tiltfile didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/config/workload.yaml didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/mvnw didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/mvnw.cmd didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/pom.xml didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/HungrymanNotifyApplication.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/config/EmailMessageConfigProperties.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/config/PublisherConfiguration.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/functions/AvailabilitySink.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/model/Availability.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/publisher/EmailPublisher.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/publisher/LoggerPublisher.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/publisher/Publisher.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/resources/application.yml didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/test/java/com/java/example/tanzu/hungryman/HungrymanNotifyApplicationTests.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/.gitignore didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/.mvn/wrapper/maven-wrapper.properties didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/README.md didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/Tiltfile didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/catalog-info.yaml didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/config/workload.yaml didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/mvnw didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/mvnw.cmd didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/pom.xml didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/java/com/java/example/tanzu/hungryman/HungrymanResApplication.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/java/com/java/example/tanzu/hungryman/config/OAuth2BindingsPropertiesProcessor.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/java/com/java/example/tanzu/hungryman/config/WebSecurityConfig.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/java/com/java/example/tanzu/hungryman/entity/Search.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/java/com/java/example/tanzu/hungryman/functions/SearchSupplier.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/java/com/java/example/tanzu/hungryman/repository/SearchRepository.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/java/com/java/example/tanzu/hungryman/resources/SearchResource.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/resources/META-INF/spring.factories didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/resources/application.yml didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/resources/schema.sql didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/test/java/com/java/example/tanzu/hungryman/HungrymanResApplicationTests.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/test/java/com/java/example/tanzu/hungryman/SpringBaseTest.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/test/java/com/java/example/tanzu/hungryman/repository/SearchRepositoryTest.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/test/resources/application.yml didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/.gitignore didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/.mvn/wrapper/maven-wrapper.properties didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/README.md didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/Tiltfile didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/config/workload.yaml didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/mvnw didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/mvnw.cmd didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/pom.xml didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/HungrymanSearchProcApplication.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/config/StaticDiningAvailability.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/feign/CrawlerClient.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/functions/Search.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/model/Availability.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/model/SearchCriteria.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/processor/SearchProcessor.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/processor/cache/HashCache.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/processor/cache/MemoryHashCache.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/searcher/Searcher.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/searcher/impl/CrawlerSearcher.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/searcher/impl/LocalRandomSearcher.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/resources/application.yml didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/test/java/com/java/example/tanzu/hungryman/HungrymanSearchProcApplicationTests.java didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/.gitignore didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/README.md didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/httpproxy.yaml didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/package-lock.json didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/package.json didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/public/favicon.png didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/public/index.html didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/public/manifest.json didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/public/robots.txt didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/App.css didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/App.js didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/App.test.js didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/Availability.js didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/DiningNames.js didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/DiningSearch.js didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/DiningSearches.js didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/DiningTypes.js didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/SearchDefForm.js didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/TimeWindow.js didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/images/delete.png didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/index.css didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/index.js didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/logo.svg didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/reportWebVitals.js didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/setupTests.js didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug icons/hungryman.png didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/appSSOInstance.yaml didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/clientRegistrationResourceClaim.yaml didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/mysqlInstance.yaml matched [**/mysqlInstance.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/mysqlResourceClaim.yaml didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqCluster.yaml didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqResourceClaim.yaml didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug templates/workloads.yaml didn't match [**/mysqlInstance.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[3].<combo>.transformations[1] (YTT)
┃ ┃ ┃ ┃ ┃ ┃ Debug Wrote values file with json content:   {"devDefaultAccountUsername":"hungryman","artifactVersion":"0.0.1-beta","dbName":"db-hungryman","dbType":"mysql","rabbitMQName":"rmq-hungryman","devDefaultAccountPassword":"$2a$10$J/EWz6Q8zxRHYCr2UwJewe5hN6uKhbytUuGGC2yHvEJ2zhH.dLvZe","appSSOIssuerURI":"http://authserver.<domainname>","enableSecurity":false,"createRabbitMQCluster":true,"appSSOName":"appsso-hungryman","createResourceClaim":true,"numRabbitMQClusterNodes":1,"enableDefaultDevAccount":true,"artifactId":"hungryman","createDBInstance":true,"serviceNamespace":"service-instances","projectName":"hungryman","workloadNamespace":"dev","appSSORedirectURI":"http://hungryman.<domain name>/login/oauth2/code/sso"}
┃ ┃ ┃ ┃ ┃ ┗  Info Shelling out to YTT with args: [ytt, -f, /tmp/ytt-input1882173910326335857, --data-values-file, /tmp/accelerator-options8431576381410265135.json, --output-files, /tmp/ytt-output14219082931051359030]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[3].<combo>.transformations[2] (RewritePath)
┃ ┃ ┃ ┃ ┗ ┗ Debug Path 'templates/mysqlInstance.yaml' matched 'templates/mysqlInstance.yaml' with groups {g0=templates/mysqlInstance.yaml} and was rewritten to 'config/service-operator/mysqlInstance.yaml'
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[4] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#createResourceClaim) evaluated to true
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Include, chain...)
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[4].<combo> (Chain)
┃ ┃ ┃ ┃ ┃  Info Condition (#createResourceClaim) evaluated to true
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, YTT, RewritePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[4].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**/rmqResourceClaim.yaml]
┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-api-gateway/hungryman-api-gateway.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-availability/hungryman-availability.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-notify/hungryman-notify.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-search/hungryman-search.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-search-proc/hungryman-search-proc.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-ui/hungryman-ui.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/groups/org.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/db/hungryman-db-resource.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/messaging/hungryman-messaging-resource.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/systems/hungryman-system.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/TAPDeployment.md didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/AppHomeScreen.png didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/HungrymanHighLevelArch.png didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/KNativeEventing.png didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/SCSMessaging.png didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-api-gateway/.gitignore didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-api-gateway/Tiltfile didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-api-gateway/config/workload.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-api-gateway/pom.xml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-api-gateway/src/main/java/com/java/example/tanzu/hungryman/HungrymanAPIGatewayApplication.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-api-gateway/src/main/resources/application.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/.gitignore didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/.mvn/wrapper/maven-wrapper.properties didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/Tiltfile didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/config/workload.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/mvnw didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/mvnw.cmd didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/pom.xml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/HungrymanAvailabilityApplication.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/config/OAuth2BindingsPropertiesProcessor.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/config/WebSecurityConfig.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/entity/Availability.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/entity/AvailabilityWindow.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/function/AvailabilitySink.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/model/Availability.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/repository/AvailabilityRepository.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/repository/AvailabilityWindowRepository.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/resources/AvailabilityResource.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/resources/META-INF/spring.factories didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/resources/application.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/resources/schema.sql didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/test/java/com/java/example/tanzu/hungryman/HungrymanAvailabilityApplicationTests.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/.gitignore didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/.mvn/wrapper/maven-wrapper.properties didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/config/workload.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/mvnw didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/mvnw.cmd didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/pom.xml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/src/main/java/com/java/example/tanzu/hungryman/HungrymanCrawlerApplication.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/src/main/java/com/java/example/tanzu/hungryman/model/Availability.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/src/main/java/com/java/example/tanzu/hungryman/model/SearchCriteria.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/src/main/java/com/java/example/tanzu/hungryman/resources/SearchResource.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/src/main/resources/application.properties didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/src/test/java/com/java/example/tanzu/hungryman/HungrymanCrawlerApplicationTests.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/.gitignore didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/.mvn/wrapper/maven-wrapper.properties didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/README.md didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/Tiltfile didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/config/workload.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/mvnw didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/mvnw.cmd didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/pom.xml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/HungrymanNotifyApplication.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/config/EmailMessageConfigProperties.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/config/PublisherConfiguration.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/functions/AvailabilitySink.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/model/Availability.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/publisher/EmailPublisher.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/publisher/LoggerPublisher.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/publisher/Publisher.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/resources/application.yml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/test/java/com/java/example/tanzu/hungryman/HungrymanNotifyApplicationTests.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/.gitignore didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/.mvn/wrapper/maven-wrapper.properties didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/README.md didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/Tiltfile didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/catalog-info.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/config/workload.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/mvnw didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/mvnw.cmd didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/pom.xml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/java/com/java/example/tanzu/hungryman/HungrymanResApplication.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/java/com/java/example/tanzu/hungryman/config/OAuth2BindingsPropertiesProcessor.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/java/com/java/example/tanzu/hungryman/config/WebSecurityConfig.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/java/com/java/example/tanzu/hungryman/entity/Search.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/java/com/java/example/tanzu/hungryman/functions/SearchSupplier.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/java/com/java/example/tanzu/hungryman/repository/SearchRepository.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/java/com/java/example/tanzu/hungryman/resources/SearchResource.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/resources/META-INF/spring.factories didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/resources/application.yml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/resources/schema.sql didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/test/java/com/java/example/tanzu/hungryman/HungrymanResApplicationTests.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/test/java/com/java/example/tanzu/hungryman/SpringBaseTest.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/test/java/com/java/example/tanzu/hungryman/repository/SearchRepositoryTest.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/test/resources/application.yml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/.gitignore didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/.mvn/wrapper/maven-wrapper.properties didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/README.md didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/Tiltfile didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/config/workload.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/mvnw didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/mvnw.cmd didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/pom.xml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/HungrymanSearchProcApplication.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/config/StaticDiningAvailability.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/feign/CrawlerClient.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/functions/Search.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/model/Availability.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/model/SearchCriteria.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/processor/SearchProcessor.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/processor/cache/HashCache.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/processor/cache/MemoryHashCache.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/searcher/Searcher.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/searcher/impl/CrawlerSearcher.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/searcher/impl/LocalRandomSearcher.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/resources/application.yml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/test/java/com/java/example/tanzu/hungryman/HungrymanSearchProcApplicationTests.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/.gitignore didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/README.md didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/httpproxy.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/package-lock.json didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/package.json didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/public/favicon.png didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/public/index.html didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/public/manifest.json didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/public/robots.txt didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/App.css didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/App.js didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/App.test.js didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/Availability.js didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/DiningNames.js didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/DiningSearch.js didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/DiningSearches.js didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/DiningTypes.js didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/SearchDefForm.js didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/TimeWindow.js didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/images/delete.png didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/index.css didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/index.js didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/logo.svg didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/reportWebVitals.js didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/setupTests.js didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug icons/hungryman.png didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/appSSOInstance.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/clientRegistrationResourceClaim.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/mysqlInstance.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/mysqlResourceClaim.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqCluster.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqResourceClaim.yaml matched [**/rmqResourceClaim.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┗ Debug templates/workloads.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[4].<combo>.transformations[1] (YTT)
┃ ┃ ┃ ┃ ┃ ┃ Debug Wrote values file with json content:   {"devDefaultAccountUsername":"hungryman","artifactVersion":"0.0.1-beta","dbName":"db-hungryman","dbType":"mysql","rabbitMQName":"rmq-hungryman","devDefaultAccountPassword":"$2a$10$J/EWz6Q8zxRHYCr2UwJewe5hN6uKhbytUuGGC2yHvEJ2zhH.dLvZe","appSSOIssuerURI":"http://authserver.<domainname>","enableSecurity":false,"createRabbitMQCluster":true,"appSSOName":"appsso-hungryman","createResourceClaim":true,"numRabbitMQClusterNodes":1,"enableDefaultDevAccount":true,"artifactId":"hungryman","createDBInstance":true,"serviceNamespace":"service-instances","projectName":"hungryman","workloadNamespace":"dev","appSSORedirectURI":"http://hungryman.<domain name>/login/oauth2/code/sso"}
┃ ┃ ┃ ┃ ┃ ┗  Info Shelling out to YTT with args: [ytt, -f, /tmp/ytt-input4624432426067865620, --data-values-file, /tmp/accelerator-options14200251357339283585.json, --output-files, /tmp/ytt-output17679126087206884186]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[4].<combo>.transformations[2] (RewritePath)
┃ ┃ ┃ ┃ ┗ ┗ Debug Path 'templates/rmqResourceClaim.yaml' matched 'templates/rmqResourceClaim.yaml' with groups {g0=templates/rmqResourceClaim.yaml} and was rewritten to 'config/app-operator/rmqResourceClaim.yaml'
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[5] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#createResourceClaim && #dbType == 'mysql') evaluated to true
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Include, chain...)
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[5].<combo> (Chain)
┃ ┃ ┃ ┃ ┃  Info Condition (#createResourceClaim && #dbType == 'mysql') evaluated to true
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, YTT, RewritePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[5].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**/mysqlResourceClaim.yaml]
┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-api-gateway/hungryman-api-gateway.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-availability/hungryman-availability.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-notify/hungryman-notify.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-search/hungryman-search.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-search-proc/hungryman-search-proc.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-ui/hungryman-ui.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/groups/org.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/db/hungryman-db-resource.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/messaging/hungryman-messaging-resource.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/systems/hungryman-system.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/TAPDeployment.md didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/AppHomeScreen.png didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/HungrymanHighLevelArch.png didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/KNativeEventing.png didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/SCSMessaging.png didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-api-gateway/.gitignore didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-api-gateway/Tiltfile didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-api-gateway/config/workload.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-api-gateway/pom.xml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-api-gateway/src/main/java/com/java/example/tanzu/hungryman/HungrymanAPIGatewayApplication.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-api-gateway/src/main/resources/application.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/.gitignore didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/.mvn/wrapper/maven-wrapper.properties didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/Tiltfile didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/config/workload.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/mvnw didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/mvnw.cmd didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/pom.xml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/HungrymanAvailabilityApplication.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/config/OAuth2BindingsPropertiesProcessor.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/config/WebSecurityConfig.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/entity/Availability.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/entity/AvailabilityWindow.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/function/AvailabilitySink.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/model/Availability.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/repository/AvailabilityRepository.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/repository/AvailabilityWindowRepository.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/java/com/java/example/tanzu/hungryman/resources/AvailabilityResource.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/resources/META-INF/spring.factories didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/resources/application.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/main/resources/schema.sql didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-availability/src/test/java/com/java/example/tanzu/hungryman/HungrymanAvailabilityApplicationTests.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/.gitignore didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/.mvn/wrapper/maven-wrapper.properties didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/config/workload.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/mvnw didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/mvnw.cmd didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/pom.xml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/src/main/java/com/java/example/tanzu/hungryman/HungrymanCrawlerApplication.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/src/main/java/com/java/example/tanzu/hungryman/model/Availability.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/src/main/java/com/java/example/tanzu/hungryman/model/SearchCriteria.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/src/main/java/com/java/example/tanzu/hungryman/resources/SearchResource.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/src/main/resources/application.properties didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-crawler/src/test/java/com/java/example/tanzu/hungryman/HungrymanCrawlerApplicationTests.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/.gitignore didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/.mvn/wrapper/maven-wrapper.properties didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/README.md didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/Tiltfile didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/config/workload.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/mvnw didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/mvnw.cmd didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/pom.xml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/HungrymanNotifyApplication.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/config/EmailMessageConfigProperties.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/config/PublisherConfiguration.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/functions/AvailabilitySink.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/model/Availability.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/publisher/EmailPublisher.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/publisher/LoggerPublisher.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/java/com/java/example/tanzu/hungryman/publisher/Publisher.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/main/resources/application.yml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-notify/src/test/java/com/java/example/tanzu/hungryman/HungrymanNotifyApplicationTests.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/.gitignore didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/.mvn/wrapper/maven-wrapper.properties didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/README.md didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/Tiltfile didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/catalog-info.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/config/workload.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/mvnw didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/mvnw.cmd didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/pom.xml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/java/com/java/example/tanzu/hungryman/HungrymanResApplication.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/java/com/java/example/tanzu/hungryman/config/OAuth2BindingsPropertiesProcessor.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/java/com/java/example/tanzu/hungryman/config/WebSecurityConfig.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/java/com/java/example/tanzu/hungryman/entity/Search.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/java/com/java/example/tanzu/hungryman/functions/SearchSupplier.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/java/com/java/example/tanzu/hungryman/repository/SearchRepository.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/java/com/java/example/tanzu/hungryman/resources/SearchResource.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/resources/META-INF/spring.factories didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/resources/application.yml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/main/resources/schema.sql didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/test/java/com/java/example/tanzu/hungryman/HungrymanResApplicationTests.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/test/java/com/java/example/tanzu/hungryman/SpringBaseTest.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/test/java/com/java/example/tanzu/hungryman/repository/SearchRepositoryTest.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search/src/test/resources/application.yml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/.gitignore didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/.mvn/wrapper/maven-wrapper.properties didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/README.md didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/Tiltfile didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/config/workload.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/mvnw didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/mvnw.cmd didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/pom.xml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/HungrymanSearchProcApplication.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/config/StaticDiningAvailability.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/feign/CrawlerClient.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/functions/Search.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/model/Availability.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/model/SearchCriteria.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/processor/SearchProcessor.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/processor/cache/HashCache.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/processor/cache/MemoryHashCache.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/searcher/Searcher.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/searcher/impl/CrawlerSearcher.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/java/com/java/example/tanzu/hungryman/searcher/impl/LocalRandomSearcher.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/main/resources/application.yml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-search-proc/src/test/java/com/java/example/tanzu/hungryman/HungrymanSearchProcApplicationTests.java didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/.gitignore didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/README.md didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/httpproxy.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/package-lock.json didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/package.json didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/public/favicon.png didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/public/index.html didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/public/manifest.json didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/public/robots.txt didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/App.css didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/App.js didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/App.test.js didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/Availability.js didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/DiningNames.js didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/DiningSearch.js didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/DiningSearches.js didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/DiningTypes.js didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/SearchDefForm.js didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/TimeWindow.js didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/images/delete.png didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/index.css didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/index.js didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/logo.svg didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/reportWebVitals.js didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug hungryman-ui/src/setupTests.js didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug icons/hungryman.png didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/appSSOInstance.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/clientRegistrationResourceClaim.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/mysqlInstance.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/mysqlResourceClaim.yaml matched [**/mysqlResourceClaim.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqCluster.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqResourceClaim.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug templates/workloads.yaml didn't match [**/mysqlResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[5].<combo>.transformations[1] (YTT)
┃ ┃ ┃ ┃ ┃ ┃ Debug Wrote values file with json content:   {"devDefaultAccountUsername":"hungryman","artifactVersion":"0.0.1-beta","dbName":"db-hungryman","dbType":"mysql","rabbitMQName":"rmq-hungryman","devDefaultAccountPassword":"$2a$10$J/EWz6Q8zxRHYCr2UwJewe5hN6uKhbytUuGGC2yHvEJ2zhH.dLvZe","appSSOIssuerURI":"http://authserver.<domainname>","enableSecurity":false,"createRabbitMQCluster":true,"appSSOName":"appsso-hungryman","createResourceClaim":true,"numRabbitMQClusterNodes":1,"enableDefaultDevAccount":true,"artifactId":"hungryman","createDBInstance":true,"serviceNamespace":"service-instances","projectName":"hungryman","workloadNamespace":"dev","appSSORedirectURI":"http://hungryman.<domain name>/login/oauth2/code/sso"}
┃ ┃ ┃ ┃ ┃ ┗  Info Shelling out to YTT with args: [ytt, -f, /tmp/ytt-input7549691467791888848, --data-values-file, /tmp/accelerator-options11265107828420724310.json, --output-files, /tmp/ytt-output15681191040818511518]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[5].<combo>.transformations[2] (RewritePath)
┃ ┃ ┃ ┃ ┗ ┗ Debug Path 'templates/mysqlResourceClaim.yaml' matched 'templates/mysqlResourceClaim.yaml' with groups {g0=templates/mysqlResourceClaim.yaml} and was rewritten to 'config/app-operator/mysqlResourceClaim.yaml'
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[6] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#enableSecurity) evaluated to false
┃ ┃ ┃ ┗ ┗ null ()
┃ ┗ ┗ ╺ engine.transformations[0].validated.merge.transformations[1] (UniquePath)
┗ ╺ engine.transformations[1] (UniquePath)
```
