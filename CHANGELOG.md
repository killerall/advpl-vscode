## 0.7.8 
 - Melhoria: [Wizard de Criação de Ambiente] (https://github.com/killerall/advpl-vscode/pull/164)
 - Melhoria: [Mensagem validação ambiente selecionado] (https://github.com/killerall/advpl-vscode/pull/156)
 - Correção: [Mostrar mensagem no Output quando ocorre algum erro na compilação de pasta] (https://github.com/killerall/advpl-vscode/issues/159)

## 0.7.7
 - Melhoria: [Dar suporte a Debug em workspace com multiplas pastas] (https://github.com/killerall/advpl-vscode/issues/157)
 - Correção: [Ao compilar pasta e o Server esta fora esta dando SyntaxError] (https://github.com/killerall/advpl-vscode/issues/145)
 - Correção: [Error in 64 bits version] (https://github.com/killerall/advpl-vscode/issues/150)
 - Correção: [Mensagem de erro não é clara quando ambiente não está selecionado.] (https://github.com/killerall/advpl-vscode/issues/125)
 
## 0.7.6
 - Correção: Aplicação de patch em binario 64 bits
 
## 0.7.5
 - Correção:[Erro ao excluir fonte do repositório] (https://github.com/killerall/advpl-vscode/issues/128)
 - Melhoria:[Read authorization file and generate setttings] (https://github.com/killerall/advpl-vscode/issues/5)
 - Melhoria:[Último programa executado fica em branco depois de cancelar execução.] (https://github.com/killerall/advpl-vscode/issues/130)
 - Melhoria:[Implementada a sintaxe para highlight de uma classe REST em AdvPl.] (https://github.com/killerall/advpl-vscode/pull/129)
 - Documentação: [removida documentação que já existe na wiki] (https://github.com/killerall/advpl-vscode/pull/126)

## 0.7.4
- Correção: [Compilação  txt, depedendo do nome da pasta] (https://github.com/killerall/advpl-vscode/issues/120)
- Correção: Depuração Multi Thread as vezes caia no inicio.

## 0.7.3
 - Correção: Compilação de .prj e txt depois da versao 0.7
 - Correção: [Erro ao compilar antes do fim da compilação anterior] (https://github.com/killerall/advpl-vscode/issues/116)
 - Melhoria: [Criar comando para gerar ppo do Fonte] (https://github.com/killerall/advpl-vscode/issues/119)

## 0.7.2
 - Correção:[Criação de patch em ambiente local ] (https://github.com/killerall/advpl-vscode/issues/112) 

## 0.7.1
 - Correção da Messagem de Erro. SyntaxError: Unexpected end of JSON input.
 
## 0.7.0
- Melhoria: Para gerar path de uma lista de arquivo, agora basta clicar com o botao direito nele, e selecionar: Advpl - Patch - Build - Cria um patch Patch(PTM) da lista de arquivo.
- Melhoria: Velocidade da compilação de pastas, foi criado uma configuração a mais, para definir o numero de threads, o padrão é 4 (advpl.compile_threads)
- Melhoria: [Desfragmentar RPO] (https://github.com/killerall/advpl-vscode/issues/103)
- Correção: [Debug com problemas] (https://github.com/killerall/advpl-vscode/issues/106)
- Correção: [Seleção de ambiente] (https://github.com/killerall/advpl-vscode/issues/89)
- Correção: [Stop não encerra conexão iniciada via Shift+F5] (https://github.com/killerall/advpl-vscode/issues/98)

## 0.6.2
- [Correção no Debug na versão 11, não parava nos breakpoints] (https://github.com/killerall/advpl-vscode/issues/105)

## 0.6.1
- Correção no Debug, quando dava errolog debugando, o Debug aparentava estar travado.

## 0.6.0
- Refactory do Debug, para melhorias de performace e principalmente quedas quando se disparava o botão de step in, causando erros de sincronia com o appserver.
- [Implementar melhorias de performance no debug] (https://github.com/killerall/advpl-vscode/issues/90)
- Atualização do protocolo de debug do vscode
- Correção via Pull Request [ de Ctrl+F11] (https://github.com/killerall/advpl-vscode/pull/95)
- Melhoria via Pull Request : [Ajustes Package.json e Gramática - Condições e Agrupamentos de comandos de menu] (https://github.com/killerall/advpl-vscode/pull/91)
- Liberada versão MAC 

## 0.5.11
- Correção: Corrigido problema ao instalar a extensão com usuarios que tinham espaço no nome, que fazia que ao compilar não retorna se tinha compilado ou não.

## 0.5.10
- Correção: Corrigido compilação em ambientes que não são TOPConnect

## 0.5.9
- Melhoria: Possiblidade de usar uma lista de fontes para compilar. Para utilizar por exemplo o arquivo de patch. (Wiki) [https://github.com/killerall/advpl-vscode/wiki/Compila%C3%A7%C3%A3o-de-lista-de-arquivo]
- Correção: [Problema ao tentar gerar Patch Protheus ADVPL] (https://github.com/killerall/advpl-vscode/issues/92) , [Patch em rpo TTTS ] (https://github.com/killerall/advpl-vscode/issues/84) 
- Correção : [Patchs] (https://github.com/killerall/advpl-vscode/issues/52)

## 0.5.8
 - Correção: [Operadores lógicos - Syntax Highlighting] (https://github.com/killerall/advpl-vscode/pull/85)
 - Suporte ao servido de build 170117A , utilize a tag:   "serverVersion" : "170117A" dentro da configuracao do ambiente.

## 0.5.7
 - Correção: [Debug não para depois da atualização 1.11.0] (https://github.com/killerall/advpl-vscode/issues/82)

## 0.5.6
 - Correção: [Problema ao compilar após atualização 0.5.5] (https://github.com/killerall/advpl-vscode/issues/79)
 Esse erro ocorre quando o ini do protheus não consegue ser lido corretamente, portanto não atigiu todas as pessoas.


## 0.5.5
 - Melhoria: Performace gerais, tanto de compilação quanto debug.
 - Melhoria:[Possibilidade de configuração de novo parametro, para determinar se vai recompilar o fonte sem alteração ´compile_force_recompile´] (https://github.com/killerall/advpl-vscode/issues/75)
 - Melhoria: Novo comando para compilar os fontes de um projeto. Basta clicar com o botão direito sobre um arquivo prj, e selecionar compilar Projeto.
 - Melhoria: Adicionado informação de data e hora de inicio e fim de compilação.
 - Correção: [Identificação de Extensão APL] (https://github.com/killerall/advpl-vscode/issues/76)
 - Correção: [Error de compilação] (https://github.com/killerall/advpl-vscode/issues/74)
 
## 0.5.4
 - Ajuste do Package.json devido a atualização do VSCODE 1.10

## 0.5.2
 - Correção: [Gerar patch que nao existe a pasta] (https://github.com/killerall/advpl-vscode/issues/64)
 - Melhoria: [Implementar o inspetor de funções] (https://github.com/killerall/advpl-vscode/issues/71)
 - Melhoria: [Adicionar campos das tabelas no Debug] (https://github.com/killerall/advpl-vscode/issues/61)
 - Melhoria: [BreakPoint Condicional no Debug] (https://github.com/killerall/advpl-vscode/issues/40)
 - Melhoria: [Não é possível passar parâmetros ao lançar o smartclient] (https://github.com/killerall/advpl-vscode/issues/50)

## 0.5.1
 - [Congelamento ao compilar] (https://github.com/killerall/advpl-vscode/issues/70)

## 0.5
 - Refactory da parte de Syntax highlighting feito pelo [Izacsc] (https://github.com/killerall/advpl-vscode/pull/62)
 - Adicionado comando para excluir fontes do RPO.[Wiki] (https://github.com/killerall/advpl-vscode/wiki/Excluindo-fontes-do-RPO)
 - Aviso de chave de compilação expirada.

## 0.4.16
 - Adicionado a chave `name` dentro da configuração de `ambiente`, permitindo nomear um ambiente com um nome, que será utilizado
 no lugar do proprio ambiente na seleção de ambiente ativo. Essa chave é opcional.

## 0.4.15
 - Implementação da geração de [Client de WebService] (https://github.com/killerall/advpl-vscode/issues/63)  
 - Correção da messagem de compilação quando não tinha warning, não informava o sucesso.
 
## 0.4.14 
 - Correção do Patch Info quando a informação é muito grande.
 
## 0.4.12
 - Implementado opção de visualizar as informações num patch. Verifique na Wiki como [utilizar] (https://github.com/killerall/advpl-vscode/wiki/Trabalhando-com-Patchs)
 - Correção [Pressionar ESC na hora de informar o programa não cancela o debug.](https://github.com/killerall/advpl-vscode/issues/58)

## 0.4.10
 - [Melhora de Performance no Debug, quando temos muitos arquivos na workspace](https://github.com/killerall/advpl-vscode/issues/57)
 - Correção: [Todos os warnings aparecem num único warning](https://github.com/killerall/advpl-vscode/issues/56)
 - Inspetor de Objeto, agora é criado o rpoinfo.log com as informações do [rpo] (https://github.com/killerall/advpl-vscode/issues/44)

## 0.4.9
 - Correção da captura da exceção no debug. Quando algum errolog ocorria no debug, o mesmo parava e não [mostrava o erro.](https://github.com/killerall/advpl-vscode/issues/54)
 - [No show error when missing `includeList` config.](https://github.com/killerall/advpl-vscode/issues/51)
 - Exclusão dos arquivos de patchs temporarios, que por vezes provocavam geração de patch errado.
 - Preparação para o lancamento da versao 0.5 com language server
 
## 0.4.8
 - Liberação da versão MAC atualizada
 - Feito melhoria de perguntar se o usuario quer salvar o arquivo ao compilar, caso o mesmo não esteja salvo

## 0.4.6
 - Correção na aplicação de patch
 - Correção na compilação de pasta com apenas resources
 - Leitura do encoding no ambiente, para ser possivel compilar em 1251 e utf8 tambem.

## 0.4.5
 - Correção da validação de compilação

## 0.4.3
 - Correção da Correção;

## 0.4.2
 - Corrigido pequenos problemas;
 - Implementação inicial para disponibilizar a lista de fonte e resources do rpo.

## 0.4.1
 - Corrigido a geração de alguns IDs de cipth, que não deixa a extensão funcionar.
 - Liberado [Trazer última execução quando for debugar](https://github.com/killerall/advpl-vscode/issues/15)

## 0.4.0
 - Liberado a possibilidade de configuração de diversos Enviroments, adicionado possiblidade de seleção do ambiente atual;
 - Reconstrução do Launch agora com e sem Debug (Agora para executar o smartclient com as mesmas configurações 
 do debug, porem sem debugar, pode-se utilizar o ctrl+F5);
 - Correção de como o Debug se comportava em relação aos breakpoints, que causava quedas estranhas no debug.
 - Atualização da extensão para ultima versão do TypeScript;

## 0.3.8
 - Adicionado validação caso a string de include estiver errada.

## 0.3.7
 - Correção de colateral do colateral da 0.3.6
 - Correção [Warnings estão sendo exibidos como erro no output](https://github.com/killerall/advpl-vscode/issues/43)

## 0.3.6
 - Correção de colateral de não compilar da 0.3.5

## 0.3.5

 - Adiciona possibilidade de se visualizar as [tabelas](https://github.com/killerall/advpl-vscode/issues/37) e variáveis publics, statics, e privates no Debug 
 - Adicionado snipett de case via [pull request](https://github.com/killerall/advpl-vscode/pull/41) 
 - Correção de compilação com folders ou arquivos com [espaço no nome](https://github.com/killerall/advpl-vscode/issues/39) e [fonte não compila](https://github.com/killerall/advpl-vscode/issues/36)
 - Correção [Not showing error message when missing or wrong passwordCipher](https://github.com/killerall/advpl-vscode/issues/6)

## 0.3.4
 - Corrigido problema de compilação de folders quando tinha caracteres especias no nome da folder

## 0.3.3
 - Corrigido problema de compilação de folders

## 0.3.1
 - Liberado configuração para ignorar fontes não encontrados no debug

## 0.3.0
 - Liberado o debug multi Thread : [Não é possível debugar em múltiplas threads](https://github.com/killerall/advpl-vscode/issues/19)
 - Melhorias e correções no Debug Issues: [Debug não para em uma user function chamada sem interface na primeira tentativa de debug](https://github.com/killerall/advpl-vscode/issues/1) e [Debug not launch if breakpoints are disabled](https://github.com/killerall/advpl-vscode/issues/27)
 - Adicionado mais palavras chaves na Syntax highlighting, e feito a separação entre comandos e funções 

## 0.2.0
 - Liberada a funcionalidade de geração e aplicação de patch
 - Correção de pequenos problemas no eval do Debug

## 0.1.0

 - Liberação Alpha da versão em OSX, não é possivel compilar ainda, apenas debugar.
 - [Compilação de pastas](https://github.com/killerall/advpl-vscode/issues/18). Liberada a função de compilar um pasta inteira. Para utiliza, na barra lateral, escolha a pasta que deseja compilar, clique com o botão direito em Advpl - Compile Folder.
O comando iria compilar a pasta e suas sub-pastas, respeitando o Regex configurado em `compileFolderRegex`. 

## 0.0.10 

 - Corrigido a data e hora do fonte na compilação [23](https://github.com/killerall/advpl-vscode/issues/23)
 - Correção do Readme, a versão do server informada estava errada.
 - Melhorias de operadores na Syntax highlighting [24](https://github.com/killerall/advpl-vscode/pull/24)

## 0.0.9 

 - Alterado o lunch de debug, pois na versão liberada no VSCODE 1.5 caso carregue o valor padrão da rotina para se debugar, ele não chama o debug.
 - Por hora não ira sugerir nenhuma rotina
 - Corrigido a avaliação de arrays no watchs.

## 0.0.8 
 - Corrigido o caminho para o Debug  

## 0.0.7
Bugfixes:  
 - Compilação com caracteres especiais - [14](https://github.com/killerall/advpl-vscode/issues/14)  
 - Avaliar Array no Debug - [20](https://github.com/killerall/advpl-vscode/issues/20)  
Features:
 - Snippets adicionados : Das estruturas basicas do ADVPL  

## 0.0.6
 - Implementação do console Advpl - As Messagens da extensão são mostradas nele agora.
 - Padronização dos comandos. Todos começam com Advpl para facilitar a busca.
 - Inicio da implementação de geração de patch(nada funcional ainda).
 - Snippets adicionados : Protheus DOC
 - Correções significativas na parte de debug, Correção de Access Violation que o debug as vezes causava no server.

## 0.0.5  
 - Melhorias nas menssagens quando os diretorios da app esta errado  
 - Correção da issue [3](https://github.com/killerall/advpl-vscode/issues/3)  
 - Correção da issue [7](https://github.com/killerall/advpl-vscode/issues/7)  
 - Correção da issue [9](https://github.com/killerall/advpl-vscode/issues/9)  
 - Correção da issue [10](https://github.com/killerall/advpl-vscode/issues/10)  

## 0.0.4
 - Correção da issue [2](https://github.com/killerall/advpl-vscode/issues/2)

## 0.0.1
 - Versão inicial.
