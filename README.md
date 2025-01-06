import random
def dadi():
  numero_dadi=int(input("Quanti dadi vuoi lanciare?"))
  somma_facce=0 
  for elemento in range(numero_dadi):
    elemento=random.randint(1,6)
    somma_facce=somma_facce+elemento
  print("La somma delle facce è:",somma_facce)
dadi()
