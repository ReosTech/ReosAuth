# Reos Auth
### Login with your Reos account anywhere using Reos Auth
#### Reos Auth uses the official OAuth 2.0 tokens for secure login. And Google Fraud Defence (formerly reCAPTCHA enterprise) for extra safety
## Setup :
### for setting up your own Reos Auth app do the following steps :

- Create your Reos Account (Or login if already created) [Reos Sign in / Sign up Page](https://reostech.web.app/login.html)
- Go to the developer console by clicking on the console open button from the dashboard when logged in

- Enter your exact site address where you want to setup the OAuth app
- Click on Create Credentials button
- Copy your client key and secret key
- ### Use the following endpoints
- #### For redirection to  Auth app `https://server-skby.onrender.com/oauth/authorize?client_id=YOUR_CLIENT_KEY&redirect_uri=YOUR_SITE&response_type=code&scope=profile`
- #### For token exchange use `https://server-skby.onrender.com/oauth/token` with `POST` request having `grant_type=authorization_code&code=AUTH_CODE&redirect_uri=YOUR_SITE&client_id=YOUR_CLIENT_KEY&client_secret=YOUR_SECRET_KEY`

#### Having Trouble? Try using the easy auth handler
[Easy Auth Handler](https://github.com/ReosTech/ReosBucket/raw/refs/heads/main/h.html)
#### For more details and support email via [Reos Mail](https://reostech.web.app/emails.html) to
#### support@reostech


### [Reos](https://reostech.web.app)
