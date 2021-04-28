# &ensp;Estratégia de Testes

## &ensp;Histórico de Revisão

 Data       | Versão | Modificação           | Autor             
 :--------: | :----: | :-------------------- | :------------
 28/04/2021 | 0.1    | Criação do documento  | Felipe Chermont
---

</br>

## 1. Objetivos
  Os testes realizados visam descrever o processo de qualidade adotado pelo time Pampas Fox para o projeto AvaInsta. Através da verificação e validação das principais funcionalidades do projeto.

## 2. Tipo de Teste
Testes de software podem ser divididos em diversos tipos, de acordo com o objetivo particular do teste que se pretende realizar. Sendo alguns dos principais: teste de configuração, teste de instalação, teste de integridade, teste de segurança, teste funcional, teste de unidade, teste de integração, teste de volume, teste de performance, teste de usabilidade, teste de caixa branca e caixa preta, teste de regressão, entre outros.

utilizaremos o tipo de teste funcional para testar as seguintes funcionalidades:

* Registro de usuários
* Cadastro de avaliações
* Atualização de avaliações


## 3. Níveis de Teste
Uma prática comum ao se realizar testes de software, é o teste da funcionalidade após o desenvolvimento da aplicação. Porém, algumas práticas emergentes do desenvolvimento ágil e programação extrema focam o modelo de desenvolvimento orientado ao teste, sendo eles escritos antes do desenvolvimento da aplicação.
os principais níveis de teste são: teste de unidade, teste de integração, teste de sistema, teste de aceitação, teste de operação, teste de regressão.

Por já estarmos com a aplicação praticamente toda em andamento ou finalizada, não é possível utilizar o modelo de testes escritos primeiro(TDD). Para o projeto, será utilizado o teste de unidade para o teste das funcionalidades citadas no tópico 2. Onde será testado unidades de software ja desenvolvidas e identificar possíveis falhas de funcionamento.

## 3. Técnicas de Teste
As técnicas de teste é o processo que vai assegurar perfeito funcionamento de alguns aspectos de software ou de sua unidade e podem ser divididas em estruturais(caixa branca) e funcionais(caixa preta).

As principais técnicas estruturais são: Stress, Execução, Recuperação Contingência, Operação, Compliance e Segurança.

Já as principais técnicas funcionais são: requisitos, regressão, tratamento de erros, manual, interfaces de integração, controle e paralelismo.

No caso de nossa aplicação, utiliziramos tecnicas de caixa preta, mais especificamente, a técnica de requisitos, para validação dos requisitos funcionais da aplicação.
