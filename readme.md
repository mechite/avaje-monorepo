<a name="readme-top"></a>

<div align="center">


  <!--Logo-->
  <a href="https://github.com/avaje">
    <img src="https://raw.githubusercontent.com/avaje/.github/refs/heads/main/profile/logo.svg" alt="Logo" width="40%">
  </a>

  <!--Title-->
  <h3 align="center">Compile-time libraries for JVM applications</h3>

  <a href="https://avaje.io" style="margin: 1em"><strong>View the documentation →</strong></a>

  <!--License badge-->
  <a href="https://github.com/javalin/javalin/blob/master/LICENSE">
    <img alt="Static Badge" src="https://img.shields.io/badge/License-Apache_2.0-blue">
  </a>
  <!--Discord badge-->
  <a href="https://discord.gg/Qcqf9R27BR">
    <img alt="Discord Link" src="https://img.shields.io/badge/discord-avaje-blue?logo=discord&logoColor=white">
  </a>
</div>
<br>

| Library | Description |
| :--- | :--- |
| [Dependency Injection](./avaje-inject) | Cloud Native/Kubernetes friendly dependency injection via source code generation instead of expensive reflection and classpath scanning. <br> It includes bean lifecycle support and component testing. |
| [Jsonb](./avaje-jsonb) | Flexible and reflection-free JSON library that uses Java annotation processing to generate JSON adapters. One of the top 3 fastest Java JSON libraries. |
| [Validator](./avaje-validator) | Reflection-free POJO validation library that uses annotation processing to generate validation adapters to run constraints. |
| [HTTP Client](./avaje-http/http-client/) | A wrapper on JDK 11's HttpClient. Includes support for defining client API's similar to JAX-RS, Retrofit and Feign. Uses Java annotation processing to generate client API implementations. |
| [Jex](./avaje-jex) | Lightweight wrapper over the JDK's own built-in HTTP server, adding various capabilities. (virtual threads, JSON, compression, etc.). |
| [HTTP Generator](./avaje-http/) | Lightweight JAX-RS style HTTP servers using Helidon SE, Javalin, or Jex. Use annotations like `@Controller`, `@Get` etc to define a REST API. <br> <br> Uses Java annotation processing to generate source code for adapting and registering JAX-RS style classes to servers. These annotation processors are included in Jex and Nima. |
| [Configuration](./avaje-config) | Provides external configuration. Loads YAML, TOML & properties files, supports dynamic configuration and plugins. |
| [Nima](./avaje-nima) | Combines avaje libraries with Helidon SE webserver to provide a lightweight, fast, and GraalVM native image compatible framework. |
| [Simple logger](./avaje-simple-logger) | A SLF4J compatible simple logger that logs to System out with structured JSON. Lightweight and GraalVM native image compatible. |
| [Prisms](./avaje-prisms) | Zero-dependency utility library for building annotation processors. |
| [SPI Service](./avaje-spi-service) | Zero-dependency library that adds SPI `META-INF/services` entries for classes and validates modular `provides` clauses. |
