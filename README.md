# resumo-do-lab
Bootcamp Microsoft Azure Essentials AZ900

Com base no que já assisti nessas primeiras atividades. Posso falar com um pouco mais de propriedade sobre: os fundamentos do **Azure Essentials (AZ900)** e as principais funcionalidades do **GitHub**.

# Conceitos de Nuvem
### Computação em Nuvem:

**Definição:** É o fornecimento de serviços de TI (como servidores, armazenamento, bancos de dados, redes, software, análises e inteligência) pela Internet. Isso permite acesso a recursos escaláveis e sob demanda, eliminando a necessidade de investimento pesado em infraestrutura física.

**Benefícios principais:**

**Escalabilidade:** A capacidade de aumentar ou diminuir a capacidade conforme necessário.
**Elasticidade:** Ajuste automático de recursos com base na demanda.
**Economias de escala:** Provedores de nuvem oferecem serviços a um custo reduzido devido à infraestrutura compartilhada.
**Agilidade:** As empresas podem experimentar, desenvolver e lançar novos serviços rapidamente.

### Responsabilidade Compartilhada:

O modelo de nuvem distribui as responsabilidades de segurança entre o provedor de nuvem e o cliente. O provedor é responsável pela segurança da nuvem (infraestrutura), enquanto o cliente é responsável pela segurança dentro da nuvem (dados, identidade, etc.).

**Exemplo:** O provedor (Azure) garante que seus datacenters sejam protegidos, mas o cliente deve configurar corretamente suas máquinas virtuais e redes virtuais.
Modelos de Nuvem:

**Nuvem Pública:** Fornecida e gerenciada por terceiros (ex: Azure, AWS). Ideal para casos em que não há necessidade de infraestrutura personalizada ou controle total sobre o ambiente.

**Nuvem Privada:** Totalmente dedicada a uma organização, oferecendo controle total sobre a segurança e a infraestrutura, mas com custos mais elevados.

**Nuvem Híbrida:** Combina nuvens públicas e privadas, oferecendo flexibilidade. Ex: Uma empresa pode rodar dados sensíveis em sua nuvem privada e usar a nuvem pública para workloads menos críticos ou que precisam de maior escalabilidade.
Comparação CapEx (Capital Expenditure) vs OpEx (Operational Expenditure):

**CapEx:** Refere-se ao investimento em infraestrutura física. A empresa paga antecipadamente por equipamentos e recursos, com amortização ao longo do tempo. Ex: Compra de servidores.
**OpEx:** Refere-se a gastos contínuos que ocorrem conforme o uso de serviços (ex: serviços de nuvem). A vantagem é pagar apenas pelo que se consome, sem necessidade de grandes investimentos iniciais.

### Modelo Baseado no Consumo:

Um dos principais atrativos da computação em nuvem é que os usuários pagam apenas pelo que utilizam, sem a necessidade de comprar ou manter infraestrutura ociosa. É um modelo flexível e que permite que as empresas ajustem seus custos de acordo com as demandas reais de TI.
**Exemplo:** No Azure, você pode provisionar máquinas virtuais e pagar apenas enquanto elas estão em execução.

### Outros Conceitos Importantes:

Elasticidade vs Escalabilidade:

**Elasticidade:** A capacidade do sistema de se ajustar dinamicamente às mudanças de carga, aumentando ou diminuindo os recursos automaticamente.
**Escalabilidade:** Refere-se à habilidade de aumentar a capacidade do sistema conforme a necessidade de maior poder computacional.

**Modelo de Preços:** O modelo de nuvem oferece preços ajustados para cada tipo de serviço e recurso, como instâncias de computação, armazenamento e largura de banda. É possível também definir orçamentos e limites de gastos para evitar surpresas na fatura.

### Falando um pouco sobre os Benefícios da Nuvem Azure

1. Alta Disponibilidade (SLA) - Refere-se à capacidade dos serviços e aplicativos de permanecerem operacionais e acessíveis, mesmo em caso de falhas ou problemas. Existem várias disponibilidades (99%... 99,5%... 99,9%), isso é estipulado no contrato. Podendo haver em algum momento que o serviço fique fora do ar. Caso passe do tempo esperado off, o cliente recebe em crédito (vaucher) em forma de ressarcimento.
2. Resumindo, se concentra em garantir a dispobinibilidade máxima independentemente de interrupções ou eventos que possam ocorrer.

### Confiabilidade

1. A confiabilidade na plataforma é baseada em arquiteturas resilientes e uma abordagem de redundância e recuperação, garantindo que os serviços estejam sempre disponíveis para atender às necessidades do negócio.

### Segurança

1. A nuvem oferece ferramentas de segurança que atendem às necessidades dos clientes, mas é importante lembrar que a implementação de muitas delas devem ser realizadas pelo cliente.
2. A aplicação de patches e a manutenção sejam tratadas automaticamente, as implantações de plataforma como serviço ou software como serviço podem ser as melhores estratégias de nuvem para você.
3. Responsabilidade do cliente é aplicar as funcionalidades oferecidas, não cabe a Microsoft implementar no sistema da empresa.

**===========================================================================================**

# GitHub e Seus Fundamentos

### Conceito: 
O GitHub é uma plataforma de hospedagem de código-fonte que utiliza o sistema de controle de versão Git. Ele é amplamente utilizado por desenvolvedores e empresas para colaborar em projetos, gerenciar código e facilitar o desenvolvimento em equipe. Aqui estão as principais funcionalidades do GitHub:

**1. Repositórios (Repos)**
Repositórios são locais onde os projetos e o código-fonte são armazenados. Cada repositório pode conter arquivos, pastas e histórico de versões de um projeto. Os repositórios podem ser públicos (acessíveis por qualquer pessoa) ou privados (restritos a membros convidados).

**2. Controle de Versão**
O GitHub utiliza o Git, um sistema de controle de versão distribuído. Isso permite acompanhar o histórico de mudanças, comparar versões, reverter alterações e colaborar eficientemente com outros desenvolvedores.

**3. Branches (Ramificações)**
Branches permitem que os desenvolvedores criem versões paralelas de um projeto para trabalhar em novos recursos ou correções de bugs sem afetar a versão principal. Depois de testadas, as alterações podem ser mescladas (merged) ao branch principal, geralmente chamado de main ou master.

**4. Pull Requests**
Um Pull Request (PR) é uma proposta de alteração no código, solicitada por um colaborador. Ele permite que outras pessoas revisem o código antes que seja integrado ao projeto principal, promovendo um fluxo de trabalho colaborativo e seguro.

**5. Issues**
As Issues são usadas para rastrear tarefas, bugs, melhorias ou discussões relacionadas ao projeto. Elas ajudam a organizar o desenvolvimento e a comunicação entre a equipe.

**6. Actions**
GitHub Actions permite automatizar fluxos de trabalho de desenvolvimento, como a execução de testes, build de código, deploy e integração contínua (CI/CD). Os fluxos podem ser definidos com base em eventos, como push de código ou a criação de PRs.

**7. GitHub Pages**
GitHub Pages permite hospedar sites estáticos diretamente de um repositório do GitHub. É útil para criar documentações, portfólios, blogs ou outros sites com facilidade.

**8. Wiki**
Cada repositório no GitHub pode ter um Wiki, que serve como uma área para documentação colaborativa, tutoriais, ou qualquer informação relacionada ao projeto.

**9. Projects**
GitHub Projects é uma ferramenta de gerenciamento de projetos integrada, que permite organizar tarefas em quadros (como o Trello), oferecendo suporte para a criação de to-do lists, cards de tarefas e sprints.

**10. Colaboração e Revisão de Código**
GitHub facilita a colaboração entre desenvolvedores com recursos como revisões de código, comentários em pull requests e code diffs (comparação de versões de código).

**11. Security Features**
Dependabot: Notifica sobre vulnerabilidades de segurança em dependências do projeto e sugere atualizações automáticas. Code Scanning: Permite a detecção automática de vulnerabilidades no código. Essas funcionalidades tornam o GitHub uma ferramenta poderosa para gerenciar o ciclo de vida do desenvolvimento de software, tanto para projetos individuais quanto para grandes equipes.
**===========================================================================================**

## Expectativas e Objetivos Alcançados
Durante o estudo inicial do Microsoft Azure Essentials AZ-900, aprofundei meu entendimento sobre os conceitos fundamentais de computação em nuvem, como responsabilidade compartilhada, modelos de nuvem (pública, privada e híbrida) e o modelo CapEx vs OpEx, além do modelo de consumo para gerenciamento de custos. Isso me permitiu entender como a nuvem facilita inovação, escalabilidade e eficiência operacional, e como esses conceitos podem ser aplicados no desenvolvimento de soluções modernas.

Paralelamente, pude rever alguns conceitos e me aprofundar um pouco mais nas funcionalidades do GitHub, consolidando práticas de versionamento de código, colaboração por meio de pull requests, gerenciamento de issues e automação de fluxos de trabalho com GitHub Actions. Essa experiência reforçou meu entendimento sobre as melhores práticas de controle de versão e colaboração em projetos de software, fundamentais para ambientes ágeis e colaborativos.

Esses estudos complementam minhas habilidades como desenvolvedor, permitindo uma aplicação mais eficiente de tecnologias modernas em projetos futuros.
