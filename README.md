# CI для проекта epm.  
В пайплайне происходит сборка deb пакета.  
Далее пакет устанавливается в чистом окружении.  
Что сделано:  
- Build deb package  
- Install deb package    
Что нужно доделать:  
- Исправить ошибку build rpm.  
- Написать test install rpm package.  
Что можно сделать лучше:  
- При использованиии имени файла пакета использовать команды  
epm --version и uname с различными ключами, 
для определения версии ядра и архитектуры.  
- На данный момент проверить успешно ли установлен пакет можно зайдя в jobs - test и посмотреть статус команды dpkg.  
Лучше переделать на использование условий.  

