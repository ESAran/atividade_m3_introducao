	No primeiro quadrante do código são feitas as importações das bibliotecas, OpenCV tratando de processamento de imagem como manipulação de cores,
 reconhecimento e detecção de objetos, calibração de câmera, entre outros e NumPy, utilizada para computação numérica e manipulação de arrays, como estruturas,
 matrizes e vetores, juntamente com cáculos numéricos.
	Posteriormente no segundo quadrante são utilizadas algumas das funções presentes nas duas bibliotecas anteriores, começando com uma declaração 
 de uma variável "img" que recebe o valor vindo de uma função, que corresponde à imagem em grayscale. Logo em seguida mais duas varáveis, de img opening e closing,
 que recebe imagens similares a primeiras, mas com ruídos e furos respectivamente, também em gray scale. Extrai a altura e largura da imagem e define um Kernel, que 
 posteriormente pode ser aplicado para diversas operações nas imagens.
	No terceiro quadrante são utilizadas duas funções, erode e dialate, que geram o resultado das imagens após as aplicações de erosão e dilatação, enviando 
 como parâmetro a imagem, o kernel e a quantidade de vezes que a operação vai ser realizado. Erosão reduz o tamanho dos obejtos da imagem, reduzindo os pixels das 
 bordas enquanto dilatação aumenta o tamanho da imagem fazendo algo próximo ao contrário da erosão.
 Na próxima seção é utilizado a função morphology para realizar operações, sendo usada para diferentes finalidades nas 3 aplicações com o uso do kernel. A abertura 
 morfológica é realizada por uma erosão seguida de uma dilatação, enquanto o fechamento morfológico é realizado por uma dilatação seguida de uma erosão, sendo 
 salvos os resultados em suas respectivas variáveis. Posteriormente é utlizado uma função para mostrar cada imagem, para que possa ser possível 
 visualizar o resultado de cada operação.
