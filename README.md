# Merhaba Git

Git ve GitHub'a ilk adım dersi için hazırlanmış, ekrana "merhaba" yazan en küçük Java projesi. Amaç kodun
kendisi değil; projeyi Eclipse'ten depoya ekleme, commit etme ve gönderme adımlarını göstermektir.

> **Not:** Bu depo 2017 yılında eğitim amaçlı yazıldı ve artık güncellenmiyor.

## İçerik

- `MerhabaGit/src/com/mustafaergan/git/Merhaba.java`: `main` metodu ekrana `merhaba` yazar.
- `MerhabaGit/src/com/mustafa/mustafa.java`: derste eklenen boş bir sınıf.

## Teknolojiler

- Java 8 (dış bağımlılık yok)

## Çalıştırma

```bash
cd MerhabaGit
javac -d out src/com/mustafaergan/git/Merhaba.java
java -cp out com.mustafaergan.git.Merhaba
```

Eclipse'te *File > New > Java Project* ile `MerhabaGit` klasörünü konum olarak gösterip de açabilirsiniz.
