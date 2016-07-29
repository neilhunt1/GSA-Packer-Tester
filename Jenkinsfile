stage name: '1st Stage'

node("master"){
	checkout scm
	sh "/usr/local/packer validate first.json"
	sh "/usr/local/packer build first.json"
}