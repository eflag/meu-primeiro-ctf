# meu-primeiro-ctf
Repositório com dicas e instruções sobre como começar em um CTF.

Meu primeiro CTF é um guia sobre como se preparar e começar a jogar CTF. Se você já leu e começou a jogar ou já é um competidor assíduo de CTFs e gostaria de deixar mais alguma dica, por favor, abra uma issue ou um PR e passe seu conhecimento para frente.

## O que é CTF?

CTF ou Capture the flag, neste contexto, é uma competição de segurança da informação onde os competidores precisam usar seus conhecimentos da área, como engenharia reversa, criptografia, redes, exploração de binárias e análise web, para solucionar problemas e marcar pontos.

Os problemas são propostos no formato de desafios ou chall(do inglês, challenges) e ao final de cada chall, o participante encontra uma flag, por isso o nome, Capture the Flag.

## Conte mais sobre challs

Challs ou desafios, podem ser apresentados de vários modos a depender de sua categoria. Para categorias de criptografia e esteganografia, podem ser apenas um arquivo contendo texto, imagem ou informações. Para categorias como web, pwn, redes, pode ser apresentado como um servidor com domínio ou IP. E para categorias como engenharia reversa, exploração de binários, pode ser arquivos de aplicativos android, binários, arquivos java.

Categorias de challs:

Web, análise de servidores ou aplicações web.
Rev, reversing ou engenharia reversa.
Crypto, desafios de criptografia.
Net, análise de redes.
For, forensics, análise forense de arquivos ou logs de sistema.
PPC, professional programming and coding, desafios voltados à análise de código ou programa em geral.

## O que sao flags?

Quando você completa um desafio recebe um pequeno texto ou você precisa encontrar ele dentro do desafio. Geralmente este texto é bem diferente do contexto que ele está, ficando fácil de perceber quando você encontrar. Abaixo alguns exemplos de possíveis flags:

FfIiBbOoNnAaCcCcIi
M3U-PR1M31R0-D3S4F10

Geralmente é usado um prefixo para ficar mais identificável, por exemplo:
CTF-BR{M3U-PR1M31R0-D3S4F10}
PYBR2021{cHl0aG9uYnJhc2lsMjAyMQ==}

Possíveis lugares que podem contem uma flag: flag.txt, user.txt. Por isso, nunca esqueça de fazer uma busca pela palavra flag :D

## Tipos de CTF

CTFs podem ter varios modelos e as vezes misturar mais de um dele, segue uma lista dos seus tipos por prioridade dos quais mais acontecem normalmente:

### Jeopardy

Neste tipo de competição são propostos vários desafios, independentes uns dos outros, com peso de valores diferentes, 150, 200, 300, 500. O nome Jeopardy vem do programa de televisão americano parecido com o Show do Milhão, onde você escolhe quais perguntas você quer acertar para ganhar mais pontos, a diferença do CTF e que estas perguntas estão no formato de desafio.
![image](https://user-images.githubusercontent.com/5755568/136852396-6d6f3cc8-59d9-4e83-8e26-e7dc522d1755.png)


### KOTH - King of the Hill

Como o nome já diz, o rei da montanha são desafios de escalagem, mas em nosso contexto, não estamos falando da aventura radical de escalar uma montanha e sim escalar privilégios em uma maquina/servidor.
Neste desafio é entregue apenas uma maquina/servidor, onde os participantes precisam conseguir o acesso de um usuário comum do servidor e depois escalar os privilégios deste usuário até chegar no admin/root, quem chegar primeiro no topo de usuários, ganha. Quando este CTF é monitorado, ele não precisa de flags, quando não, as flags podem ser o nome e senha dos usuários.

### Attack/Defense

Uma das competições mais acirradas, neste tipo de CTF dois times recebem um servidor igual com várias vulnerabilidades, o objetivo dos times e arrumar as vulnerabilidades e proteger seu próprio servidor, enquanto isso os times tentam invadir o servidor do inimigo, ganha quem conseguir se proteger e ganhar acesso ao servidor inimigo.

## O que eu preciso para jogar um CTF?

Recomendamos o uso de algum sistema operacional Linux, pois muitas ferramentas de análise de segurança são desenvolvidas para linux, mas ainda sim, algumas das ferramentas mais conhecidas também tem suas versões para windows, basta você conhecer bem o seu sistema operacional e procurar por ferramentas similares.

Tanto para quem trabalha com segurança ou apenas compete em CTFs, o pessoal gosta de utilizar o sistema operacional Kali Linux ou ParrotOS, pois eles já vem com centenas de ferramentas para análise de segurança, mas quase todas podem ser baixadas em outros sistemas operacionais. Caso você queira utilizar o Kali como VM ou Docker, vamos deixar alguns links aqui em baixo:

https://www.kali.org/get-kali/
https://hub.docker.com/u/kalilinux/
https://www.parrotsec.org/
