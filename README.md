#  Habla Fluido  Aprende inglés con un tutor de IA

R2
### la prueba existe pero `comparador.dart` todavía no, así que no compila.
![R2 rojo](capturas/R2_comparador_rojo.jpg)
tes
<img width="996" height="827" alt="image" src="https://github.com/user-attachments/assets/497c3f32-1da5-4203-b283-802c4d35d16d" />

** Verde:** con `comparador.dart` pasan las 12 pruebas.
![R2 verde](capturas/R2_comparador_verde.jpg)

--gren aha
<img width="1491" height="1095" alt="Captura de pantalla 2026-11-23 114939" src="https://github.com/user-attachments/assets/1ccd2a5b-befa-42f6-b065-869ae3cf6b0c" />

<img width="1900" height="1101" alt="image" src="https://github.com/user-attachments/assets/cc9810c6-dd3b-412f-b43f-d727519e94bd" />


** Rojo:** faltan `repaso.dart`, `progreso.dart` y `plan_diario.dart`.
![R3 rojo](capturas/R3_repaso_progreso_rojo.jpg)

test 

<img width="808" height="607" alt="image" src="https://github.com/user-attachments/assets/54c58444-0ba7-46f1-b9f8-4c4a7b28fca9" />


** Verde:** 32/32 en verde.
![R3 verde](capturas/R3_repaso_progreso_verde.jpg)

V
<img width="867" height="691" alt="image" src="https://github.com/user-attachments/assets/b14f32f4-c01a-438f-837d-e086c030981a" />
**Rojo:** faltan `tutor_simulado.dart` y `tutor_http.dart` (0/17).
![R7 rojo](capturas/R7_tutor_rojo.jpg)

** Verde:** 17/17 del tutor, 49/49 en total.
![R7 verde](capturas/R7_tutor_verde.jpg)

<img width="1901" height="1081" alt="image" src="https://github.com/user-attachments/assets/221a0953-0da6-45b6-ab9e-772d1cd8d224" />
### ViewModels.
![Todas verde](capturas/R9_todas_verde.jpg)

---
Rojo
<img width="1513" height="1002" alt="Captura de pantalla 2026-11-23 121352" src="https://github.com/user-attachments/assets/bb4d9fb4-0e4e-4d36-b664-62f1da0834ec" />
 verde

 

<img width="720" height="1600" alt="image" src="https://github.com/user-attachments/assets/073a6055-60e7-40c5-8969-59781dc5b479" />

<img width="720" height="1600" alt="image" src="https://github.com/user-attachments/assets/4bffa6ae-edd8-4972-b649-aad388560ca5" />

<img width="720" height="1600" alt="image" src="https://github.com/user-attachments/assets/9d7a5f60-b5cb-44b0-bca9-8a7b6f24ae90" />


##  Cómo ejecutarlo
```bash
flutter create .        # genera android/ ios/ etc. (solo la primera vez)
flutter pub get
flutter test
flutter run
```
Para el proxy:
```bash
cd proxy
node --test
```

## 🔒 Privacidad
- Solo se guarda progreso y tarjetas en el teléfono; la conversación no se guarda.
- La llave de la IA y el prompt viven en el proxy, nunca en la app.
- No escribas datos personales en el chat con el tutor.
