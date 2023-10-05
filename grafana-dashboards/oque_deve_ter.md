
https://medium.com/@dotdc/a-set-of-modern-grafana-dashboards-for-kubernetes-4b989c72a4b2

Visão Geral do Cluster:

Status do cluster.
Uso de recursos (CPU, memória, armazenamento).
Número de nós no cluster.
Status dos nós (up/down).

Monitoramento de Pods e Containers:

Número de pods em execução, pendentes e em falha.
Utilização de recursos por namespace (CPU, memória).
Gráficos de tendência de implantações de pods.

Monitoramento de Serviços:

Status dos serviços (ativo/inativo).
Latência, taxas de erro e solicitações por segundo para serviços expostos.
Taxa de transferência de dados.
Logs e Eventos:

Exibir logs e eventos críticos.
Pesquisa e filtragem de logs por namespace, contêiner ou tempo.
Autoscaling:

Estatísticas sobre escalonamento automático.
Mostrar quando e como o escalonamento automático ocorreu.
Estado das Implantações:

Status de implantações, como implantações em progresso, bem-sucedidas e falhas.
Histórico de versões.
Redes:

Taxas de transferência e latência de rede.
Monitoramento de políticas de rede (Network Policies).
Armazenamento:

Uso de armazenamento por namespace e volume.
Status de PVs (Persistent Volumes) e PVCs (Persistent Volume Claims).
Segurança:

Status de políticas de segurança (PodSecurityPolicies, Network Policies).
Eventos de segurança (falhas de autenticação, violações de políticas).
Alertas e Notificações:

Configuração de alertas para eventos críticos.
Integração com ferramentas de notificação (como Slack ou e-mail).
Tempo Real vs. Histórico:

Permita alternar entre visualizações em tempo real e histórico.
Filtros e Seleções:

Capacidade de filtrar dados com base em namespaces, serviços, contêineres, etc.
Gráficos e Gráficos Interativos:

Use gráficos de séries temporais para exibir métricas ao longo do tempo.
Gráficos interativos que permitem ampliar e selecionar intervalos de tempo específicos.
Personalização:

Permita que os usuários personalizem o dashboard de acordo com suas necessidades.
Documentação e Ajuda:

Forneça documentação ou dicas de uso para ajudar os usuários a interpretar os dados.