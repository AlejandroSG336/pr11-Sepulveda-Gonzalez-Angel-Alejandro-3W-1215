# pr11-Sepulveda-Gonzalez-Angel-Alejandro-3W-1215

import math  # Importamos la librería math para usar sqrt


# 11. Función que calcula la distancia dirigida entre dos puntos (x1, y1) y (x2, y2)

def distancia_dirigida(x1, y1, x2, y2):

  # Calculamos la distancia usando la fórmula de distancia entre dos puntos
    
   distancia = math.sqrt((x2 - x1) ** 2 + (y2 - y1) ** 2)
    
   # Devolvemos la distancia calculada
    
   return distancia

# Pedimos al usuario que introduzca las coordenadas de los dos puntos

x1 = float(input("Introduce la coordenada x1 del primer punto: "))

y1 = float(input("Introduce la coordenada y1 del primer punto: "))

x2 = float(input("Introduce la coordenada x2 del segundo punto: "))

y2 = float(input("Introduce la coordenada y2 del segundo punto: "))

# Calculamos la distancia entre los dos puntos

distancia = distancia_dirigida(x1, y1, x2, y2)

# Mostramos el resultado

print(f"La distancia dirigida entre los puntos ({x1}, {y1}) y ({x2}, {y2}) es: {distancia}")

![image](https://github.com/user-attachments/assets/78d5f050-8b24-4e2e-876b-661715d5b0e7)
![image](https://github.com/user-attachments/assets/b0ba6208-a345-4b10-b417-948c9ef6d77f)
![image](https://github.com/user-attachments/assets/31438032-9f4a-4983-ac6e-a260ef722b4d)

