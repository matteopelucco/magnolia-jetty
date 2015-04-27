# magnolia-jetty
Magnolia and Jetty together

This simple project aims to be a base to test Magnolia CMS over HTTP/2 protocol, from both website than CMS interface perspective.

many configurations are available: 
- HTTP1/1 + simple webapp (index.html). Run with clean package jetty:run
- HTTP1/1 + Magnolia webapp. Run with clean package jetty:run-exploded
- HTTP2 + simple webapp (index.html). Run with clean package jetty:run-forked
- HTTP2 + Magnolia webapp. Run with clean package jetty:run-exploded *plus* additional JVM parameters: -Xbootclasspath/p:C:/dev/maven/repository/org/mortbay/jetty/alpn/alpn-boot/8.1.3.v20150130/alpn-boot-8.1.3.v20150130.jar


Credits: 
Configure HTTPS for jetty-maven-plugin 9.0.x
http://juplo.de/configure-https-for-jetty-maven-plugin-9-0-x/
https://github.com/wuic/wuic-samples
