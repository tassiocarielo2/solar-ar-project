# Projeto Solar AR - Júpiter

Este projeto utiliza realidade aumentada para exibir um modelo 3D de Júpiter quando a câmera reconhece uma imagem do planeta.

## Configuração

### 1. Preparar a imagem de Júpiter para reconhecimento

Você precisa criar um arquivo `jupiter-target.mind` que será usado para reconhecer a imagem. Você pode usar o MindAR Image Target Compiler para isso:

1. Visite: https://hiukim.github.io/mind-ar-js-doc/tools/compile/
2. Faça upload de uma imagem de Júpiter de boa qualidade
3. Clique em "Compile" e baixe o arquivo .mind gerado
4. Coloque o arquivo baixado como `jupiter-target.mind` na pasta raiz do projeto

### 2. Obter um modelo 3D de Júpiter

1. Você pode baixar modelos 3D de Júpiter em formato GLB/GLTF de sites como:
   - [Sketchfab](https://sketchfab.com)
   - [NASA 3D Resources](https://solarsystem.nasa.gov/resources/)
   - [TurboSquid](https://www.turbosquid.com)

2. Coloque o arquivo de modelo como `jupiter-model.glb` na pasta raiz do projeto.

3. Se necessário, ajuste os valores de `scale`, `position` e `rotation` no código HTML para adaptar o tamanho e orientação do modelo.

## Uso

1. Abra a aplicação em um dispositivo móvel
2. Permita o acesso à câmera
3. Aponte a câmera para uma imagem de Júpiter
4. Um modelo 3D do planeta será exibido sobre a imagem
