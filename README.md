## 🏠 Home Assistant Blueprints and Automation files
Welcome to this automation repository! The main purpose is YAML code storage of adjusted community blueprints into working automation files.
Navigate to Home Assistant blueprints to find both generic and specialised automation files, without the need to YAML code modification. 

## 🚀 Usage

### Two options for YAML code creation/modification:

##### OPTION 1 - Using HAOS UI: 
Install Studio Code Server
Navigate to automation files using the SCS explorer:

`` /root/homeassistant/blueprints/automation/`` 

Modify/Create automation files.

##### OPTION 2 - Using HAOS VM Console
Type ``login`` to open bash cli.
Navigate to automation YAML files using: 
``cd /mnt/data/supervisor/homeassistant/blueprints/automation/``
Modify/Create automation files using:
``vi automation_file.YAML``
Type ``i`` to edit, type ``ESC + :wq`` to save and exit. 

#### HAOS UI: Import new automation
Navigate to Settings -> Automations & Scenes -> Create Automation. 
Click on the created automation file. 
Follow the on-screen prompts (if coded) to configure the automation with your entities and settings.

#### HAOS UI: Reload modification to existing automation
Click Settings -> Developer Tools -> Automations.
This will reload the modified automation file to memory.

For more detailed instructions, please refer to the official Home Assistant documentation on Blueprints.
