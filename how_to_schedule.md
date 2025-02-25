# How to schedule a script in Synology Task Manager

To schedule a script to run on your Synology at boot-up or shutdown follow these steps:

**Note:** You can setup a schedule task and leave it disabled, so it only runs when you select the task in the Task Scheduler and click on the Run button.

1. Go to **Control Panel** > **Task Scheduler** > click **Create** > and select **Triggered Task**.
2. Select **User-defined script**.
3. Enter a task name.
4. Select **root** as the user (The script needs to run as root).
5. Select **Shutdown** as the event that triggers the task.
6. Leave **Enable** ticked.
7. Click **Task Settings**.
8. Optionally you can tick **Send run details by email** and **Send run details only when the script terminates abnormally** then enter your email address.
9. In the box under **User-defined script** type the path to the script. 
    - e.g. If you saved the script to a shared folder on volume1 called "scripts" you'd type: **/volume1/scripts/syno_enable_m2_volume.sh**
11. Click **OK** to save the settings.

Here's some screenshots showing what needs to set:

<p align="leftr"><img src="images/schedule1.png"></p>

<p align="leftr"><img src="images/schedule2b.png"></p>

<p align="leftr"><img src="images/schedule3.png"></p>
