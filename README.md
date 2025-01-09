# Relatório de Implementação de Serviços AWS  

**Data:** 01/09/2025
**Empresa:** Abstergo Industries  
**Responsável:** Matheos Chiyuki Kusakabe  

---

## Introdução  
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Matheos Chiyuki Kusakabe. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.  

---

## Descrição do Projeto  
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:  

---

### Etapa 1: Amazon S3 (Simple Storage Service)  
- **Foco da ferramenta**: Armazenamento escalável e econômico.  
- **Descrição de caso de uso**:  
  O Amazon S3 foi implementado para armazenar arquivos estáticos, backups de dados e logs. A migração de dados de servidores locais para o S3 permitiu a eliminação de hardware físico e uma redução significativa nos custos operacionais, graças à sua estrutura de preços baseada no uso real e na possibilidade de utilização de classes de armazenamento como "S3 Intelligent-Tiering" para otimização automática dos custos.  

---

### Etapa 2: Amazon EC2 (Elastic Compute Cloud) com instâncias Spot  
- **Foco da ferramenta**: Computação escalável com custo reduzido.  
- **Descrição de caso de uso**:  
  Instâncias Spot do Amazon EC2 foram utilizadas para hospedar cargas de trabalho não críticas, como análise de dados em lote e tarefas de processamento. Essas instâncias aproveitam a capacidade ociosa da AWS, fornecendo economia de até 90% em relação às instâncias sob demanda, sem comprometer a eficiência do processamento.  

---

### Etapa 3: AWS Lambda  
- **Foco da ferramenta**: Execução de código sem provisionamento de servidores.  
- **Descrição de caso de uso**:  
  A AWS Lambda foi implementada para automatizar tarefas e processos internos, como o processamento de eventos e gatilhos em tempo real. Essa abordagem eliminou a necessidade de servidores dedicados, reduzindo custos de manutenção e garantindo uma cobrança apenas pelo tempo de execução real.  

---

## Conclusão  
A implementação das ferramentas Amazon S3, Amazon EC2 com instâncias Spot, e AWS Lambda na empresa Abstergo Industries resultou em uma redução imediata dos custos operacionais. Esses serviços proporcionaram uma infraestrutura mais flexível, escalável e econômica, aumentando a eficiência e produtividade da empresa.  

Recomenda-se a continuidade da utilização das ferramentas implementadas e a avaliação periódica de novos serviços AWS que possam oferecer benefícios adicionais para a organização.  

---

## Anexos  
- Guia de configuração do Amazon S3.  
- Documentação sobre instâncias Spot no Amazon EC2.  
- Manual de uso e exemplos práticos de AWS Lambda.  

---

**Assinatura do Responsável pelo Projeto:**  
Matheos Chiyuki Kusakabe
