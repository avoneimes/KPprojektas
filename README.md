#Projektas - Komunalinės Paslaugos

#Aprašymas
Šis projektas yra skirtas valdyti komunalines paslaugas, leidžiant administratoriui prisijungti, valdyti pirkėjus ir prekes bei generuoti sąskaitas faktūras.

#Naudojimo Galimybės
Prisijungimas prie sistemos
Pridėti, ištrinti, redaguoti pirkėjus
Peržiūrėti visų esamų pirkėjų sąrašą
Pridėti, ištrinti, redaguoti prekes
Peržiūrėti visų esamų prekių sąrašą
Surasti pirkėją ir prekes pagal paiešką
Įrašyti prekių kiekį ir sugeneruoti PDF sąskaitą faktūrą

#Login langas:
Username: admin
Password: admin01
"Show password" - * paverčia į raides ir parodo slaptažodį
"Log in" - prisijungti prie sistemos
"Close" - uždaryti programėlę

#Home langas:
"Show" mygtukas - išskleidžia meniu:

  #New Buyer puslpapis:
  Name - Įrašyti vardą
  Phone No - Įrašyti tel. nr
  Email - įrašyti el. pašto adresą
  Address - Įrašyti gyvenamosios vietos adresą
  Gender - pasirinkti lytį
  "Save" mygtukas - išsaugoti naują sukurtą pirkėją
  "Reset" mygtukas - ištrinti visą įrašytą/pasirinktą informaciją
  "Close" mygtukas - uždaryti langą
  
  #Update Buyer puslpapis:
  Phone number - įrašyti esamą duombazėj (jau sukurtą) tel. nr.
  "Search" mygtukas - ieško pirkėją iš duombazės pagal tel. nr. ir išveda pirkėjo informacija ekrane (Name, Phone No, Email, Address, Gender) 
  *į paieškos langą galima įrašyti kitą tel. nr. tik paspaudus "Reset" mygtuką
  Suradus egzistuojantį tel. nr. galima keisti pirkėjo duomenys (Name, Phone No, Email, Address, Gender) 
  "Update" mygtukas - atnaujinti (išsaugoti naujus įvestus) pirkėjo duomanys
  "Reset" mygtukas - ištrinti visą informaciją text field'uose (galimybė ieškotį kitą tel. nr. pirkėją)
  "Close" mygtukas - uždaryti langą
  
  #Buyers Details langas:
  Išveda visų esamų pirkėjų duombazėje sąrašą ir informaciją apie juos (Name, Phone No, Email, Address, Gender) 
  "Print" mygtukas - atsispausdinti sąrašą
  "Close" mygtukas - uždaryti langą
  
  #Delete Buyer langas:
  Phone number - įrašyti esamą duombazėj (jau sukurtą) tel. nr.
  "Search" mygtukas - ieško pirkėją iš duombazės pagal tel. nr. ir išveda pirkėjo informacija ekrane (Name, Phone No, Email, Address, Gender) 
  *į paieškos langą galima įrašyti kitą tel. nr. tik paspaudus "Reset" mygtuką
  Suradus egzistuojantį tel. nr. galima ištrinti pirkėją ir jo duomenys (Name, Phone No, Email, Address, Gender) iš duombazės
  "Delete" mygtukas - ištrinti pirkėją ir jo duomenys (Name, Phone No, Email, Address, Gender) iš duombazės
  "Reset" mygtukas - ištrinti visą informaciją text field'uose (galimybė ieškotį kitą tel. nr. pirkėją)
  "Close" mygtukas - uždaryti langą
  
  #New Product langas:
  Product ID - automatiškai sukuriamas skaičius nurodantis produkto ID (aplengvina produkto paiešką)
  Product Name - Įrašyti produkto pavadinimą
  Rate - Įrašyti produkto kainą
  Description - įrašyti aprašymą
  Activate - pasirinkti aktyvuoti produktą ar ne
  "Save" mygtukas - išsaugoti naują sukurtą pirkėją
  "Reset" mygtukas - ištrinti visą įrašytą/pasirinktą informaciją
  "Close" mygtukas - uždaryti langą
  
  #Update Product langas:
  Product ID - įrašyti esamą duombazėj (jau sukurtą) tel. nr.
  "Search" mygtukas - ieško produktą iš duombazės pagal prekės ID ir išveda produkto informaciją ekrane (Product Name, Rate, Description, Activate) 
  *į paieškos langą galima įrašyti kitą Product ID tik paspaudus "Reset" mygtuką
  Suradus egzistuojantį produkto ID galima keisti prekės informaciją (Product Name, Rate, Description, Activate) 
  "Update" mygtukas - atnaujinti (išsaugoti naujus įvestus) prekės duomanys
  "Reset" mygtukas - ištrinti visą informaciją text field'uose (galimybė ieškotį kitą Product ID (prekę))
  "Close" mygtukas - uždaryti langą
  
  #Product Details langas:
  Išveda visų esamų produktų duombazėje sąrašą ir informaciją apie juos (Product Name, Rate, Description, Activate) 
  "Print" mygtukas - atsispausdinti sąrašą
  "Close" mygtukas - uždaryti langą

  #Delete Product langas:
  Product ID - įrašyti esamą duombazėj (jau sukurtą) produkto ID
  "Search" mygtukas - ieško prekę iš duombazės pagal produkto ID ir išveda produkto informaciją ekrane (Product Name, Rate, Description, Activate) 
  *į paieškos langą galima įrašyti kitą Product ID tik paspaudus "Reset" mygtuką
  Suradus egzistuojantį Product ID galima ištrinti produktą ir jo duomenys (Product Name, Rate, Description, Activate) iš duombazės
  "Delete" mygtukas - ištrinti produktą ir jo duomenys (Product Name, Rate, Description, Activate)  iš duombazės
  "Reset" mygtukas - ištrinti visą informaciją text field'uose (galimybė ieškotį kitą Product ID (produktą))
  "Close" mygtukas - uždaryti langą
  
  #Billing langas:
  Date - rodoma šiandienos data
  Time - rodomas dabartinis laikas
  Buyers Details:
  Surandame reikiamą pirkėją:
  Pirkėjo paieškai užtenka įrašyti pirmąją pirkėjo vardo raidę arba tel. nr. ir paspausti enter - pasirodys visi pirkėjo duomenys (jeigu toks pirkėjas egzistuoja)
  Product Details:
  Surandame reikiamą produktą:
  Produkto paieškai įrašykite product ID ir paspauskite Enter - pasirodys visi produkto duomenys (jeigu toks produktas egzistuoja)
  Quantity - įrašome prekių kiekį ir spaudžiame "ADD" mygtuką - produktas ir jo duomenys pasirodys lentelėje, taip pat, prie Calculation Details pasirodys Total skaičius
  *į lentelė galima pridėti kelis produktus ir kiekius ieškodami naują produktą pagal ID, ivedus Quantity ir paspaudus "ADD"
  Paid Amount - įrašome (išgalvotą) skaičių kiek mums sumokėjo pirkėjas, spaudžiame Enter - atsiras Return Amount - kiek grąžos mes skolingi pirkėjui
  "Save" mygtukas - išsaugoja sugeneruotą sąskaitą faktūrą jūsų kompiuteryje "Desktop" aplanke
  "Reset" mygtukas - ištrinti visą informaciją text field'uose (galimybė ieškotį kitą pirkėją, produktą ir generuoti naują sąsk. fakt.)
  "Close" mygtukas - uždaryti langą
  
  #Logout mygtukas:
  Išsiregistruoti iš sistemos (grįžtama į Log in langą)
  
  #Close Application mygtukas:
  uždaryti programėlę
