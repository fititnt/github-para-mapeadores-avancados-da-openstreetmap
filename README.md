# github-para-mapeadores-avancados-da-openstreetmap
![img/vida-de-suporte.png](img/banner-vida-de-suporte.png)

**[RASCUNHO] Sugestões de pautas mínimas à voluntários de [suporte técnico](https://pt.wikipedia.org/wiki/Suporte_t%C3%A9cnico) para introduzir (ou atualizar) conhecimento a colegas que [já sabem muito bem como mapear no OpenStreetMap](https://www.openstreetmap.org/help) a também terem [proficiência em GitHub](https://docs.github.com/pt) para [lidar administração de organizações](https://docs.github.com/pt/organizations) e [publicação de conteúdo](https://pages.github.com/).**


---

<!-- TOC depthfrom:2 -->

- [Repositórios adicionais](#reposit%C3%B3rios-adicionais)
- [Pauta sugerida](#pauta-sugerida)
    - [Introdução](#introdu%C3%A7%C3%A3o)
        - [Conta pessoal](#conta-pessoal)
        - [Seguir e ser seguido simples](#seguir-e-ser-seguido-simples)
        - [Seguir outros da comunidade](#seguir-outros-da-comunidade)
        - [Página pessoal](#p%C3%A1gina-pessoal)
    - [Organizações](#organiza%C3%A7%C3%B5es)
    - [Automação](#automa%C3%A7%C3%A3o)

<!-- /TOC -->

---

<!--
## Publico alvo

O público alvo deste guia são pessoas dispostas a dar suporte 1 a 1 preferencialmente por videoconferência em seções curtas para ajudar com o ecossistema do GitHub para pessoas que já tenham proficiência com OpenStreetMap.
-->

## Repositórios adicionais

**Exemplos de projetos**
- https://github.com/fititnt/openstreetmap-exemplo-minimo-mapa-cidade
- https://github.com/fititnt/openstreetmap-exemplo-basico-mapa-unidade-federativa

**Exemplos de automação**
- https://github.com/fititnt/openstreetmap-github-actions

## Pauta sugerida

> Os tópicos aqui assumem que você está vendo a tela da pessoa, dá instruções e, quando necessário, auxilia para resolver imprevistos.

### 1. Introdução

#### 1.1. Conta pessoal

> Nota: procure levar até 10 minutos nessa etapa.

1. **Auxilie a pessoa a criar conta pessoal de usuário no GitHub**
    1. Se a pessoa já tem conta, ajude a recuperar acesso à conta antiga.
2. **Perfil de conta pessoal deve ter alguma foto em vez do padrão sem foto do GitHub.**
    1. Na dúvida, sugira reusar foto de alguma outra rede social da pessoa.
    2. Se a pessoa não quer usar foto pessoal (por exemplo, questões de privacidade), sem problema, então sugira escolher algo que ela goste.
3. **Perfil de conta pessoal deve ter local de onde ela é**
    1. Sugira colocar apenas o país, mas a pessoa pode colocar a cidade
4. **(Opcional) caso tenha uma descrição curta da pessoa pronta, diga que pessoa pode informar no perfil**
    1. Como há limite de tamanho ou a pessoa pode não saber o que escrever, pode pular essa etapa.
    2. Explique para pessoa que essa descrição pode ser usada por outros para saber quem ela é. Sugira pelo menos citar grupos ou iniciativas existentes da OpenStreetMap do país dela.
5. **Perfil da pessoa deve ter algum link para algum site externo**; se a pessoa não tiver opinião, sugira colocar link para o perfil pessoal da OpenStreetMap
    1. Em especial se o link colocado for do OpenStreetMap, diga para pessoa considerar no futuro editar perfil dela lá para informar o o link do GitHub que agora tem.
6. (Sugestões?)

#### 1.2. Seguir e ser seguido (simples)

1. **Você, que presta auxílio técnico, deve usar sua conta pessoal para seguir a pessoa.**
2. **Diga para pessoa visitar (ou atualizar) a própria página de usuário e mostre que algo (numero de seguidores) mudou**
3. **Explique para ela que outra conta de usuário a seguiu**
    1. Fale que GitHub é uma espécia de _"rede social para pessoas da área de tecnologia"_ sem dar muitos detalhes.
4. **Explique para pessoa como ela pode seguir outros ao seguir seu perfil de volta**
    1. Diga que a partir de agora, a página inicial de ambos (contexto: https://github.com/) passará a exibir ações algumas recentes que o outro faz.

<!--
2. **Avise a pessoa que ela recebeu uma notificação, sugira ver o que significa clicando no "sininho"**
    1. Contexto: o sininho leva para tela https://github.com/notifications.
-->

#### 1.3. Seguir outros da comunidade

> (...)

#### 1.4. Página pessoal

> - https://pages.github.com/

(...)

### Organizações

1. Crie uma organização com nome `teste-organizacao-000` onde `000` deve ser alterado
   1. Se <https://github.com/teste-organizacao-001> existir: crie <https://github.com/teste-organizacao-002>
   2. Se <https://github.com/teste-organizacao-002> existir: crie <https://github.com/teste-organizacao-003>
   3. E assim por diante. Apenas pegue um número livre
> (...)

### Automação

> Nota: esta etapa varia conforme o interesse do aluno.
> Pode usar <https://github.com/fititnt/openstreetmap-github-actions> como referência de qual action escolher.


---

# Texto original

> Remover isto no futuro.

```txt
Então, sábado 15 de outubro (amanhã/hoje) exceto horário das 16h, já vou começar com todo mundo fazendo 1 a 1. Periodo da tarde. Chamo no Hangout/Whatsapp/Skype seja o que for, mas tenho que ouvir a voz da pessoa e ver a tela do computador. Tempo médio: de 20 a 40 minutos (se precisar mais, vai outras secções curtas). Minha ideia é começar com pessoal que já é ativo na OSM mas não sabe github.

Pauta:

1. Criar conta de GitHub; ter fotinho, descrição curta, e aprender seguir os os colegas.
2. Aprender GitHub pages (hxxps//seu-usuario.github.io)
3. Saber criar organização de GitHub (cria-se uma de teste); como dar permissões para membros por organização e por repositório)
4. Aprender editar arquivos via interface web do GitHub e via hxxps://github.dev/ (abre um VS Codes no navegador)

Coisas que não vão estar na primeira leva:

1. GitHub Actions. Até posso citar, mas o ideal é explicar como copiar, dar fork etc.

A diferença desse 1 a 1 para fazer apresentação é que é mais fácil não só para vocês, mas para quem ajuda. Isso é parecido com suporte técnico "avançado" (tipo suporte de computador, só que online): pode até ter documentação e vídeo, mas a pessoa pode travar por causa que um problema como antivírus dela (ou sem querer digitar site errado) leva numa tela diferente; daí que ver ao vivo é mais rápido do que explicar por texto.
```
