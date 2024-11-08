1. Скачала VirtualBox на Windows 11
2. Создала виртуальну машину Ubuntu- "A"
3. Создала в ней два сетевых адаптера (Adapter2 и Adapter 3)
![image](https://github.com/user-attachments/assets/78da8e49-a191-44d5-a47b-6f87fbb05a65)
![image](https://github.com/user-attachments/assets/d2b2193f-fdb3-439c-8b50-068e8d7ce045)

4. Клонировала машину А и создала машины В и С
![image](https://github.com/user-attachments/assets/c02158f3-e71e-4661-8de6-0430bba64482)

5. Настроила по одному адаптеру в В и С (чтобы В  и С были в разных сетях)
![image](https://github.com/user-attachments/assets/dd906532-2b66-4bbf-b877-12dc95796a48)
![image](https://github.com/user-attachments/assets/1e2e16cc-1018-4a3a-be1b-0f2536556ac7)

6. Настроила сетевые настройки каждого адаптера в машине А
   настроила две сетки с разными адресами- для В и для С
  ![image](https://github.com/user-attachments/assets/ad45cfe0-5e34-49bc-a38e-8cd7908e7cf6)
  ![image](https://github.com/user-attachments/assets/a5d7ba04-e912-4d0f-8f65-d8bedd66cb0b)
  ![image](https://github.com/user-attachments/assets/ffe2561b-59c6-4c36-9c6e-9a46f7d6ea8e)

  
7. Изменила сетевые настройки в машинах В и С (настроила две сетки - абсолютно идентичные, только разный IP адрес)
![image](https://github.com/user-attachments/assets/13d8adfe-3082-4d0a-82fe-2343ce5a96c2)
![image](https://github.com/user-attachments/assets/c22b61ca-f7bc-4567-bf6d-ede53e5921fe)

![image](https://github.com/user-attachments/assets/de0d1781-37f0-4be5-a37d-68487d7f1ea9)
![image](https://github.com/user-attachments/assets/70410755-325c-4291-9eba-d32363a4ebca)

8. Проверяем есть ли доступ из А в В
![image](https://github.com/user-attachments/assets/7eedfdd3-7505-4d2e-a5b6-574c6f65acdd)

9. Проверяем есть ли доступ из А в С
![image](https://github.com/user-attachments/assets/a5f56dcb-d5a9-4c0b-80c2-28a42104736e)

10. Проверяем что нет доступа из В в С
![image](https://github.com/user-attachments/assets/8a3f6708-9bc0-4165-a269-661ed615e2b4)

