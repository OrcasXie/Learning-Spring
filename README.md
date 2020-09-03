# Learning-Spring
Learning Spring source code based on version 5.2.8.RELEASE.

Prepare:
1. Download the latest [spring-framework-5.2.8.RELEASE](https://github.com/spring-projects/spring-framework/tree/v5.2.8.RELEASE).
2. Ensure the version of Git and JDK is 8 update 262 or later.
3. Precompile `spring-oxm` with `./gradlew :spring-oxm:compileTestJava`
4. Import into IntelliJ and exclude the `spring-aspects` module which uses the AspectJ compiler(ajc), not the default compiler `javac` for IDEA.

For more we can link to the official [README.md](https://github.com/spring-projects/spring-framework/blob/master/README.md) from [spring-framework](https://github.com/spring-projects/spring-framework).

Of course we can build the spring modules by Gradle directly.
