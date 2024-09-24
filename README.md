# ansi-1
ansible hw-1

### 1. Попробуйте запустить playbook на окружении из test.yml, зафиксируйте значение, которое имеет факт some_fact для указанного хоста при выполнении playbook.
"12"
![alt text](image.png)

### 4. Проведите запуск playbook на окружении из prod.yml. Зафиксируйте полученные значения some_fact для каждого из managed host.
![alt text](image-2.png)

### 5. Добавьте факты в group_vars каждой из групп хостов так, чтобы для some_fact получились значения: для deb — deb default fact, для el — el default fact.
### 6. Повторите запуск playbook на окружении prod.yml. Убедитесь, что выдаются корректные значения для всех хостов.
![alt text](image-3.png)

### 7. При помощи ansible-vault зашифруйте факты в group_vars/deb и group_vars/el с паролем netology.
![alt text](image-4.png)

### 8. Запустите playbook на окружении prod.yml. При запуске ansible должен запросить у вас пароль. Убедитесь в работоспособности.
![alt text](image-5.png)

### 9. Посмотрите при помощи ansible-doc список плагинов для подключения. Выберите подходящий для работы на control node.
### 10. В prod.yml добавьте новую группу хостов с именем local, в ней разместите localhost с необходимым типом подключения.
### 11. Запустите playbook на окружении prod.yml. При запуске ansible должен запросить у вас пароль. Убедитесь, что факты some_fact для каждого из хостов определены из верных group_vars.
![alt text](image-6.png)
