# Tradutor-de-Lingaguem-de-Sinais
Projeto para promover a inclusão e a comunicação entre pessoas surdas e ouvintes.

Desenvolvi um programa em Python utilizando a biblioteca TensorFlow. Esse programa tinha a capacidade de reconhecer
sinais da linguagem de sinais da Libras e, em tempo real, traduzi-los na tela.

Passo 1: Executando o `criar_fotos.py`
1. Abra o arquivo `criar_fotos.py` no seu editor de código.
2. Verifique se todas as dependências necessárias estão instaladas. Caso não estejam, você pode instalá-las usando o gerenciador de pacotes do Python, como o `pip`.
3. Execute o script `criar_fotos.py` para gerar as fotos dos gestos do alfabeto de Libras. Certifique-se de que sua câmera esteja funcionando corretamente e esteja posicionada adequadamente para capturar os gestos.
4. Durante a execução do script, siga as instruções para realizar os gestos das letras do alfabeto de Libras. Esses gestos serão capturados pela câmera e salvos como imagens para uso posterior.
5. Aguarde até que o script termine de capturar o número necessário de fotos para treinamento e teste.

Passo 2: Executando o `treinar_modelo.py`
1. Abra o arquivo `treinar_modelo.py` no seu editor de código.
2. Verifique se todas as dependências necessárias estão instaladas. Caso não estejam, você pode instalá-las usando o gerenciador de pacotes do Python, como o `pip`.
3. Certifique-se de que as fotos geradas pelo script anterior estão disponíveis no local correto ou atualize o caminho das imagens no arquivo `treinar_modelo.py`, se necessário.
4. Execute o script `treinar_modelo.py` para treinar o modelo de reconhecimento de gestos de Libras. O algoritmo de treinamento utilizará as fotos geradas anteriormente para aprender a reconhecer os gestos corretamente.
5. Aguarde até que o treinamento seja concluído. Esse processo pode levar algum tempo, dependendo do tamanho do conjunto de dados e da complexidade do modelo.

Passo 3: Executando o `main.py`
1. Abra o arquivo `main.py` no seu editor de código.
2. Verifique se todas as dependências necessárias estão instaladas. Caso não estejam, você pode instalá-las usando o gerenciador de pacotes do Python, como o `pip`.
3. Certifique-se de que o modelo treinado está disponível no local correto ou atualize o caminho do modelo no arquivo `main.py`, se necessário.
4. Execute o script `main.py` para iniciar o programa principal.
5. O programa `main.py` utilizará o modelo treinado para reconhecer os gestos da sua mão imitando as letras do alfabeto de Libras em tempo real, com base nas imagens capturadas pela câmera.
6. Verifique se a câmera está funcionando corretamente e posicione sua mão adequadamente para que os gestos sejam corretamente capturados e reconhecidos.
7. O programa exibirá a letra de Libras reconhecida no console ou em uma interface gráfica.
