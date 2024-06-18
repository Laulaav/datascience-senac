# Análise de Dados sobre Trabalho Análogo à Escravidão

## Introdução

O Supremo Tribunal Federal considerou constitucional a criação do Cadastro de Empregadores que tenham cometido o crime de sujeitar seus trabalhadores a condições análogas à escravidão, inserindo-os na "lista suja do trabalho escravo". A Associação Brasileira de Incorporadoras Imobiliárias (Abrainc) contestou a constitucionalidade da Portaria Interministerial 4/2016, porém o ministro Marco Aurélio explicou que o objetivo é promover a transparência ativa. O cadastro não é uma sanção, mas sim uma forma de dar visibilidade a decisões administrativas definitivas sobre casos de trabalho análogo à escravidão. Tudo é julgado com cuidado para confirmar a infração, por isso, o infrator é mantido na lista por dois anos, sob monitoramento contínuo. Nesse tempo, as autoridades podem avaliar se as práticas melhoraram ou se permanecem de forma irregular.

## Justificativa

Escolhemos esse conjunto de dados com o objetivo de analisar essa questão mais de perto, uma vez que é uma prática deplorável que ainda persiste nos dias de hoje. Com esses dados, pretendemos analisar quais regiões são mais propensas a essa prática, identificar o ano de maior ocorrência, avaliar se realmente são cumpridos dois anos de avaliação para cada empregador e identificar os locais mais comuns dessa prática.

## Base de Dados

### Registros:

Existem 652 registros no total.

### Variáveis:

- **ID**
- **Ano da ação fiscal**
- **UF**
- **Empregador**
- **CNPJ/CPF**
- **Estabelecimento**
- **Trabalhadores envolvidos**
- **CNAE**
- **Decisão administrativa de procedência**
- **Inclusão no cadastro de empregadores**
  
## Dicionário de Dados

| Variável                         | Tipo            | Descrição                                                                                   |
|----------------------------------|-----------------|---------------------------------------------------------------------------------------------|
| ID                               | Numérico (Int)  | Identificador                                                                               |
| Ano da ação fiscal               | Numérico (Int)  | Ano que ocorreu a fiscalização                                                              |
| UF                               | Texto (String)  | Unidade de federação onde ocorreu a fiscalização                                            |
| Empregador                       | Texto (String)  | Nome do empregador envolvido na ação fiscal                                                 |
| CNPJ/CPF                         | Texto (String)  | Número do CNPJ (empresa) ou CPF (pessoa física) do empregador                               |
| Estabelecimento                  | Texto (String)  | Localização do estabelecimento fiscalizado                                                  |
| Trabalhadores envolvidos         | Numérico (Int)  | Quantidade dos trabalhadores sujeitos a condições análogas à escravidão                     |
| CNAE                             | Texto (String)  | Classificação nacional de atividades econômicas do estabelecimento                          |
| Decisão administrativa de procedência | Data       | Data em que a reclamação é declarada válida por uma autoridade                              |
| Inclusão no Cadastro de Empregadores | Data        | Data em que o empregador foi incluído no cadastro                                           |

---


