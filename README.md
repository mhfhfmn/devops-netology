# devops-netology
## First modify
Описание gitignore для Terraform
Будет проигнорирована папка .terraform со всем ее содержимым, где бы она ни находилась в проекте: .terraform/

Будут проигнорированы файлы, заканчивающиеся на .tfstate, например example.tfstate: *.tfstate

Будут проигнорированы файлы, в середине названий которых имеется .tfstate., например example.tfstate.1: .tfstate.

Будет проигнорирован файл crash.log: crash.log

Будет проигнорирован файл, который начинается на crash. и заканчивается на .log, например crash.1203.log: crash.*.log

Будут проигнорированы файлы, заканчивающиеся на .tfvars, например example.tfvars: *.tfvars

Будут проигнорированы файлы, заканчивающиеся на .tfvars.json, например example.tfvars.json: *.tfvars.json

Будет проигнорирован файл override.tf: override.tf

Будет проигнорирован файл override.tf.json: override.tf.json

Будут проигнорированы файлы, заканчивающиеся на _override.tf, например example_override.tf: *_override.tf

Будут проигнорированы файлы, заканчивающиеся на _override.tf.json, например example_override.tf.json: *_override.tf.json

Будет проигнорирован файл .terraform.tfstate.lock.info: .terraform.tfstate.lock.info

Будет проигнорирован файл .terraformrc: .terraformrc

Будет проигнорирован файл terraform.rc: terraform.rc

add new string
new string in IDE Visual Studio Code