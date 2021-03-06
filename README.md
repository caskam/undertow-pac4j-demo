<p align="center">
  <img src="https://pac4j.github.io/pac4j/img/logo-undertow.png" width="300" />
</p>

This `undertow-pac4j-demo` project is an Undertow web application to test the [undertow-pac4j](https://github.com/pac4j/undertow-pac4j) security library with various authentication mechanisms: Facebook, Twitter, form, basic auth, CAS, SAML, OpenID Connect, JWT...

## Start & test

Build the project and launch the web app on [http://localhost:8080](http://localhost:8080):

    cd undertow-pac4j-demo
    mvn clean compile exec:java

To test, you can call a protected url by clicking on the "Protected url by **xxx**" link, which will start the authentication process with the **xxx** provider.
