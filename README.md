# RF-V28
List of valid sms commands for the tracker rf-v28 from reachfar

Check out: https://ands.dk/onewebmedia/RF-V28_user.pdf for a list of commands.

https://github.com/tananaev/traccar/files/213814/3g.elec.comm.protocol.docx for the data protocol.

Standard ip settings: ip,113.81.229.9,5900# (doesn't reset with factory reset)

traccar protocoll: watch , port 5013

	ts#

		reply with config info
	
	von,[1-4]# / voff#

		vibration alarm, 4 is lowest sens, mod command changes this alarm type too
	
	non,[0-1?]#

		  noise alarm?
	
	verno#

		  replies with version number
	
	sms,[0-1]#

  		set sending of sms
	
	aon,[0-1]#

 		battery alarm
	
	url#

  		send LBS data or google maps link
	
	gprsgps,[0-1],[0-1]#

  		set gprs funktion and continuos gps tracking function
	
	upload,[sec]#

  		set tracking interval for continuos tracking
	
	cr#

  		single positioning
	
	worktime,[sec?]#

  		how long to track for single positioning
	
	update#

  		???
	
	monitor,[phone nr]#

  		silently calls this number
	
	hon,[0-1]#

  		??? reply with the state is open/closed
	
	find#

  		lets tracker ring
	
	where#

  		track & no sms
