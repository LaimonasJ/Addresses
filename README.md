#Adresu registras. #v.1 Paprastas adresu sarasas. Kiekvienam adresui suteikiamas ID, pagal kuri adresus galima istrinti, surasti. Galimos komandos: GetAll - grazina visus adresus AddModel - prideda nauja modeli GetModel - grazina adresa pagal nurodyta ID DeleteModel - istrina adresa pagal nurodyta ID. Lenteles atributai: ID, Salis, Miestas, Namo numeris buto numeris, Zip kodas
#Gyventoju registras. #v.1 Paprastas gyventoju sarasas. Kiekvienam gyventojui suteikiamas ID pgal kuriuos galima gyventojus surasti istrinti. Galimos komanods: GetAll- grazina visus gyventojus AddModel- prideda gyventoja GetModel- grazina gyventoja pagal nurodyta ID DeleteModel- istrina gyventoja pagal nurodyta ID. Lenteles atributai: ID, vardas, pavarde, asmens kodas, gyvenamojo namo adreso ID

paleidimui paleisti komandas:
  docker build -t laju2259/addresses .
  docker run -d -p 8080:1234 laju2259/addresses:1
