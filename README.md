# O que são Media Queries?

Media query, nada mais é do que uma estrutura do CSS que permite aplicar estilizações especificas para uma página web de acordo com certas condições, fazendo assim com esta página possa se adequar ao layout de tela em diferentes tamanhos e tipos de mídia.

# Tipos de media ou Media types

Sua funcionalidade serve para direcionar determinado CSS para um meio específico de dispositivo, ou seja, definem para qual tipo de media, o CSS que você aplica em seu site será direcionado.

Existem vários media types, aqui, citarei alguns:

print: Para impressoras;

# Media features no media query

Um media feature é a largura da janela do documento, normalmente usado para atribuir uma condição que vai testar se o que foi definido é verdadeiro ou falso, ou seja, são elementos do CSS que atribuídos a estrutura do media para exibir quando a estilização sofrerá modificação.

De forma simplificada, podemos destacar alguns:

orientation
width
height
O orientation possui dois possíveis valores, os quais são portrait e landscape, onde o primeiro define a orientação em retrato, ou seja, se a altura é maior ou igual à largura e o segundo, orientação paisagem seguindo o mesmo resultado citado antes

Já o width define a largura do elemento na horizontal. E por último o height que define a altura do elemento na vertical.

Muitos media features podem ter prefixado min- ou max-, ou seja, servem para definir a largura mínima ou máxima de uma condição, assim definindo se nossas estilizações serão aplicadas conforme o tamanho da tela. Vamos ver alguns exemplos:

