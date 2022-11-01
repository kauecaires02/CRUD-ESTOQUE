# CRUD-ESTOQUE
#Incluir, Excluir, Alterar e Listar itens de estoque(Price)
#created, read, update, delete
#Database simulator

class Estoque:
    Itens = {}
    def incluir(self,codigo,desc,preco):
    if codigo not in self.itens:
    self.itens[codigo]={"descricao":desc,"preco":preco}
    
else:
   print("Codigo cadastrado") 
   
def alterar(self,codigo,preco):
if codigo in self.itens:
  self.itens[codigo]["preco"]=preco
     
else:
    print("codigo nao ta na base")
    
def excluir(self,codigo):
if codigo in self.itens:
   self.itens.pop.(codigo)
else:
   print ("cod inexistente")
   
def listar(self):
   print("**************************************")
   for codigo in self.itens:
   print(codigo,self,itens[codigo]["descricao"],self.itens[codigo]["preco"])
print("*****************************************")

e = estoque()

e.incluir("x01","computador",750)
e.incluir("x02","monitor",200)
e.incluir("x03",teclado"50)
e.excluir("x03")
e.listar()
e.incluir("x04"",mouse",400)
e.incluir("x05",,headset, 1k)

#finish, debugar para uso.

