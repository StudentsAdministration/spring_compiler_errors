# spring_compiler_errors
Possible compiler errors


````    
***************************
APPLICATION FAILED TO START
***************************

Description:

The Tomcat connector configured to listen on port 8080 failed to start. The port may already be in use or the connector may be misconfigured.

Action:

Verify the connector's configuration, identify and stop any process that's listening on port 8080, or configure this application to listen on another port.

2017-12-06 18:20:58.240  INFO 18967 --- [           main] ationConfigEmbeddedWebApplicationContext : Closing org.springframework.boot.context.embedded.AnnotationConfigEmbeddedWebApplicationContext@13eb8acf: startup date [Wed Dec 06 18:20:57 CET 2017]; root of context hierarchy
2017-12-06 18:20:58.241  INFO 18967 --- [           main] o.s.j.e.a.AnnotationMBeanExporter        : Unregistering JMX-exposed beans on shutdown

Process finished with exit code 1

````    
