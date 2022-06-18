# Instalando e Configurando o git no seu 🖥️ 💻.

### No mundo da programação, o git é uma ferramenta extremamente útil para o controle de versões do seu código. Ele permite que você rastreie as alterações que você faz no seu código, compartilhe suas alterações com outros desenvolvedores e faça backup de seu código. Neste tutorial, mostraremos como instalar e configurar o git no seu computador.

Primeiro, você precisará baixar e instalar o git em seu computador. Se você está utilizando o sistema operacional Windows, pode obter o git a partir do site oficial do git (http://git-scm.com/download/win). Uma vez que o git esteja instalado em seu computador, você precisará configurá-lo para funcionar com seu nome e endereço de e-mail. Você pode fazer isso executando os seguintes comandos no terminal:

git config --global user.name "Seu Nome" 
git config --global user.email "seu@email.com"

Se na sua realidade trata-se de um outro sistema operacional recomendo que sigam o passo a passo no site (https://git-scm.com/book/pt-br/v2/Come%C3%A7ando-Instalando-o-Git) 

Agora que o git está configurado, você pode começar a usá-lo para controlar as versões do seu código. Para isso, você precisará inicializar um repositório git em sua pasta de projeto usando o comando 'git init'. Isso criará um diretório chamado '.git' na sua pasta de projeto que conterá todas as informações necessárias para rastrear as alterações em seu código.

Uma vez que um repositório git foi inicializado, você pode adicionar arquivos a ele usando o comando 'git add'. Por exemplo, para adicionar um arquivo chamado 'main.c' ao repositório, você pode executar o comando:

git add main.c

Após adicionar os arquivos que deseja rastrear ao repositório, você precisará commitá-los usando o comando 'git commit'. Isso irá salvar uma snapshot do estado atual do código em sua máquina local e permitir que você volte para essa versão caso precise reverter alguma alteração posteriormente. 


# Os 5 maiores erros cometidos no uso do Git (e como evitá-los) 


## Se você está iniciando seus estudos com o Git, é importante evitar os seguintes erros comuns:

### Não aprender os conceitos básicos do Git.
Muitos desenvolvedores iniciantes querem aprender a usar o Git sem antes compreender os conceitos fundamentais por trás dele. Isso pode levar a confusão e a frustração mais tarde, quando enfrentarem problemas mais complexos. É importante ter um bom entendimento dos conceitos do Git, como commits, branches e merge antes de começar a usá-lo.

Usar o Git de forma errada.
O Git é uma ferramenta extremamente poderosa e versátil, mas isso também significa que há muitas maneiras de usá-lo de forma incorreta. Por exemplo, alguns desenvolvedores podem não saber como fazer um commit corretamente, o que pode levar à perda de dados importantes. Outros podem não saber como criar branches corretamente, o que pode causar problemas na integração do código posteriormente. É importante ler a documentação do Git e seguir as boas práticas recomendadas para evitar esses erros.

Não gerenciar suas credenciais do Git adequadamente.
Gerenciar suas credenciais do Git de forma incorreta pode ser extremamente perigoso e levar à comprometimento da segurança da sua conta e dos seus dados. Por exemplo, alguns desenvolvedores podem armazenar suas senhas do Git em arquivos texto sem proteção, o que significa que qualquer pessoa que tenha acesso a esses arquivos poderá facilmente obter suas credenciais. Outros podem compartilhar seus repositórios do Git publicamente sem proteger as chaves SSH, o que também representa um risco para a segurança das suas contas e dos seus dados. É importante tomar as medidas necessárias para garantir que suas credenciais estejam sempre protegidas adequadamente.

Não fazer backups regulares dos seus dados do Git.
Outro erro comum cometido pelos desenvolvedores é não fazer backups regulares dos dados armazenados nos repositórios do Git. Isso significa que qualquer problema no servidor onde os repositórios estão hospedados (por exemplo, um ataque hacker) pode levar à perda irreparável desses dados. É por isso que é altamente recomendado fazer backups regulares dos repositórios do Git para garantir a continuidade dos trabalhos em caso de falha no servidor principal.

Não ter cuidado ao trabalhar com branches no git. 
Sempre é bom ter cuidado especialment quando se trabalha com branches no git , pois deletar acidentalmentepor exemploo branch principal(master) causaria sérios problemas. Para evitar isso, certifique-se detrabalhar somente em copias locais dessas branches em modificacoes ; nao altere diretamente na branch original até que esteja certo da consistência dessas informacões.



