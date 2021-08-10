# rsa_alg
RSA ALGORİTMASI

-  2 tane asal sayı seçilir.
-  seçilen iki sayi çarpılır bir n degeri bulunur.
-  fi sayısını bulmak için asal sayıların bir eksiği alınıp çarpılır.
-  e degeri bulmak için 1 ile fi arasında aralarında asal gcd(e,fi)=1 olacak şekilde e sayısı seçilir.
-  e n sayısı şifrelemek için kullanılır ve açıktırlar.
-  fi sayısı gizlidir.
-  deşifreleme için d degeri bulmak gerekiyor 1 ile fi arasında  e.d=1mod(fi) , mod(fi)=1 olacak sekilde d sayısı hesaplanır bu da desifreleme anahtarı oluşmuş olur.
-  şifreleme kısmı için dışardan girilen mesaj 0 ile n-1 arasında olacak sekilde m<n şeklinde bir rakama çevrilir.
-  şifrelemek için c=m^e % n
-  deşifrelemek için m=c^d % n kullanılır.
