# Getting started with UR-Vault on macOS

## Steps


### 1. Install UR-Vault from AppStore

UR-Vault for macOS can be installed from:
https://apps.apple.com/in/app/ur-vault/id6756403309

#### 1.1 Launch UR-Vault after device authentication

![](images/device_auth_login.png)

#### 1.2 Sign in using Apple ID

![](images/apple_sign_in.png)

### 2. Install browser extension
Click on the link for instructions to install the `UR-Vault` extension on the browser. The extension enables auto-fill of new and rotated passwords.
For installing browser extensions, please refer to: https://balajikadambi.github.io/UR-Vault/browser-support/.
![](images/install_browser_extn.png)

#### 2.1 Configure settings on UR-Vault App for browser integration

Go to `Settings` on `UR-Vault` App.

![](images/app_settings.png)

Change the Port number on Settings App if needed:

![](images/change_port.png)

Open the `Configuration` tab on browser extension. Change the port number to match the port number set on the `UR-Vault` App. Click on `Connection` icon.

![](images/test_connection.png)

Once the connection is successful, save the port number by clicking on `Save` button.

![](images/save_port.png)

Next on the `Autofill` tab, click on `Register with UR-Vault App` button. 

![](images/register_urvault.png)
![](images/registered.png)

### 3. Password generation for a website

Open a website on the browser (e.g. http://localhost:3000/home.html).
Open the extension and copy the website name.

![](images/copy_website_name.png)

Open the `UR-Vault` App. Go to `Manage Passwords`. Select `Generate`. Click on `Paste` icon to paste the website name. 

![](images/paste_website_name.png)

Enter `Account nickname` and `username`. 

![](images/account_details.png)

Enter `Password rules` for the website. You can use the `Chat Assistant` to get password rules for public websites.

![](images/choose_rules.png)

Enter a unique secret name for the password generation. It can be the default secret configured on the `Settings` page.
> Note: Please change the default secret value on Settings page before selection on this page.

![](images/enter_secret_gen.png)

Click on `Generate` to generate the password. The passwords are now copied to clipboard in encrypted format.
![](images/generate_pass.png)

Next, go back to the browser extension Autofill tab.
Select the option `Fill passwords generated on UR-Vault App`. Click on `Paste` icon to load the passwords.

![](images/load_gen_passwords.png)

Now the username and password are available on the webpage for auto-fill into text fields. Please click on the `UR-Vault` icon at the right end of the text field to display list of options for autofill.

![](images/autofill_user.png)
![](images/autofill_pass.png)







 
