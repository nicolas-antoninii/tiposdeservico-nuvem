# 🛡️ Modelo de Responsabilidade Compartilhada na Nuvem
## 🌐 O que é?
O modelo de responsabilidade compartilhada define quem é responsável pelo quê na computação em nuvem.

Em vez de o provedor de nuvem (como Microsoft Azure) assumir todas as responsabilidades ou o cliente cuidar de tudo sozinho, as tarefas são divididas entre os dois.

Isso garante:
✅ Maior segurança
✅ Melhor governança
✅ Clareza sobre obrigações

### 🔍 Como funciona?
O modelo varia conforme o tipo de serviço usado:

### 🏗️ IaaS (Infrastructure as a Service)
Provedor (Azure): infraestrutura física, redes, data centers, virtualização

Cliente: sistema operacional, aplicativos, dados, configurações de rede, controle de acessos

### 🛠️ PaaS (Platform as a Service)
Provedor (Azure): infraestrutura, sistema operacional, plataforma de execução

Cliente: aplicativos, dados, identidade e acesso dos usuários

### 🖥️ SaaS (Software as a Service)
Provedor (Azure): infraestrutura, plataforma, aplicativos, segurança do software

Cliente: dados (inseridos e gerados), configurações de conta, permissões de acesso

## 📌 Exemplo Prático
Imagine um app hospedado no Azure:

No IaaS, você é responsável por configurar e proteger o sistema operacional da máquina virtual.

No PaaS, você só cuida do código e das permissões de quem usa.

No SaaS, você só gerencia os usuários e dados — o provedor cuida do resto.
