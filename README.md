# Automa-o-de-teste
Projeto de automação de testes com orientação DIO
Requisitos para BDD
- mavem
- ide
- VSCode
- jdk8
- projeto git
# O que é BDD
-Resolver processo calaborativo de envolve membros do mesmo time com perspectivas diferentes.Visa entegrar a regra de negócio com linguagem além da programação visa um passo além do BDD
# Estrutura de (Gherkin):
# -Fucionalidade: Realizar a compra no E-commerce
Como um comprador quero ver a lista de produtos disponiveis para que eu possa escoljer qual devo comprar.
# Cenário acionar produto ao carrinho
 Dado ( * que um usuario acesse o site "https://automationpractice.com")
 E (* pesquise pelo produto "Blouse")
 Quando (*adicione o produto "Blouse" ao carrinho)
 Então (* o produto "Blouse" deve etar no carrinho)
 Script com critérios de aceite.
 