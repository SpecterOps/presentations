# LSA Whisper

**Speaker:** Evan McBroom

# Abstract

Accessing LSASS memory has been a common goal for attackers due to its management of user credential 
material. Microsoft has added multiple features to Windows to make gaining such access more difficult 
including Credential Guard, Remote Credential Guard, and Protected Processes Light (PPL). These 
features are helpful but irrelevant if an attacker is able to request credentials from the LSA 
directly. The presentation cover such an approach and how accessing LSASS memory is unneeded to recover 
a wealth of credential data and to perform other attacker tradecraft.