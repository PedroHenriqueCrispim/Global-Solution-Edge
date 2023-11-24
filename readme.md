Integrantes: 
Pedro Henrique Crispim - RM99005 
Rafael Autieri - RM550855


Descrição do Problema de Saúde Abordado:

O problema de saúde que motiva nossa proposta está relacionado à falta de eficiência na gestão de utensílios cirúrgicos em hospitais, resultando em atrasos e possíveis complicações para os pacientes. A inconsistência na preparação e disponibilidade de instrumentos cirúrgicos essenciais pode impactar diretamente a qualidade do atendimento e a segurança do paciente.


Visão Geral da Solução Proposta:

A solução que apresentamos visa melhorar a gestão de utensílios cirúrgicos por meio de um sistema integrado de planejamento e acompanhamento. Desenvolvemos um software específico, adaptável aos sistemas hospitalares existentes, que automatiza e otimiza o processo de preparação de utensílios para cirurgias.


Agendamento Inteligente:
O sistema é integrado ao processo de agendamento de cirurgias, identificando automaticamente os utensílios necessários para cada procedimento com base em critérios específicos, como o tipo de intervenção e o histórico clínico do paciente.

Comunicação Eficiente:
Facilitamos a comunicação entre cirurgiões, equipe médica e responsáveis pela preparação dos utensílios. As informações sobre os instrumentos necessários são compartilhadas de maneira instantânea e transparente, evitando mal-entendidos e atrasos.

Rastreamento em Tempo Real:
Implementamos um sistema de rastreamento em tempo real para monitorar o status da preparação dos utensílios. Isso permite que a equipe médica tenha visibilidade imediata sobre a disponibilidade de instrumentos, possibilitando ajustes rápidos, se necessário.

Alertas e Notificações:
O sistema emite alertas automáticos em caso de atrasos na preparação dos utensílios, garantindo que a equipe responsável seja notificada a tempo de corrigir o problema antes da cirurgia.

Registro e Análise de Dados:
Todas as interações e decisões relacionadas à preparação dos utensílios são registradas no sistema. Isso não apenas permite uma revisão pós-cirúrgica detalhada, mas também facilita análises de desempenho e a implementação contínua de melhorias.

Ao adotar nossa solução, os hospitais podem esperar uma significativa redução nos atrasos cirúrgicos, melhorando a eficiência operacional, a satisfação do paciente e garantindo um ambiente mais seguro para intervenções médicas. Estamos comprometidos em proporcionar uma solução robusta que atenda às necessidades específicas de cada instituição de saúde, contribuindo para um sistema de saúde mais eficaz e centrado no paciente.




Como Funciona:

O código fornecido é destinado a um dispositivo ESP32 e parece ser um simples programa que detecta quando um dos três botões (conectados aos pinos buttonPin1, buttonPin2 e buttonPin3) é pressionado. Quando um botão é pressionado, um sinal sonoro é emitido pelo buzzer (conectado ao pino buzzerPin) por 3 segundos.

Aqui estão as instruções sobre como configurar e executar a aplicação:

Pré-requisitos:
Arduino IDE: Certifique-se de ter o Arduino IDE instalado em seu computador.

Suporte ao ESP32 na Arduino IDE: Certifique-se de ter o suporte para ESP32 instalado na Arduino IDE.

Configuração do Hardware:
Conexão dos Botões: Conecte os botões aos pinos especificados no código (buttonPin1, buttonPin2 e buttonPin3). Certifique-se de conectar os botões da maneira correta.

Conexão do Buzzer: Conecte o buzzer ao pino especificado no código (buzzerPin). Certifique-se de conectar o lado positivo ao pino e o lado negativo a GND.

Carregando o Código:
Abra o Arduino IDE: Inicie o Arduino IDE no seu computador.

Configuração do Tipo de Placa: Vá para "Ferramentas" > "Placa" e selecione a placa "ESP32 Dev Module" ou a placa ESP32 correspondente ao seu dispositivo.

Configuração da Porta: Vá para "Ferramentas" > "Porta" e selecione a porta à qual o seu ESP32 está conectado.

Verificação e Carregamento: Clique no ícone de visto ("Verificar") para verificar se há erros no código. Se não houver erros, clique na seta para a direita ("Carregar") para carregar o código no ESP32.

Executando o Código:
Abra a Janela de Monitor Serial: Vá para "Ferramentas" > "Monitor Serial" para abrir a janela de monitor serial.

Observando a Saída: Após carregar o código no ESP32, você verá a mensagem "Hello, ESP32!" no monitor serial.

Pressione os Botões: Pressione um ou mais dos botões conectados aos pinos especificados. Você deverá ver a mensagem "Botão pressionado!" no monitor serial e ouvir um som do buzzer por 3 segundos.


Link para a simulação do projeto no Wokwi.

https://wokwi.com/projects/382250058722725889