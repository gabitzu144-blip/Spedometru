# Vehicle Speedometer (plugin)

HUD de vitezometru pentru **MrCrayfish's Vehicle (Unofficial 1.20.1)** și **Immersive Vehicles 24.0.0**.
Doar client, Forge 1.20.1 (47.x). Nu depinde la compilare de niciunul dintre moduri – citește datele prin reflecție,
deci rulează cu oricare dintre ele sau cu amândouă (Framework e cerut doar de Vehicle).

## Build
    gradle build            # sau ./gradlew build dacă ai wrapper (gradle wrapper)
    # jar-ul rezultat: build/libs/vehicle-speedo-1.20.1-1.0.0.jar  -> pune-l în mods/

## Config (config/vehiclespeedo-client.toml)
enabled, scale, margin, maxSpeedKmh
