## Mean Time To Dopamine

#### A very important metric

---

#### Who is using M1 or Raspberry Pi

---

## GraalVM JIT

```bash
curl https://start.spring.io/starter.tgz \
-d dependencies=web,actuator \
-d javaVersion=17 \
-d bootVersion=3.0.0-RC2 \
-d type=maven-project | tar -xzf -

```

---

## Build Time

```bash
./mvnw clean package
```

---

## Build Time

```bash
mvnd clean package
```

---

### Startup Time

```bash
./mvnw spring-boot:run
```

---

### Test it

```bash
http :8080/actuator/health
```

---

### Memory at runtime

```bash
vmmap [PROCCESS_ID] | grep Physical
```

---

## Buildpack

```bash
./mvnw spring-boot:build-image
```