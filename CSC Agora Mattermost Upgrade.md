# CSC Agora Mattermost Upgrade

## Summary: Upgrade 5-6 March 2022
- The CSC Agora Mattermost service will be down for one to several hours this weekend, 5-6 March 2022, for scheduled maintenance (a software upgrade).
	- Starting at 7:30am PST Saturday morning.
- After the service is back, Mattermost will have forgotten everybody's password. To fix that, you will need to go to <https://chat.collectivesensecommons.org/> and use the “I forgot my password” link to reset your password to sign into the new version. It’s okay to use the same password as the previous one if you want.
	- To avoid unnecessarily changing your password, you can wait until you get a message that you aren't signed in or that your email/password isn't valid.
- See <https://status.collectivesensecommons.org/> (and this page) at any time for updated information.
- If you have problems/questions not addressed on the this page, send email to <support@collectivesensecommons.org>.

## Other Things To Note

- Attachments to messages posted before the upgrade will no longer be viewable or directly accessible. Pete can retrieve a few attachments from the backups. If there are many people who need the old attachments, perhaps there will be some way to automate this.
- All your channels and DMs will be marked unread. After you've reset your password and signed in, just select a channel to mark it read again.
- The color of the interface is a bit darker in the new version.

## Background

The instance of Mattermost where **[CSC Agora](https://chat.collectivesensecommons.org/)** lives has needed an upgrade for a while, and **Peter Kaminski** has finally gotten the stars to align to make it happen soon, perhaps even this weekend, 5-6 March.

We will be upgrading from an older 5.29.0 version to the newest 6.4 version, which among other things, should fix the annoying “Server upgrade required” popup on mobile devices. A new deployment method should also make future upgrades much easier and more frequent, with less disruption.

Due to database changes between version 5.x to version 6.x,  a few things will happen:

-   Everybody will need a password reset. There will be a one-time requirement to use the “I forgot my password” link to reset your password to sign into the new version. It’s okay to use the same password as the previous version if desired.
-   All your channels and DMs will be marked unread; just select a channel to mark it read again.
-   Previously-posted messages with attachments will lose the attachments. Email [Pete](mailto:kaminski@istori.com) to access any critical attachments from the archive after the upgrade.

Stay tuned to the this page for more information as it becomes available. You’ll also receive an email with information before the upgrade. Join the [[csc] Meta](https://chat.collectivesensecommons.org/agora/channels/meta-csc) channel for discussion about the upgrade.