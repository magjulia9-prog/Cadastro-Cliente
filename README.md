Sistema de Cadastro em Java (Swing)

Aplicação desktop desenvolvida em Java utilizando Swing para criação de uma tela de cadastro com interface gráfica.

🚀 Funcionalidades

Campo para:

Nome

Idade (selecionada através de um slider)

Cidade

Bairro

Estado

Seleção de gênero:

Masculino

Feminino

Outros

Exibição dos dados cadastrados em uma caixa de diálogo

Interface gráfica com Nimbus Look and Feel

🖥️ Interface

A aplicação possui:

Formulário simples e intuitivo

Slider para seleção da idade (0 a 100)

Botão SALVAR para exibir os dados

Botão X para fechar a tela

Atualização dinâmica da idade conforme o slider é movimentado

🛠️ Tecnologias utilizadas

Java

Java Swing

JOptionPane

NetBeans GUI Builder

📂 Estrutura do Projeto
cadastro/
 └── Tela.java

▶️ Como executar
✅ Pré-requisitos

Java JDK 8 ou superior

NetBeans (recomendado)

✅ Passos

Clone o repositório:

git clone https://github.com/seu-usuario/seu-repositorio.git


Abra o projeto no NetBeans

Execute a classe:

Tela.java

💡 Lógica do funcionamento

O valor da idade é controlado pelo JSlider

O gênero é identificado pelo JRadioButton selecionado

Ao clicar em SALVAR, os dados são capturados e exibidos com:

JOptionPane.showMessageDialog()

📸 Exemplo de saída
nome: João
idade: 25
cidade: São Paulo
bairro: Centro
estado: SP
genero: Masculino

📌 Melhorias futuras

 Validação de campos obrigatórios

 Agrupar os RadioButtons com ButtonGroup

 Botão funcional para fechar a aplicação

 Limpar campos após salvar

 Persistência dos dados (arquivo ou banco de dados)

👩‍💻 Autora

Desenvolvido por Magda Lima
