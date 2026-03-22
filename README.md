# Simulación Piper Alpha – Entrega 2

## Descripción del Proyecto
Esta simulación representa la plataforma Piper Alpha y recrea de manera interactiva el primer piso crítico donde ocurrió la tragedia, destacando zonas de riesgo y procedimientos de seguridad. El objetivo del proyecto es comprender la dinámica de la plataforma y los riesgos presentes, integrando triggers, partículas y elementos interactivos para simular la pérdida de vida y las zonas seguras.  

La simulación se basa en el artículo de Fiona Macleod CEng FIChemE y Stephen Richardson, y en el informe de la investigación pública de W.D. Cullen (1990), que documenta los eventos ocurridos el 6 de julio de 1988.  

Artículo base incluyendo PFD y Plot Plant: https://www.thechemicalengineer.com/features/piper-alpha-the-disaster-in-detail/

---

## Escenas y Estructura
1. **Primer piso – Zona crítica**  
   - Contiene compresores y triggers de riesgo.  
   - El personaje pierde vida al acercarse a zonas peligrosas.  
   - Interacciones con elementos mediante raycast para aprender información de la plataforma.  

2. **Segundo piso – Oficinas y áreas seguras**  
   - Área donde el personaje se salva.  
   - Presencia de un NPC patrullando (IA básica).  
   - Elementos de interacción: camas y objetos de oficina.  

3. **Tercer piso – Helipuerto**    
   - Representa la zona de evacuación.  

4. **Menú principal**  
   - Botón para iniciar la simulación.  
   - Botón para salir de la aplicación.  

---

## Controles del Jugador
- **Moverse:** Teclas W, A, S, D  
- **Saltar:** Barra espaciadora
- **Correr:** Shift Izquierdo 
- **Interactuar con objetos:** Acercar la cámara (raycast)  
- **Regresar al menú:** Tecla específica (Q)  

---

## IA de Enemigos/NPC
- NPC en segundo piso patrullando.  
- Patrullaje por puntos y detección de proximidad.   

---

## Interacciones y Triggers
- Primer piso contiene triggers de pérdida de vida y partículas visuales que indican peligro.  
- Elementos informativos interactivos mediante raycast.  
- Zonas seguras en el segundo piso permiten al jugador recuperar estabilidad.  
- Finalización de la simulación al llegar al segundo piso.  

---

## Cómo Ejecutar la APK
1. Descargar el archivo `Simulacion_PiperAlpha.apk` desde este repositorio.  
2. Transferir el APK a un dispositivo Android compatible.  
3. Instalar la aplicación (habilitar instalación desde fuentes desconocidas si es necesario).  
4. Ejecutar la aplicación y usar los controles para interactuar con la simulación.  

---

## Créditos y Referencias
- Artículo base: Fiona Macleod CEng FIChemE y Stephen Richardson.  
- Informe de la investigación pública: W.D. Cullen, *The Public Inquiry into the Piper Alpha Disaster*, HMSO, London, 1990.  
- Modelos y assets 3D tomados de Assets de Unity.  
- Partículas y triggers implementados en Unity 3D.  
