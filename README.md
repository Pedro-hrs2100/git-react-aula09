1. Importar biblioteca:
import React, { useState } from 'react';: Importe as funções React e useState para criar e gerenciar o estado do componente.
import { Media } from 'reactstrap';: Importe o componente Media do Reactstrap, o que facilita a criação de layouts responsivos no React usando Bootstrap.

2. Defina os componentes do menu:
O componente Menu é uma função que retorna a estrutura HTML da página.
Dentro do componente, o gancho useState é usado para armazenar uma lista de pratos (chamados de pratos).

3. Crie um cardápio:
As constantes do menu são geradas usando a função .map(), que percorre a lista de pratos e cria um conjunto de elementos HTML.
Cada prato é representado por uma <div> com classes para organizar o layout.
Dentro do <div> , o componente Media do Reactstrap é usado para exibir:
Imagem do prato à esquerda (<media left center>).
Nome e descrição do prato à direita (<texto da mídia>).

4. Atualização da Página:
O componente fornece uma estrutura HTML que contém um container (uma área central).
Em uma linha, os pratos são organizados e mostrados como uma lista utilizando a <Media list>.


5. Organização dos Pratos:
Cada porção inclui:

Id: Número exclusivo do prato.

Nome: Título do prato.

Imagem: Rota da imagem da refeição.

categoria: Tipo de prato (por exemplo, "principal", "appetizer").

etiqueta: Etiqueta especial (como "Quente", "Novo").

Preço: Valor do prato.

descrição: Descrição da refeição.

6. Conclusão Final:
Ao ser exibido, o componente exibe:

Uma lista de refeições, cada uma contendo:
Imagem localizada à esquerda.
Em destaque está o nome do prato.
Descrição do prato na imagem ao lado.

7. Comercialização:
O componente Menu é exportado ao término, possibilitando seu uso em outros locais do código.
