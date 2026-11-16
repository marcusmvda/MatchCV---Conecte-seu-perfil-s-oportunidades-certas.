# MatchCV: Conecte seu perfil às oportunidades certas.

O MatchCV é uma aplicação que utiliza inteligência artificial para conectar candidatos a vagas de emprego compatíveis com seus perfis profissionais e desenvolver currículos personalizados e otimizados para sistemas ATS.

## 1. Qual problema a aplicação resolve?

Muitos candidatos utilizam o mesmo currículo para diferentes oportunidades, sem considerar os requisitos específicos de cada vaga.

O MatchCV busca facilitar esse processo, identificando oportunidades compatíveis com o perfil do usuário e adaptando seu currículo para destacar experiências e competências relevantes para cada processo seletivo.

## 2. Mega Prompt utilizado e alterações até a versão final

A aplicação foi desenvolvida a partir de um Mega Prompt elaborado para o Lovable, especificando funcionalidades, tecnologias, identidade visual e estrutura do produto.

O prompt contemplou:
- shadcn/ui como design system.
- Identidade visual em azul-claro, branco e amarelo-claro.
- Matchmaking de vagas com inteligência artificial.
- Geração de currículos personalizados.
- Análise de compatibilidade ATS.
- Exportação em PDF e DOCX.

Na versão final, foram estabelecidas algumas simplificações:
- Remoção do login e cadastro, permitindo acesso direto.
- Utilização de armazenamento local (`localStorage`).
- Cadastro manual de vagas, sem integrações externas.
- Execução das análises de IA somente mediante solicitação do usuário.
- Priorização das funcionalidades essenciais para reduzir o consumo de créditos no Lovable.

## 3. Como funciona a análise: da vaga colada ao currículo ajustado?

O processo funciona em quatro etapas:

1. **Perfil profissional:** o usuário informa suas experiências, formação acadêmica e competências, além de cadastrar seu currículo base.
2. **Análise da vaga:** a descrição é inserida na plataforma e a IA identifica requisitos, responsabilidades e palavras-chave.
3. **Matchmaking:** o sistema compara os requisitos da oportunidade com o perfil do candidato, apresentando um percentual de compatibilidade, pontos fortes e lacunas.
4. **Personalização:** a IA adapta as seções do currículo à vaga, realiza uma análise ATS e permite editar e exportar o documento.

O currículo original é preservado, e a IA não deve inventar experiências ou qualificações.

## 4. Ajustes solicitados após a primeira geração e justificativas

Os ajustes definidos para a evolução do projeto incluem:

- **Acesso direto:** eliminar login e cadastro para simplificar a experiência.
- **Interface:** manter uma identidade visual consistente com o design system shadcn/ui.
- **Armazenamento:** utilizar armazenamento local para simplificar a infraestrutura.
- **Economia de créditos:** reduzir operações desnecessárias e chamadas automáticas de IA.
- **Funcionalidades:** priorizar o matchmaking e a geração de currículos ATS.

Essas decisões buscam tornar o MVP mais simples, funcional e econômico.

## 5. Endereço da aplicação publicada

**Link:** [https://matchcraft-career-studio.lovable.app]

---





