# devops-netology
devops-netology
# Мой репозиторий для DevOps

## Правила игнорирования в .gitignore

В каталоге `terraform/` используется файл `.gitignore`, который содержит следующие правила:

- `*.tfstate` – игнорируются все файлы с расширением `.tfstate` (знак `*` заменяет любое имя файла).
- `*.tfstate.*` – игнорируются все файлы, в имени которых после `.tfstate` идёт точка и любое окончание.
- `crash.log` – игнорируется конкретный файл `crash.log`.
- `*.tfvars` – игнорируются все файлы с расширением `.tfvars`.
- `override.tf` – игнорируется конкретный файл `override.tf`.
- `terraform.tfplan` – игнорируется конкретный файл `terraform.tfplan`.
- `!example.tfplan` – восклицательный знак означает исключение из игнорирования (файл `example.tfplan` не будет игнорироваться, даже если подпадает под другие правила).
- и другие, перечисленные в файле.

<img width="1919" height="1199" alt="image" src="https://github.com/user-attachments/assets/136f3b6c-d8fb-4d68-b253-1029f0d77567" />

<img width="1919" height="1094" alt="image" src="https://github.com/user-attachments/assets/def89a9a-632b-4507-af46-1b24ee68cce9" />
