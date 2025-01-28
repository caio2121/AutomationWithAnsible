Automação de Tarefas com Ansible
Este repositório contém uma coleção de playbooks Ansible projetados para automatizar diversas tarefas administrativas e de infraestrutura. O objetivo é simplificar processos complexos e garantir consistência na execução.

📌 Playbooks Disponíveis
1️⃣ Full Bacula Install (fullbaculainstall.yml)
O primeiro playbook do repositório, fullbaculainstall.yml, automatiza a instalação e configuração completa do Bacula Director e do Baculum, fornecendo um ambiente de backup robusto e gerenciável via interface web.

🔹 Funcionalidades
✅ Instalação do Bacula Director (versão 15.0.2) com suporte ao PostgreSQL.
✅ Configuração automática do banco de dados PostgreSQL e ajustes no pg_hba.conf.
✅ Instalação e configuração do Baculum (interface web de gerenciamento).
✅ Habilitação de repositórios oficiais e instalação de dependências do PHP e Apache.
✅ Ajustes de permissões e habilitação de módulos do Apache.
✅ Configuração pronta para uso com interface gráfica de gerenciamento.

🚀 Como Usar
Clone este repositório:
bash
Copiar
Editar
git clone https://github.com/caio2121/AutomationWithAnsible.git
cd AutomationWithAnsible/backup
Execute o playbook no controlador Ansible:
bash
Copiar
Editar
ansible-playbook -i <arquivo-inventario> fullbaculainstall.yml
Substitua <arquivo-inventario> pelo inventário de hosts adequado.
📌 Após a execução, o Bacula e o Baculum estarão configurados e prontos para uso!

🔄 Sobre este Repositório
Este repositório será continuamente atualizado com novos playbooks para automação de tarefas administrativas e operacionais.
Os scripts estarão organizados por propósito, como monitoramento, backups e configurações de rede, entre outros.

🤝 Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues, sugerir melhorias ou enviar pull requests.

