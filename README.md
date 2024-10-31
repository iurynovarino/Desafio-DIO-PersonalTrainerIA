# Desafio-DIO-PersonalTrainerIA

<p align="center">
    <img width="300px" src="https://github.com/digitalinnovationone/prompt-challenger-personal-ia/blob/main/.github/assets/logo_2.png">
</p>

<p align="center">
<a href="https://dio.me/"><img src="https://img.shields.io/badge/DIO-Project-FED564?logo=youtube" alt="DIO - Project"></a>
<a href="https://www.gnu.org/software/bash/" title="Go to Bash homepage"><img src="https://img.shields.io/badge/Prompt-Project-FED564?logo=gnu-bash&amp;logoColor=white" alt="Made with Bash"></a>
<a href="https://aws.amazon.com/" title="Powered by AWS">
  <img src="https://img.shields.io/badge/Powered%20by-AWS-FED564?logo=icloud&logoColor=white" alt="Powered by AWS">
</a>
</p>

<p align="center">
  <h3 align="center">🏋️‍♂️ Assistente de Personal Trainer - Gerador de Treino Ideal</h3>
Este projeto é um desafio de Prompt Engineer, onde o objetivo é criar um prompt que ajuda a montar o treino ideal para cada combinação de fatores, como biotipo corporal, disponibilidade de tempo e tipo de exercícios preferidos. O assistente de personal trainer gerado por esse prompt será capaz de personalizar os treinos de acordo com as características e necessidades do usuário.
O projeto deve ser feito utilizando as boas práticas de prompt engineer.
</p>

## 📋 Índice

- [📋 Índice](#-índice)
- [📝 Introdução](#-introdução)
- [💪 Biotipos Corporais](#-biotipos-corporais)
- [📅 Dias Disponíveis para Treino](#-dias-disponíveis-para-treino)
- [🏋️ Tipos de Exercícios](#️-tipos-de-exercícios)
- [🛠️ Regras de negócio](#️-regras-de-negócio)
- [📖 Material de Apoio](#-material-de-apoio)
- [🎯 Prompt de Resposta Proposto](#-prompt-de-resposta-proposto)

---

## 📝 Introdução

Este projeto visa criar um assistente de personal trainer automatizado que ajuda a gerar treinos personalizados. O usuário fornecerá informações como o biotipo corporal, a quantidade de dias disponíveis para treinar na semana e o tipo de exercício preferido, e o assistente gerará um plano de treino ideal com base nessas informações.

---

## 💪 Biotipos Corporais

A primeira regra para personalizar o treino é determinar o biotipo corporal do usuário. Existem três biotipos principais:

<table>
  <tr>
    <th>Imagem</th>
    <th>Biotipo</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src="https://github.com/digitalinnovationone/prompt-challenger-personal-ia/blob/main/.github/assets/ectomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Ectomorfo</strong></td>
    <td>Corpo mais magro, difícil ganhar peso e massa muscular.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src="https://github.com/digitalinnovationone/prompt-challenger-personal-ia/blob/main/.github/assets/mesomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Mesomorfo</strong></td>
    <td>Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src="https://github.com/digitalinnovationone/prompt-challenger-personal-ia/blob/main/.github/assets/endmorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Endomorfo</strong></td>
    <td>Corpo com tendência a acumular gordura, maior dificuldade em perder peso.</td>
  </tr>
</table>

> **Nota:** Escolha o biotipo que mais se aproxima do seu corpo atual para que o treino seja mais eficiente.

---

## 📅 Dias Disponíveis para Treino

A segunda regra é determinar quantos dias por semana o usuário tem disponível para treinar. Dependendo do número de dias, o treino sugerido pode variar:

| **Imagem**                                                     | **Dias por Semana** | **Tipo de Treino Sugerido** |
| -------------------------------------------------------------- | ------------------- | --------------------------- |
| <img src="https://github.com/digitalinnovationone/prompt-challenger-personal-ia/blob/main/.github/assets/calendar.png" height="50"> | 1 dia               | Treino Full Body            |
| <img src="https://github.com/digitalinnovationone/prompt-challenger-personal-ia/blob/main/.github/assets/calendar.png" width="50" height="50"> | 3 dias              | Treino ABC                  |
| <img src="https://github.com/digitalinnovationone/prompt-challenger-personal-ia/blob/main/.github/assets/calendar.png" width="50" height="50"> | 5 dias              | Treino ABCDE                |

- **Full Body**: Treino que trabalha o corpo todo em uma única sessão.
- **ABC**: Divisão do treino em três dias, cada um focado em grupos musculares diferentes.
- **ABCDE**: Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.

---

## 🏋️ Tipos de Exercícios

A terceira regra envolve a escolha do tipo de exercício preferido. Aqui estão algumas categorias com exemplos:

| **Imagem**                                                       | **Tipo de Treino** | **Descrição**                                                                                                 |
| ---------------------------------------------------------------- | ------------------ | ------------------------------------------------------------------------------------------------------------- |
| <img src="https://github.com/digitalinnovationone/prompt-challenger-personal-ia/blob/main/.github/assets/dumbells.png" width="50%" height="50%"> | **Funcional**      | Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.                                |
| <img src="https://github.com/digitalinnovationone/prompt-challenger-personal-ia/blob/main/.github/assets/4760665.png" width="50%" height="50%">  | **Maquinário**     | Exercícios feitos em máquinas, com foco em isolar grupos musculares.                                          |
| <img src="https://github.com/digitalinnovationone/prompt-challenger-personal-ia/blob/main/.github/assets/barr.png" width="50%" height="50%">     | **Peso Livre**     | Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente. |
| <img src="https://github.com/digitalinnovationone/prompt-challenger-personal-ia/blob/main/.github/assets/cardio.png" width="50%" height="50%">   | **Cardio**         | Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.                     |
| <img src="https://github.com/digitalinnovationone/prompt-challenger-personal-ia/blob/main/.github/assets/hiit.png" width="50%" height="50%">     | **HIIT**           | Treinos intervalados de alta intensidade, ótimos para queima de gordura.                                      |

---

## 🛠️ Regras de negócio

1. **Identifique seu biotipo corporal** consultando a seção de biotipos.
2. **Determine quantos dias por semana você pode treinar** e escolha o tipo de treino mais adequado.
3. **Selecione o tipo de exercício** que prefere realizar e que se encaixa melhor nos seus objetivos.
4. Use o prompt do assistente para gerar um plano de treino personalizado.

---

## 📖 Material de Apoio

Aqui estão alguns recursos adicionais que podem ser úteis para entender melhor o projeto e as práticas de prompt engineering:

- [Fundamentos de Engenharia de prompt](https://elidianaandrade.gitbook.io/fundamentos-de-engenharia-de-prompts-com-claude-3)
- [Boas práticas de prompt](https://aline-antunes.gitbook.io/otimize-seus-prompts-e-aprenda-mais-usando-ias-1)

---

## 🎯 Prompt de Resposta Proposto
Como um personal trainer criaria um plano de treinamento com base nas seguintes instruções:

biotipo corporal ectomorfo que é corpo mais magro, difícil ganhar peso e massa muscular;
frequência de treinamento será 3 vezes por semana;
escolher exercícios que trabalhem o cardio, pois quero melhorar a resistência cardiovascular tendo como objetivo praticar atividade física regularmente com isso espero melhorar a minha saúde. Gostaria que esse plano seja criado para a pratica de um desses exercícios: corrida, ciclismo ou pular corda; Escolha de acordo com o exercício que tenha o melhor desempenho. 

## 🎯 Saída do Prompt em resposta ao prompt acima

Plano de Treinamento para Ectomorfo Focado em Cardio
Análise do Perfil:

Biotipo: Ectomorfo, com dificuldade em ganhar massa muscular.
Objetivo: Melhorar a resistência cardiovascular e praticar atividade física regularmente.
Frequência: 3 vezes por semana.
Considerações:

Prioridade: O foco principal será o desenvolvimento da resistência cardiovascular, considerando a dificuldade do ectomorfo em ganhar massa muscular.
Intensidade: Os treinos serão progressivamente mais intensos ao longo das semanas, buscando adaptar o corpo aos estímulos.
Variedade: A variação dos exercícios e da intensidade é fundamental para evitar platôs e manter a motivação.
Nutrição: Uma dieta equilibrada e rica em nutrientes é essencial para o bom desempenho e recuperação muscular, mesmo com o foco em cardio.
Escolha do Exercício:

Considerando o objetivo de melhorar a resistência cardiovascular e a praticidade, a corrida se mostra como a melhor opção. Ela permite uma progressão gradual da intensidade e pode ser realizada em diversos locais.

Plano de Treinamento (8 semanas):
<table>
  <tr>
    <th>Semana</th>	
    <th>Dia 1</th>		
    <th>Dia 2</th>		
    <th>Dia 3</th>		
    <th>Observações
  </tr>
  <tr> 
    <td>1-2</td>	
    <td>Corrida leve (30 min)</td>
    <td>Descanso</td>	
    <td>Corrida leve (30 min)</td>	
    <td>Foco na adaptação e técnica.</td>
  </tr> 
  <tr> 
    <td>3-4</td>
    <td>Corrida leve (35 min)</td>	
    <td>Descanso</td>	
    <td>Corrida intervalada (4x4 min rápido/2 min lento)</td>	
    <td>Introdução de intervalos para aumentar a intensidade.</td>
  </tr>
  <tr>  
    <td>5-6</td>
    <td>Corrida leve (40 min)</td>	
    <td>Descanso</td>	
    <td>Corrida longa (50 min)</td>	
    <td>Aumento da duração para melhorar a resistência.</td>
  </tr>
  <tr>    
    <td>7-8</td>
    <td>Corrida intervalada (6x4 min rápido/2 min lento)</td>
    <td>Descanso</td>	
    <td>Corrida longa (60 min)</td>	
    <td>Maior intensidade e duração nos intervalos e na corrida longa.</td>
  </tr>    
</table>

Dicas Adicionais:

Aquecimento: Sempre inicie os treinos com 5-10 minutos de alongamento dinâmico e um leve trote.
Resfriamento: Finalize com 5-10 minutos de alongamento estático.
Hidratação: Beba bastante água antes, durante e após os treinos.
Nutrição: Consulte um nutricionista para um plano alimentar personalizado.
Variação: Após 8 semanas, é recomendado variar os treinos, incluindo outras atividades como natação ou ciclismo, para evitar a monotonia e continuar desafiando o corpo.
Acompanhamento: Consulte um profissional de educação física para um acompanhamento individualizado e ajuste do plano de acordo com seus resultados e progressos.
Importante: Este é um plano geral e pode ser adaptado às suas necessidades e preferências. É fundamental ouvir seu corpo e ajustar a intensidade e duração dos treinos conforme necessário.

Observações:

Ectomorfos e ganho de massa: Mesmo com foco em cardio, é possível estimular o ganho de massa magra através de uma dieta adequada e exercícios de força em baixa intensidade. Consulte um profissional para um programa de treinamento completo.
Evolução: A evolução é gradual e individual. Seja paciente e celebre cada pequena conquista.
Lembre-se: O mais importante é manter a regularidade nos treinos e buscar o prazer na atividade física. Com dedicação e acompanhamento profissional, você alcançará seus objetivos e terá uma vida mais saudável.

Gostaria de personalizar ainda mais este plano? Posso te ajudar a ajustar a intensidade, duração e frequência dos treinos de acordo com suas necessidades e objetivos.

##  Considerações finais

Utilizei a técnica de prompt "solicitação de poucos disparos" para melhorar a resposta do modelo de inteligencia artificial como 




