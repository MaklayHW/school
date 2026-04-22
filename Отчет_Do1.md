## Part 1
<img width="254" height="43" alt="image" src="https://github.com/user-attachments/assets/597d8bac-1214-435d-a209-2d625e55a438" />

Узнаем версию Ubuntu, выполнив команду
cat /etc/issue
## Part2
<img width="1100" height="894" alt="Снимок экрана 2026-04-18 в 22 55 30" src="https://github.com/user-attachments/assets/5923e6b2-cb67-46ed-9c83-026c68981f16" />

Создаем нового пользователя adm_user и добавляем его в группу adm, на скриншоте вывод команды cat /etc/passwd
<img width="507" height="50" alt="Снимок экрана 2026-04-18 в 22 59 55" src="https://github.com/user-attachments/assets/6295f356-6c93-4e5c-8d36-eaa6fd9dca05" />

Тут показано, что пользователь adm_user находится в группе adm
### Part3.1
с помощью команды sudo hostname user-1 задаем название машины 
<img width="337" height="17" alt="image" src="https://github.com/user-attachments/assets/421bb724-71fb-43c6-b4d9-d2b67136a02d" />
<img width="250" height="55" alt="image" src="https://github.com/user-attachments/assets/aef96870-9e77-4155-8863-083aedd17dd4" />

### Part3.2
timedatectl set-timezone Europe/Moscow - меняем часовой пояс на московский(+3)
### Part3.3
<img width="2396" height="672" alt="image" src="https://github.com/user-attachments/assets/b43ab35f-7e5b-4ba0-9408-1a2525785ed0" />

тут два сетевых интерфейса: lo, enp0s3. lo это виртуальный сетевой интерфейс, который перенаправляет любой трафик обратно на компьютер, он нужен, например, для обмена данными между клиентскими и серверными приложениями.
###Part3.4
<img width="1758" height="700" alt="image" src="https://github.com/user-attachments/assets/78d1d85c-fe73-48ed-b5b9-8d8e057bdcf9" />

ip адрес на строчке inet, Dynamic Host Configuration Protocol(DHCP)
### Part3.5
<img width="1758" height="700" alt="image" src="https://github.com/user-attachments/assets/167aae1b-90d1-4f6d-80ab-1e697aa2f53e" />

curl ifconfig.me для внешнего и ip a для внутреннего(enp0s3 inet)

### Part 3.6
<img width="217" height="224" alt="image" src="https://github.com/user-attachments/assets/20d7e771-a8ac-40bb-979c-344f5a221675" />
sudo nano /etc/netplan/00-installer-config.yaml
Прописываем, как на скриншоте
sudo netplan apply
<img width="507" height="307" alt="image" src="https://github.com/user-attachments/assets/8e2d5f94-d0b7-41ef-adaa-7422f46d0641" />
### Part3.7
<img width="538" height="259" alt="image" src="https://github.com/user-attachments/assets/4c60d30f-2ba2-476b-92dc-be7560f434d3" />
<img width="565" height="343" alt="image" src="https://github.com/user-attachments/assets/95cf25b7-3634-4962-8b8b-35448ca05c7f" />
## Part4
<img width="805" height="114" alt="image" src="https://github.com/user-attachments/assets/196c0b61-e884-497a-84f4-e51c17b375a8" />
## Part5
<img width="364" height="64" alt="image" src="https://github.com/user-attachments/assets/82a956a8-b12a-4df4-a106-41de1aa67b9e" />

sudo (SuperUser DO) позволяет авторизованным пользователям выполнять команды с привилегиями суперпользователя.
## Part6
<img width="350" height="232" alt="image" src="https://github.com/user-attachments/assets/e36c35b2-506b-40be-8d2e-01ec98e947dd" />
## Part7
<img width="801" height="610" alt="image" src="https://github.com/user-attachments/assets/d8bb07a3-7df2-4d77-aac0-c5709591f1ee" />
:wq enter
<img width="773" height="585" alt="image" src="https://github.com/user-attachments/assets/3f82b3ec-f372-4b85-952e-9b8e7ed86c70" />
ctrl + o, enter, ctrl + x

<img width="824" height="594" alt="image" src="https://github.com/user-attachments/assets/354a307c-d30a-4e13-9532-48e8aab8befe" />
ctrl + k, x

<img width="809" height="608" alt="image" src="https://github.com/user-attachments/assets/873686a5-bf71-4dc4-9afc-eaa7d3f7afc8" />
:q1 enter

<img width="803" height="591" alt="image" src="https://github.com/user-attachments/assets/ec14a629-30c4-4d46-99bb-178fdc061fc6" />
ctrl + x, n
<img width="803" height="585" alt="image" src="https://github.com/user-attachments/assets/5d33bfef-1131-4d91-ab81-077d81b585d6" />
ctrl + c, y

<img width="801" height="602" alt="image" src="https://github.com/user-attachments/assets/41a0b9b2-9a43-4c6d-a72c-ab354597f0ba" />
<img width="360" height="601" alt="image" src="https://github.com/user-attachments/assets/dea46104-a6d9-4e08-90a4-06051082e4cd" />

<img width="475" height="547" alt="image" src="https://github.com/user-attachments/assets/f7f9ad43-0ca9-4c82-ae17-6925e86e3c7f" />
Alt + R, School, enter, uni, enter, a
<img width="122" height="25" alt="image" src="https://github.com/user-attachments/assets/418c9a4a-5968-44ca-a8aa-1c440fe74610" />
Ctrl + k, f, r
## Part 8
<img width="641" height="95" alt="image" src="https://github.com/user-attachments/assets/d048aa92-bf9e-4d6e-bbd8-3e2b8f2f45a6" />
## Part 9
<img width="801" height="606" alt="image" src="https://github.com/user-attachments/assets/61d47890-ca0a-4910-b491-64b694ad8038" />
784 mem

<img width="802" height="603" alt="image" src="https://github.com/user-attachments/assets/f85b4eeb-e7d5-4999-977f-bbef25cd4849" />

<img width="803" height="601" alt="image" src="https://github.com/user-attachments/assets/8ba9fdc7-976f-40b9-91c3-10507e1bf5d9" />

<img width="799" height="599" alt="image" src="https://github.com/user-attachments/assets/803f170e-d9cc-43f9-82bd-63eda2b76dd8" />

<img width="798" height="600" alt="image" src="https://github.com/user-attachments/assets/9fcf4c2d-8ab3-4abc-ba0d-bc1509b0b647" />

<img width="803" height="600" alt="image" src="https://github.com/user-attachments/assets/bdba6eef-960f-4d46-a478-dbaa97ff91f3" />

<img width="804" height="601" alt="image" src="https://github.com/user-attachments/assets/f4a35f73-f076-4dbf-a23f-b6c67e5359a6" />

<img width="797" height="598" alt="image" src="https://github.com/user-attachments/assets/7ff2c037-e6d0-4244-98b7-53be55eaaeca" />
## Part14
<img width="802" height="47" alt="image" src="https://github.com/user-attachments/assets/78f0f060-78ca-42ba-8b0a-b07a06b91b47" />

<img width="650" height="85" alt="image" src="https://github.com/user-attachments/assets/ebd264a1-151f-44b3-a296-76e7ad2474b3" />




















