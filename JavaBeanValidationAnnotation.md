Java uygulamalarımızdaki sınıflarımızın ve bağlı alanlarımızın validate edebileceğimiz anotasyonlar bulunmaktadır.

Uygulamalarımızda kullanabileceğimiz bu anotasyonlar sayesinde daha hızlı bir şekilde isteklerimize göre doğrulama yapabilmekteyiz.

### Java Bean Validation Geçmişi

Bean validation geçmişine bakacak olursak

JSR 303 ile 2009 yılında kabul edildi.
JSR 349 1.1 versiyon olarka yayındandı.
JSR 380 ile 2017 yılında 2. versiyon yayınlandı Hibernate Validator kullanıldı ve Spring Framework 5’e eklendi.

### Java Bean Validation Anotasyonları

Uygulamalarımızda kullanabileceğimiz Java anotasyonlarına bakalım. Bu anotasyonların içerisinde hem Java spesifikasyonundan gelen hem de Hibernate Validator’den implement edilen anotasyonlar bulunmaktadır. Sıklıkla kullanabileceğiniz validasyon anotasyonları aşağıdadır.

**@Null – Null olur.**

**@NotNull – Null olamaz.**

**@Pattern – Yazılan RegEx patern doğruluğu**

**@NotEmpty – Null ya da empty olamaz.**

**@NonBlank – Whitespace ya da null olamaz.**

**@Email – Email formatını doğrular**

**@AssertTrue – Değer doğru**

**@AssertFalse – Değer yanlış**

**@Min – Büyük veya eşit**

**@Max – Küçük veya eşit**

**@Negative – Negatif zorunlu.**

**@NegativeOrZero – 0 ya da negatif zorunlu**

**@Positive – Pozitif zorunlu**

**@PositiveOrZero – 0 ya da pozitif.**

**@Size – size’ın verilen aralıkta olmalı.**

**@Past – Geçmiş tarih olmalıdır.**

**@PastOrPresent – Geçmiş tarih ya da şimdiki bir tarih olmalıdır.**

**@Future – Gelecek tarih olmalıdır.**

**@FutureOrPresent – Gelecek tarih ya da şimdiki tarih olmalıdır.**

**@CreditCardNumber – Kredi kartı formatı**

**@Currency – Değer kontrolü**

**@EAN – EAN format**

**@ISBN – ISBN format**

**@Length – Verilen uzunlukta olmalıdır.**
1
