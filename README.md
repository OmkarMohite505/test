### Spring Security

### Weather GET API Endpoint
```bash
https://home.openweathermap.org/
https://api.openweathermap.org/data/2.5/weather?lat=73.75&lon=18.64&appid=ccfcadc9a73d82ec42c90a6ea4829810
```

### Get State and Cities List
```bash
https://cdn-api.co-vin.in/api/v2/admin/location/districts/1
https://cdn-api.co-vin.in/api/v2/admin/location/states
```

### Google Map Implementation
<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1890.2043639616168!2d73.75686630183439!3d18.64564600146357!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3bc2b9f04635518b%3A0xea525f504f61f2a4!2sInstitute%20for%20Advanced%20Computing%20%26%20Software%20Development!5e0!3m2!1sen!2sin!4v1722578185236!5m2!1sen!2sin" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>

### Deployment
https://my-app-test11.azurewebsites.net/swagger/index.html

```bash
<dependency>
			<groupId>org.springdoc</groupId>
			<artifactId>springdoc-openapi-starter-webmvc-ui</artifactId>
			<version>2.1.0</version>
		</dependency>
```

### DB properites
```bash
spring.datasource.url=jdbc:mysql://localhost:3306/springsecurity?createDatabaseIfNotExist=true&useSSL=false&allowPublicKeyRetrieval=true
#spring.datasource.url=jdbc:mysql://database-1.cnfjksdjkfu.ap-south-3.rds.amazonaws.com:3306/meetyourdoctor?createDatabaseIfNotExist=true&useSSL=false&allowPublicKeyRetrieval=true
spring.datasource.username=root
spring.datasource.password=root

# JPA properties
spring.jpa.show-sql = true
spring.jpa.hibernate.ddl-auto = update
```


