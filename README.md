# devops-netology
Домашняя работа №2
игнорируем файлы в папке .terraform
игнорируем файлы которые оканчиваются на ".tfstate" и в которых в середине есть ".tfstate."
игнорируем лог файл crash.log
игнорируем файл с окончанием ".tfvars"
игнорируем файлы "override.tf" и "override.tf.json"
Игнорируем файлы, которые оканчиваются на "_override.tf" и "_override.tf.json"
Игнорируем файлы .terraformc и terraform.rc

все эти файлы не будут учитыватья при коммите и работать с Git
