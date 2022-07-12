# banknote_authentication
Exercício do curso OUTSPOKEN MARKET do professor Leandro Guerra

## **DESCRIÇÃO**

Os dados foram extraídos de imagens que foram tiradas de espécimes semelhantes a notas de banco genuínas class = 1 e forjadas . class = 0Para a digitalização, foi utilizada uma câmera industrial usualmente utilizada para inspeção de impressão. As imagens finais continham 400 x 400 pixels. Devido à lente do objeto e à distância do objeto investigado, foram obtidas imagens em escala de cinza com resolução de cerca de 660 dpi. Ferramentas de transformação wavelet foram usadas para extrair características das imagens.

**FORMATO**

Um data frame com 1372 linhas e 5 variáveis.


**DETELHES**


- **vow**

Variação da imagem transformada wavelet (contínua)

- **sow**

Distorção da imagem transformada wavelet (contínua)

- **kow**

Curtose da imagem transformada wavelet (contínua)

- **eoi**

Entropia da imagem (contínua)

- **class**

Inteiro especificando se o espécime era ou não genuíno ( class = 1) ou forjado ( class = 0).

**FONTE DOS DADOS**

Dua, D. e Graff, C. (2019). Repositório de aprendizado de máquina UCI [http://archive.ics.uci.edu/ml]. Irvine, CA: Universidade da Califórnia, Escola de Informação e Ciência da Computação.

