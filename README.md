
## Reproduce the problem

```bash
git clone https://github.com/veita/dependency-check-cache-bug.git
cd dependency-check-cache-bug
```

Reproduce the InstanceAlreadyExistsException: org.apache.commons.jcs3:type=JCSAdminBean

```bash
./gradlew dependencyCheckAnalyze
```
