#  Habla Fluido — Aprende inglés con un tutor de IA


### la prueba existe pero `comparador.dart` todavía no, así que no compila.
![R2 rojo](capturas/R2_comparador_rojo.jpg)

** Verde:** con `comparador.dart` pasan las 12 pruebas.
![R2 verde](capturas/R2_comparador_verde.jpg)

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
