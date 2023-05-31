<div align="center">
 
  # Problem Set 1
 
</div>

#### Aluno: Luis Henrique Gomes Zortea | Curso: Ciência da Computação | Turma: CC3M | Professor(a): Abrantes Araújo Silva Filho 

## Questões
- #### Questão 01 
> Se você passar essa imagem pelo filtro de inversão, qual seria o output esperado? Justifique sua resposta.

 O resultado será: [226, 166, 119, 200].

- #### Questão 02
> Faça a depuração e, quando terminar, seu código deve conseguir passar em todos os testes do grupo de teste TestInvertida (incluindo especificamente o que você acabou de criar). Execute seu filtro de inversão na imagem test_images/bluegill.png, salve o resultado como uma imagem PNG e salve a imagem em seu repositório GitHub.

![bluegillinvertido.png](https://github.com/LuisHZortea/uvv_lp_cc3m/blob/main/Imagens/bluegillinvertido.png)

- #### Questão 03
> Considere uma etapa de correlacionar uma imagem com o seguinte kernel:
0.00 -0.07 0.00
-0.45 1.20 -0.25
0.00 -0.12 0.00
>Aqui está uma parte de uma imagem de amostra, com as luminosidades específicas de alguns pixels:

>Qual será o valor do pixel na imagem de saída no local indicado pelo destaquevermelho? Observe que neste ponto ainda não arredondamos ou recortamos o valor, informe exatamente como você calculou. Observação: demonstre passo a passo os cálculos realizados.
- #### Questão 04
> Quando você tiver implementado seu código, tente executá-lo em test_images/pigbird.png com o seguinte kernel 9 × 9. Ao rodar esse kernel, salve a imagem resultante em seu repositório GitHub.

- #### Questão 05
> Se quisermos usar uma versão desfocada B que foi feita com umkernel de desfoque de caixa de 3 × 3, que kernel k poderíamos usar para calcular toda a imagem nítida com uma única correlação? Justifique sua resposta mostrando os cálculos.

- #### Questão 06
> Explique o que cada um dos kernels acima, por si só, está fazendo. Tente executar mostrar nos resultados dessas correlações intermediárias para ter uma noção do que está acontecendo aqui. Implemente o detector de bordas como o método bordas dentro da classe Imagem. O método deve retornar uma nova instância de Imagem resultante das operações acima. Quando terminar e seu código passar nos testes de detecção de borda, execute seu detector de borda na imagem test_images/construct.png, salve o resultado como uma imagem PNG e faça o upload para seu repositório GitHub.

