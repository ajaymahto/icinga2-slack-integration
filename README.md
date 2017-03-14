STEPS to integrate Slack Channel to Icinga Notification System:

1. Create an App on Slack.
2. Create the channel where the alerts would be posted.
3. Create an incoming webhook for the app, pointing to the channel created.
4. Copy slack-service-notification.sh file into /etc/icinga2/scripts/ directory
	and edit the entries as suggested.
	Enter Host IP Address.
	Enter webhook URL.
	Enter Channel Name.
	Enter Bot Name.
5. Copy slack.conf file into /etc/icinga2/conf.d/ directory and
	restart icinga2 service.

We can use the same App with multiple webhook url for different channels.

Enjoy.
