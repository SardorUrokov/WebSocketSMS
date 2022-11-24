
***https://www.twilio.com/.com***

> Send SMS with Spring Boot App

> In this tutorial, find complete sample code to send a SMS in Java through Spring Boot and display callback messages using WebSockets.

> #TwilioSMS #Websockets

### Setup

- Dependencies in build.gradle file
---

```javascript
dependencies {
    implementation 'org.springframework.boot:spring-boot-starter-websocket'
    implementation 'org.springframework.boot:spring-boot-starter-thymeleaf'
    implementation group: "com.twilio.sdk", name: "twilio", version : "7.47.2"
    testImplementation('org.springframework.boot:spring-boot-starter-test') {
        exclude group: 'org.junit.vintage', module: 'junit-vintage-engine'
    }
}

```

---

<!-- 
> ngrok allows you to expose a web server running on your local machine to the internet. By informing the port #, we can expose the localhost

```shell
$ ./ngrok http 8080
```

> Run the app by entering the following commands in the terminal

```shell
$ ./gradlew bootRun
```

> Test the app by sending a SMS through localhost:8080
---
 -->
