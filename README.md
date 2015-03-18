# JWT authentication for AngularJS.
### This gem is currently under development. If you see this message, do not use it.

This module provides the following features:

* Oauth2 authentication
* Email authentication, including:
  * [User registration](#authsubmitregistration)
  * [Password reset](#authrequestpasswordreset)
  * [Account updates](#authupdateaccount)
  * [Account deletion](#authdestroyaccount)
* Seamless integration with the [devise token auth](https://github.com/lynndylanhurley/devise_token_auth) Rails gem
* Extensive [event notifications](#events)
* Allows for extensive [configuration](#configuration) to work with any API
* Session support using cookies or localStorage
* Tested with Chrome, Safari, Firefox and [IE8+](#internet-explorer)
