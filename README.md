# ArmTemplate

# Folder Structure

MyARMTemplateProject/
│
├── templates/
│   ├── mainTemplate.json
│   ├── parameters.json
│   └── (other-template-files.json)
│
├── scripts/
│   ├── patching-script.sh
│   ├── antivirus-script.sh
│   └── (other-scripts)
│
├── resources/
│   ├── virtualMachines/
│   │   ├── customScriptExtension/
│   │   │   ├── patch-extension.json
│   │   │   ├── antivirus-extension.json
│   │   │   └── (other-extensions)
│   │   └── (other-vm-resource-files.json)
│   │
│   ├── virtualNetwork.json
│   ├── subnet.json
│   ├── networkSecurityGroup.json
│   └── (other-resource-files.json)
│
├── parameters/
│   ├── vmParameters.json
│   ├── networkParameters.json
│   ├── extensionParameters.json
│   └── (other-parameter-files.json)
│
├── scripts/
│   ├── patching-script.sh
│   ├── antivirus-script.sh
│   └── (other-scripts)
│
└── README.md
