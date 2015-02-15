# EXPERIMENTAL OpenShift Spring Boot

Install by using [this URL](https://raw.githubusercontent.com/cedricziel/openshift-cartridge-springboot/master/metadata/manifest.yml) as custom cartridge definition

Documentation follows once stable

```
rhc app create bootservice \
http://cartreflect-claytondev.rhcloud.com/reflect?github=cedricziel/openshift-cartridge-springboot
```

## Goals

* Template for Microservices with Spring Boot
* Gradle or Maven
* Scalable (hence custom cartridge, not diy)
