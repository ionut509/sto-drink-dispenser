# Lista de componente (BOM — Bill of Materials)

| Cantitate | Componentă | Specificații / Rol |
| :---: | :--- | :--- |
| 1 | Sursă de alimentare | AC 230V → DC 12V / 5A + conector Jack |
| 1 | Întrerupător general | Întrerupere alimentare principală 12V |
| 1 | Convertor Buck DC-DC | Coborâtor 12V → 5V pentru alimentarea ESP32 |
| 1 | Microcontroler ESP32 | Placă de dezvoltare `ESP32-WROOM-32` (Wi-Fi AP + Web Server) |
| 3 | Driver motoare `TB6612FNG` | Drivere duale H-bridge (comutare 12V pentru câte 2 pompe fiecare) |
| 6 | Pompe peristaltice Kamoer | 12V DC, 5W, cap peristaltic pentru uz alimentar |
| 1 | Microswitch | Senzor mecanic de prezență pahar (oprire de siguranță) |
| 1 | Condensator electrolitic `1000 µF` | Filtrare magistrală principală 12V |
| 1 | Condensator electrolitic `470 µF` | Stabilizare alimentare 5V către ESP32 |
| 3 | Condensatoare electrolitice `100 µF` | Decuplare locală pe alimentarea `VM` a fiecărui modul `TB6612FNG` |
| ~6 m | Furtun din silicon alimentar | Traseu igienic sticlă → pompă → duză comună |
| 1 set | Carcasă printată 3D | Filament **PETG**, design stilizat „Șto” |

> **Notă de siguranță:** Verificați polaritatea condensatoarelor electrolitice înainte de alimentare și asigurați izolarea compartimentului de electronică față de zona de turnare a lichidelor.
