
# Prettier Eslint Husky Template

 - [Read in English](https://github.com/ugurkellecioglu/prettier-eslint-husky-template/blob/main/README.EN.md)

Bu repository mediumdaki yazıma ithafen açılmıştır.
Gerekli paketlerin projeye eklenmiş (prettier, eslint, husky) ve konfigürasyonları yapılmış hali.

Proje create-react-app ile oluşturulmuş olup, kurulum sonrasında cra-template yüzünden gelen test dosyalarına, public dosyalarına falan dokunulmamıştır.
Yani npx create-react-app prettier-eslint-husky-template yazıp kurduğunuz takdirde oluşan dosyalarla birliktedir, tek farkı bizim pre-commit hookumuzun kurulu olmasıdır.




## Installation

Install prettier-eslint-husky-template with npm

```bash
  npm i prettier-eslint-husky-template
  cd prettier-eslint-husky-template
```
    
## Dokümantasyon

    1. Projeyi klonlayın
    2. npm install ya da yarn çalıştırın
    3. Herhangi bir dosyaya girin, app.js ya da app.test.js
    4. Eslint hata vermeli, veriyorsa başarılı
![image](https://user-images.githubusercontent.com/51965140/180928929-5b451d6f-0751-468b-aa6e-4139e7ad464b.png)

    5. Terminaline npm run precommit yazıp bu scripti çalıştırabilirsin.
    6. Böylece prettier çalışacak ve eslint'de hatalarını gösterecek
    7. İlk görevin eslintin gösterdiği hataları fixlemek
    8. Üşenmece gücenmece yok, bu zorlu maceranın sadece ilk adımı bu. Normalde sürekli karşılaşacaksın ve fixleyeceksin eslint hatalarını.
    9. Unutma prettier ve linter'in amacı projene bi standart oluşturmak.



## Katkıda Bulun

Katkıda mı bulunmak istiyosun?

Projeyi klonla, yeni bir branch aç, değişiklik yap, pull request aç.

## Kaynaklar

 - [Prettier](https://github.com/prettier/prettier)
 - [Eslint](https://github.com/eslint/eslint)
 - [Husky](https://github.com/typicode/husky)

