# kevin88
def calcular_total(precio_componente, descuento):
    """Calcula el precio final con descuento aplicado."""
    valor_descuento = precio_componente * descuento / 100
    precio_final = precio_componente - valor_descuento
    return precio_final
# Descuento
Porcentaje_Descuento = 10  
# Pedimos solo el precio al usuario
precio = float(input("Ingresa el precio del componente eléctrico: "))
# Calculamos y mostramos el resultado
resultado = calcular_total(precio, Porcentaje_Descuento)
print(f"Descuento fijo aplicado: {Porcentaje_Descuento}%")
print(f"precio final a pagar: {resultado}")
