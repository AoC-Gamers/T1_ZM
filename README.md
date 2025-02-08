# Tier1 ZoneMod v2.8.9e

[EN] [translation](https://translate.google.com/translate?sl=es&tl=en&u=https://github.com/AoC-Gamers/t1_zm)

*T1 ZM* es una configuración competitiva para Left 4 Dead 2, cuyo objetivo es proporcionar la experiencia de zonemod para jugadores nuevos.

## Características

### Diferencia con ZoneMod
- Se reemplaza el sistema de bonus de zonemod por el oficial.
- Se eliminan las restricciones para las armas smg, shotgun
- Se eliminan las restricciones de reaparición de infectado bot.
- El rango de lerps para la interpolación es de 0 a 100.
- Se podrá cancelar el inicio de readyup solo 1 vez.

## Instalación
1. T1 ZM requiere el proyecto base [L4D2-Competitive-Rework](https://github.com/SirPlease/L4D2-Competitive-Rework). Descárgalo e instálalo primero.
2. Descarga los archivos desde el [repositorio de GitHub](https://github.com/AoC-Gamers/t1_zm).
3. Extrae los archivos en la carpeta principal de tu servidor.
4. Configura los archivos según tus necesidades (ver [Configuración](wiki/Configuración.md)).
5. Reinicia el servidor para aplicar los cambios.

### Complementos sugeridos
- [anti-friendly_fire](https://github.com/fbef0102/L4D1_2-Plugins/tree/master/anti-friendly_fire)

## Configuración

### Agregar modo de juego
Para habilitar *T1 ZM* en las votaciones del servidor, edita el archivo `addons/sourcemod/configs/matchmodes.txt` y agrega:

```plaintext
"MatchModes"
{
    "Tier1 ZM Configs"
    {
        "t1_zm"
        {
            "name" "Tier1 ZM"
        }
    }
}
```
Luego, reinicia el servidor para aplicar los cambios.

## Contribuciones
Gracias por tu interés en contribuir a *T1 ZM*, Puedes reportar problemas o sugerir mejoras a través de la [página de issues](https://github.com/AoC-Gamers/t1_zm/issues) o enviando un *pull request* en el [repositorio de GitHub](https://github.com/AoC-Gamers/t1_zm/pulls).

## Licencia
*T1 ZM* está licenciado bajo la licencia **CC-BY-SA 3.0**. Para más información, consulta el [texto completo de la licencia](http://creativecommons.org/licenses/by-sa/3.0/legalcode).

# Copyright
*Tier1 ZM* es es una adaptación de "ZoneMod".
Todos los complementos y códigos acondicionados son de sus respectivos autores.
```
- https://github.com/SirPlease/L4D2-Competitive-Rework
```
