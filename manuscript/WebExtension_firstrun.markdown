# Running WebExtension in Firefox

In this section we will be exploring more how to run an Firefox WebExtensions.

I will be showing this demo with the help of the small extension I have written before, feel free to download it from github [1], you can clone whole repo [2].  I personally use web-ext [3]  tool for packing my extension, but for basic learning it is not mandatory.

## Step by Step procedure for running WebExtension

### Step1: Go to the directory which has contents of Extension

In my case it will look like the below. The content showed below is the contents of Extension, which the link is shared above.

![Directory Image](images/content_directory.png)

### Step 2: We have to compress all the contents into Zip

- Select all the folders and files
- Make it to a zip, anyname.zip

![Directory Image](images/tabopenzip.png)

### Step 3: Open about:addons

![Directory Image](images/about-addon.png)

### Step 4: Install Addons

- Click on Tools for all add-ons (the icon - which is like Setting icon )
- Select Install Add-on From File ..
- Make sure you have set the file type to all files
- Choose the Zip which you created in step 2

![Choose the Zip file](images/select_zip.png)

- You will get a pop-up notification after selecting at left croner

![Choose the Zip file](images/install_pop.png)

- In that pop-up click Install button
- Now your Extension is installed.

### Step 5: Run the Extension

For most of Extensions you will get the icon in the tool bar itself. So for this a page like icon will be coming at toolbar, if every code is run properly. Click on that icon.

![Choose the Zip file](images/extension_popup.png)

So on Selecting any one of the three websites, it will open a new tab and open the site. As of now it is in static mode.

In future, based on user usage we can show top 3 websites there. 

Follow for amazing journey of Building WebExtensions.

## References 

- [1] https://github.com/iamVP7/MyExtensions/tree/master/tabopen/Firefox
- [2] https://github.com/iamVP7/MyExtensions/
- [3] https://github.com/mozilla/web-ext