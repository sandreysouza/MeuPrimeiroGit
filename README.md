# Meu primeiro projeto Git
# Sandrey Cristhian Moreira de Souza - 2026

Etapa 1 - Criado estrutura inicial do projeto.
Etapa 2 - Adicionado documentação dos produtos.
Etapa 3 - Adicionado página de produtos.
Etapa 4 - Adicionado estilização inicial.
Etapa 5 - Adicionado documentação e página inicial de pedidos.
Etapa 6 - Atualizado documentação do projeto.
Etapa 7 - Adicionado documentação e página inicial de contato.

Qual é a diferença entre Working Directory, Staging Area e Repository? 
R:  Working Directory: é a pasta do projeto no computador, onde os arquivos existem e podem ser editados livremente.
    Staging Area: é uma área intermediária onde ficam as mudanças selecionadas (com git add) que serão incluídas no próximo commit.
    Repository: é onde o histórico de commits fica armazenado permanentemente, com todas as versões salvas do projeto.

Qual é a diferença entre git commit e git push? 
R: O git commit salva um snapshot das mudanças no repositório local. Já o git push envia esses commits salvos localmente para o repositório remoto, tornando-os visíveis para outras pessoas.

É possível realizar vários commits antes de executar um git push? Explique.
R: Sim. É possível fazer quantos commits forem necessários localmente antes de enviar para o remoto. Cada commit fica registrado no histórico local, e só quando o git push é executado é que todos esses commits são enviados de uma vez para o repositório remoto.

Por que é interessante realizar commits pequenos e descritivos? 
R: Commits pequenos facilitam entender o que mudou em cada etapa, tornam mais fácil identificar e corrigir erros, e ajudam outras pessoas a entender o histórico do projeto. Mensagens descritivas tornam esse histórico compreensível sem precisar abrir cada commit para ver o que foi alterado.

O que acontece com os commits locais quando ainda não executamos o git push?
R: Eles ficam salvos apenas no repositório local, na máquina do desenvolvedor. O repositório remoto não tem conhecimento dessas mudanças até que o git push seja executado. Se o computador for perdido ou o repositório local for apagado sem um push anterior, esses commits podem ser perdidos.

Como verificar, pelo GitHub, se os commits foram enviados corretamente?
R: Basta acessar o repositório no GitHub pelo navegador e conferir a aba de commits, verificando se as mensagens de commit e os arquivos alterados aparecem lá, condizentes com o que foi feito localmente.
