== Kautilya

Kautilya is a toolkit which provides various payloads for a Human Interface Device which may help in breaking in a computer. The toolkit is written in Ruby. 

- The Windows payloads and modules are written mostly in powershell (in combination with native commands) and are tested on Windows 7 and Windows 8. 

- The Linux payloads are mostly shell scripts (those installed by default) in combination with commands. These are tested on Ubuntu 11.

- The OS X payloads are shell scripts (those installed by default) with usage of native commands. Tested on OS X Lion running on a VMWare


In principal Kautilya should work with any HID capable of acting as a keyboard. Kautilya has been tested on Teensy++2.0 and Teensy 3.0 from pjrc.com. Updates about Kautilya can be found most of the times at my blog http://labofapenetrationtester.blogspot.com/ and google group.

For any queries or feedback, post to official google group http://groups.google.com/group/kautilya-users or mail me at nikhil d0t uitrgpv at gmail.com 


You need colored and highline gem to use Kautilya
"gem install colored"
"gem install highline"

In some cases you may need to install gems to user home dir
"gem install --user-install colored"
"gem install --user-install highline"

A five part blog post on my blog could be useful for those new to HID and Kautilya:

Part 1: http://labofapenetrationtester.blogspot.in/2012/04/teensy-usb-hid-for-penetration-testers.html

Part 2: http://labofapenetrationtester.blogspot.in/2012/04/teensy-usb-hid-for-penetration-testers_04.html

Part 3: http://labofapenetrationtester.blogspot.in/2012/04/teensy-usb-hid-for-penetration-testers_25.html

Part 4: http://labofapenetrationtester.blogspot.in/2012/05/teensy-usb-hid-for-penetration-testers.html

Part 5: http://labofapenetrationtester.blogspot.in/2012/09/usb-hid-for-pen-testers-part5.html 


Due Credits and Borrowed Code: I do not put credits of any borrowed code inside the payloads generated by Kautilya to save space. Credits and thanks are generally mentioned either in the description of payloads or accompanying blog post. If you think I missed any due credit, please let me know. I will add the credits with apologies.

