# Programming with Sockets

## Përshkrimi i Projektit

Ky projekt paraqet një implementim praktik të komunikimit klient-server duke përdorur protokollin UDP. Ai është zhvilluar në gjuhën C++ në mjedisin Windows dhe demonstron mënyrën se si një server dhe disa klientë mund të komunikojnë në rrjet për të kryer operacione të caktuara.
Serveri ruan skedarë të ndryshëm, përfshirë një skedar tekstual dhe një batch file, ndërsa klientët mund të ndërveprojnë me serverin duke dërguar kërkesa të ndryshme. Sistemi është ndërtuar mbi një model me role, ku ekzistojnë dy role kryesore: **admin** dhe **klient**. Admini ka privilegje shtesë, si shkrimi në skedarët e serverit dhe ekzekutimi i komandave të caktuara, ndërsa klientët e zakonshëm kanë qasje më të kufizuar.
Funksionalitetet kryesore të projektit përfshijnë leximin e një skedari të ruajtur në server, shkrimin në atë skedar me autorizim të adminit, si dhe marrjen dhe ekzekutimin e një batch file nga serveri në kompjuterin e klientit.
Në përgjithësi, ky projekt demonstron përdorimin praktik të komunikimit përmes UDP-së, menaxhimin e skedarëve dhe kontrollin e qasjes bazuar në role në një aplikacion të thjeshtë klient-server.
Ky projekt është testuar me sukses në një rrjet real lokal duke përdorur të paktën katër pajisje të ndryshme, sipas kërkesave të detyrës. Një pajisje ka funksionuar si server, ndërsa pajisjet tjera janë lidhur si klientë në të njëjtin rrjet përmes Wi-Fi ose hotspot-it. Gjatë testimit është verifikuar dërgimi dhe pranimi korrekt i mesazheve ndërmjet pajisjeve, si dhe funksionimi stabil i komunikimit përmes UDP-së.

## Përfundim

Ky projekt paraqet një zgjidhje funksionale dhe të qartë për realizimin e komunikimit ndërmjet serverit dhe klientëve në rrjet. Përmes organizimit të roleve dhe përdorimit të funksioneve të ndryshme, sistemi arrin të kryejë detyrat e kërkuara në mënyrë të saktë dhe efikase.

