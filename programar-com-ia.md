# 🤖 Programando com Inteligência Artificial

Este guia apresenta pontos importantes e uma metodologia para utilizar a Inteligência Artificial (IA) de forma eficaz no seu processo de programação.

---

## 📌 Pontos Importantes

* **O Ser Humano é Você!**
    * O processo de pensar e de criar é do ser humano que escreve o código.
    * Você é quem possui o domínio de todo o contexto do seu código.
    * Utilize a IA como uma ferramenta para polir o que você está criando.
* **Seja Bastante Crítico**
    * Analise bem todas as soluções dadas pela IA, antes de implementá-las.
* **IA Pode Ser o Pontapé Inicial**
    * Às vezes, podemos ter dificuldade para iniciar um algoritmo.
    * Utilize a IA como um meio para iniciar a codificar o que precisa.
* **Vamos Por Partes!**
    * Trabalhe com trechos menores de código que, se possível, possuam um contexto completo dentro de si mesmo.
    * Isso ajuda a análise da IA a ser melhor e com menos erros.

---

## 🛠️ Metodologia

Tenha senso crítico e analise seu código, escolhendo as partes que acredita precisarem de melhoria. Um bom começo é pensar em **quatro pilares**: **performance**, **erros**, **segurança** e **padrões de estilo da linguagem**.

### 1. Enviar

* Após escolher o trecho de código a ser analisado, envie-o para a IA.
* Lembre-se de enviar todo e qualquer trecho de código que irá ajudar a IA a entender o contexto.
* Ao enviar o código, você pode enviar um texto explicando o funcionamento do mesmo e qual é o resultado esperado.
* *Dica:* Peça para que a IA apenas responda que recebeu o código e que não tome nenhuma ação.

### 2. Analisar

* Peça para a IA analisar o trecho de código e pontuar os potenciais problemas, de acordo com o foco escolhido (**sem fazer alterações de código**).
* Leia os potenciais problemas listados e verifique se todos fazem sentido.

### 3. Ajustar

* Ajuste o trecho de código necessário a partir da explicação da IA.
* Se a IA tiver respondido uma possível solução, este é o momento para aplicar o código sugerido.
* Caso veja necessidade, modifique esse código.

### 4. Verificar

* Após a correção de um problema, peça para a IA **verificar se o mesmo foi resolvido**.

### 5. Testar

* Após a solução do problema, **teste se a funcionalidade do código permanece a mesma**.
* É preciso garantir que as alterações não criaram nenhum **efeito colateral ou novos erros**.

---

## 📝 Lista de Prompts

A seguir, uma lista de exemplos de prompts para serem usados com qualquer IA para auxiliar na sua programação.

| Número | Categoria | Prompt |
| :---: | :---: | :--- |
| 1 | Debug | "Você pode me ajudar a debugar esta mensagem de erro do meu programa em [linguagem]: [mensagem]" |
| 2 | Debug | Descreva o comportamento inesperado que você está observando no código e forneça quaisquer mensagens de erro ou rastreamentos de pilha para análise posterior. |
| 3 | Debug | "Ajude-me a debugar este script em [linguagem] que processa uma lista de objetos e sugira possíveis correções." |
| 4 | Debug | Destaque quaisquer mecanismos de tratamento de erros no código e explique como eles estão atualmente lidando ou falhando em lidar com o problema encontrado. |
| 5 | Debug | "Debuge o código [linguagem] fornecido. Ele deveria realizar [comportamento esperado], mas está produzindo [comportamento atual]." |
| 6 | Debug | "Debuge o seguinte código [linguagem]: É esperado que ele execute [comportamento esperado], mas, em vez disso, está produzindo [comportamento atual] quando fornecidos os inputs: [exemplos de input]." |
| 7 | Issues | "Você poderia encontrar problemas potenciais neste código [linguagem]:" |
| 8 | Issues | "Você consegue identificar algum bug neste trecho de código [linguagem]:" |
| 9 | Issues | "Revise este script em [linguagem] para verificar se há algum bug." |
| 10 | Issues | "Ajude-me a entender por que esta função [linguagem] não está funcionando como esperado." |
| 11 | Issues | "Quais são os problemas potenciais com esta função recursiva [linguagem]:" |
| 12 | Issues | "Encontre quaisquer problemas potenciais neste código [linguagem] que processa um array de strings:" |
| 13 | Issues | "Você consegue identificar o bug nesta função [linguagem] que lida com conexão de banco de dados:" |
| 14 | Issues | "O que há de errado com este método [linguagem] que deveria analisar um arquivo CSV:" |
| 15 | Issues | "Encontre o erro de lógica nesta função [linguagem] que se destina a reverter o array, dados estes inputs: [parâmetros de entrada], e esperado produzir [saída], mas atualmente fornece [saída incorreta]." |
| 16 | Issues | "Encontre bugs potenciais no script [linguagem] que processa [tipo de input] e gera [tipo de output]:" |
| 17 | Issues | "Identifique o erro de lógica nesta função [linguagem] destinada a verificar a força da senha com estes inputs: [parâmetros de entrada] e output esperado: [saída]" |
| 18 | Performance | "Você consegue encontrar algum problema de desempenho neste código [linguagem]:" |
| 19 | Performance | "Existem vazamentos de memória (memory leaks) neste código [linguagem]:" |
| 20 | Performance | "Revise a seguinte função [linguagem]. Por favor, identifique quaisquer bugs potenciais, problemas de desempenho, e não conformidade." |
| 21 | Performance | "Por favor, revise a função [linguagem] quanto a quaisquer vazamentos de memória ou problemas de desempenho potenciais ao processar um Array de um milhão de registros." |
| 22 | Performance | "Encontre os vazamentos de memória no seguinte código [linguagem] e sugira possíveis otimizações:" |
| 23 | Performance | "Revise o código [linguagem] fornecido em busca de problemas potenciais de escalabilidade:" |
| 24 | Performance | Revise os algoritmos e estruturas de dados usados no código para garantir que estejam otimizados para desempenho. |
| 25 | Review | "Revise esta função [linguagem] em busca de erros:" |
| 26 | Review | "Você pode revisar esta função [linguagem] e sugerir áreas para tratamento de erros (error handling)" |
| 27 | Review | "Revise a seguinte função [linguagem] e forneça sugestões para tratamento de erros e gargalos potenciais (bottlenecks)." |
| 28 | Review | "Você consegue identificar quaisquer problemas potenciais com esta definição de classe [linguagem]:" |
| 29 | Review | "Você pode analisar este código [linguagem] e apontar erros potenciais?" |
| 30 | Review | "Por favor, revise este código [linguagem] quanto a estilo e melhores práticas:" |
| 31 | Review | "Por favor, revise o seguinte [linguagem] para verificar se está seguindo o Guia de Estilo do Google (Google Style Guide):" |
| 32 | Review | "Por favor, revise este código [linguagem] que deve calcular o fatorial dadas as entradas [variáveis de entrada] e retornar [saída]:" |
| 33 | Security | "Existem vulnerabilidades de segurança neste código [linguagem]:" |
| 34 | Security | Identifique vulnerabilidades potenciais no código e proponha estratégias de mitigação. |
| 35 | Security | Analise o código em busca de quaisquer brechas de segurança potenciais e sugira maneiras de abordá-las. |
| 36 | Security | "Estou preocupado com problemas de segurança neste código [linguagem]. Quais são suas considerações?" |
| 37 | Security | Examine o código em busca de possíveis riscos de segurança e forneça recomendações para aprimorar sua postura de segurança. |
| 38 | Security | Inspecione o código em busca de quaisquer vulnerabilidades de segurança e descreva as etapas para remediá-las. |
| 39 | Security | Ajude a identificar quaisquer problemas de segurança potenciais no seguinte código Java relacionados a cross-site scripting (XSS). |
| 40 | Security | Examine o código em busca de quaisquer fraquezas ou brechas de segurança e sugira medidas para fortalecer sua postura de segurança. |
