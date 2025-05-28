Proyecto: 
project-java-herencia

Descripcion jerarquia de clases: 
┌────────────────────┐
│ ComponenteVehicular│  ← Clase base
└────────────────────┘
         ▲
         │
 ┌───────┼────────────────────────────────────────────────┐
 │       │               │              │                 │
▼       ▼               ▼              ▼                ▼
Motor  Transmision   Neumatico       Chasis     SistemaFrenos

Ejecucion Main:
PS D:\Java\project-java-herencia>  & 'C:\Program Files\Java\jdk-24\bin\java.exe' '--enable-preview' '-XX:+ShowCodeDetailsInExceptionMessages' '-cp' 'D:\Java\project-java-herencia\bin' 'Main' 
==== MOTOR ====
Código: M001
Fabricante: Bosch
Cilindros: 4
Potencia: 120 HP
Motor encendido con 4 cilindros y 120 HP.

==== TRANSMISIÓN ====
Código: T001
Fabricante: ZF
Tipo: Automática
Número de marchas: 6
Cambiando a la marcha 3...

==== NEUMÁTICO ====
Código: N001
Fabricante: Michelin
Tamaño: 17 pulgadas
Presión: 32.5 PSI
Presión óptima.

==== CHASIS ====
Código: C001
Fabricante: Toyota
Tipo de chasis: Monocasco
Peso: 250.0 kg
Carga máxima estimada: 875.0 kg

==== SISTEMA DE FRENOS ====
Código: F001
Fabricante: Brembo
Sistema ABS: Sí
Tipo de discos: Discos ventilados
Sistema ABS operativo.