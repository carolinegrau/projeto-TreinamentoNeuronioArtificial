# 🧠 Projeto de Treinamento de Neurônio (Perceptron)

Este repositório contém o trabalho desenvolvido na disciplina de Inteligência Artificial, com foco no **treinamento de um neurônio simples (perceptron)** para reconhecer o RU **5282467**.  
O projeto aplica conceitos de aprendizado supervisionado, regra delta e validação de modelo.

---

## 🎯 Objetivo
Treinar um perceptron para classificar entradas relacionadas ao RU:
- Saída **1** → quando o RU for maior ou igual ao valor de referência.  
- Saída **-1** → quando o RU for menor.  

---

## 🛠️ Metodologia
- **Modelo**: Neurônio simples com pesos e bias inicializados.  
- **Treinamento**: Aplicação da **regra delta** com taxa de aprendizagem de 0,1.  
- **Ajustes**: Pesos e bias atualizados linha a linha com base no erro.  
- **Processo**: Treinamento por épocas, simulando aprendizado sequencial.  
- **Validação**: Testes realizados com RUs não vistos anteriormente para avaliar generalização.  

---

## 📊 Resultados
- Taxa de acerto na validação: **85,7%**.  
- Pesos e bias finais extraídos da última época de treinamento.  
- Modelo demonstrou **capacidade de generalização**, embora tenha apresentado dificuldade em reconhecer o RU original em algumas fases intermediárias.  

---

## 📌 Conclusão
O perceptron treinado foi capaz de aprender a tarefa proposta com boa eficiência.  
Para aprimoramento, recomenda-se:
- Treinar com mais épocas.  
- Reforçar o RU original no conjunto de treino.  
- Testar com RUs extremos para garantir robustez.  

---

## 🤝 Contribuição
Sugestões de melhorias são bem-vindas!  
Abra uma issue ou envie um pull request para colaborar.

---
