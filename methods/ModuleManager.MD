# Module Manager
**Explanation for every module manager method available in the ZarScript scripting language**
Access the following methods by doing **moduleManager.** and then the following method's name.
## registerModule(moduleInstance)
Registers a scripting module 
## unregisterModule(moduleInstance)
Unregisters a scripting module that has been already registered.
##  registerBoolean(moduleName, settingName, settingDescription, defaultValue)
Registers a setting to a scripting module:
	

 1. moduleName - the scripting modules name
 2. settingName - settings name
 3. settingDescription - concisely explain what the setting does
 4. defaultValue - true/false for the boolean value
 
 ## getBoolean(name)
 Returns a value for a registered boolean **ONLY FOR REGISTERED BOOLEANS IN SCRIPTS!**.
 
