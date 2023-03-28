To write such an unscrupulous script, the Python programming language, requests and json libraries were used.

Description of the script operation:

Reading login and password data from a JSON file. The data is stored as a dictionary with the keys "username" and "password".

collecting cookies, coupons for sending requests

Sending a POST request to the authorization page of the Epic Games website using the transmitted username and password as request parameters.

Checking the server response for the presence of a captcha. If there is a captcha, then the captcha auto-access method is used through the service rucaptcha.com

If the captcha is not required or the auto-access was successful, then the server response is analyzed for authorization errors.

If the authorization was successful, the session data is saved for later use in other requests on the Epic Games website.

In case of an authorization error, an error message is displayed, the login and password are entered in the list of incorrect data, and authorization is repeated with other login and password data.

In open access, I do not debug because this is an unscrupulous script, sorry.)
