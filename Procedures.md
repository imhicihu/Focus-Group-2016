### The net ###

+ Cloud:
    * No cloud service was used along the process: No Dropbox, no Google Drive, no Evernote, no WeTransfer. Reason: security & data breach threats 
+ Email:
	* software: [GNUP](https://www.gnupg.org/software/index.html)
	* generate [Public key](http://www.dewinter.com/gnupg_howto/english/GPGMiniHowto-1.html#ss1.1) inside [GNUPG](https://www.gnupg.org/software/index.html)
	* apply PGP encryption schema between pairs


### Hardware ###

+ Ipad:
    * verify current date & hour
	* Enable [TouchID](https://support.apple.com/en-us/HT204587)
	* Enable [Passcode](https://support.apple.com/en-us/HT204060)
	* verify capacity available. Go to `Settings --) General --) About`
	* connect to electrical surge (to avoid warnings of low battery)
	* sound volume of [Voice Recorder Pro](https://itunes.apple.com/ar/app/voice-record-pro/id546983235?mt=8): maximum as possible
	* turn off "energy saver" features
	* system notifications off
	* turn off sound alarms
	* turn off gps (location services off)
	* turn off wifi
	* no hdmi cable attached
	* no A/V remote connector attached
	* [VoiceOver](https://www.apple.com/accessibility/iphone/vision/) disabled
	* no headphones monitoring attached
	* a dedicated [microphone](https://bitbucket.org/imhicihu/focus-group-2016/src/efe6ed9347a086fea9f3a0b01b9b1705809d2dce/improvements.md?at=default) is a must (the better sound capture, the better and swifter transcripts will be!)

+ Video recorder:
    * format internal hard disk drive
	* verify battery charge (100% charge is advisable)
    * fasten to the tripod
	* measure [ambiental lux](https://itunes.apple.com/es/app/light-meter-lux-measurement-tool/id642285909?mt=8)
    * verify current date & hour
	* verify exposure / white balance
	* no gps data allowed
	* video compression format: AVCHD (HD)
	* recording quality: HD (1080/60I)
	* turn off flash light
    * sound volume: middle setting, not to the max to avoid saturation
	* sound format: 2 channels, stereo, 44000 Mhz
	* video format: mpeg 4
	* no zoom
	* disable face detection feature
	* manual focus on
	* SD card (encrypted with [VeraCrypt](https://veracrypt.codeplex.com/))
    * internal hard disk: once the edition of sound was made and backed on DVDs, the internal hard disk of the camcorder was formatted. (Vide on [SR11 Guide](https://bitbucket.org/imhicihu/focus-group-2016/downloads/sr11guide.pdf), p. 7)

+ Computer (Mac OS X El Capitan operating system)
    * enable login password for session
	* disable automatic login
	* disable energy savers: no screen sleep / no put hard drive on sleep
	* verify battery charge: 100% charge is advisable
	* enable [FileVault](https://support.apple.com/en-us/HT204837)
	* disabe wifi
	* disable geolocation
	* install [VirtualBox](https://www.virtualbox.org/wiki/VirtualBox)
	* create a [virtual machine](https://en.wikipedia.org/wiki/Virtual_machine)
	* install inside this virtual machine: [Audacity](http://www.audacityteam.org/) for audio treatment & noise reduction
	* during audio edition: no background tasks allowed
	* install [Disco](http://www.discoapp.com/): record & transfer to DVD both video & audio treated
	* during recording-transference of data to DVD: no background tasks allowed

+ Pen drives
    * no pen drives was used (media insecure and prone to error) along the project

+ Hard drives
    * Lacie 3Tb [LaCie Private-Public](http://www.lacie.com/la/es/products/software/private-public/) encryption schema activated
	* Toshiba 1Tb (encrypted by [VeraCrypt](https://veracrypt.codeplex.com/))
	* both hard drives will be used in case of emergency (as backup purpose)

### Location ###

+ Focus Group Room 
    * verify the environmental temperature
	* verify the surround noise of close rooms & outsides. Measure the [decibels](https://bitbucket.org/imhicihu/focus-group-2016/issues/12/workflow-software-involved).
	* verify the illumination. Measure the [lux](https://bitbucket.org/imhicihu/focus-group-2016/issues/12/workflow-software-involved).


### Procedures: ###

+ Emails:
	    * send invitations via [Mailchimp](https://bitbucket.org/imhicihu/focus-group-2016/issues/17/workflow-webapp-used)
+ Video:
        * all the sessions were recorded on HD.
	    * from the internal hard drive of the digital video camcorder were transferred to the hard drive encripted of a macbook computer. Moreover, it was created a virtual machine, from where it were recorded to blank dvds for backup purpose
	    * Once recorded, it was delivered by hand to destination
	    * The virtual machine was obliterated
	    * Both portable hard drives were wipped once the process ended
+ Audio:
        * all the videos were extracted the sound
	    * those sounds were treated and improved: i.e. noise reduction (mostly) it was applied for a better transcription
		* `experimental:` all the sounds will be treated with this webapp for future speech recognition: [Speechmatics](https://www.speechmatics.com/labs/real-time-demo/)