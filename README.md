## Hermes:  Sistema  de  Relatório  Automatizado  para  Socorristas

### Descrição

O Hermes  automatiza  a  geração  de  relatórios  para  socorristas  e  paramédicos,  agilizando  a  transmissão  de  informações  cruciais  para  o  hospital  receptor  do  paciente.  O  software  analisa  o  áudio  gravado  durante  o  atendimento,  extraindo  informações  relevantes  e  organizando-as  para serem enviadas ao hospital antes mesmo da chegada do paciente.

### Funcionalidades

-   **Transcrição  de  Áudio:**  Converte  a  gravação  de  áudio  do  atendimento  em  texto.
    
-   **Extração  de  Dados:**  Identifica  e  extrai  informações  relevantes  do  texto  transcrito,  incluindo:
    
    -   Breve  resumo  das  circunstâncias  em  que  o  paciente  foi  encontrado.
        
    -   Ferimentos  identificados.
        
    -   Primeiros  socorros  realizados.
        
-   **Geração  de  Relatório  JSON:**  Compila  as  informações  extraídas  em  um  arquivo  JSON  estruturado,  pronto  para  ser  enviado  ao sistema do hospital.
    
-   **Sugestão  de  Exames:**  Baseado  nos  dados  coletados,  Hermes  sugere  exames  que  podem  ser  necessários  para  o  diagnóstico  e  tratamento  do  paciente. Podem assim, agilizar o preparo das salas e equipamentos.
    

### Benefícios

-   **Agilidade  na  Comunicação:**  Reduz  o  tempo  necessário  para  transmitir  informações  para  o  hospital,  permitindo  que  a  equipe  médica  se  prepare  para  receber  o  paciente  de  forma  mais  eficiente.
    
-   **Redução  de  Erros:**  Minimiza  a  chance  de  erros  na  comunicação  de  informações  importantes.
    
-   **Padronização  de  Relatórios:**  Cria  relatórios  padronizados  e  organizados,  facilitando  a  compreensão  das  informações. 
    
-   **Auxílio  na  Tomada  de  Decisão:**  As  sugestões  de  exames  auxiliam  a  equipe  médica  na  tomada  de  decisões  rápidas  e  eficazes.
    

### Como  Usar  Hermes

1.  **Gravação  de  Áudio:**  Grave  o  áudio  durante  o  atendimento  ao  paciente, anexando o equipamento de gravação no socorrista.
    
2.  **Processamento  do  Áudio:**  Utilize  Hermes  para  processar  o  áudio  gravado.
    
3.  **Geração  de  Relatório:**  Hermes  gerará  automaticamente  um  relatório  em  formato  JSON.
    
4.  **Envio  do  Relatório:**  Após gerado, relatório é automaticamente enviado ao hospital destino.
    

### Tecnologias  Utilizadas

-   **Processamento  de  Linguagem  Natural  (PNL):**  Para  transcrever  o  áudio  e  extrair  informações  relevantes.
    
-   **Inteligência  Artificial  (IA):**  Para  sugerir  exames  com  base  nos  dados  coletados.
    

### Próximos  Passos

-   Integração  com  sistemas  de  comunicação  hospitalar  para  envio  automático  dos  relatórios.
    
-   Expansão  da  base  de  dados  de  sintomas  e  exames  para  melhorar  a  precisão  das  sugestões.

  

## Ajustes para rodar o Hermes em sua maquina

### Executando via Google Colab:

- Crie o seguinte diretório e copie o caminho do arquivo desejado.
![image](https://github.com/GuilhermeDuar/ProjetoImersao/assets/89658024/78418bd1-7403-43d0-ad95-441e88f2f5f4)

- Atualize o parametro com o caminho.
![image](https://github.com/GuilhermeDuar/ProjetoImersao/assets/89658024/c1a9d086-51fa-4c4f-8b74-3622ef7ea11a)


### Executando via IDEs de python:

- Crie uma pasta contendo os áudios no mesmo diretório do projeto.

- Atualize o parametro com o caminho do arquivo desejado.
![image](https://github.com/GuilhermeDuar/ProjetoImersao/assets/89658024/c1a9d086-51fa-4c4f-8b74-3622ef7ea11a)

