# GroupShare API Documentation #
## Introduction ##
This page contains links to the available resources you'll need to work with the current version of the GroupShare REST API. Through the use of the REST Web API 3rd party developers can extend the GroupShare eco-system. 

Your applications can integrate with GroupShare using simple HTTP methods - supporting JSON format. All the calls in this specification are OAuth 2.0 protected resources. This means that callers must provide a so called "bearer token". This token can be obtained by issuing a POST request to api/authentication/token. The received token can be used to get access to the associated resources (all of the exposed API calls).

To consult the available API calls, please access the Web API Help Page on your GroupShare installation under *[servername.domain]/documentation/api/index*.
For example, you can find the current version on our development test server here: https://groupsharedev.sdlproducts.com/documentation/api/index

## GroupShareKit ##
To provide an easy way to interact with the REST API above we have created the GroupShareKit which is a client library targeting .NET 4.8 and .NetStandard 2.0.

This can be found here: https://github.com/sdl/groupsharekit.net

We have also created a sample web application using the GroupShareKit. The source code of the application is available here : https://github.com/sdl/GroupShareKit-Sample

### Where to get further help ###

If you have any questions on any of the GroupShare APIs the best place to ask is in the community here: https://community.sdl.com/developers-more/developers/language-developers/f/sdk_qa
