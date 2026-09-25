# Задание 1
Доступа к докер хабу нет, так что просто скрин образа кастомного
<img width="836" height="517" alt="image" src="https://github.com/user-attachments/assets/ccbe0e42-7bbe-4a29-9cbf-f8508c8bfe78" />

# Задание 2
<img width="1062" height="38" alt="image" src="https://github.com/user-attachments/assets/df957f9e-9aca-49bc-9ffe-54109fdb6102" />
<img width="1790" height="158" alt="image" src="https://github.com/user-attachments/assets/45e334b2-97f1-427b-bda8-378720f9d911" />
<img width="650" height="154" alt="image" src="https://github.com/user-attachments/assets/97e4414d-1ff6-4f07-b1fd-baefb4fdfc89" />

# Задание 3
<img width="1265" height="348" alt="image" src="https://github.com/user-attachments/assets/22de37ad-b340-438b-a113-ced365805741" />
<img width="623" height="209" alt="image" src="https://github.com/user-attachments/assets/cc691383-92a0-4e91-abc8-0733cc695076" />
<img width="648" height="121" alt="image" src="https://github.com/user-attachments/assets/ae416e45-bbaa-44ab-a022-d92d8f9f344f" />

Когда мы настраивали докер контейнер, мы настраивали пересылку с 8080 на 80 порт, но внутри образа контейнера мы поменяли на 81 порт, веб сервер перестал слушать 80 порт вообще, а при обращении на 8080 мы все еще стучимся на 80 порт

<img width="723" height="70" alt="image" src="https://github.com/user-attachments/assets/c4d7e41d-3eb3-4902-bb4e-d719b6b3a741" />

# Задание 4
<img width="1038" height="178" alt="image" src="https://github.com/user-attachments/assets/ef26196f-3e73-4821-b5d8-02932598b599" />
<img width="1220" height="175" alt="image" src="https://github.com/user-attachments/assets/a864d13a-c174-48b2-a67e-eeed03f51c2c" />

# Задание 5
<img width="1127" height="186" alt="image" src="https://github.com/user-attachments/assets/f1bc5f1a-3166-4d0a-b5c9-16421b5644e3" />
первым запустился файл compose.yaml, тк докер композ ищет конфигурационные файлы в строго определенном порядке, согласно спецификации

<img width="1196" height="445" alt="image" src="https://github.com/user-attachments/assets/682f2144-f07f-45d4-8654-e4c0b217468b" />
<img width="825" height="432" alt="image" src="https://github.com/user-attachments/assets/c753f9c1-0a5a-45d4-abbe-3dba8976ab74" />

<img width="1261" height="790" alt="image" src="https://github.com/user-attachments/assets/43e5ab8b-ef0a-4cc2-8393-2e89323e0ea1" />
<img width="887" height="414" alt="image" src="https://github.com/user-attachments/assets/a1beafb4-3b21-4a02-b101-63b936e568c7" />

<img width="1484" height="79" alt="image" src="https://github.com/user-attachments/assets/13b40633-2d45-46da-84bc-3a750acc83c1" />

Docker Compose обнаружил работающий контейнер portainer, созданный этим проектом ранее, однако в оставшемся файле конфигурации этот сервис отсутствует. Compose помечает такие контейнеры как "осиротевшие" (orphaned). Для их автоматической очистки Compose предлагает использовать флаг --remove-orphans»

<img width="1191" height="119" alt="image" src="https://github.com/user-attachments/assets/aa2d2c45-7537-4dd4-8a9a-fe63aabb5d65" />
