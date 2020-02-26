apply plugin: “java”
apply plugin: “application”

task wrapper(type: Wrapper) {
    gradleVersion = '1.12'
}
