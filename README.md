Repositório: Automação de Tarefas com Ansible
Este repositório contém uma coleção de playbooks Ansible projetados para automatizar diversas tarefas administrativas e de infraestrutura, com foco em simplificar processos complexos e garantir consistência na execução.

Playbooks Disponíveis
1. Full Bacula Install (fullbaculainstall.yml)
O primeiro playbook do repositório, fullbaculainstall.yml, automatiza a instalação e configuração completa do Bacula Director e do Baculum, oferecendo um ambiente de backup robusto e gerenciável via interface web.

Funcionalidades:
Instalação do Bacula Director (versão 15.0.2) com suporte ao PostgreSQL.
Configuração automática do banco de dados PostgreSQL e ajustes no pg_hba.conf.
Instalação e configuração do Baculum, incluindo:
Repositórios oficiais.
Dependências do PHP e do Apache.
Ajustes de permissões e habilitação de módulos do Apache.
Configuração pronta para uso com interface gráfica de gerenciamento.
Como usar:
Clone este repositório:

bash
Copiar
Editar
git clone https://github.com/caio2121/
cd automation-playbooks
Execute o playbook no controlador Ansible:

bash
Copiar
Editar
ansible-playbook -i inventario fullbaculainstall.yml
Após a execução, o Bacula e o Baculum estarão configurados e prontos para uso.

Sobre este Repositório
Este repositório será continuamente atualizado com novos playbooks para automação de tarefas administrativas e operacionais. Os scripts serão organizados por propósito, como monitoramento, backups, configurações de rede, entre outros.

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues, sugerir melhorias ou enviar pull requests.
