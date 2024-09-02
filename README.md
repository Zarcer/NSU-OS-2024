# NSU-OS-2024
The repository for NSU Operating Systems course for 2024/2025 academic year

Задачи должны отправляться как pull requests к ветке вашего семинариста (если вы не знаете фамилию вашего семинариста, у вас проблемы). Если не знаете, что такое пулл реквест, уточните у семинариста или ознакомьтесь с материалами в классруме. В одном пулл реквесте должна быть ровно одна задача (иначе нельзя будет одну задачу принять, а другую нет).  В пулл реквесте не должно быть посторонних файлов, кроме исходных текстов, Makefile и "персонального" .gitignore (см. последний абзац).

Делайте каждый пулл реквест из отдельной ветки. Перед отведением ветки или перед созданием пулл реквеста, выполните последовательность операций git fetch upstream 
git checkout your_branch 
git rebase upstream/<prepod>/accepted
(при этом в вашей ветке появятся все принятые к данному моменту задачи, это нормально).

Файлы в пулл реквесте должны размещаться в каталогах с именами вида <номер группы>/<имя студента>/lab<номер задачи>/, например 21285/v.pupkin/lab4. "Имя студента" должно совпадать с префиксом e-mail адреса в домене НГУ и именем учетной записи на ccfit.

Если вы хотите создать .gitignore и включить в него файлы, создаваемые вашей средой разработки, вы можете создать его в "вашем" каталоге, e.q. 21285/v.pupkin/.gitignore, и включить его в пулл реквест одной из задач.
