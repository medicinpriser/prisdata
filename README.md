# Medicinpriser.se
Med start från 2015 samlade medicinpriser.se in prisuppgifter på receptfria och receptbelagda läkemedel. Här finns all data fram tills nerstägningen den 8 Mars 2021.

## Struktur
Prisdatan är i CSV format där varje rad är en en prisuppdatering för en viss produkt och butik. Till varje rad finns följande information:

Kolumn | Beskrivning
--- | ---
`productNumber` | Unikt produktnummer
`title` | Produktens namn
`shop` | Namn på apotek/butik
`url` | Url till produkten för detta apotek/butik
`packageType` | Typ av förpackning
`size` | Storlek på förpackningen
`prescription` | Om läkemedlet är receptbelagt
`price` | Pris (inkl. moms)
`isCurrentPrice` | Sant om det är det aktuella priset, Falskt om det är historik data
`lastChecked`| När priset senast uppdaterades
`createdAt` | När priset hittades för första gången
`deletedAt` | Om det finns är det tidpunkten när produkten togs bort

