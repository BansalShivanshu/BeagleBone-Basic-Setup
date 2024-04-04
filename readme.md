## BeagleBone Basic Setup Script

### Execution Instructions
1. In line 38, replace `<USER>` with the username of your host
1. Copy main.sh to `~/`
1. From `~/` run the following command
    ```
    chmod +x main.sh
    ```
1. Now execute the script using `sudo main.sh`
*Note:* This requires your host to be pre-setup properly, otherwise script will run into issues and terminate.
*Note* Script needs superuser privillages to execute the setup. Cannot be run otherwise.

### What does this do?
1. Adds basic aliases such as `ll` and `public` to basrc
1. Initializes Networking and NFS setups
1. Adds scripts to boot runtime
1. Updates packages to latest

### Contribution
What I have here at the moment is a very basic setup with minimal error checking. Please feel free to contribute by creating new issues and pusing Pull Requests. Feel free to email me at `sdev.shivanshu@gmail.com` for any questions or discussions. 

Cheers!
