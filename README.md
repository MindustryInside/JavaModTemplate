# Java Mod Template

## Building
First, make sure you have JDK 14 installed. Then, setup [mod.json](assets/mod.json) and run the following commands:

### Windows

* Desktop only: `gradlew desktop`
* Desktop & Android: `gradlew dist`

### *nix/Mac OS

* Desktop only: `./gradlew desktop`
* Desktop & Android: `./gradlew dist`

Note that Android build requires Android `build-tools` >= `28`

### Troubleshooting

* If the terminal returns `Permission denied` or `Command not found`, run `chmod +x ./gradlew`.
