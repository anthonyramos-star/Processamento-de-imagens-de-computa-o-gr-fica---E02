🧠 Sistema de Análise de Padrões em Imagens

🎯 Objetivo do módulo desenvolvido
O projeto tem como objetivo realizar **análises automáticas em imagens**, extraindo informações sobre **textura, formas geométricas, complexidade e propriedades visuais**.  
Ele permite converter imagens, detectar bordas, binarizar, calcular métricas estatísticas (como entropia e homogeneidade), gerar relatórios e identificar figuras geométricas a partir de um arquivo JSON de referência.



🧩 Bibliotecas utilizadas
O código utiliza as seguintes bibliotecas Python:

- **OpenCV (`cv2`)** → leitura, conversão e processamento de imagens.  
- **NumPy (`numpy`)** → operações matemáticas e manipulação de matrizes.  
- **Matplotlib (`matplotlib.pyplot`)** → geração de gráficos e exibição de resultados.  
- **Scikit-Image (`skimage.feature`, `skimage.measure`)** → cálculo de métricas de textura e entropia.  
- **JSON (`json`)** → leitura de configurações e dicionários de formas geométricas.  
- **OS (`os`) e Time (`time`)** → manipulação de arquivos e controle de execução.  


⚙️ Instruções de execução

🔧 Pré-requisitos
Certifique-se de ter o **Python 3.8+** instalado e as bibliotecas necessárias.  
Você pode instalar todas com:
```bash
pip install opencv-python numpy matplotlib scikit-image
