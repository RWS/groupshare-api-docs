# GroupShare API Documentation #
## Introduction ##
This page contains links to the available resources you'll need to work with the current version of the GroupShare REST API. Through the use of the REST Web API 3rd party developers can extend the GroupShare eco-system. Your applications can integrate with GroupShare using simple HTTP methods - supporting JSON format. All the calls in this specifications are OAuth 2.0 protected resources. This means that callers must provide a so called "bearer token". This token can be obtained by issuing a POST request, to the authentication/api/1.0/login URL (see the **Login section** of the GroupShare Web API). The received token can be used to get access to the associated resources (all of the exposed API calls).

The API documentation is currently split into two parts:
1. The GroupShare Web API
2. The TM Service API

## GroupShare Web API ##
This includes the documentation for authentication, user management, project management and terminology management. The documentation can be found in your implementation of GroupShare at *[servername.domain]/documentation/api/index*. For example, you can find the current version on our development test server here: https://groupsharedev.sdlproducts.com/documentation/api/index

## TM Service API ##
This includes the documentation for Translation Memory management. The documentation can be found in your implementation of GroupShare at *[servername.domain]/docs/ui/index*. For example, you can find the current version on our development test server here: https://groupsharedev.sdlproducts.com/docs/ui/index

## GroupShareKit ##
To provide an easy way to interact with the REST API above we have created the GroupShareKit which is a client library targeting .NET 4.6 and above. It currently supports two versions:
- GroupShareKit
- GroupShareKit-2017

This can be found here: https://github.com/sdl/groupsharekit.net

We have also created a sample web application using the GroupShareKit. The source code of the application is available here : https://github.com/sdl/GroupShareKit-Sample

## Additional helpful resources ##
### Video exploring the use of Swagger with the GroupShare REST API ###
There is also a useful video here on how to work with the REST APIs and the swagger page. It is based on working with the 2017 version of GroupShare, but the principles are the same:

[![Explore GroupShare 2017 REST API's using swagger](https://img.youtube.com/vi/jmaZyarM-8s/0.jpg)](https://youtu.be/jmaZyarM-8s "Explore GroupShare 2017 REST API's using swagger")

### GroupShare Api endpoints step by step ###
This wiki in the Language Developers forum on the RWS Community explains everything you need to know about working with the GroupShare API endpoints:
https://community.sdl.com/developers-more/developers/language-developers/w/wiki/3395.groupshare-api-endpoints-step-by-step

### GroupShare WebHooks Service ###
WebHooks provide a publish / subscribe model for wiring together Web APIs and services. You can subscribe to GroupShare events and get notified when that event happens through a callback. This wiki in the Language Developers forum on the RWS Community explains:
https://community.sdl.com/developers-more/developers/language-developers/w/wiki/3388.groupshare-webhooks-service

### Where to get further help ###

If you have any questions on any of the GroupShare APIs the best place to ask is in the community here: https://community.sdl.com/developers-more/developers/language-developers/f/sdk_qa
