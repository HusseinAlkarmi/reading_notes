# read11

## What is OAuth:


## What is OAuth?

+ OAuth is an open-standard authorization protocol or framework that describes how unrelated servers/services can safely allow authorized access to their assets without actually sharing their login information.

## Give an example of what using OAuth would look like.

+ The simplest example of OAuth in action is one website saying “hey, do you want to log into our website with other website’s login?” In this scenario, the only thing the first website – let’s refer to that website as the consumer – wants to know is that the user is the same user on both websites and has logged in successfully to the service provider – which is the site the user initially logged into, not the consumer.

## How does OAuth work? What are the steps that it takes to authenticate the user?

+ OAuth is primarily concerned with authorization rather than authentication.

"Authentication is the process by which a user/subject proves ownership of a presented identity by giving a password or another uniquely owned or presented factor."

## What is OpenID?


+ OAuth is for machines logging into machines on behalf of humans, while OpenID is for humans logging onto machines.

## Authorization and Authentication flows:


## What is the difference between authorization and authentication?

+ There are a few key differences between authorization and authentication, despite the fact that they are sometimes used interchangeably. Authentication, for example, verifies who the user is and authorisation verifies what they have access to.

## What is Authorization Code Flow?

+ its Flow exchanges a code for a token.

## What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

+ Mobile and native applications require additional security, which is provided via OAuth 2.0. Where a PKCE is used in the Authorization code flow.

## What is Implicit Flow with Form Post?

+ Implicit Flow with Form Post flow uses OIDC to implement web sign-in that is very similar to the way SAML and WS-Federation operates. The web app requests and obtains tokens through the front channel, without the need for secrets or extra backend calls.

## What is Client Credentials Flow?

+ The Client Credentials flow is a server-to-server communication channel. The process does not require user authentication. This flow is useful for systems that must perform API activities without the presence of a user. It might be nightly operations or other procedures that require contacting OAuth-protected APIs.

## What is Device Authorization Flow?

+ two different paths one occurs on the device requesting authorization and the other occurs in a browser.

## What is Resource Owner Password Flow?

+ This request for credential is often made through an interactive form, which is not advised.
