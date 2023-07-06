# Problema de três corpos - Introdução à computação em física
Nesse repositório, é possível encontrar cinco arquivos: um arquivo .ipynb que apresenta o primeiro método explicado na
seção anterior, chamado de problema-de-três-corpos-odeint.ipynb; um arquivo .ipynb que apresenta o segundo método explicado na seção anterior, chamado de problema-de-três-corpos-euler-vpython.ipynb; um
arquivo README.md em branco; um arquivo .gif que demonstra um resultado do segundo método; esta
documentação. Ambos arquivos possuem os mesmo valores iniciais, permitindo que o usuário escolha
entre a opção 1 de velocidade inicial ou a opção 2 de velocidade inicial. A posição inicial é fixa para uma
melhor demonstração das trajetórias. Se o usuário desejar mudar os dados iniciais manualmente para ver
o resultado, é de extrema importância analisar se as velocidade estão fazendo os corpos se aproximarem
ou distanciarem, porque, se os vetores da posição inicial e velocidade inicial forem opostos, não haverá
interação aparente. Também, se as velocidades iniciais forem valores muito altos, os corpos escapam de
seus campos gravitacionais rapidamente, não havendo interação aparente (é aconselhado que utilize valores próximos entre −0.01 m/s e 0.01 m/s para as velocidade iniciais). Para uma melhor visualização das
interações e trajetórias de cada corpo, ao final do código é possível baixar um arquivo .gif que mostra as
posições em um período de tempo, deixando a opção anima.save() não comentada. Se preferir por uma
visualização dentro do próprio código, deve-se comentar a opção anterior e deixar a linha que inicia com
HTML não comentada. Para animar o gráfico dentro do código ou baixá-lo, é levado cerca de dois minutos.
OBS.: É necessário reiniciar o kernel toda vez que for executar o código, pelo fato de os valores serem
concatenados numa lista, ao invés de serem resetados. Dessa maneira, para uma melhor performance do
código em seu computador e para que não acumulem 1 milhão de pontos para serem plotados, por favor,
reinicie o kernel.
