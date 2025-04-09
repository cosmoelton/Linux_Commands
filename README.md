# 🚀 Linux_Commands

##  Sobre mim: 
#### Meu nome é Cosmo Elton, seu sou profissional de tecnologica atuando na aréa de suporte, Sysadmin em sistema LINUX, tentando evoluir para Cloud, Devops Enginee e Desenvolvimento.

##### Vamos fazer network? Conecte-se...
##### Shall we network? Contact.

Vou postar uns comandos os que mais utilizado do meu dia dia, em Linux para ajudar outros Sysadmin, pois vejo que muitas pessoas tem dificuldade em sistemas UNIX, caso alguém use um comando que não está na lista pode comentar,servirá pra troca de ideias.

###### COMANDO MV - movimenta (renomeia) os arquivos.

###### SINOPSE       mv [OPÇÃO]... [-T] ORIGEM DESTINO
       mv [OPÇÃO]... ORIGEM... DIRETÓRIO
       mv [OPÇÃO]... -t DIRETÓRIO ORIGEM...

###### DESCRIÇÃO
       Renomeia ORIGEM para DESTINO ou move ORIGEM(ns) para DIRETÓRIO.

       Argumentos obrigatórios para opções longas também o são para opções curtas.

       --backup[=CONTROLE]
              faz uma cópia de segurança de cada arquivo de destino já existente

       -b     como --backup, mas não aceita argumentos

       -f, --force
              não pergunta antes de sobrescrever

       -i, --interactive
              pergunta antes de sobrescrever

       -n, --no-clobber
              não sobrescreve um arquivo existente

       Se você especificar mais que um dentre -i, -f ou -n, apenas o último terá efeito.

       --strip-trailing-slashes
              remove quaisquer barras ao final de cada argumento ORIGEM

       -S, --suffix=SUFIXO
              sobrescreve o sufixo comum de cópia de segurança

       -t, --target-directory=DIRETÓRIO
              move todos os argumentos ORIGEM para o DIRETÓRIO

       -T, --no-target-directory
              trata DESTINO como um arquivo normal

       -u, --update
              move somente quando o arquivo de ORIGEM for mais novo do que o de destino ou quando o arquivo de destino não existe

       -v, --verbose
              explica o que está sendo feito

       -Z, --context
              define o contexto de segurança SELinux do arquivo de destino para o tipo padrão

       --help mostra esta ajuda e sai

       --version
              informa a versão e sai

       O  sufixo  de  cópia  de  segurança  é  "~",  a  não  ser  que esteja definido --suffix ou SIMPLE_BACKUP_SUFFIX. O método de controle de versão pode ser definido com --backup ou a variável de ambiente
       VERSION_CONTROL. Os valores possíveis são:

       none, off
              nunca faz cópias de segurança (mesmo se --backup for especificado)

       numbered, t
              faz cópias de segurança numeradas

       existing, nil
              numeradas se já existirem cópias de segurança numeradas, simples em caso contrário

       simple, never
              sempre faz cópias de segurança simples

AUTOR
       Escrito por Mike Parker, David MacKenzie e Jim Meyering.

       RELATANDO PROBLEMAS
       Página de ajuda do GNU coreutils: <https://www.gnu.org/software/coreutils/>
       Relate erros de tradução para <https://translationproject.org/team/pt_BR.html>.

DIREITOS AUTORAIS
       Copyright © 2022 Free Software Foundation, Inc. Licença GPLv3+: GNU GPL versão 3 ou posterior <https://gnu.org/licenses/gpl.html>.
       Este é um software livre: você é livre para alterá-lo e redistribuí-lo. NÃO HÁ QUALQUER GARANTIA, na máxima extensão permitida em lei.

VEJA TAMBÉM
       rename(2)

       Documentação completa: <https://www.gnu.org/software/coreutils/mv>
       ou disponível localmente via: info '(coreutils) mv invocation'



