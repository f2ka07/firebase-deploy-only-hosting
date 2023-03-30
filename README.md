# Firebase Deploy Only Hosting : Host a Website on Firebase

The commands ***Firebase deploy --only hosting*** or ***firebase deploy hosting*** are used to deploy a website for firebase hosting. The steps involved are explained in this video.

[![Firebase Deploy Only Hosting](https://solid-future.com/wp-content/uploads/2023/03/Firebase-Deploy-Only-Hosting.webp)](https://www.youtube.com/watch?v=cdxWLVIvsJ8 "Firebase Deploy Only Hosting")

## Firebase Hosting Architecture

Firebase Hosting is a [cloud-based hosting](https://solid-future.com/docs/linode-docs-how-to-create-a-5-monthly-linode-virtual-private-server/) service provided by Google Firebase. It is designed to host static content, such as HTML, CSS, and JavaScript files, and deliver them to end-users over HTTPS.

[Firebase Hosting](https://firebase.google.com/docs/hosting) architecture is based on a global content delivery network (CDN) that caches and distributes website content to edge locations worldwide. This ensures that website visitors experience fast load times and low latency, regardless of their geographic location.

The architecture consists of three main components:

**Firebase Hosting servers:** 

These are the servers that host your website's content and serve it to end-users. Firebase Hosting servers are deployed in multiple regions worldwide, ensuring that your website is always available and responsive.

**Firebase Hosting CDN:**

This is the content delivery network that caches your website's content and distributes it to edge locations worldwide. The CDN reduces the distance between the end-users and your website's content, resulting in faster load times and improved user experience.

**Firebase Hosting SSL:**

Firebase Hosting provides free SSL certificates for all websites hosted on its platform. SSL certificates encrypt website traffic and protect sensitive data, ensuring that your website is secure and trustworthy.

## Steps Firebase Hosting: Static Website  

The following are the steps involved in hosting a static website on Firebase Hosting.

### Step 1: Create a new project on Firebase Console
Firstly, create a new project on Firebase Console and enable Firebase Hosting for the project. This enables you to access Firebase Hosting services and features.

To create a new project on Firebase Console, you need to have a Google account. Once you have signed into the Firebase Console with your Google account, you can create a new project by clicking on the 'Add project' button. You will be prompted to enter a name for your project and select a billing account if required.

![Firebase Deploy Only Hosting](https://solid-future.com/wp-content/uploads/2023/01/1.-Firebase-hosting-create-project.webp)

After creating the project, you need to enable Firebase Hosting for the project. This can be done by clicking on the 'Hosting' option from the left-hand menu and following the on-screen instructions.  

 - Enabling Firebase Hosting creates a default Firebase Hosting site for
   the project with a unique subdomain. This subdomain is used to access
   the website until a custom domain is added.
   
   Enabling Firebase Hosting also provides access to other Firebase
   Hosting features such as HTTPS enforcement, custom domain support,
   and SSL certificate management. These features enhance the website's
   security, reliability, and performance.
   
#### Choose the type of platform

Then select **Web Option** from the four options given. i.e, ios,android, web and unity.

![Firebase hosting account](https://solid-future.com/wp-content/uploads/2023/01/2.-Firebase-hosting-app.webp)

#### Add Firebase to your web App

![Firebase host static website](https://solid-future.com/wp-content/uploads/2023/01/4.-Firebase-hosting-app-name.webp)

### Step 2: Initialize your project with Firebase CLI

Next, initialize your project with Firebase CLI by running the command:

     'firebase init'. 

This sets up the basic configuration files and folders required for hosting the static website.
![Firebase deploy hosting only](https://solid-future.com/wp-content/uploads/2023/01/5.-npm-install-g-firebase-tools.webp)

#### Log in to Firebase Console Using the CLI
![Firebase deploy only hosting](https://solid-future.com/wp-content/uploads/2023/01/5.-npm-install-g-firebase-tools.webp)

### Step 3: Add the static website files to the 'public' folder. 

After initializing the project, navigate to the project's root directory and add the static website files to the 'public' folder. Ensure that the file names and folder structure are consistent with the website's design.

### Step 4: Deploy the static website to Firebase Hosting

Once the files are added, you can deploy the static website to Firebase Hosting by running the command:

    'firebase deploy'. 

This command uploads the website files to Firebase Hosting servers and makes them available to the public.


### Step 4: Configure custom domain and SSL certificates.

After deploying the website, you can configure custom domain and SSL certificates to enhance the website's security and branding. Firebase Hosting allows you to add custom domains and certificates with ease using its intuitive interface.

## Step 5: Monitor the website's performance and usage using Firebase Analytics

Finally, monitor the website's performance and usage using Firebase Analytics and other available tools. Firebase Hosting provides useful metrics and insights to help you optimize the website for better performance and user experience.

## Conclusion

In conclusion, hosting a static website on Firebase Hosting involves creating a new project, initializing the project with Firebase CLI, adding website files to the 'public' folder, deploying the website using the 'firebase deploy' command, configuring custom domains and SSL certificates, and monitoring website performance using Firebase Analytics and other tools.
