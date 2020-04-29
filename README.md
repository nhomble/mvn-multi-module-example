maven multi module example
==========================

quick sandbox to try out different maven things for multi module projects

## Plugin Configuration Merging
Check the [apache docs](https://maven.apache.org/pom.html#Plugins). The key bit being
```text
You can control how child POMs inherit configuration from parent POMs by adding attributes to the children
of the configuration element. The attributes are combine.children and combine.self. Use these attributes in
a child POM to control how Maven combines plugin configuration from the parent with the explicit configuration 
in the child.
```