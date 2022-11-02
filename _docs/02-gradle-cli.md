# Gradle CLI

gradle init

gradle tasks --all

## Tasks runnable from root project 'BasicGradle'

Build Setup tasks
-----------------
init - Initializes a new Gradle build.
wrapper - Generates Gradle wrapper files.

Help tasks
----------
buildEnvironment    - Displays all buildscript dependencies declared in root project 'BasicGradle'.
dependencies        - Displays all dependencies declared in root project 'BasicGradle'.
dependencyInsight   - Displays the insight into a specific dependency in root project 'BasicGradle'.
help                - Displays a help message.
javaToolchains      - Displays the detected java toolchains.
outgoingVariants    - Displays the outgoing variants of root project 'BasicGradle'.
projects            - Displays the sub-projects of root project 'BasicGradle'.
properties          - Displays the properties of root project 'BasicGradle'.
resolvableConfigurations - Displays the configurations that can be resolved in root project 'BasicGradle'.
tasks               - Displays the tasks runnable from root project 'BasicGradle'.

Other tasks
-----------
components          - Displays the components produced by root project 'BasicGradle'. [deprecated]
dependentComponents - Displays the dependent components of components in root project 'BasicGradle'. [deprecated]
model               - Displays the configuration model of root project 'BasicGradle'. [deprecated]
prepareKotlinBuildScriptModel

## Running tasks

gradle -q hello

What does -q do?

Most of the examples in this user guide are run with the -q command-line option. 
This suppresses Gradle’s log messages, so that only the output of the tasks is shown. 
This keeps the example output in this user guide a little clearer. 
You don’t need to use this option if you don’t want to. 
See Logging for more details about the command-line options which affect Gradle’s output.


