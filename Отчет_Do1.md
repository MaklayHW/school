##Part 1
![alt text](https://file%2B.vscode-resource.vscode-cdn.net/Users/nitaalvi/Desktop/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202026-04-18%20%D0%B2%2022.21.21.png?version%3D1776540112135)
Узнаем версию Ubuntu, выполнив команду
cat /etc/issue
##Part2
<img width="1100" height="894" alt="Снимок экрана 2026-04-18 в 22 55 30" src="https://github.com/user-attachments/assets/5923e6b2-cb67-46ed-9c83-026c68981f16" />

Создаем нового пользователя adm_user и добавляем его в группу adm, на скриншоте вывод команды cat /etc/passwd
![alt text](file:///Users/nitaalvi/Desktop/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202026-04-18%20%D0%B2%2022.59.55.png)
Тут показано, что пользователь adm_user находится в группе adm
###Part3.1
с помощью команды sudo hostnamectl set-hostname user-1 задаем название машины 
![alt text](<Снимок экрана 2026-04-20 в 19.29.07.png>)
###Part3.2
timedatectl set-timezone Europe/Moscow - меняем часовой пояс на московский(+3)
###Part3.3
![alt text](https://file%2B.vscode-resource.vscode-cdn.net/Users/nitaalvi/Desktop/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202026-04-20%20%D0%B2%2018.52.47.png?version%3D1776701823300)
тут два сетевых интерфейса: lo, enp0s3. lo это виртуальный сетевой интерфейс, который перенаправляет любой трафик обратно на компьютер, он нужен, например, для обмена данными между клиентскими и серверными приложениями.
###Part3.4
![alt text](<Снимок экрана 2026-04-20 в 19.17.51.png>)
ip адрес на строчке inet, Dynamic Host Configuration Protocol(DHCP)
###Part3.5
![alt text](<Снимок экрана 2026-04-20 в 19.34.28.png>)
curl ifconfig.me для внешнего и ip a для внутреннего(enp0s3 inet)
