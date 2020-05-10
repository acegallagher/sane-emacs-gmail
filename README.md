# sane-emacs-gmail

All the conf files and scripts to sanely access gmail in emacs using isync to download inbox via IMAP, mu4e to read and index the emails, and msmtp for sending them.

This repo includes configuration files for emacs, mbsync, as well as systemd timer units to synchronize the email on any given schedule. 

# Requirements: 

2FA must be setup on the account so that a one-time 'app password' can be generated to provide access to the account using IMAP and SMTP services. You must go to  (https://security.google.com/settings/security/apppasswords) to generate the password. 


# How to setup on Linux:

## Arch Linux:

yay -S emacs-nox mu msmtp isync
