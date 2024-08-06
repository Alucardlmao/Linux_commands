# Change the current user's password.
passwd

# Switch to the root account with root's environment. (Login shell.)
sudo -i

# Execute your current shell as root. (Non-login shell.)
sudo -s

# List sudo privileges for the current user.
sudo -l

# Edit the sudoers configuration file.
visudo

# Display the current SELinux mode.
getenforce

# Display SELinux details such as the current SELinux mode, the configured mode, and the loaded policy.
sestatus

# Change the current SELinux mode to Permissive. (Does not survive a reboot.)
setenforce 0

# Change the current SELinux mode to Enforcing. (Does not survive a reboot.)
setenforce 1

# Set the SELinux mode to enforcing on boot by using this setting in the /etc/selinux/config file.
SELINUX=enforcing

# Set the SELinux mode to permissive on boot by using this setting in the /etc/selinux/config file.
SELINUX=permissive

# Set the SELinux mode to disabled on boot by using this setting in the /etc/selinux/config file.
SELINUX=disabled
