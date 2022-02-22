# Windows server

## Развертывание и управление контроллерами домена локально

![image](https://user-images.githubusercontent.com/79700810/154964932-b68f6a18-e7f1-4fd0-b324-a7a36d5d98a4.png)

![image](https://user-images.githubusercontent.com/79700810/154964957-2ea50603-b7c4-42f9-8da6-f95455292dd2.png)



![image](https://user-images.githubusercontent.com/79700810/154964987-939d9408-08b9-412e-ae77-68ce42cf33da.png)

Установка и настройка ролей осуществляется на в кладке Manage также есть возможность управлениями несколькими удаленными серверами

![image](https://user-images.githubusercontent.com/79700810/154965027-d8eb9355-5b67-4102-94f3-54b0f2c7abe4.png)

Установка роли осуществляется отметкой в check box при выборе роли есть краткое описание ее назначения 

![image](https://user-images.githubusercontent.com/79700810/154965085-a2622606-f2bd-4a8d-a2c2-77284169b627.png)

![image](https://user-images.githubusercontent.com/79700810/154965103-6bd8e207-dd54-4ca7-ad4f-96bd2197b241.png)

![image](https://user-images.githubusercontent.com/79700810/154965133-7425e06f-8225-4583-9fa6-23197fb7b61e.png)

В ходе установки и настройки может понадобиться перезагрузка при установке отметки сервер это сделает в автоматическом режиме 

![image](https://user-images.githubusercontent.com/79700810/154965154-e8f3c1da-fa5f-42a0-a0ae-abd21da5e0e9.png)

## настраивать и управлять сайтами AD DS

![image](https://user-images.githubusercontent.com/79700810/154965381-f6d1cc6c-a081-4a24-b436-1665b48345d1.png)

После установки роли необходимо ее настроить, а именно указать имя нового домена и создать лес.

![image](https://user-images.githubusercontent.com/79700810/154965889-6a087975-c671-406d-a7c8-85a852f95c88.png)

Далее выбрать уровень работы леса и домена, задать криптостойки пароль для базы данных 

![image](https://user-images.githubusercontent.com/79700810/154965994-e47be956-22d8-4999-a1e6-ff677f14955c.png)

![image](https://user-images.githubusercontent.com/79700810/154966018-0073551c-60a0-4e2a-a5dc-3f6dc74009b0.png)

![image](https://user-images.githubusercontent.com/79700810/154966050-7908ae4b-5c31-44bd-a142-232701f74740.png)

![image](https://user-images.githubusercontent.com/79700810/154966074-7b9c7acf-ecbf-4709-be3c-3fcb74df873f.png)

![image](https://user-images.githubusercontent.com/79700810/154966095-df3a4e10-9ddf-4ea7-a3fe-29791a5b788e.png)

Перед завершение настроек сервер автоматически произведет валидацию конфигурации и даст рекомендации 

![image](https://user-images.githubusercontent.com/79700810/154966151-e787e998-116d-4988-8733-c9f1b8278217.png)

В ходе завершения настройки сервер автоматически перезагрузиться 


![image](https://user-images.githubusercontent.com/79700810/154967257-2b4e2fb8-4a3c-4e45-9bf5-5b3324565f17.png)

![image](https://user-images.githubusercontent.com/79700810/154967495-feba7c5d-9599-4d06-bdc9-317c0802b268.png)

![image](https://user-images.githubusercontent.com/79700810/154967596-40efebb7-a450-411f-9bd1-66469339bdc7.png)


## Развертывание контроллеров домена только для чтения (RODC)

