# laraveltest2-create

## STEP00-- create 
    cmd指令:  composer create-project laravel/laravel --prefer-dist `專案名稱`
         ->>  產生 `專案名稱` 的laravel專案  (專案位置從cmd的指令可以查看)
   ![00](https://user-images.githubusercontent.com/87159618/125014338-1b291b00-e0a0-11eb-800f-eaa57bcc0b27.PNG)

## STEP01--啟動檔案
    cmd指令:  cd XXX/XXX
         ->>  進入專案資料夾
    cmd指令:  php artisan serve
         ->>  用指令的方式開啟php檔案
```diff
- Fatal error:  require():   "可能原因1"composer沒完整安裝成功
```
![01](https://user-images.githubusercontent.com/87159618/125013730-f2545600-e09e-11eb-88ce-f84d8948f802.PNG)


```diff
#    cmd指令:  composer install
#        ->>   安裝composer
```
![3](https://user-images.githubusercontent.com/87159618/125015909-026e3480-e0a3-11eb-8400-9ee80066546f.PNG)

## STEP02--再次啟動檔案
    cmd指令:  php artisan serve
         ->>  用指令的方式開啟php檔案
```diff
+ 成功開啟
```      
![4](https://user-images.githubusercontent.com/87159618/125016190-7d374f80-e0a3-11eb-9f76-c8f601aba8f6.PNG)

## STEP03--開啟瀏覽器
    網址輸入:  http://127.0.0.1:8000
         ->>  在瀏覽器上開啟我們的專案
 ```diff
- missing key:generate:   "可能原因" 專案資料夾下的.env 找不到KEY
-                  ->>   .env 裡的 APP_KEY= 的資料是空的(網站專屬密鑰用來確保session、password等加密資料安全性)
```
 ![error](https://user-images.githubusercontent.com/87159618/125016572-2716dc00-e0a4-11eb-8186-6fd1708c43c1.PNG)

```diff
#    cmd指令:  php  artisan key:generate
#        ->>   產生APP_KEY(網站專屬密鑰)
```
    
![圖片](https://user-images.githubusercontent.com/87159618/125017047-f1bebe00-e0a4-11eb-86e1-d28bfed6aa0b.png)
## STEP04--開啟瀏覽器(專案建立與開啟成功)
    網址輸入:  http://127.0.0.1:8000
         ->>  在瀏覽器上開啟我們的專案
![6](https://user-images.githubusercontent.com/87159618/125017106-0c913280-e0a5-11eb-8140-4f69d019c6d2.PNG)

         



