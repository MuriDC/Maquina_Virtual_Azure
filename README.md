# Maquina_Virtual_Azure
# Desafio

Criar um repositório público no GitHub contendo:   
Um arquivo README.md detalhado   
Quaisquer arquivos adicionais que sejam relevantes para documentar sua experiência   
Opcionalmente, capturas de tela relevantes organizadas em uma pasta /images   

# Criando máquina virtual
Para criação de uma máquina virtual é necessário primeiramente fazer uma conta na Azure no link abaixo. Grátis por 30 dias.  
https://azure.microsoft.com/pt-br/pricing/purchase-options/azure-account/search?icid=free-search&ef_id=_k_CjwKCAjw9uPCBhATEiwABHN9K9D0KT1DueU7mJ0BIpAwR0IIUr37SL2erUWqavFoJANP-xdDWcQUnhoCirkQAvD_BwE_k_&OCID=AIDcmmzmnb0182_SEM__k_CjwKCAjw9uPCBhATEiwABHN9K9D0KT1DueU7mJ0BIpAwR0IIUr37SL2erUWqavFoJANP-xdDWcQUnhoCirkQAvD_BwE_k_&gad_source=1&gad_campaignid=1634421586&gbraid=0AAAAADcJh_uCIyY_osDvEavQsCEXxa5Dh&gclid=CjwKCAjw9uPCBhATEiwABHN9K9D0KT1DueU7mJ0BIpAwR0IIUr37SL2erUWqavFoJANP-xdDWcQUnhoCirkQAvD_BwE  


Após preencher o cadastro do usuário é necessário fornecer os dados do cartão. Como dica podemos fazer um cartão virtual. É sugerido que se crie uma autenticação multifator.
# Fazendo o passo a passo
Ao entrar na conta é possível criar um recurso (máquina), na página inicial informações dos principais serviços da Azure e tarefas comuns são exibidas. No painel é mostrado recursos, serviços, alertas, tutoriais e etc. Em todos os serviços é mostrado a variedade de serviços disponíveis na Azure. Favoritos é configurável de acordo com o que quisermos mostar. Há uma barra de pesquisa na parte de cima. Disponível ao lado há o microsoft copilot que ajuda com diversas atividades. Tabém é mostrado as notificações, Ajuda + suporte e os dados da conta, como senha e fatura.

# Centro de acesso rápido
- Como navegar pelo portal da Azure.
Comece a trabalhar com sua assinatura do Azure usando o portal do Azure baseado na Web.  
Use o portal do Azure para procurar os serviços do Azure, criar e localizar seus recursos e personalizar sua experiência no portal.  
O Centro de Início Rápido do Azure fornece uma experiência guiada para iniciar um projeto com etapas e diretrizes estruturadas.  

- Aproveite mais sua conta gratuita
Experimente todos os serviços do Azure gratuitamente nos primeiros 30 dias usando o crédito de US$ 200 incluído em sua nova conta gratuita do Azure.
A mudança para preços de pagamento conforme o uso em até 30 dias ou depois de usar seu crédito de US$ 200 desbloqueia serviços gratuitos que você pode usar nos primeiros 12 meses.  
Mais de 55 serviços estão incluídos com valores gratuitos mensais mesmo após os 12 primeiros meses.  
Os serviços gratuitos podem ser usados em seus cenários de produção, não apenas para desenvolvimento e teste.  
Você pode usar combinações dos serviços gratuitos para criar muitos tipos de soluções, incluindo aplicativos Web escalonáveis, experiências móveis alimentadas por IA, modernização de aplicativos usando contêineres e muito mais.  
Se você não mudar para preços de pagamento conforme o uso depois de gastar seu crédito de US$ 200 ou após seus primeiros 30 dias, você não será cobrado por nada, mas sua conta e os seus serviços serão desabilitados.

- Arquitete suas soluções do Azure
Identifique soluções que serão boas candidatas para o Azure considerando drivers comuns, como trabalho remoto, redução de custos, envelhecimento da infraestrutura local, conformidade, segurança e dimensionamento para atender à demanda.  
O Centro de Arquitetura do Azure é um recurso valioso para aprender sobre como arquitetar aplicativos e soluções no Azure.  
O Guia de Arquitetura do Aplicativo (encontrado no Centro de Arquitetura do Azure) orientará você por meio de uma abordagem estruturada para projetar seus aplicativos no Azure.  
As arquiteturas de referência no Centro de Arquitetura do Azure fornecem exemplos e inspiração para a arquitetura da sua solução.

- Gerencie e organize os recursos do Azure
Uma boa organização ajuda a proteger, gerenciar e acompanhar os custos.  
O Azure fornece estruturas de organização hierárquicas e não hierárquicas.  
Estrutura hierárquica: recurso < grupo de recursos < assinatura <grupo de gerenciamento  
Marcas (não hierárquicas): podem ser adicionadas a recursos, grupos de recursos e assinaturas; marcas podem ser usadas para filtrar  
Recomendação: planeje sua convenção de nomenclatura antecipadamente; pode ser outra maneira de organizar seus recursos.

- Selecione a melhor região do Azure
A infraestrutura global do Azure é composta por mais de 60 regiões de data center em geografias em todo o mundo, conectadas por mais de 165 mil milhas de fibra e cabos submarinos.  
Ao selecionar uma região do Azure para suas cargas de trabalho, você deve escolher uma região próxima dos usuários para reduzir a latência de rede e aprimorar a experiência do usuário.  
Você deve considerar os regulamentos de conformidade e residência de dados aos quais deve aderir ao selecionar uma região do Azure. O hub de conformidade do Azure fornece informações sobre as ofertas de conformidade do Azure.  
Você deve selecionar uma região que tenha todos os serviços e tamanhos de serviço necessários para sua solução. Você pode encontrar regiões que tenham os serviços necessários usando a ferramenta Produtos disponíveis por região.  
Se sua carga de trabalho tiver usuários distribuídos em todo o mundo ou sua carga de trabalho for extremamente sensível a interrupções e tempo de inatividade além dos SLAs de região única, considere implantar suas cargas de trabalho em várias regiões.

- Estime e reduza os custos do Azure
Para estimar o custo da sua solução, você precisa entender a arquitetura da sua solução e os serviços necessários.  
Os serviços do Azure são cobrados com base na quantidade de tempo que um recurso é provisionado (preço fixo) ou com base no uso do recurso do Azure (baseado em consumo).  
Você pode usar a calculadora de preços do Azure para estimar o custo das suas soluções. Você pode configurar os serviços necessários para suas soluções, salvar uma estimativa, compartilhá-la com outras pessoas e exportá-la para o Excel.  
Alguns serviços de cobrança de preço fixo, como Máquinas Virtuais, podem ser interrompidos para pausar a cobrança. Outros serviços precisam ser desprovisionados e removidos de sua assinatura do Azure para interromper a cobrança.  

- Gerenciar custos e gastos
Você deve planejar e estimar os custos do Azure. Isso permitirá que você faça a linha de base dos seus custos e terá uma meta para gerenciar seus custos.  
Organizar seus recursos e ter um ambiente do Azure bem estruturado ajudará você a obter visibilidade dos custos.  
O Gerenciamento de Custos no portal do Azure fornece ferramentas para analisar e detalhar os custos do Azure.  
Os orçamentos ajudam você a gerenciar proativamente os custos disparando notificações e automações quando seus gastos atingem determinados níveis que você define.  
O Assistente do Azure analisa a configuração e o uso de recursos para recomendações para ajudar você a aprimorar o custo-benefício em seu ambiente do Azure. Ele também fornece recomendações para confiabilidade, segurança, desempenho e operações.  


# Máquinas virtuais
As principais facilidades que o Azure oferece são Escalabilidade e flexibilidade, Serviços integrados e segurança e conformidade.   
A criação de máquina virtual é o primeiro passo para acessar estas facilidades. Ao clicar em criar podemos optar por criar uma máquina virtual, conjunto de dimensionamentos de máuinas virtuais (VMSS), Predefinições (criando uma VM Pré definida e otimizada para uso geral - opção que parece ser mais rápida) e SOluções híbridas (também pré configurados).   
Para entender quais as possibilidades vamos seguir por criar uma VM mais personalizável. 

- Detalhes do projeto  
Selecione a assinatura para gerenciar os custos e os recursos implantados.  
- Detalhes da instância -> Vou detalhar por ser o coração da máquina.  
Nome da máquina virtual  
Região -> Podemos escolher entre 44 zonas. Inclusive Brasil  
Opções de disponibilidade -> Nenhuma redundância, ZOna de disponibilidade, Conjunto de dimensionamento de máquinas virtuais ou Conjunto de disponibilidade.  
Opções de Zona -> Autoselecionada ou selecionada pela Azure  
Zona de disponibilidade -> Escolher entre 1 a 3 zonas.  
Tipo de segurança -> Padrão, conputadores virtuais de inicialização confiável e máquinas virtuais confidenciais.  
Imagem -> 13598 opções de máquinas para escolher o sistema operacional e formatação.  
Arquitetura de VM -> Arm64 ou x64  
Executar com desconto de Spot do Azure -> Checkbox para habilitar utilizar máquinas ociosas, podendo perder a infra constantemente.  
Tamanho -> 917 tamanhos de VM disponíveis  
Habilitar Hibernação ->A hibernação economiza tempo e dinheiro, desalocando a RAM para HD e permitindo continuar de onde parou assim que a VM for reiniciada.

- Conta de administrador
Tipo de Autenticação
Nome de usuário  
Origem de chave SSH pública
Tipo de chave SSH
Nome do par de chaves  

- Regras de portas de entrada
Portas de entrada públicas
Selecione as portas de entrada

Ao fazer estas definições é possível definir as características do Disco da VM, como Criptografia, O próprio disco e disco de dados.  
Dando sequência para a rede, onde é possível definir a interface da rede e balanceamento de carga.  
Passadno opara o Gerenciamento, que define delisgamento automático, backup, atualizações e gerenciamento de identidade.  
Seguindo para o Monitoramento onde é possível habilitar alertas. Seguindo para outras configurações avançadas.  

Bem mais simples selecionar uma VM já pré definida no caso de estar aprendendo ou não ter um uso muito nichado para a máquina.

