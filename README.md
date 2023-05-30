Sistemi i Shpërndarë duke përdorur Komunikime Ndërmjet Procesesh (IPC), Threads dhe Sinkronizim

Ky projekt implementon një sistem të shpërndarë në C në Linux, duke përdorur Komunikimet Ndërmjet Procesesh (IPC), Threads dhe mekanizma të sinkronizimit. Sistemi përbëhet nga një server që mund të trajtojë kërkesa nga shumë klientë në të njëjtën kohë.


Veçoritë: 
Është caktuar një numër maksimal i klientëve që mund të lidhen me serverin.
Serveri kthen përgjigjen e të dhënave të klientit në përgjigje.


Mekanizmat e Implementuar: 
Serveri implementon mekanizmat IPC të mëposhtëm:
Komunikim me Mesazhe: Klientët komunikojnë me serverin duke përdorur radhë mesazhesh (message queues).
Memorie e Ndajtur: Memorien e ndarë të përdorë për komunikim midis proceseve në server dhe klientë.
Pipes: Pipes përdoren për komunikim midis serverit dhe klientëve.


Kërkesat Bazë: 
Sistemi përfshin një program serveri që mund të trajtojë kërkesa nga shumë klientë duke përdorur mekanizmat IPC, threads dhe sinkronizim.
Programi server është në gjendje të trajtojë një numër maksimal të klientëve, numri maksimal të caktuar në një konstante ose skedar konfigurimi.
Klientët janë në gjendje të lidhen me serverin dhe të dërgojnë kërkesa duke përdorur mekanizmat IPC.
Serveri kthen përgjigjen e të dhënave të klientit në përgjigje.
Implementimi demonstron përdorimin e duhur të mekanizmave të sinkronizimit për të siguruar ndarjen dhe mbrojtjen e burimeve.
