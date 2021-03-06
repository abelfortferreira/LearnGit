# LearnGit
Um curso básico Open Source de introdução ao Git e GitHub.

# Sobre Git e GitHub

## Git
[Git](https://git-scm.com/) é um sistema Open Source de versionamento de código, desenvolvido para aguentar projetos de pequenos a grandes, com velocidade e efiência. Serve basicamente para que vários programadores (Sejam de Ciência da Computação ou Design) trabalhem no mesmo projeto, sem que tudo vire uma grande bagunça. [Um tutorial mais completo pode ser encontrado aqui.](https://try.github.io/levels/1/challenges/1)

## GitHub
[GitHub](https://github.com/) é uma plataforma de hospedagem de código fonte, com controle de versão Git. (GitHub é só uma das alternativas de hospedagem para códigos versionados com Git, outras delas são o [GitLab](https://gitlab.com/) e o [BitBucket](https://bitbucket.org/)).

Vale ressaltar que o GitHub possui um [programa educacional incrível](https://education.github.com/pack), com parceria com grandes outras empresas que fornecem licenças de softwares e créditos gratuitamente.


# Iniciando o ambiente

## Linux e Mac
Se você é usuário de Linux ou Mac, muito provavelmente você já tem o Git instalado no seu computador, basta apenas que você abra um terminal e digite: `git --version` caso o terminal responda com a versão do Git, você já tem o Git instalado.

## Windows
Se você é usuário Windows ~~(Mude para Linux agora!)~~, existem algumas opções possíveis, você pode [instalar o Git no CMD](https://git-scm.com/download/win) ou [instalar um terminal Linux no windows 10](https://docs.microsoft.com/en-us/windows/wsl/install-win10) onde a segunda é mais recomendada.

# O Exercício

## Faça um fork do repositório
Um fork é como que uma cópia do repositório original, todo repositório no GitHub é composto pelo `NomeDoUsuario/NomeDoRepositório`, neste caso especificamente o repositório é o `Abduzidos/LearnGit` onde abduzidos é o usuário e LearnGit é o repositório.

Para [criar um fork](https://guides.github.com/activities/forking/) basta clicar no botão de Fork no canto superior direito do cabeçalho do repositório, ao criar um fork, você cria uma cópia para si em `SeuUsuario/LearnGit`, onde você terá direito de escrita e leitura e pode editar à vontade na sua cópia do repositório.

Pronto, agora navegue pelo GitHub até o seu fork onde você tem write/read access.

## Faça um clone do seu fork
Um clone, de forma bastante simplificada, pode se considerar como "um download do seu repositório" que está hospedado no GitHub ("Nuvem", onde chamaremos de **Remoto**), para o seu computador (ao qual chamaremos de **Local**), [para fazer um clone](https://help.github.com/articles/cloning-a-repository/) clique no botão verde do seu repositório onde tem escrito `Clone or download`, então copie este link.

Abra o terminal e digite `git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY` substituindo ` https://github.com/YOUR-USERNAME/YOUR-REPOSITORY ` pelo link que você copiou.

Se tudo deu certo, agora seu repositório está disponível no seu computador (local), você pode digitar ls para listar os arquivos, para entender melhor como navegar no terminal [este tutorial ensina CLI de forma prática](http://rik.smith-unna.com/command_line_bootcamp/?id=jxxppxvp5ek), então navegue para dentro da pasta utilizando o comando `cd LearnGit`

## Edite o arquivo
Dentro do seu clone, existe um arquivo chamado `aboutClass00.md`, abra-o utilizando um editor de texto, o próprio GitHub mantém o [Atom](https://atom.io/), um editor de texto Open Source, então observe as instruções do arquivo e os exemplos inseridos, siga os passos e aplique você mesmo neste arquivo. Perceba que neste arquivo os textos devem estar em Inglês, pois os mesmos podem ser utilizados futuramente para outros propósitos. 

## Faça um commit
Então agora que você salvou suas mudanças no editor de texto, no terminal digite: `git add aboutClass00.md` para adicionar o arquivo às mudanças a serem commitadas, e então digite: `git commit -m "Adding myself to aboutClass00.md"` para adicionar sua mensagem de modificação do arquivo, por fim digite: `git push` para enviar seus commits locais (no seu computador) para o remoto (no servidor do GitHub), então digite o seu nome de usuário do GitHub e em seguida sua senha.

## Faça um Pull Request
Após ter feito um push com sucesso você deverá ver o seu commit no seu fork, então basta clicar no botão de [Pull Request](https://help.github.com/articles/about-pull-requests/) e submeter para a avaliação.

# Links Úteis
[Contribuindo para um projeto](https://git-scm.com/book/pt-br/v1/Git-Distribu%C3%ADdo-Contribuindo-Para-Um-Projeto)

[Do clone ao Pull Request](https://blog.da2k.com.br/2015/02/04/git-e-github-do-clone-ao-pull-request/)

[Lista de comandos](https://www.codecademy.com/articles/command-line-commands)

# Dúvidas? 
É natural que dúvidas surjam durante o processo, então para as eventuais dúvidas que possam surgir temos uma [thread issue](https://github.com/Abduzidos/LearnGit/issues/1) aberta onde você pode perguntar por lá e o mais rápido possível um colega deverá responder.

Prefere de outra forma? Você pode me procurar pelos corredores do Cesar School ou através do Slack!

