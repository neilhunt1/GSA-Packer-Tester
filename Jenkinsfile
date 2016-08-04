stage name: '1st Stage'

node("master"){
	checkout scm
	sh "/usr/local/packer validate initial.json"
	sh "/usr/local/packer build initial.json"
}