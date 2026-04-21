##Part 1
![alt text](https://file%2B.vscode-resource.vscode-cdn.net/Users/nitaalvi/Desktop/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202026-04-18%20%D0%B2%2022.21.21.png?version%3D1776540112135)
Узнаем версию Ubuntu, выполнив команду
cat /etc/issue
##Part2
<img width="1100" height="894" alt="Снимок экрана 2026-04-18 в 22 55 30" src="https://github.com/user-attachments/assets/5923e6b2-cb67-46ed-9c83-026c68981f16" />

Создаем нового пользователя adm_user и добавляем его в группу adm, на скриншоте вывод команды cat /etc/passwd
<img width="507" height="50" alt="Снимок экрана 2026-04-18 в 22 59 55" src="https://github.com/user-attachments/assets/6295f356-6c93-4e5c-8d36-eaa6fd9dca05" />

Тут показано, что пользователь adm_user находится в группе adm
###Part3.1
с помощью команды sudo hostname user-1 задаем название машины 
<img width="337" height="17" alt="image" src="https://github.com/user-attachments/assets/421bb724-71fb-43c6-b4d9-d2b67136a02d" />
<img width="250" height="55" alt="image" src="https://github.com/user-attachments/assets/aef96870-9e77-4155-8863-083aedd17dd4" />

###Part3.2
timedatectl set-timezone Europe/Moscow - меняем часовой пояс на московский(+3)
###Part3.3
<img width="2396" height="672" alt="image" src="https://github.com/user-attachments/assets/b43ab35f-7e5b-4ba0-9408-1a2525785ed0" />

тут два сетевых интерфейса: lo, enp0s3. lo это виртуальный сетевой интерфейс, который перенаправляет любой трафик обратно на компьютер, он нужен, например, для обмена данными между клиентскими и серверными приложениями.
###Part3.4
<img width="1758" height="700" alt="image" src="https://github.com/user-attachments/assets/78d1d85c-fe73-48ed-b5b9-8d8e057bdcf9" />

ip адрес на строчке inet, Dynamic Host Configuration Protocol(DHCP)
###Part3.5
<img width="1758" height="700" alt="image" src="https://github.com/user-attachments/assets/167aae1b-90d1-4f6d-80ab-1e697aa2f53e" />

curl ifconfig.me для внешнего и ip a для внутреннего(enp0s3 inet)
