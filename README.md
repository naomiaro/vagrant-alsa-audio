Vagrantfile with a Mac OSX host that makes sound work with alsa on an Ubuntu/Trusty guest.

This vagrant box has been set up specifically to run code in the Coursera course [Audio Signal Processing for Music Applications](https://www.coursera.org/course/audio)

After the vagrant provision script has run for the first time, call 'vagrant reload' before sshing into the box so that the alsa audio drivers will load properly.
