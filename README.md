# OAuth (Open Authorization)
### 
<img src = 'https://d33wubrfki0l68.cloudfront.net/ecfd750086b8ac97fe5aaa08fdde917732b13225/f58f5/assets-jekyll/blog/oauth/biketoworkday-fb-login-f00e39aabbf3e44bc3570333643cbf5d966fc27367dbffd2623ff4a3694831c3.png'>

## What Is OAuth ? 
OAuth is an open-standard authorization protocol or framework that provides applications the ability for “secure designated access.” For example, you can tell Facebook that it’s OK for ESPN.com to access your profile or post updates to your timeline without having to give ESPN your Facebook password. This minimizes risk in a major way: In the event ESPN suffers a breach, your Facebook password remains safe.

OAuth is about authorization and not authentication. Authorization is asking for permission to do stuff. Authentication is about proving you are the correct person because you know things. OAuth doesn’t pass authentication data between consumers and service providers – but instead acts as an authorization token of sorts.


## OAuth Examples
The simplest example of OAuth in action is one website saying “hey, do you want to log into our website with other website’s login?

## Why to use OAuth?
OAuth was created as a response to the direct authentication pattern. This pattern was made famous by HTTP Basic Authentication, where the user is prompted for a username and password. Basic Authentication is still used as a primitive form of API authentication for server-side applications: instead of sending a username and password to the server with each request, the user sends an API key ID and secret. Before OAuth, sites would prompt you to enter your username and password directly into a form and they would login to your data (e.g. your Gmail account) as you. This is often called the password anti-pattern.

## OAuth and APIs, How OAuth Is Used to Access APIs?
### 
<img src ='https://d33wubrfki0l68.cloudfront.net/99bea281c4d8758b97fe07ded0136019b0ed75f6/3da15/assets-jekyll/blog/oauth/oauth-actors-cd8b4861e839037400d8521e97c5d8cf0cb029add65d1036488991c7e85dcb72.png'>

OAuth is a delegated authorization framework for REST/APIs. It enables apps to obtain limited access (scopes) to a user’s data without giving away a user’s password. It decouples authentication from authorization and supports multiple use cases addressing different device capabilities. It supports server-to-server apps, browser-based apps, mobile/native apps, and consoles/TVs.

You can think of this like hotel key cards, but for apps. If you have a hotel key card, you can get access to your room. How do you get a hotel key card? You have to do an authentication process at the front desk to get it. After authenticating and obtaining the key card, you can access resources across the hotel.

 OAuth is where:

- App requests authorization from User.
- User authorizes App and delivers proof.
- App presents proof of authorization to server to get a Token.
- Token is restricted to only access what the User authorized for the specific App.


## OAuth 1.0 vs. OAuth 2.0
- OAuth 2.0 is a complete redesign from OAuth 1.0, and the two are not compatible. If you create a new application today, use OAuth 2.0. This blog only applies to OAuth 2.0, since OAuth 1.0 is deprecated.

- OAuth 2.0 is faster and easier to implement. OAuth 1.0 used complicated cryptographic requirements, only supported three flows, and did not scale.

- OAuth 2.0, on the other hand, has six flows for different types of applications and requirements, and enables signed secrets over HTTPS. OAuth tokens no longer need to be encrypted on the endpoints in 2.0 since they are encrypted in transit




**********
