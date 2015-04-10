# i0 Java

Use ansible to deploy service. This repository provide two ways to deploy java service. One is jar.standalone.daemon, the other one is war.tomcat.
Follow the convention, you can easily deploy your service through this tool.

# Roles

## jar.standalone.daemon

This will help you to turn off iptables, install java, install flyway, migrate the schema, start jar service as a daemon.

## war.tomcat

This will help you to turn off iptables, install java, install tomcat, deploy war