OAuth2orizeRecipes
==================

OAuth2 security recipes and examples based on OAuth2orize.

What is different here from the plain grants example from OAuth2orize?  The plain grants example from OAuth2orize is
meant to be a very simple example which show cases the bare minimum of an OAuth2 Server in Node.js so that you get an
idea of how to write your own.  The recipes here are more complete but come with more complexity.  However, if you're
looking for a more complete OAuth2 code solution to run on Node.js, then this is the place you want to be.

Features of the Authorization Server
* Access Tokens (includes configurable expiration)
* Refresh Tokens
* All 4 grant types exposed out of the box
* REST tokeninfo endPoint for verifying a token is valid.  This is similar to Google's tokeninfo endpoint and is useful
for token validations between the Resource Server and the Authorization Server

For good examples of how to utilize the Authorization Server go to the wiki here:
https://github.com/FrankHassanabad/Oauth2orizeRecipes/wiki