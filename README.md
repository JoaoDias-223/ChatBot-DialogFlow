# ChatBot-DialogFlow

Gabriel Bueno - 22.119.077-0


João Vitor Dias - 22.119.006-9

É possível baixar os arquivos, zipá-los e rodar no DialogFlow

# Laboratório de Inteligência Artificial - Atividade 03
GitHub: https://github.com/JoaoDias-223/ChatBot-DialogFlow

## 1. Intents
#### a. Saudação
São frases ligadas à intenção de inciar o contato com o chatbot. As frases que utilizamos no treinamento foram:
- Qual é menó?
- Tudo sussa, grande?
- Beleza man?
- Eae, parça
- Salve
- Oi
- Olá

E as respostas que escolhemos para o robô foram:
- Salve
- Oi, meu chapa
- Tudo tranquilo, man
- Eae, suave?

#### b. Sobre IC
São frases ligadas à intenção de saber sobre o quê é a IC. As frases que utilizamos no treinamento foram:
- Me fale sobre a IC
- Me fale um pouco sobre o programa de Iniciação Científica
- Me fale um pouco sobre o programa de IC
- O que é o programa de IC?
- O que é o programa de iniciação científica?

E as respostas que escolhemos para o robô foram:
- O programa de IC é um projeto que visa introduzir alunos de graduação à metodologia científica aplicados a projetos de pesquisa científica e tecnológica.

#### c. Adesão IC
São frases ligadas à intenção de saber quem pode participar do programa de IC. As frases que utilizamos no treinamento foram:
- Qualquer um pode participar do programa?
- Qualquer um pode participar?
- Quem pode participar do programa?

E as respostas que escolhemos para o robô foram:
- Este Programa destina-se a alunos com bom rendimento acadêmico que buscam complementar sua formação através da execução de projetos de pesquisa, elaboração de relatórios e divulgação dos seus resultados em eventos de pesquisas científicas e de investigação tecnológica.
- O programa de IC destina-se a alunos com bom rendimento acadêmico que buscam complementar sua formação através da execução de projetos de pesquisa, elaboração de relatórios e divulgação dos seus resultados em eventos de pesquisas científicas e de investigação tecnológica.
- A Iniciação Científica destina-se a alunos com bom rendimento acadêmico que buscam complementar sua formação através da execução de projetos de pesquisa, elaboração de relatórios e divulgação dos seus resultados em eventos de pesquisas científicas e de investigação tecnológica.

#### d. Como participar?
São frases ligadas à intenção de saber quais são os passos para participar do programa de IC. As frases que utilizamos no treinamento foram:
- Como posso participar da IC?
- Quais são os passos para ingressar no programa?
- Como posso fazer para ingressar no programa?
- Como posso participar do programa?
		
E as respostas que escolhemos para o robô foram:
- O aluno deve procurar um professor do departamento, com disponibilidade para orientação e verificar as vagas disponíveis para projetos de iniciação. Tendo sido selecionado um aluno, o professor deve então elaborar uma proposta de projeto individual, dentro dos moldes exigidos pela Comissão de Iniciação Científica e encaminhá-la à Coordenação.

#### e. Despedida
São frases ligadas à intenção de se despedir do robô. Essa intenção marca o fim da interação entre as duas partes. As frases que utilizamos no treinamento foram:
- Até mais
- Tchau
- É nois cria
- Falou mano
- Valeu irmão!
- Mete o pé
- Obrigado!

E as respostas que escolhemos para o robô foram:
- Falou irmão
- Vá com Deus
- É nois cria
- Tamo junto, sangue bom
- Deus lhe proteja, filho

## 2. Entities
#### Iniciação Científica
Essa entidade define a Iniciação Científica. Ela é utilizada em algumas frases de treinamento para notificar o robô do assunto que ele está falando. Os sinônimos dessa entidade são:
- Programa de Iniciação Científica
- IC
- Iniciação Científica

## 3. Diálogo

![OI](https://user-images.githubusercontent.com/63318342/155564470-f9bf8c11-3568-44a0-a5c0-360ff94ae337.png)

![Sobre IC](https://user-images.githubusercontent.com/63318342/155564683-5b4e0894-bc7e-4091-98c1-0177375b203a.png)

![quem_pode_participar](https://user-images.githubusercontent.com/63318342/155564717-88cf8a1d-fbd7-461a-b103-57c57d934ad3.png)

![como_participar](https://user-images.githubusercontent.com/63318342/155564744-f4a9d9e0-252e-4895-b941-9f56bd792258.png)

![despedida](https://user-images.githubusercontent.com/63318342/155564770-5b1bdd7c-43ee-43b7-a0d4-045a6878267f.png)
