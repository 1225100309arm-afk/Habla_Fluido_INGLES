#  Habla Fluido  Aprende inglés con un tutor de IA


### la prueba existe pero `comparador.dart` todavía no, así que no compila.
![R2 rojo](capturas/R2_comparador_rojo.jpg)

** Verde:** con `comparador.dart` pasan las 12 pruebas.
![R2 verde](capturas/R2_comparador_verde.jpg)

<img width="1900" height="1101" alt="image" src="https://github.com/user-attachments/assets/cc9810c6-dd3b-412f-b43f-d727519e94bd" />


** Rojo:** faltan `repaso.dart`, `progreso.dart` y `plan_diario.dart`.
![R3 rojo](capturas/R3_repaso_progreso_rojo.jpg)

** Verde:** 32/32 en verde.
![R3 verde](capturas/R3_repaso_progreso_verde.jpg)

**Rojo:** faltan `tutor_simulado.dart` y `tutor_http.dart` (0/17).
![R7 rojo](capturas/R7_tutor_rojo.jpg)

** Verde:** 17/17 del tutor, 49/49 en total.
![R7 verde](capturas/R7_tutor_verde.jpg)

### ViewModels.
![Todas verde](capturas/R9_todas_verde.jpg)

---
<img width="1901" height="1081" alt="image" src="https://github.com/user-attachments/assets/221a0953-0da6-45b6-ab9e-772d1cd8d224" />


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
