Implementation Overview

For this project we'll be using Spring Security 5 through Spring Boot. If you're familiar with the earlier versions this Spring Boot Migration Guide might be useful.
OAuth2 Terminology

    Resource Owner
        The user who authorizes an application to access his account. The access is limited to the scope.
    Resource Server:
        A server that handles authenticated requests after the client has obtained an access token.
    Client
        An application that access protected resources on behalf of the resource owner.
    Authorization Server
        A server which issues access tokens after successfully authenticating a client and resource owner, and authorizing the request.
    Access Token
        A unique token used to access protected resources
    Scope
        A Permission
    JWT
        JSON Web Token is a method for representing claims securely between two parties as defined in RFC 7519
    Grant type
        A grant is a method of acquiring an access token.
        Read more about grant types here
