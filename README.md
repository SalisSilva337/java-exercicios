GRUPO: ARTHUR DAVIS, JOSÉ BULHÕES E SALIS SILVA;

O projeto simula o gerenciamento de uma loja, permitindo a adição de produtos, bem como a busca por nome e categoria. O código utiliza três classes principais:
Estrutura de Classes:

    Classe App:
        Função principal (main), responsável por iniciar o programa.
        Exemplo de produtos são adicionados à loja e exibidos no console.
    Classe Loja:
        Gerencia uma lista de produtos.
        Métodos:
            adicionarProduto(Produto produto): Adiciona um produto à lista.
            retornarLista(): Retorna a lista de produtos.
            buscarPorNome(String nome): Busca um produto pelo nome.
            buscarPorCategoria(String categoria): Busca produtos por categoria.
    Classe Produto:
        Representa um produto com três atributos:
            nome: Nome do produto.
            preco: Preço do produto.
            categoria: Categoria do produto.
        Método toString(): Retorna uma representação em texto do produto.;

Este projeto é voltado para o gerenciamento de estudantes, permitindo a adição de alunos e o registro de notas por matéria. A estrutura básica foca em duas classes principais, além do arquivo principal App.java.
Estrutura de Classes:

    Classe App:
        Função principal (main), que, atualmente, exibe uma mensagem "Hello, World!".

    Classe School:
        Gerencia uma lista de estudantes.
        Métodos:
            addStudent(Student student): Adiciona um aluno à lista.
            registerNote(String register, String matter, List<Double> notes): Registra notas de uma matéria para um aluno.
            calcularMedia(String matricula, String disciplina): Calcula a média das notas de uma disciplina.
            listarAlunos(): Lista todos os alunos.
            findStudentByRegister(String register): Busca um aluno pelo número de registro.   

