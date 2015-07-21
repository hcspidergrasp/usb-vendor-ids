#Ubuntu udev USB configuration for using with ADB

`51-android.rules` file contains USB configuration for each type of you want to use in development in Ubuntu.

##How to use it?

Just copy `51-android.rules` into `/etc/udev/rules.d/` directory and run this command:

	```sh
	$ sudo /etc/init.d/udev reload
	```

For more information check [Android Developer documentation](http://developer.android.com/tools/device.html).
