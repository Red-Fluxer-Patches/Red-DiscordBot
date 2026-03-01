===========================================
Creating a bot account
===========================================

To use Red you will require a bot account and to enable privileged intents. Both these steps will be covered below.

.. _creating-a-bot-account:

-------------------------------
Creating the bot application
-------------------------------

In order to use Red, we must first create a Fluxer Bot account.

Creating a Bot account is a pretty straightforward process.

1. Go to the `Fluxer client <https://web.fluxer.app/>`__.
2. Open the User Settings and navigate to the Applications tab.

    .. image:: /.resources/bot-guide/fluxer_settings.png
        :alt: The Applications tab.

3. Click on the "Create Application" button.

    .. image:: /.resources/bot-guide/fluxer_create_app_button.png
        :alt: The new application button.

4. Give the application a name and click "Create".

    .. image::  /.resources/bot-guide/fluxer_create_app_form.png
        :alt: The new application form filled in.

5. If you don't want others to be able to invite your bot untick the **Public Bot**. When this is unticked, it will prevent others from inviting your bot to their servers and only you will be able to add the bot to servers (provided that you have needed permissions in the server you want to add the bot to).

    - Make sure **Require OAuth2 Code Grant** is unchecked.

    .. image::  /.resources/bot-guide/fluxer_bot_user_options.png
        :alt: How the Bot User options should look like for most people.

6. Acquire the token using the "Regenerate" button below the "Bot token" field, then "Copy" after it is revealed.

    - **This is not the Client Secret at the General Information page**

    .. warning::

        Do not share your token as it is like your password.
        If you shared your token you can regenerate it.
