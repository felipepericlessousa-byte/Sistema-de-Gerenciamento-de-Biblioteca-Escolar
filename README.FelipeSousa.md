# **Sistema-de-Gerenciamento-de-Biblioteca-Escolar** ![Logo do Sistema](https://static.vecteezy.com/ti/vetor-gratis/p1/19953419-icone-de-de-biblioteca-digital-gratis-vetor.png)
Código de Ilustração

# models.py

from django.db import models

class Categoria(models.Model):
    nome = models.CharField(max_length=100)

    def __str__(self):
        return self.nome

class Livro(models.Model):
    titulo = models.CharField(max_length=200)
    autor = models.CharField(max_length=100)
    categoria = models.ForeignKey(Categoria, on_delete=models.CASCADE)

    def __str__(self):
        return self.titulo


> Esse projeto tem como objetivo
> a administração e organização
> da Escola SESI Djalma Pessoa

O sistema consiste de separações de seções de "Romance", "Clássicos", "Fantasia".


**Repositórios Relacionados**

[Atividade passada](https://github.com/NirtonAfonso/Atividade-Markdown/tree/main)

*
## **Índice**

1. [Funcionalidades](https://github.com/cristianomsanto/Sistema-de-Gerenciamento-de-Biblioteca-Escolar/edit/main/README.md#%C3%ADndice)
2. [Tecnologias](https://github.com/cristianomsanto/Sistema-de-Gerenciamento-de-Biblioteca-Escolar/edit/main/README.md#%C3%ADndice)
3. [Como usar](https://github.com/cristianomsanto/Sistema-de-Gerenciamento-de-Biblioteca-Escolar/edit/main/README.md#%C3%ADndice)

### **Funcionalidades**

* Busca de livros
* Gerenciamento de Devoluções
* Procura de seções individuais
* Organização Profissional

### **Tecnologias**
| *Linguagem de Programação* | *Banco de Dados* | *Framework* | *Sistema Operacional* |
|--------------------------|----------------|-----------|----------------------|
| JavaScript               | SQL            | Django    | Windows              |

### **Como usar**
1. Obtenha o link de acesso ao download do sistema
2. Clique no link de acesso e abra o site
3. Dentro do site, clique no botão de "Download"
4. Abra o Explorador de Arquivos e abra o arquivo do sistema da biblioteca após instalar. 

**Próximas Atualizações ao Código**
- [ ] Adicionar Ficção Científica
- [ ] Adicionar Suspense
- [ ] Adicionar Autoajuda
- [ ] Adicionar Infantil

#### Contribuidores
@Sávio Luiz @Felipe Pericles @Cristiano Miguel

*

#### Contatos
savioluizcs@gmail.com
felipe.pericles.sousa@gmail.com

