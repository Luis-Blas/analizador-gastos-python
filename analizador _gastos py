gastos =[1200,200,500,800,200]
presupuesto_diario = 550 
total = sum(gastos)
promedio = total / len(gastos)
print("--REPORTE DE GASTOS--")
print("total gastado: $", total)
print("promedio diario: $", round(promedio,2))
print("gasto mas alto: $", max(gastos))
print("gasto mas bajo: $", min(gastos))
print("----------------")
if promedio > presupuesto_diario:
    print("ALERTA: Te pasaste por $ ", round(promedio-presupuesto_diario, 2))
else:
    print("BIEN: Ahorraste $", round(presupuesto_diario- promedio, 2))
