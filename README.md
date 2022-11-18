# PowSyBl Dependencies

PowSyBl Dependencies helps you with dependency management in PowSyBl:
it contains the set of compatible version numbers of PowSyBl repositories.

*Note: If you're looking for a set of PowSyBl artifacts which covers the most common use cases,
go have a look at [PowSyBl Starter](https://github.com/powsybl/powsybl-starter/)!*

## PowSyBl included repositories versions
Below is the table of the set of compatible releases of PowSyBl repositories for each release of `powsybl-dependencies`.

| powsybl-dependencies |                              powsybl-core                              |                              powsybl-open-loadflow                              |                              powsybl-diagram                              |                               powsybl-dynawo                               |                              powsybl-entsoe                              |                             powsybl-network-area-diagram                             |                              powsybl-balances-adjustment                              |
|:--------------------:|:----------------------------------------------------------------------:|:-------------------------------------------------------------------------------:|:-------------------------------------------------------------------------:|:--------------------------------------------------------------------------:|:------------------------------------------------------------------------:|:------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
|        2.0.0         |  [5.0.0](https://github.com/powsybl/powsybl-core/releases/tag/v5.0.0)  | [0.24.0](https://github.com/powsybl/powsybl-open-loadflow/releases/tag/v0.24.0) | [3.0.0](https://github.com/powsybl/powsybl-diagram/releases/tag/v3.0.0)   |  [1.11.0](https://github.com/powsybl/powsybl-dynawo/releases/tag/v1.11.0)  |  [2.0.0](https://github.com/powsybl/powsybl-entsoe/releases/tag/v2.0.0)  |                                        -[^1]                                         |                                         -[^2]                                         |
|        1.3.1         | [4.10.1](https://github.com/powsybl/powsybl-core/releases/tag/v4.10.1) | [0.23.2](https://github.com/powsybl/powsybl-open-loadflow/releases/tag/v0.23.2) | [2.13.0](https://github.com/powsybl/powsybl-diagram/releases/tag/v2.13.0) |  [1.10.0](https://github.com/powsybl/powsybl-dynawo/releases/tag/v1.10.0)  |  [1.6.1](https://github.com/powsybl/powsybl-entsoe/releases/tag/v1.6.1)  | [0.6.0](https://github.com/powsybl/powsybl-network-area-diagram/releases/tag/v0.6.0) | [1.14.0](https://github.com/powsybl/powsybl-balances-adjustment/releases/tag/v1.14.0) |
|        1.3.0         | [4.10.1](https://github.com/powsybl/powsybl-core/releases/tag/v4.10.1) | [0.23.1](https://github.com/powsybl/powsybl-open-loadflow/releases/tag/v0.23.1) | [2.13.0](https://github.com/powsybl/powsybl-diagram/releases/tag/v2.13.0) |  [1.10.0](https://github.com/powsybl/powsybl-dynawo/releases/tag/v1.10.0)  |  [1.6.0](https://github.com/powsybl/powsybl-entsoe/releases/tag/v1.6.0)  | [0.6.0](https://github.com/powsybl/powsybl-network-area-diagram/releases/tag/v0.6.0) | [1.14.0](https://github.com/powsybl/powsybl-balances-adjustment/releases/tag/v1.14.0) |
|        1.2.2         |  [4.9.1](https://github.com/powsybl/powsybl-core/releases/tag/v4.9.1)  | [0.22.0](https://github.com/powsybl/powsybl-open-loadflow/releases/tag/v0.22.0) | [2.12.0](https://github.com/powsybl/powsybl-diagram/releases/tag/v2.12.0) |   [1.9.0](https://github.com/powsybl/powsybl-dynawo/releases/tag/v1.9.0)   |  [1.5.1](https://github.com/powsybl/powsybl-entsoe/releases/tag/v1.5.1)  | [0.5.0](https://github.com/powsybl/powsybl-network-area-diagram/releases/tag/v0.5.0) | [1.13.0](https://github.com/powsybl/powsybl-balances-adjustment/releases/tag/v1.13.0) |
|        1.2.1         |  [4.9.1](https://github.com/powsybl/powsybl-core/releases/tag/v4.9.1)  | [0.21.0](https://github.com/powsybl/powsybl-open-loadflow/releases/tag/v0.21.0) | [2.11.0](https://github.com/powsybl/powsybl-diagram/releases/tag/v2.11.0) |   [1.9.0](https://github.com/powsybl/powsybl-dynawo/releases/tag/v1.9.0)   |  [1.5.1](https://github.com/powsybl/powsybl-entsoe/releases/tag/v1.5.1)  | [0.5.0](https://github.com/powsybl/powsybl-network-area-diagram/releases/tag/v0.5.0) | [1.13.0](https://github.com/powsybl/powsybl-balances-adjustment/releases/tag/v1.13.0) |
|        1.2.0         |  [4.9.0](https://github.com/powsybl/powsybl-core/releases/tag/v4.9.0)  | [0.21.0](https://github.com/powsybl/powsybl-open-loadflow/releases/tag/v0.21.0) | [2.11.0](https://github.com/powsybl/powsybl-diagram/releases/tag/v2.11.0) |   [1.9.0](https://github.com/powsybl/powsybl-dynawo/releases/tag/v1.9.0)   |  [1.5.0](https://github.com/powsybl/powsybl-entsoe/releases/tag/v1.5.0)  | [0.5.0](https://github.com/powsybl/powsybl-network-area-diagram/releases/tag/v0.5.0) | [1.13.0](https://github.com/powsybl/powsybl-balances-adjustment/releases/tag/v1.13.0) |
|        1.1.0         |  [4.8.0](https://github.com/powsybl/powsybl-core/releases/tag/v4.8.0)  | [0.20.0](https://github.com/powsybl/powsybl-open-loadflow/releases/tag/v0.20.0) | [2.10.0](https://github.com/powsybl/powsybl-diagram/releases/tag/v2.10.0) |   [1.8.0](https://github.com/powsybl/powsybl-dynawo/releases/tag/v1.8.0)   |  [1.4.0](https://github.com/powsybl/powsybl-entsoe/releases/tag/v1.4.0)  | [0.4.0](https://github.com/powsybl/powsybl-network-area-diagram/releases/tag/v0.4.0) | [1.12.0](https://github.com/powsybl/powsybl-balances-adjustment/releases/tag/v1.12.0) |
|        1.0.0         |  [4.7.0](https://github.com/powsybl/powsybl-core/releases/tag/v4.7.0)  | [0.19.0](https://github.com/powsybl/powsybl-open-loadflow/releases/tag/v0.19.0) |  [2.9.1](https://github.com/powsybl/powsybl-diagram/releases/tag/v2.9.1)  |   [1.7.0](https://github.com/powsybl/powsybl-dynawo/releases/tag/v1.7.0)   |                                    -                                     | [0.3.0](https://github.com/powsybl/powsybl-network-area-diagram/releases/tag/v0.3.0) |                                           -                                           |

[^1]: [powsybl-network-area-diagram](https://github.com/powsybl/powsybl-network-area-diagram/) has been merged into [powsybl-diagram](https://github.com/powsybl/powsybl-diagram/) in [release 3.0.0](https://github.com/powsybl/powsybl-diagram/releases/tag/v3.0.0).

[^2]: [powsybl-balances-adjustment](https://github.com/powsybl/powsybl-balances-adjustment/) has been merged into [powsybl-entsoe](https://github.com/powsybl/powsybl-entsoe/) in [release 2.0.0](https://github.com/powsybl/powsybl-entsoe/releases/tag/v2.0.0). 

## Getting started
To start using PowSyBl Dependencies, include it in the dependency management of your `pom.xml`

```xml
<dependencyManagement>
    <dependencies>
        <dependency>
            <groupId>com.powsybl</groupId>
            <artifactId>powsybl-dependencies</artifactId>
            <version>2.0.0</version>
            <type>pom</type>
            <scope>import</scope>
        </dependency>
    </dependencies>
</dependencyManagement>
```

Then you can include all PowSyBl artifacts that you need without specifying their version and without worrying whether the versions of each artifact are compatible.


## Example
In this example we'd like to launch an AC loadflow with `powsybl-open-loadflow` and then display the substation diagram thanks to `powsybl-single-line-diagram`.
This is done on a test network included in `powsybl-iidm-tests`, with the default iidm implementation `powsybl-iidm-impl`.

Thanks to `powsybl-dependencies`, we simply need to add in our `pom.xml` the corresponding artifacts without specifying their versions:

```xml
<dependencies>
    <dependency>
        <groupId>com.powsybl</groupId>
        <artifactId>powsybl-iidm-impl</artifactId>
    </dependency>
    <dependency>
        <groupId>com.powsybl</groupId>
        <artifactId>powsybl-iidm-test</artifactId>
    </dependency>
    <dependency>
        <groupId>com.powsybl</groupId>
        <artifactId>powsybl-open-loadflow</artifactId>
    </dependency>
    <dependency>
        <groupId>com.powsybl</groupId>
        <artifactId>powsybl-single-line-diagram-core</artifactId>
    </dependency>
</dependencies>

```

The example mentioned using these four artifacts being:
```java
Network network = FourSubstationsNodeBreakerFactory.create(); // create the test network
LoadFlowResult result = LoadFlow.run(network); // launch AC loadflow
SingleLineDiagram.draw(network, "S1", "/path/to/s1.svg"); // generate the SVG file of S1 single line diagram
```
