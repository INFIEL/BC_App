# BC_App
Aplicativo para Banco Central.
Objetivo do App: Ensinar um uso inteligente do dinheiro e recursos disponíveis por parte do usuário

Recursos disponíveis:

    - Uso da banco de dados Firebase;
    - Uso do Android 6 como ambiente de desenvolvimento;
    - Base de dados:
    
        + Taxa SELIC:https://dadosabertos.bcb.gov.br/dataset/11-taxa-de-juros---selic 
        + Taxa IPCA: https://dadosabertos.bcb.gov.br/dataset/4447-indice-nacional -de-precos-ao-consumidor-amplo-ipca---comercializaveis         + Indice IBOVESPA:
         http://www.bmfbovespa.com.br/pt_br/servicos/market-data/cotacoes/ Yahoo Finance: https://ﬁnance.yahoo.com/ Google Finance: https://www.google.com/ﬁnance 
        + Investing: https://br.investing.com/ 
        + Infomoney: https://www.infomoney.com.br/ 


Principais Funções do Programa:

    - Banco de Dados: será utilizado pelo programa para pegar seus dados para sua exibição em diferentes telas e sua armazenação no firebase;
    - Cadastro do usuário:
        + Nome de Usurário;
        + Nome Completo;
        + Telefone;
        + Data de Nascimento(Restrição a menores de 16 anos??) ;
        + Localidade;
        + Sexo;
        + Senha;
        + Assinatura Eletrônica (necessário para realizar transações e confirmações de quaisquer alterações na conta do usuário);

    - Dados Bancários:
        + Necessário já possuir um cadastro previamente aprovado!!!
        + CPF (Necessário??);
        + Contas Bancárias(numero, agência e tipo talvez?) => OPICIONAL;
        + Renda Mensal Bruta;


    - Uso de Histórias Interativas com o objetivo de intruir o usuário a melhor aplicar seu dinheiro, apresentando-o as consequências, sejam positivas(ganho) ou negativas(perca desnecessária) do seu dinheiro (Questionários ou um "Mini-Game" de testes com um valor fictício a ser gasto ou ganho pelo usuário => RPG ANTIGO??);
    
    - Simulador de uso dos recursos financeiros para pagar dívidas:
        + Entrada: Valor real da Dívida ou/e Valor da Dívida??(Outras entradas de dados também serão necesárias??);
        + Escolha feita pelo processo de Gamificação;
        + Armazanação do Nome do usuário, valores inseridos e escolha feita para futuras análises;





Programa:
    - Tela Inicial:
        + Cadastro;
        + Login;
        + Informações sobre o APP;

    - Cadastro:
        + Escrito anteriormente;
        + Confirmação do E-mail;
        + Redirecionamento automático para o Login;

    - Login:
        + Entrada: Usuário e Senha;
        + Acesso para a área MENU;

    - Menu:
        + Simuladores (=> GAME);
        + Informativo;
        + Avatar;

    - Avatar:
        + Editar Perfil;
        + Badges;
        + Conquistas;
        + Verinhas(nome fictício para o dinheiro virtual => USO
        ESPECÍFICO PARA OS SIMULADORES);
            * Adcionar Verdinhas;
            * Emprestar Verdinhas;
            * Pedir emprestado Verdinhas;

    - Simuladores:
        + Investimentos;
        + Pagamento de Dívidas;
        + Vida Financeira;


    - Vida Financeira:
        + Jogo => Tomada de Decisão com base em situações financeiras reais;
        + Escolhas: Comprar(parcelar, á vista, etc.), Vender, Não-Comprar/Vender (=> IPCA PODE SER APRESENTADO DESSA FORMA, MOSTRANDO A IMPORTÂNCIA DO MESMO NO MERCADO FINCANCEIRO);
        + Carteira: Mostra todas as Verdinhas Disponíveis(pode ser todas do seu Avatar ou uma pequena parte), bem como os métodos de pagamentos disponíveis(cartão de crédito poderia ser uma conquista após um número X de Verdinhas adiquiridas pelo Avatar, por exemplo);
        + Posses adquiridas: uma espécie de Inventário, mostrando seu valor em Verdinhas, que pode oscilando também em função dos ìndices;

    - Investimentos: Nessa parte, será focada a questão dos investimentos, sendo apresentado ao usuário as diferentes formas de se investir, seja na Bolsa, Fundos de Investimentos, Renda Fixa, Poupança, etc.(Seus lucros serão passados para sua Carteira de Verdinhas no Avatar, seguindo os preceitos de cada investimento);
        + Tempo acelerado: para o investimento não ser demorado, será necessário "adiar" o tempo dos investimentos (Ex.: a cada jogada(situação apresentada mediante escolha de decisão do usuário) será avançado em um dia(ou 3 horas??) na Vida Financeira. Dessa forma, ele poderá entender a duração do seu investimento);
        + Investimentos Adquiridos: semelhante à função Posses Adquiridas, porém para Investimentos, sendo mostrado em cada um o Nome do Investimento, o tipo, a data de compra, a rentabilidade, a data de validade do vencimento, e possíveis taxas de custo, mostrando por fim o valor investido, o retorno bruto e liquido, e qualquer informação necessária para permitir que o próprio usuário faça, de maneira simples, o cálculo da sua rentabilidade);
        + Mini Calculadora de Rentabilidade??


    - Informativo/Teoria a ser aplicada no Jogo (=> ACREDITO QUE PARA ESSA PARTE SERÁ FUNDAMENTAL O CONHECIMENTO DA LEILA!!!):
        + Formas de Pagamento: funcionamento dos cartões de crédito, cheques(especiais ou convencionais), parcelamento,etc. 
        + Tipos de Dívidas e possíveis formas de solucioná-las;
        + Tipos de Investimentos e suas vantagens e desvantagens;
        + Cálculo de Rentabilidade para Investimentos;




