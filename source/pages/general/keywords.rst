Key words
=========

..	- What: 
	- Where:
	- How:

This file contains all the key words that need to be linked to a documentation
source

**Installing a box for a specific client**

.. code-block:: yaml
	:linenos:
	
	steps:
		- What: a step is
		- Where: steps are stored
		- How: steps work/ the step proccess works
		- How: to activate a set of steps
		- How: to modify steps
		- How: to create new steps

	box iframe:
		- What: is the Cleed box iFrame
		- Where: From where does it get the box application
		- How: Does the link between the client's website and Cleed's server work
		- How: does its intallation on a client's website work
		- What: doest the <script> line do exactly
		- How: to generate a new <script> line for a client and for a box
		- How: to deactivate a box for a specific client
		- How: to deactivate all the boxes
		- Mobile:
			- How to deactivate on mobile (all and specific)

	scrapping:
		- What: the scrapping process does
		- Where: the scrapper is located
		- How: the scrapping works
		- What: tools are being used
		- How: to launch a scrapping process
		- Shopify:
			- Shopify scrapping

	normalization:
		- What: the process is
		- Where: the tools are stored
		- How: the process works
		- CSV:
			- What: it represents for Cleed
			- Where: they are stored
			- How: they interact with other components
			- How: to use them / fill them
			- Which: other tools they interact with

	admin:
		- What: is the admin panel
		- Where: is the code
		- How: to access it
		- How: create a new store account
		- MISSING DETAILS: What else is there to know about admin

	matomo:
		- What: is Matomo's role in the box, admin, or other tools
		- Where: is Matomo's data stored
		- Where: is the code stored
		- How: to access its data
		- How: to configure it
		- How: to create new data entries, triggers, ...

	parameters:
		- Assistant:
			- How: to swtich between human & bot
			- What: other options are there
		- Scroll:
			- How: to modify / remove scroll timing
		- Staging:
			- How: to deploy to staging
			- Where: is a stagging deploy stored
			- How: to setup auto-deploy
		- Style:
			- How: to modify the styling
			- Where: is it stored
		- Text (i18n):
			- How: to modifiy the text
			- Where: is it stored

	deployment:
		- How: to deploy to production
		- How: to deploy *only* for one client

	box loging in:
		- What: what it is
		- How: how it works
		- Where: is the code for this feature stored
		- How: does it link itself to a client's users database
		- How: to activate it
		- MISSING DETAILS: What else is there to know about the box login process

	recomendations: .

	databases:
		- access:
			- Where: are the databased located at
			- How: to access the databases
		- store products:
			- How: products are stored (fields, client customizations ?, ...)
		- store configuration:
			- What: is a store configuration
			- How: to access it
			- How: to correctly download JSONs and reupload them

	AWS:
		- How: to access the AWS console
		- How: to turn an instance ON / Off
		- How: to swtich between regions
		- How: to open ports on an instance

	dialogflow: 
		- MISSING DETAILS: What else is there to know about dialogflow

	Assistant Chat:
		- Slack:
			- How: to create a new user for a client
			- Where: is the code that manages Slack communications

	workflow:
		- ( How the team works or should be working )
		- ( & How stuff has been organised so far )

		- Git:
			- What: workflow is being used
			- What: are the naming rules of that workflow
			- How: is the code review being done

		- Tests:
			- How: is unit testing setup (standards, dates, ...)
			- How: is functional testing setup (standards, dates, ...)
			- (If setup) How: is e2e testing setup (standards, dates, ...)
			- What: tools are being used

		- Technical specs:
			- How: are technical specs & details being shared
			- How: are projects described
			- What: are all the types of documents used for tech specs
				- Project file
				- Readme
				- Manuals
				- Feature file
				- Hotfix file
				- Gantt charts
				- ...

		- Sprints:
			- How: are sprints organized
			- What: tools are being used
