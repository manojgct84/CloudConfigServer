# CloudConfigServer

## To enable cloud config 
```
  Add @EnableAutoConfiguration
```

### Properties 

```
  spring.cloud.config.server.native.search-locations - Location where the property is present
  spring.cloud.config.server.git.uri:  - Location forom the repo
```

### Profile
 ```
   Launch the Config Server with spring.profiles.active=native
 ```   