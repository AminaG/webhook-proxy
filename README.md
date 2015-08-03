Example for settings.json

	[
	{
		"ip":"127.0.0.5",
		"log":"mylog1.json",
		"webhooks":[
			{
				"url":"http://requestb.in/1fdvicp1",
				"log":"mylog2.json"
			},
			{
				"url":"https://ek0fcy1x0jjm.runscope.net/abc?d",
				"log":"mylog2.json"
			}
		]
	}
	]


Run example:

	node webhoook-proxy --help						
	node webhook-proxy --config "settings.json"	
	node webhook-proxy --watch						Reload everytime the settings file changed.