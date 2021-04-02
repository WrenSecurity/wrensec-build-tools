# Wren Security Build Tools

Project with shared build artefacts (e.g. checkstyle configuration).

## TODO

* This project should be dropped in favor of adding checkstyle and javadoc resources as
additional wrensec-parent artifacts. Our goal should be to minimize number of independent
projects Wren Security has to maintain.

* As far as I can tell there is no value in TestNG components contained in this project.

* Checkstyle configuration should be reviewed (possibly completely rewritten) to comply
with our coding standards - https://github.com/WrenSecurity/wrensec-docs/wiki/Java-Style-Guide.