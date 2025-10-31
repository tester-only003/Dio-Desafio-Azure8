# GERENCIAMENTO E GOVERNANÇA NA AZURE

## Gerenciamento de Custos na Azure

*Como conseguimos ter uma previsibilidade de quanto vai sair a conta.*  
<br> 
*Como determinar a melhor estratégia para uma migração de serviço, por exemplo.*
<br>
<br>

  - Descrever fatores que podem afetar os custos do Azure.

  - Compare a calculadora de preços com a calculadora de custo total de propriedade (TCO).

  - Descreva a Ferramenta de Gerenciamento de Custos do Azure.

  - Descrever a finalidade das marcas.

<br>

- Calculadora de Custos e Preços.
- Gerenciamento de Custos e Marcas.

<br>

### Fatores que afetam os Custos


### 1 - Tipo de Recurso
(Finalidade do recurso) <br>
**Os custos são específicos do recurso**, portanto, o uso que um medidor rastreia e o número de medidores associados a um recurso, irão depender do tipo de recurso.

<br>

### 2 - Consumo
Com um modelo pago conforme o uso, o consumo é um dos maiores geradores de custos.

<br>

### 3 - Manutenção
Monitorar seu volume do Azure e manter seu ambiente pode ajudá-lo a identificar e reduzir os custos que não são necessários, como ao desligar máquinas virtuais subutilizadas.

<br>

### 4 - Área Geográfica
O mesmo tipo de recurso pode custar valores diferentes dependendo da área geográfica, o que afeta os custos do Azure.

 > Um dos fatores responsáveis pela diferença de valor de um mesmo serviço em regiões diferentes, é o imposto sobre o produto / serviço.

<br>

### 5 - Tráfego de Rede
Embora algumas transferências de dados de entrada sejam gratuitas, o custo para dados de saída ou dados entre recursos do Azure é afetado por zonas de cobrança.

  **Exemplo:** <br>
    *Fazer a migração do ambiente on-premises para a nuvem.
     Ao levar os dados para a nuvem não há cobrança sobre os mesmos.
     Contudo, se eu quiser levar os dados para outra região (fora do país) será gerado um tráfego de rede (entre regiões). Logo tenho que avaliar quanto irá sair esta conta.*
    <br>
    <br>
    *(outro exemplo) Uma aplicação que se comunica em diversos pontos.*

<br>

### 6 - Assinatura
O tipo e a configuração da assinatura também podem afetar o custo. <br>
Por exemplo, a avaliação gratuita permite explorar alguns recursos do Azure gratuitamente.
<br>

*(outro exemplo) Uma grande empresa que vai utilizar seus serviços no Azure, pode ganhar créditos em alguns serviços.*

<br>

### Explorar o Azure Marketplace
O Azure Marketplace permite que os clientes encontrem, experimentem, comprem e provisionem aplicativos e serviços de centenas de provedores de serviços líderes, que são todos certificados para execução no Azure.
<br>

- Plataformas de contêineres de software livre.
- Imagens da máquina virtual e do banco de dados.
- Software de compilação e implantação de aplicativos.
- Ferramentas para desenvolvedores.
- E muito mais, com mais de 10.000 itens listados!

<br>

> ***Quando nós adicionamos um recurso não nativo do Azure em nosso ambiente, caso ele apresente algum problema e nós precisemos entrar em contato com o suporte, o suporte que devemos procurar não é da Microsoft mas sim o suporte do fabricante / desenvolvedor.***

<br>

### Calculando o Custo Total no Azure

#### Calculadora de Preços

[https://azure.microsoft.com/pt-br/pricing/calculator/](https://azure.microsoft.com/pt-br/pricing/calculator/)
<br>

- Importante lembrar que a calculadora traz uma estimativa e não o valor exato que será cobrado
<br>

   <div align="center">
       <img width="920" height="412" alt="Calculadora-1" src="https://github.com/user-attachments/assets/62235f74-6c04-4c08-a29c-9f1ecca6f433" />
   </div>

<br>
A calculadora de preços é uma ferramenta que ajuda a estimar o custo dos produtos do Azure.
As opções que você pode configurar na calculadora de preços variam entre os produtos, mas as opções básicas de configuração incluem:
<br>

   - Região
   - Camada
   - Opções de cobrança
   - Opções de suporte
   - Programas e ofertas
   - Preço de Desenvolvimento / Teste do Azure

<br>

#### Calculadora de Custo Total de Propriedade (TCO)

  - Uma ferramenta para estimar a economia de custos possíveis ao migrar para o Azure.
  - Um relatório compara os custos das infraestruturas locais com os custos de uso de produtos e serviços do Azure na Nuvem.
<br>

   <div align="center">
       <img width="880" height="237" alt="TCO-1" src="https://github.com/user-attachments/assets/7120e50b-7dff-4403-84f4-256982f30cfe" />
   </div>

<br>
<br>

   <div align="center">
       <img width="797" height="391" alt="TCO-2" src="https://github.com/user-attachments/assets/6ee502a8-58be-433c-9720-d5ddb9d1b4a6" />

   </div>

<br>

#### Gerenciamento de Custos do Azure
   - Relatórios de cobrança
   - Enriquecimento de dados

   *No gerenciamento de custos podemos colocar alertas quando alguma coisa estiver fora do normal.*
<br>

   - Orçamentos: definir Orçamentos de gastos.

   - Alertas: quando o custo excede os limites.

- Recomendação: recomendações de custo.
<br>

   <div align="center">
       <img width="634" height="415" alt="Azure-Pass-1" src="https://github.com/user-attachments/assets/9055e40b-54a4-4c7d-bd7d-554e902c79a3" />
   </div>

<br>

#### Marcas (Tags) no Azure
*Não são obrigatórias.* <br>
*Não são herdáveis.*

<br>

- Fornecem metadados aos recursos do Azure.
- Organizam os recursos em uma taxonomia de maneira lógica.
- Consistem em um par nome-valor.
- Muito úteis para reunir informações de cobrança.

<br> 

   <div align="center">
       <img width="434" height="361" alt="Tags-1" src="https://github.com/user-attachments/assets/6cd8568f-9435-4859-bf88-98713331bad9" />
   </div>









