# Thais Nexus

Bot gratuito para operar opciones sobre los índices sintéticos de Deriv (Volatility 10, 25, 50, 75 y 100, y sus versiones de 1 segundo). Opera Even/Odd, Rise/Fall, Over/Under y Matches/Differs, corre en tu propio computador y lo manejas desde el navegador.

Lo hizo Jorge Valencia · Automatizaciones.

## Descarga

Descarga la última versión en **[Releases](../../releases/latest)**. Son dos archivos: `ThaisNexus.exe` y `LEEME.txt`.

Descárgalo solo desde aquí. Si alguien te pasa el bot por WhatsApp o por otro lado, compara la huella SHA-256 con la publicada en el release. Si no coincide, no lo abras.

Para ver la huella en Windows, abre PowerShell en la carpeta del archivo y escribe:

```
Get-FileHash ThaisNexus.exe
```

## Cómo empezar

1. Abre `ThaisNexus.exe`. El navegador se abre solo en `http://localhost:5003`.
2. Ve a **Configuración** y pulsa **Conectar con Deriv**. Inicias sesión en la página oficial de Deriv y autorizas la app. El bot nunca ve tu contraseña y solo pide permiso para operar: no puede retirar ni mover tu dinero.
3. Deja el **Modo de cuenta en DEMO** y pruébalo con dinero virtual todo el tiempo que necesites.
4. Elige qué operar, el stake y tu Stop Loss, y pulsa **Iniciar bot**.

Cuando sale una versión nueva, el bot te avisa al abrirlo.

## Requisitos

- Windows 10 u 11. No hace falta instalar Python ni nada más.
- Una cuenta en Deriv (la demo es gratis).
- Que el puerto 5003 esté libre. Si tienes otro programa usándolo, ciérralo antes de abrir el bot.

Windows o tu antivirus pueden avisar que el archivo es de un editor desconocido. Pasa con programas que no están firmados digitalmente. Si la huella SHA-256 coincide con la del release, es el archivo original.

## Es gratis: así se financia

No pagas nada por el bot. Deriv le paga al desarrollador un markup del **3 % sobre el pago potencial** de cada contrato que se abre con él. Ese 3 % hace que lo que cobras cuando ganas sea un poco menor: en un contrato que pagaría $10, recibes $9,70.

## Antes de usarlo con dinero real

Esto es trading, y en el trading se puede perder dinero. Lee esto con calma:

- **El bot no garantiza ganancias.** Ni este ni ningún otro bot puede prometerte un resultado fijo. Habrá rachas buenas y rachas malas.
- El bot elige la estrategia a la que mejor le fue hace poco. Eso no asegura que le vaya a ir bien después.
- La martingala hace las pérdidas más grandes, no las evita.
- El **Stop Loss** es tu protección real. Ponlo siempre.
- Opera solo dinero que puedas perder.

No es asesoría financiera. Solo para mayores de 18 años y en los países donde Deriv ofrece sus servicios.

## Aviso

Thais Nexus es un proyecto independiente. No lo hizo Deriv ni tiene relación con Deriv. "Deriv" es una marca de su respectivo dueño.
