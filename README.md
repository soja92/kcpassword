# kcpassword
OS X autologin enabler utility based on script from [osx-vm-templates](https://github.com/timsutton/osx-vm-templates/blob/master/scripts/autologin.sh)

# Usage

To enable OS X autologin for user:

```shell
enable_autologin "username" "password"
```

Note: You may need to ```chmod +x``` both the enable_autologin file and the kcpassword file.

When making a Jamf imaging drive, the ```kcpassword``` file may need to be copied to ```/private/etc/kcpassword``` to properly enable autologin



