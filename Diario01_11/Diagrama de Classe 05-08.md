[Exercicios](https://github.com/heliokamakawa/ifpr/blob/main/aps/aulas/2-tri/03-desafio.md)     
[SUAP](https://suap.ifpr.edu.br/edu/disciplina/18789/?tab=trabalhos)



```
@startuml

class Acervo {
	
}

class Livro {
	-Autor autor
	-String titulo
    -int id
}


class Usuario {
	-String nome
	-String cpf
}



class Reserva {
	-Usuario usuario
}

class Funcionario {
	
}

class Professor {
	
}

class Aluno {

}

class Autor {
	-String nome
    -String sobrenome

}

class PalavraChave {
	
}


Funcionario <|-- Usuario 
```




