<div align="center">

### ***"Дополнительное задание"*** 
</div>

+ Отправить http запрос на сервер.
http://162.55.220.72:5005/object_info_3?name=Vadim&age=32&salary=1000
 Отправить http запрос на сервер.
http://162.55.220.72:5005/terminal-hw-request
curl -X GET "http://162.55.220.72:5005/object_info_3?name=Vadim&age=32&salary=1000"
curl -X GET "http://162.55.220.72:5005/terminal-hw-request".

 
+ Написать скрипт который выполнит автоматически пункты 3, 4, 5, 6, 7, 8, 132. 
1   `vim good.sh`
Нажать `i`.
ВВедем команды:
`mkdir document_book
cd document_book
mkdir Mor_1 Mor_2 Mor_3
touch crud_1.txt crud_2.txt crud_3.txt puh_1.json puh_2.json
mkdir bit_1 bit_2 bit_3
ls -la
mv crud_1.txt puh_1.json Mor_1/`
Нажмем ESC. Сохраним и выйдем: `:wq
2 chmod +x good.sh
3 ./good.sh1`