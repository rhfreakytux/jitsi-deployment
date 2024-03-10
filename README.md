# jitsi-deployment
This is my personal project for the deployment of Jitsi Meet server. 

This done and tested in the **Ubuntu 22.04**. You can fork and make your own version of it. 

After executing this playbook, don't forget to to install the **jitsi-meet**. 
As we're doing jitsi-meet automated installation and not manual, we're only setting the up the server environment that's required for the jisti to be installed. 

    # apt install jitsi-meet -y
After installing the jisti-meet and setting up all the required things, do exeucte to reload the systemd process limit restrictions: 

    # systemctl daemon-reload && systemctl restart jitsi-videobridge2
   
Feel free to commit. 
