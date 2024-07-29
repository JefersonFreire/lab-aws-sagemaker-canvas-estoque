# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

Bem-vindo ao desafio de projeto "Previsão de Estoque Inteligente na AWS com SageMaker Canvas. Neste Lab DIO, você aprenderá a usar o SageMaker Canvas para criar previsões de estoque baseadas em Machine Learning (ML). Siga os passos abaixo para completar o desafio!

## 📋 Pré-requisitos

Antes de começar, certifique-se de ter uma conta na AWS. Se precisar de ajuda para criar sua conta, confira nosso repositório [AWS Cloud Quickstart](https://github.com/digitalinnovationone/aws-cloud-quickstart).


## 🎯 Objetivos Deste Desafio de Projeto (Lab)

![image](https://github.com/digitalinnovationone/lab-aws-sagemaker-canvas-estoque/assets/730492/72f5c21f-5562-491e-aa42-2885a3184650)

- Dê um fork neste projeto e reescreva este `README.md`. Sinta-se à vontade para detalhar todo o processo de criação do seu Modelo de ML para uma "Previsão de Estoque Inteligente".
- Para isso, siga o [passo a passo] descrito a seguir e evolua as suas habilidades em ML no-code com o Amazon SageMaker Canvas.
- Ao concluir, envie a URL do seu repositório com a solução na plataforma da DIO.


## 🚀 Passo a Passo

### 1. Selecionar Dataset

  <p>O dataset selecionado foi disponibilizado pela DIO para a execução do projeto.</p>
  <div align="center">
  <img src="https://github.com/user-attachments/assets/020b3be6-5b11-4312-beeb-35b12b84d353"/>    
  <img src="https://github.com/user-attachments/assets/0fd25ae8-7895-4bf1-a46c-037c3d416ef7"/>    
  </div>

### 2. Construir/Treinar

   <p>O modelo construído realizará a previsão da coluna QUANTIDADE_ESTOQUE.</p>
    <div align="center">
      <img src="https://github.com/user-attachments/assets/2ab1cffa-ad05-4e4b-a495-0fa1b3122249"/>
    </div>

   <p>Configuração do modelo:</p>
   <p>Será utilizado a coluna ID_PRODUTO como identificador único.</p>
   <p>Será feita uma previsão de 9 dias, sendo considerado o calendário de feriados no Brasil, com o objetivo de ver se existe uma relação entre os feriados e a quantidade de vendas.</p>  
    <div align="center">
      <img src="https://github.com/user-attachments/assets/25e0b152-942d-4848-9143-2f567f62aeb1"/>
    </div>

### 3. Analisar
 
  <div align="center">
    <img src="https://github.com/user-attachments/assets/98062e09-41a1-45a2-9320-91c6216493c5"/>
  </div>

  <p>O preço tem influência de 43,08% na variação do estoque.</p>
  <p>Enquanto feriados influenciam 1,96%.</p>

### 4. Prever

  <p>Item 6</p>
  <div align="center">
    <img src="https://github.com/user-attachments/assets/f8286a5f-1c67-4737-ab4f-265bae320084"/>
    <img src="https://github.com/user-attachments/assets/f752b340-cd8a-43a2-8bda-114077ee752b"/>
  </div>

  <p>Item 16</p>
  <div align="center">
    <img src="https://github.com/user-attachments/assets/77e81d0d-c83d-4523-a18d-265dc330b16d"/>
    <img src="https://github.com/user-attachments/assets/ae16ba6e-3f95-490d-81b5-597519b0d398"/>
  </div>


## 🤔 Dúvidas?

Esperamos que esta experiência tenha sido enriquecedora e que você tenha aprendido mais sobre Machine Learning aplicado a problemas reais. Se tiver alguma dúvida, não hesite em abrir uma issue neste repositório ou entrar em contato com a equipe da DIO.
