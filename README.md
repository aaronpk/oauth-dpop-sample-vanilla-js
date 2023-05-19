OAuth DPoP Demo in Vanilla JS
=============================

https://oauth.net/2/dpop/

DPoP is a proof-of-possession technique for binding access tokens to a private key. The client signs each request to the authorization server and resource server with a private key and sends a DPoP proof in the request header.

This is an implementation of DPoP in JavaScript with no external libraries used. Because of this, the code is more verbose than you would typically see in an application that uses a DPoP library, but is a demonstration of what it takes to create DPoP proofs.

For a more thorough implementation that is suitable for production use, see [panva/dpop](https://github.com/panva/dpop).

