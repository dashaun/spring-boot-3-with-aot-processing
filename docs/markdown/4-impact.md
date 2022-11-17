## GraalVM AOT

---

## Native Build

```bash
./mvnw -Pnative native:compile
```

---

## Build Time

```text
Finished generating 'demo' in 6m 11s.
```

---

## Startup Time

```bash
./target/demo
```

---

## Test it

```bash
http :8080/actuator/health
```

---

## Memory at runtime

```bash
vmmap [PID] | grep Physical
```

---

## Buildpack

```bash
./mvnw -Pnative spring-boot:build-image
```

---

## Buildpack Build Time

```text
[INFO] Successfully built image 'docker.io/library/demo:0.0.1-SNAPSHOT'
[INFO] 
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  05:36 min
```

---

## Keep in mind

- Architecture Specific