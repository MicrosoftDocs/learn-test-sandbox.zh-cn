Now that you know how to build an app, you'll learn how to share it. You can share an app with specific users, groups, or your whole organization. When you share an app with other people, they can run it from the Microsoft Dynamics 365 home page in a browser or in Microsoft PowerApps Mobile for Microsoft Windows, Apple iOS, or Google Android.

Even better, you can give someone permission to update the app.

## Prepare to share an app

1. In PowerApps Studio, select **App settings** on the **File** menu.

1. Give the app a meaningful name and description so that your team knows what your app does and can easily find it in a list.

1. On the **File** menu, select **Save as**, and then select **The cloud**.

    You must save an app to the cloud before you can share it.

1. Select **Save**, and then elect **Share this app**.

1. On the **Share** tab, specify the users or groups with whom you want to share the app. To add everyone in your organization, select the **Add everyone in my org** button.

1. To notify users by email, select the **Send an email invitation** check box.

    If you select that check box, everyone you shared the app with will get an email message that has a link to Dynamics 365. People whom you granted edit permission for the app will also get a link to web.powerapps.com.

    Only people who follow the link to Dynamics 365 will see the app there. The app will also be in Microsoft AppSource. Anyone who didn't follow the link will have to add the app from AppSource to Dynamics 365 themselves.

1. In the **Shared with** list, in the **Permission** list on the right, specify how each user or group can interact with the app:

    - **Can edit**: Users can change the app by using PowerApps Studio.
    - **Can use**: Users can view and use the app, but they can't change it.

1. Select **Save**.

If you make and save changes to a shared app, the people you shared it with will see your changes as soon as you publish them. This immediacy can be great if you improve the app, but it can also negatively affect other users if you remove or significantly change features.

## Permissions and licensing

Here are some basics about permissions and licensing that you should be aware of:

- Users and contributors need permissions to any data connections and gateways that a shared app uses. Some permissions come implicitly with the app, but you must explicitly grant others.
- People who have **Can edit** permission also need a PowerApps "P2" license to work directly with entities.

Sharing apps is easy, and it's a great way to take an app that you find useful and make it available to people across your organization.