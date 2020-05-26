# Set up Elasticsearch 安装ES
*This section includes information on how to setup Elasticsearch and get it running, including:*  
本章包含如何安装并运行ElasticSearch的信息，包括：

* Downloading
* Installing
* Starting
* Configuring

## Supported platforms 支持的平台

*The matrix of officially supported operating systems and JVMs is available here: Support Matrix. Elasticsearch is tested on the listed platforms, but it is possible that it will work on other platforms too.*

## Java (JVM) Version Java版本
*Elasticsearch is built using Java, and includes a bundled version of OpenJDK from the JDK maintainers (GPLv2+CE) within each distribution. The bundled JVM is the recommended JVM and is located within the jdk directory of the Elasticsearch home directory.*

*To use your own version of Java, set the JAVA_HOME environment variable. If you must use a version of Java that is different from the bundled JVM, we recommend using a supported LTS version of Java. Elasticsearch will refuse to start if a known-bad version of Java is used. The bundled JVM directory may be removed when using your own JVM.*