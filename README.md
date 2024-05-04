Zenphoto CMS | adminBranding
==============================

adminBranding is a rework of zp-branding plugin for Zenphoto CMS for customization of backend.

Originally intended as a fork of zp-branding v1.4 to be merged with zp-branding, it has transformed into a rewritten plugin and completely changed logic of operation, by getting rid of included custom Logo image (to protect files from being overwritten on the update).

Instead user can mix and match plugin Options to combine custom and default elements for their desired look.

NB! Since our approaches to the task and customization needs are so different, me and @fretzl have decided to keep projects separate (hence the rename).
Instead of proposed **zp-branding ver 2.0** this work is released as **adminBranding v1.0**
 
**Options:**

 - Logo for Admin (Default, Custom, No logo) with ability to specify width and margins.
 - Background styling for Admin (Default image, Custom image, No image, Image repeat behaviour, Color)
 - Styling of Text and Links in Admin.
 - Custom CSS for further alterations.

Custom Logo and Background files should be placed in "/uploaded/design" folder of your Zenphoto install
(see more info on [UPLOAD FOLDER](https://www.zenphoto.org/news/path-constants/) of Zenphoto).

**Installation:**

1. Copy "/admin-branding" folder and "admin-branding.php" and into the "/plugins" folder of your Zenphoto installation.
2. Enable the "adminBranding" plugin in the Zenphoto backend (Admin section of plugins list).
3. Upload custom Logo and background images into "/uploaded/design" folder (see above).
4. Setup plugin to your liking via plugin options.
   
**Screenshot**
Options and their effect:

![admin-branding-settings](https://github.com/kuz-z-zma/adminBranding/assets/75898540/8e0d5f9f-5d16-4ee4-bc4a-494380ea62d9)
