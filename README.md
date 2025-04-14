🌍 Azure Global — Regiões, Replicação e Compliance
📌 Sobre o Azure Global

O Microsoft Azure é uma plataforma de computação em nuvem global, que oferece infraestrutura, serviços e segurança de alto nível. Suas Regiões são distribuídas ao redor do mundo, permitindo ao cliente escolher onde deseja que seus dados e aplicações sejam hospedados, pensando em latência, disponibilidade e conformidade.
🇧🇷 Região do Brasil

No Brasil, a Microsoft mantém uma região principal chamada Brazil South (localizada em São Paulo). Esta região garante baixa latência e alta disponibilidade para aplicações hospedadas dentro do território nacional.

Além da região principal, a Microsoft também possui uma estrutura de região emparelhada de suporte localizada no Rio de Janeiro, que funciona como backup ou replicação, especialmente importante em cenários onde normas de proteção de dados precisam ser respeitadas.

🛡️ Replicação e Compliance

A Microsoft oferece replicação geográfica para garantir a durabilidade dos dados e recuperação de desastres.

No contexto brasileiro, com a vigência da LGPD (Lei Geral de Proteção de Dados), a replicação para o Rio de Janeiro é priorizada para manter os dados dentro do território nacional, cumprindo normas legais.

Caso não seja possível, os dados podem ser replicados para outra região Azure emparelhada que ofereça o nível de segurança e conformidade adequado.
⚙️ Criando um Grupo de Recursos no Azure — Passo a Passo

1️⃣ Acesse o portal:
https://portal.azure.com

2️⃣ No menu lateral, clique em Grupos de recursos.

3️⃣ Clique em + Criar.

4️⃣ Preencha os dados:

    Assinatura: Escolha a assinatura correta.

    Grupo de Recursos: Dê um nome intuitivo.

    Região: Escolha a mais próxima (ex: Brazil South).

5️⃣ Clique em Revisar + Criar e, se estiver tudo certo, clique em Criar.
🔐 IAM — Controle de Acesso Baseado em Identidade

O Azure IAM (Identity and Access Management) permite gerenciar quem pode acessar os recursos, quem pode fazer o quê e em quais recursos.

Principais funções:

    Owner → controle total.

    Contributor → pode criar e gerenciar, mas não atribui permissões.

    Reader → apenas visualiza.

Usar o IAM corretamente é essencial para manter a segurança, aplicar boas práticas de princípio do menor privilégio e garantir que somente pessoas autorizadas possam manipular recursos críticos.
