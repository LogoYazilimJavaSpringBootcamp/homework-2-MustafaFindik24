# homework-2

Java dünyasındaki framework’ler ve çözdükleri problemler nedir?(Spring MVC, JSP,
Struct, Vaadin). Örnekler ile açıklayın. (20 Puan)




• Katmanlı mimari nedir? (10 Puan)

  Geliştirilen projenin iş bölümünün aşamalara ayrıldığı bir sistemdir. Her katmanın yapacağı iş bellidir ve diğer katmanlarda gerçekleşen işlerden izole şekilde bir geliştirme yapılır. Projelerimizde yaptığımız model, service, controller gibi ayrı ayrı oluşturduğumuz packagelar katmanlı mimariye örnek verilebilir. 

• Garbage collector nedir, nasıl çalışır? Diğer C++ ile karşılaştırın. (10 Puan)

  Yaratılan nesneler bellekte yer kaplar. Java' da ise eğer nesne kullanılmıyorsa JVM' in içinde bulunan Garbage Collector bellekte o nesneye ayrılan yeri
  boşa çıkarır ve bellek kullanımı en aza indirgenir. C/C++ dillerde ise bir nesne oluşturulduktan sonra eğer nesneyle işimiz biterse manuel olarak         kapatmamız gerekir. Java bu özelliğiyle birlikte daha verimli ve performansı daha yüksek bir dildir. 

• Spring frameworkünün kullandığı design patternlar neler? (10 Puan)

  - Singleton pattern --> Spring' in default olarak kullandığı pattern çeşididir. 
  - Factory Method pattern
  - Proxy pattern
  - Template pattern


• Creational Patterns neler? Önceki ödevde oluşturulan nesnelerinizi factory Design
patterni ile oluşacak şekilde düzenleyin. (25 Puan)

• Singleton ve AbstractFactory patterlerini implemente eden kodu yazın.(25 Puan)
