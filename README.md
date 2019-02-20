# Spring Data JPA with Hibernate using MySql Example
Bu proje MySQL Örneğini kullanarak Hibernate ile Spring Data JPA ile Spring Boot Örneğini göstermektedir.

## Description
Bu Proje, MySQL Veritabanında depolanan Kullanıcıların listesini gösterir. Aşağıda belirtildiği gibi  kullanarak, farklı işlemler elde edilebilir:
- `/rest/users/all` - Bu, MySQL Tablosunda (kullanıcılar) oluşturulan Kullanıcılar tablosundaki Kullanıcılar listesini döndürür.
- `/rest/users/{name}` - Bu, URL’de geçen Kullanıcıların ayrıntılarını döndürür
- `/rest/id/{id}` -Bu, URL’de geçen kullanıcı kimliği için Kullanıcıların ayrıntılarını döndürür
- `/rest/update/{id}/{name}` -Bu, URL’de geçirilen kullanıcı kimliği için kullanıcının adını günceller.

## Libraries used
- Spring Boot
- Spring MVC (Spring Web)
- Spring Data JPA with Hibernate
- MySql

## Tools used
- IntelliJ IDEA 
- MySql running locally

