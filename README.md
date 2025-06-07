public class Pessoa {
    private String nome;
    private int idade;
    private String cpf;
    private String email;
    private double altura;
    private double peso;
    
    public void andar() {
        System.out.println("Pessoa está andando");
    }
    
    public void comer() {
        System.out.println("Pessoa está comendo");
    }
    
    public void dormir() {
        System.out.println("Pessoa está dormindo");
    }
    
    public void falar() {
        System.out.println("Pessoa está falando");
    }
    
    public void trabalhar() {
        System.out.println("Pessoa está trabalhando");
    }
    
    public void estudar() {
        System.out.println("Pessoa está estudando");
    }
    
    public String getNome() { return nome; }
    public void setNome(String nome) { this.nome = nome; }
    
    public int getIdade() { return idade; }
    public void setIdade(int idade) { this.idade = idade; }
    
    public String getCpf() { return cpf; }
    public void setCpf(String cpf) { this.cpf = cpf; }
    
    public String getEmail() { return email; }
    public void setEmail(String email) { this.email = email; }
    
    public double getAltura() { return altura; }
    public void setAltura(double altura) { this.altura = altura; }
    
    public double getPeso() { return peso; }
    public void setPeso(double peso) { this.peso = peso; }
}

public class Animal {
    private String especie;
    private int idade;
    private double peso;
    private String cor;
    private String habitat;
    private String tamanho;
    
    public void mover() {
        System.out.println("Animal está se movendo");
    }
    
    public void comer() {
        System.out.println("Animal está comendo");
    }
    
    public void dormir() {
        System.out.println("Animal está dormindo");
    }
    
    public void reproduzir() {
        System.out.println("Animal está se reproduzindo");
    }
    
    public void comunicar() {
        System.out.println("Animal está se comunicando");
    }
    
    public void cacar() {
        System.out.println("Animal está caçando");
    }
    
    public String getEspecie() { return especie; }
    public void setEspecie(String especie) { this.especie = especie; }
    
    public int getIdade() { return idade; }
    public void setIdade(int idade) { this.idade = idade; }
    
    public double getPeso() { return peso; }
    public void setPeso(double peso) { this.peso = peso; }
    
    public String getCor() { return cor; }
    public void setCor(String cor) { this.cor = cor; }
    
    public String getHabitat() { return habitat; }
    public void setHabitat(String habitat) { this.habitat = habitat; }
    
    public String getTamanho() { return tamanho; }
    public void setTamanho(String tamanho) { this.tamanho = tamanho; }
}

public class Carro {
    private String marca;
    private String modelo;
    private String cor;
    private int ano;
    private String placa;
    private String combustivel;
    
    public void acelerar() {
        System.out.println("Carro está acelerando");
    }
    
    public void frear() {
        System.out.println("Carro está freando");
    }
    
    public void virar() {
        System.out.println("Carro está virando");
    }
    
    public void ligar() {
        System.out.println("Carro está ligando");
    }
    
    public void desligar() {
        System.out.println("Carro está desligando");
    }
    
    public void abastecer() {
        System.out.println("Carro está abastecendo");
    }
    
    public String getMarca() { return marca; }
    public void setMarca(String marca) { this.marca = marca; }
    
    public String getModelo() { return modelo; }
    public void setModelo(String modelo) { this.modelo = modelo; }
    
    public String getCor() { return cor; }
    public void setCor(String cor) { this.cor = cor; }
    
    public int getAno() { return ano; }
    public void setAno(int ano) { this.ano = ano; }
    
    public String getPlaca() { return placa; }
    public void setPlaca(String placa) { this.placa = placa; }
    
    public String getCombustivel() { return combustivel; }
    public void setCombustivel(String combustivel) { this.combustivel = combustivel; }
}

public class Livro {
    private String titulo;
    private String autor;
    private int numeroPaginas;
    private String isbn;
    private String editora;
    private String genero;
    
    public void abrir() {
        System.out.println("Livro está sendo aberto");
    }
    
    public void fechar() {
        System.out.println("Livro está sendo fechado");
    }
    
    public void folhear() {
        System.out.println("Folheando o livro");
    }
    
    public void ler() {
        System.out.println("Lendo o livro");
    }
    
    public void marcarPagina() {
        System.out.println("Marcando página do livro");
    }
    
    public void emprestar() {
        System.out.println("Emprestando o livro");
    }
    
    public String getTitulo() { return titulo; }
    public void setTitulo(String titulo) { this.titulo = titulo; }
    
    public String getAutor() { return autor; }
    public void setAutor(String autor) { this.autor = autor; }
    
    public int getNumeroPaginas() { return numeroPaginas; }
    public void setNumeroPaginas(int numeroPaginas) { this.numeroPaginas = numeroPaginas; }
    
    public String getIsbn() { return isbn; }
    public void setIsbn(String isbn) { this.isbn = isbn; }
    
    public String getEditora() { return editora; }
    public void setEditora(String editora) { this.editora = editora; }
    
    public String getGenero() { return genero; }
    public void setGenero(String genero) { this.genero = genero; }
}

public class Smartphone {
    private String marca;
    private String modelo;
    private String sistemaOperacional;
    private int bateria;
    private int memoria;
    private String cor;
    
    public void ligar() {
        System.out.println("Smartphone está ligando");
    }
    
    public void desligar() {
        System.out.println("Smartphone está desligando");
    }
    
    public void fazerChamada() {
        System.out.println("Fazendo chamada");
    }
    
    public void enviarMensagem() {
        System.out.println("Enviando mensagem");
    }
    
    public void tirarFoto() {
        System.out.println("Tirando foto");
    }
    
    public void conectarInternet() {
        System.out.println("Conectando à internet");
    }
    
    public String getMarca() { return marca; }
    public void setMarca(String marca) { this.marca = marca; }
    
    public String getModelo() { return modelo; }
    public void setModelo(String modelo) { this.modelo = modelo; }
    
    public String getSistemaOperacional() { return sistemaOperacional; }
    public void setSistemaOperacional(String sistemaOperacional) { this.sistemaOperacional = sistemaOperacional; }
    
    public int getBateria() { return bateria; }
    public void setBateria(int bateria) { this.bateria = bateria; }
    
    public int getMemoria() { return memoria; }
    public void setMemoria(int memoria) { this.memoria = memoria; }
    
    public String getCor() { return cor; }
    public void setCor(String cor) { this.cor = cor; }
}

public class Casa {
    private String endereco;
    private int numeroComodos;
    private double areaTotal;
    private String cor;
    private String tipo;
    private double valor;
    
    public void abrirPorta() {
        System.out.println("Abrindo porta da casa");
    }
    
    public void fecharPorta() {
        System.out.println("Fechando porta da casa");
    }
    
    public void ligarLuz() {
        System.out.println("Ligando luz da casa");
    }
    
    public void desligarLuz() {
        System.out.println("Desligando luz da casa");
    }
    
    public void aquecer() {
        System.out.println("Aquecendo a casa");
    }
    
    public void resfriar() {
        System.out.println("Resfriando a casa");
    }
    
    public String getEndereco() { return endereco; }
    public void setEndereco(String endereco) { this.endereco = endereco; }
    
    public int getNumeroComodos() { return numeroComodos; }
    public void setNumeroComodos(int numeroComodos) { this.numeroComodos = numeroComodos; }
    
    public double getAreaTotal() { return areaTotal; }
    public void setAreaTotal(double areaTotal) { this.areaTotal = areaTotal; }
    
    public String getCor() { return cor; }
    public void setCor(String cor) { this.cor = cor; }
    
    public String getTipo() { return tipo; }
    public void setTipo(String tipo) { this.tipo = tipo; }
    
    public double getValor() { return valor; }
    public void setValor(double valor) { this.valor = valor; }
}

public class ContaBancaria {
    private String numero;
    private double saldo;
    private String titular;
    private String agencia;
    private String tipo;
    private double limite;
    
    public void depositar(double valor) {
        this.saldo += valor;
        System.out.println("Depósito realizado. Novo saldo: " + this.saldo);
    }
    
    public void sacar(double valor) {
        if (valor <= this.saldo) {
            this.saldo -= valor;
            System.out.println("Saque realizado. Novo saldo: " + this.saldo);
        } else {
            System.out.println("Saldo insuficiente");
        }
    }
    
    public void transferir(double valor) {
        System.out.println("Transferindo valor: " + valor);
    }
    
    public void consultarSaldo() {
        System.out.println("Saldo atual: " + this.saldo);
    }
    
    public void pagarConta(double valor) {
        System.out.println("Pagando conta no valor de: " + valor);
    }
    
    public void investir(double valor) {
        System.out.println("Investindo valor: " + valor);
    }
    
    public String getNumero() { return numero; }
    public void setNumero(String numero) { this.numero = numero; }
    
    public double getSaldo() { return saldo; }
    public void setSaldo(double saldo) { this.saldo = saldo; }
    
    public String getTitular() { return titular; }
    public void setTitular(String titular) { this.titular = titular; }
    
    public String getAgencia() { return agencia; }
    public void setAgencia(String agencia) { this.agencia = agencia; }
    
    public String getTipo() { return tipo; }
    public void setTipo(String tipo) { this.tipo = tipo; }
    
    public double getLimite() { return limite; }
    public void setLimite(double limite) { this.limite = limite; }
}

public class Produto {
    private String nome;
    private double preco;
    private String codigo;
    private String categoria;
    private int estoque;
    private String fornecedor;
    
    public void vender(int quantidade) {
        if (quantidade <= this.estoque) {
            this.estoque -= quantidade;
            System.out.println("Produto vendido. Estoque restante: " + this.estoque);
        } else {
            System.out.println("Estoque insuficiente");
        }
    }
    
    public void comprar(int quantidade) {
        System.out.println("Comprando " + quantidade + " unidades do produto");
    }
    
    public void aplicarDesconto(double percentual) {
        this.preco = this.preco * (1 - percentual/100);
        System.out.println("Desconto aplicado. Novo preço: " + this.preco);
    }
    
    public double calcularImposto() {
        double imposto = this.preco * 0.18;
        System.out.println("Imposto calculado: " + imposto);
        return imposto;
    }
    
    public void reporEstoque(int quantidade) {
        this.estoque += quantidade;
        System.out.println("Estoque reposto. Novo estoque: " + this.estoque);
    }
    
    public void avaliar(int nota) {
        System.out.println("Produto avaliado com nota: " + nota);
    }
    
    public String getNome() { return nome; }
    public void setNome(String nome) { this.nome = nome; }
    
    public double getPreco() { return preco; }
    public void setPreco(double preco) { this.preco = preco; }
    
    public String getCodigo() { return codigo; }
    public void setCodigo(String codigo) { this.codigo = codigo; }
    
    public String getCategoria() { return categoria; }
    public void setCategoria(String categoria) { this.categoria = categoria; }
    
    public int getEstoque() { return estoque; }
    public void setEstoque(int estoque) { this.estoque = estoque; }
    
    public String getFornecedor() { return fornecedor; }
    public void setFornecedor(String fornecedor) { this.fornecedor = fornecedor; }
}

public class Funcionario {
    private String nome;
    private String cargo;
    private double salario;
    private String matricula;
    private String departamento;
    private String dataAdmissao;
    
    public void trabalhar() {
        System.out.println("Funcionário está trabalhando");
    }
    
    public void receberSalario() {
        System.out.println("Recebendo salário: " + this.salario);
    }
    
    public void baterPonto() {
        System.out.println("Batendo ponto");
    }
    
    public void tirarFerias() {
        System.out.println("Tirando férias");
    }
    
    public void participarReuniao() {
        System.out.println("Participando de reunião");
    }
    
    public void fazerRelatorio() {
        System.out.println("Fazendo relatório");
    }
    
    public String getNome() { return nome; }
    public void setNome(String nome) { this.nome = nome; }
    
    public String getCargo() { return cargo; }
    public void setCargo(String cargo) { this.cargo = cargo; }
    
    public double getSalario() { return salario; }
    public void setSalario(double salario) { this.salario = salario; }
    
    public String getMatricula() { return matricula; }
    public void setMatricula(String matricula) { this.matricula = matricula; }
    
    public String getDepartamento() { return departamento; }
    public void setDepartamento(String departamento) { this.departamento = departamento; }
    
    public String getDataAdmissao() { return dataAdmissao; }
    public void setDataAdmissao(String dataAdmissao) { this.dataAdmissao = dataAdmissao; }
}
