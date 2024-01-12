# Docker

O Docker é um software de código aberto escrito na linguagem [Go](https://github.com/golang/go) usado para implantar aplicativos dentro de containeres virtuais, que por sua vez rodam dentro de servidores físicos ou virtualizados. A conteinerização permite que vários aplicativos funcionem em diferentes ambientes complexos. 

Por exemplo: o Docker permite executar o WordPress em sistemas Windows, Linux e macOS fazendo poucas ou nenhuma configuração adicional para funcionar em diferentes Sistemas Operacionais.

Você pode ser levado a comparar containeres com máquinas virtuais. Não caia nessa! 

Embora o Docker e as máquinas virtuais tenham um propósito semelhante, seu desempenho, portabilidade e suporte a sistemas operacionais diferem significativamente.

A principal diferença é que os containeres do Docker compartilham o sistema operacional do host, enquanto as máquinas virtuais também têm um sistema operacional convidado sendo executado no sistema host. Esse método de operação afeta o desempenho, as necessidades de hardware e o suporte do SO. Confira a tabela abaixo para uma comparação detalhada.


|     | Docker | Máquina Virtual |
| --- | --- | --- |
| **SO**                            | SO compartilhado entre containeres             | Novo SO para cada MV
| **Segurança**                     | Menos seguro¹ porque o sistema operacional     | Mais seguro, pois as MVs não compartilham o sistema operacional
| **Desempenho**                    | Desempenho rápido mesmo com vários containeres | Mais máquinas virtuais equivalem a desempenho menos estável
| **Tempo de inicialização**        | Rápido (segundos)                              | Lento (minutos)
| **Necessidades de memória**       | Leve                                           | Requer muita memória
| **Necessidades de armazenamento** | Geralmente megabytes                           | Geralmente gigabytes 
| **Portabilidade**                 | Fácil de implantar em diferentes ambientes     | Difícil portar uma MV para outro sistema

1 -  Claro que há várias boas práticas para tornar uma aplicação em container mais segura. Mas essencialmente, as máquinas virtuais estão mais isoladas umas das outras e do sistema host do que os containeres. Isso ocorre porque as máquinas virtuais, não compartilham diretamente o kernel ou outros recursos com o sistema host.

**Fontes:**
- https://www.hostinger.com.br/tutoriais/o-que-e-docker
- https://www.weave.works/blog/a-practical-guide-to-choosing-between-docker-containers-and-vms
##
> [!NOTE]
> Esse tópico vai ter apenas dois links. Sim! e é tudo que você precisa 😉. O primeiro é um vídeo excelente do Fábio Akita caso você queria entender as entranhas dos containeres. O segundo é um vídeo que eu criei para o meu canal [DualBoot](https://www.youtube.com/@DualBootTech?sub_confirmation=1) no Youtube onde faço uma lista dos MELHORES CURSOS DE DOCKER NO YOUTUBE. Aprecie sem moderação hehe.
##
## Recursos de Estudo:
- [Entendendo Funcionamento de Containers](https://www.youtube.com/watch?v=85k8se4Zo70)
- [Os melhores cursos de docker do Youtube](https://youtu.be/pVVL0CM6eWg?si=_xqBSq594LkrnD2T)
