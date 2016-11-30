# cs-android-archetype

An empty Android application and library with initial configuration.

The intention of this project is to have a base from where projects start. Normally there are plenty of configurations we need to make on top of the new project template so that we can use the project safely. This project provides some of them already configured either as a reference or as a base for a clone. What we provide here is:

- An app and library module
- Updated Gradle version (currently 3.2.1)
- A more complete `.gitignore` with a whole Android, JetBrains and MacOS X template in it
- A default keystore for debug (this eases configuring dependencies like Facebook)
- Several pre-configured tools like:
    - Linters:
        - Checkstyle configuration following [Google convention for Java](https://google.github.io/styleguide/javaguide.html)
        - FindBugs Android configuration
        - PMD Android configuration
    - A shell script and a bat file for importing the Checkstyle configuration into Android Studio
    - [Jacoco unified coverage report generation](https://medium.com/@rafael_toledo/setting-up-an-unified-coverage-report-in-android-with-jacoco-robolectric-and-espresso-ffe239aaf3fa#.xi8eqpkl8)
    - [Test Butler configuration](https://github.com/linkedin/test-butler) with automatic APK instalation via custom gradle plugin
    - Retrolambda configuration (for using Java 8 features)
- Test dependencies already configured
    - Espresso for insturmented tests
    - Robolectric for local tests
- Documentation for the topics of:
    - GIT
    - Style-guide
    - Gradle organization
    - Testing best practices
    - Dependencies
