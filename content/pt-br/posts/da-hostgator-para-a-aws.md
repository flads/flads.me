---
title: "Da Hostagor Para a AWS"
date: 2021-03-25
description: "Trago nesta postagem minhas experiências com esses dois provedores de hospedagem e porquê prefiro o último."
draft: false
hideToc: false
enableToc: true
enableTocContent: false
author: flads
tags:
    - hospedagem
    - provedores de hospedagem
    - desenvolvimento de software
    - hostgator
    - aws
pinned: false
---

Lembro bem quando comecei a desenvolver sites, o serviço de hospedagem que comecei a usar foi o plano compartilhado da Hostgator, hospedagem fácil com o cpanel, usando o tão famigerado FTP e com alguns serviços já inclusos, como servidor de e-mail, certificado SSL e backup automático.

Para um iniciante na área de desenvolvimento pra web é muito útil, ajuda bastante. Você não precisa se preocupar com muitas coisas e em poucas horas já tem seu site disponível na web. Entretanto, se existem esses pontos positivos, existem outros negativos que se sobressaem.

Um servidor de hospedagem compartilhada, pelo menos os com preços mais acessíveis e que mais são contratados, possuem limitações para projetos que estão crescendo. Os recursos do servidor são divididos com outros usuários, se a aplicação de algum desses usuários for comprometida, você corre um grande risco de sofrer também. Todos os servidores que tive acesso possuíam uma lentidão enorme, ainda mais considerando que rodavam um projeto wordpress que precisa constantemente estabelecer conexão com o banco de dados. Um site estático rodaria até de forma razoável, mas se fosse acessado por muitas pessoas, o risco de ficar fora do ar seria grande.

Outro ponto negativo que acho dos servidores compartilhados são a falta de liberdade na utilização de determinados softwares. Certa vez precisei utilizar um servidor Nodejs e não pude. Era oferecido basicamente uma pilha LAMPP.

Mas tudo melhorou quando conheci a AWS. Já ouvia falar bastante de nuvem e da ideia de pagar somente pelo que usar.

Quando entendi que a AWS me permitia ter uma máquina totalmente customizável e que eu poderia ter isso de forma gratuita por 1 ano, achei fantástico. Existe somente um serviço pelo qual pago até hoje, que é o servidor de DNS Route 53, porém é uma taxa quase insignificativa.

A rapidez e a liberdade é o que mais gosto nesse tipo de tecnologia. E quando uma empresa disponibiliza seu serviço para que possamos testar e utilizar, até para projetos da vida real, é melhor ainda.

Para mais detalhes sobre o nível gratuito da AWS: https://aws.amazon.com/pt/free/ .
