# devops-netology
-first note<br><br>
В .gitignore терраформа указаны следующие ограничения:<br>
– .terraform/ - игнорируется папка .terraform и всё её содержимое.<br>
– *.tfstate, *.tfstate.* — игнорируются все файлы с расширением .tfstate и любые файлы, имя которых начинается с .tfstate<br>
– crash.log, crash.*.log — игнорируется файл crash.log и все файлы формата crash.что-угодно.log<br>
– *.tfvars, *.tfvars.json — игнорируются все файлы с расширением .tfvars и .tfvars.json<br>
– override.tf, override.tf.json — игнорируются файлы с именами override.tf и override.tf.json<br>
– *_override.tf, *_override.tf.json — игнорируются все файлы, имя которых заканчивается на _override.tf или _override.tf.json<br>
– .terraform.tfstate.lock.info — игнорируется файл блокировки terraform.tfstate.lock.info<br>
– .terraformrc, terraform.rc — игнорируются файлы конфигурации CLI с такими именами<br>

