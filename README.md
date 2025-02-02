Öncelikle dosyamızı ve github üzerinden repositoryimizi oluşturdum. Daha sonra dosyayı git bash'le açarak git init yaptım.
git remote add origin https://github.com/gokdenizayrilmis/akademi-aralikproje1.git yazarak terminale git repomun yolunu gösterdim ve tanıttım
touch komutunu kullanarak not isimli bir txt dosyası oluşturdum. Not dosyası olusturuldu mesajıyla ilk commitimi attım.
readme dosyamı github üzerinde oluşturmuştum dolayısıyla localde geride kaldım. git pull yazarak repodaki değişiklikleri locale çektim
ve readme dosyasını oluştururken attığım commit locale geldi. Simdi not üzerinde değişiklik yapıp commit atacağım. 
Simdi git branch features yazıp features isimli bir branch oluşturacağım. git switch features yazıp features branchine geçeceğim
Su an features içerisindeyim not üzerinde değişiklik yapacağım ve commitleyeceğim. Simdi master branchine geri dönüp kontrol edeceğim.
git log yazdığım zaman features üzerinden attığım commiti göremiyorum. git merge features yazdığım zaman features içinde yaptığım değişiklikleri master'a getirmiş oldum
master branchinde herhangi bir değişiklik yapmadan features branchinde geliştirmelerimi yapabiliyorum eğer uygun görürsem mastera entegre edebiliyorum.
git checkout attığımız commitlerin id'sini kullanarak o anki durumuna dönmek için kullanıyoruz.
git reset <commit'inhashcode'u> = Commit'i siler.
git reset --hard <commit'inhashcode'u> = Hash code'u yazılan commit'e döner. Bu commit'ten sonra atılmış tüm commit'ler kalıcı olarak silinir.
*git stash = x branchi içinde çalışmalarını yaparken yaptığın değişiklikleri commit etmeden çıkabilmene yarıyor örneğin: x içinden master'a geçeceksin ama x'te biraz değişiklik var o değişiklikleri kaybetmemeni sağlıyor save ediyor. 
*git stash pop = save ettiğin değişiklikleri geri getiriyor.
*git conflict hatası = aynı anda aynı branche commit atmaya çalışılınca bu hata meydana geliyor. merge işlemi uygulanmalı 

ödevde sırayla nasıl yaptığımı yazdım.
