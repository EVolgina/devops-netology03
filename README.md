# devops-netology03
# 3 time 
# исключить локальный каталог terraform , где бы он не находлся и все файлы в нем.
# исключить все файлы с расширением *.tfstate и все файлы с расширением *.rfstate.* и
# содержащиеся в этом каталоге файлы
# исключить все файлы с расширением .*tfvars .*tfvars.json , которые могут содержать конф данные
# игнорируйте все файлы переопределения для локального переопределения ресурсов, кроме override.tf
# override.tf.json, *_override.tf, *_override.tf.json
# Включите переопределяющие файлы, которые вы хотите добавить в систему управления версиями,
# используя шаблон !exemple_override.tf. Включите файлы tfplan, чтобы игнорировать вывод команды
# plan:terraform-out=tfplan exmple :*tfplan*. Игнорировать файлы конфигурации CLI
# .terraformrc terraform.rc
# 3 домашка, день второй
