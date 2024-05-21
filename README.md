# Curso de Inteligência Artificial e Google Gemini

ℹ️ **Sobre o Curso:**

O curso trouxe atividades e curiosidades para saber mais sobre **Inteligência Artificial e Google Gemini**. A Inteligência Artificial (IA) não é um tema novo na área de tecnologia, mas o desenvolvimento de diferentes **IAs Generativas** tem gerado grandes impactos neste mercado. Eu e a Sabrina Berno (@sabrinaberno) entramos nesse desafio para um aprendizado muito interessante sobre Inteligência Artificial (IA).

---

📝 **Conteúdo:**

1. **Introdução à Inteligência Artificial**
   - O que é IA?
   - História da IA
   - Aplicações da IA
   
2. **Google Gemini: Uma Visão Geral**
   - O que é Google Gemini?
   - Como o Google Gemini utiliza IA?
   - Impacto do Google Gemini no mercado
   
3. **IAs Generativas**
   - Definição e conceito
   - Exemplos de IAs Generativas
   - Potenciais aplicações e desafios
   
4. **Hands-on: Explorando o Google Gemini**
   - Tutorial passo a passo
   - Experimentação prática
   - Dicas e truques
   
5. **Aplicações Práticas**
   - Estudos de caso
   - Projetos reais utilizando Google Gemini
   - Oportunidades de carreira e mercado
   
---

🔧 **Estudos:**

- Programação em Python
- Google Gemini
- Inteligência Artificial
- Prompt 
- Machine Learning
   
---

📧 **Contato:**

Para dúvidas ou mais informações, entre em contato conosco em [meu e-mail](eduardaabritta@gmail.com).

---

🚀 **Desafio**
O objetivo deste desafio foi aplicar os conhecimentos adquiridos durante o curso de Inteligência Artificial e Google Gemini em um projeto real. Você será responsável por desenvolver uma aplicação que utilize as funcionalidades do Google Gemini para resolver um problema específico ou melhorar um processo existente.

- Utilize a API do Google Gemini ou outras ferramentas conforme necessário.
- Implemente as funcionalidades de acordo com o plano elaborado.
- Documente o processo de desenvolvimento, incluindo decisões tomadas e desafios enfrentados.
- Realize testes para garantir o funcionamento correto.
- Prepare um guia de uso para facilitar a compreensão da aplicação.

---

🌱 **Projeto** 🌱

Este código é como um assistente para ajudar a cuidar de plantas. Ele armazena informações sobre várias plantas, como quanto de água elas precisam e quanto de sol devem receber. Depois, quando alguém pergunta sobre uma planta específica, o código verifica se tem essas informações. Se tiver, mostra as instruções de cuidado para aquela planta. Se não tiver, o código diz que não conhece aquela planta.

1. **Instalação de Dependências:**

Começamos instalando a biblioteca google-generativeai, que fornece acesso a modelos de IA poderosos, e outras bibliotecas como numpy e pandas, que são ferramentas populares para manipulação de dados numéricos e tabulares em Python.

2. **Configuração da API e Carregamento dos Dados:**

Configuramos a API para autenticação usando uma chave secreta. Em seguida, carregamos os dados sobre diferentes plantas em uma estrutura de dados chamada DataFrame, fornecida pela biblioteca pandas.

3. **Geração de Embeddings:**

Cada planta é representada por duas informações principais: como regar e quanto de sol precisa. Utilizamos essas informações para gerar embeddings, que são representações numéricas compactas das descrições das plantas. Isso é feito usando um modelo pré-treinado chamado embedding-001.

4. **Função de Busca:**

Definimos uma função chamada gerar_e_buscar_consulta que recebe o nome da planta como entrada. Primeiro, verifica se a planta está presente nos dados carregados. Se estiver, usa o modelo de embedding para calcular a similaridade entre a consulta (nome da planta) e os dados de todas as plantas. A planta mais similar é então retornada como resposta.

5. **Interface de Chat:**

Por fim, criamos uma interface de chat simples, onde o usuário pode digitar o nome de uma planta. Se a planta existir nos dados, suas informações de rega e exposição ao sol são exibidas. Caso contrário, uma mensagem é exibida informando que a planta não está na memória.

6. **Tratamento de Exceções:**

Se a consulta não corresponder a nenhuma planta existente nos dados, o código usa um modelo chamado gemini-1.0-pro para gerar uma resposta com base na consulta. Isso garante uma experiência mais amigável para o usuário, mesmo que a planta não esteja na base de dados.
