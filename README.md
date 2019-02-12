# JIB GRADLE BUILD

## build project

```bash
./gradlew build
```

## run tests

```bash
./gradlew test
```

## run app

```bash
./gradlew run
```
## build docker image(layers)

```bash
./gradlew jibBuildTar
```

## test docker image locally

```bash
./gradlew jibDockerBuild
docker run -it --rm myimage
```

