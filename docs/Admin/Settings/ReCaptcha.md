A captcha is a program that can help ensure that only actual people, not spammers or robots, are using particular parts of your site. [ReCaptcha](http://recaptcha.net) displays an image of two words and asks the user to type them in before continuing.

Omeka versions 1.3 and higher have built-in support for ReCaptcha, a free captcha service from Google. Several Omeka plugins that used to handle captchas individually now all use Omeka's built-in support.

Configuring
---------------------------------------------------------------
In order to enable ReCaptcha for your plugins, you need to do a little configuration.

1.  Go to [recaptcha.net](http://recaptcha.net) to sign up for a
 ReCaptcha key. When you sign up, ReCaptcha will provide you with a  "public" and "private" key. You will need both.
2.  Once you have your keys, go to your Omeka admin dashboard, and go to Settings in the top nav. 
1. Go to the Security tab in Settings and scroll down to the Captcha section. 
3.  There are two text boxes in this section, one for the public key, one for the private key. Copy the keys you got in Step 1 into the appropriate boxes.
4.  Click "Save Changes" at the bottom of the page.

![Security Settings with red arrow pointing to the header for Captcha settings](/doc_files/captchaSettings.png)

Now, plugins will be able to display a captcha, and prevent automated programs from abusing your site.

Plugins that use ReCaptcha
---------------------------------------------------------------
The following plugins use Omeka's ReCaptcha support, and configuring ReCaptcha as explained above should enable captchas for all of them. Please make sure you are using the latest version of these plugins.

-   [Contribution](../../Plugins/Contribution.md)
-   [SimpleContactForm](../../Plugins/SimpleContactForm.md)


