# desafio_profissional_dw_pos


<h2>1. Caso - Novos Fatos de Data Marts para Agripoli Brasil</h2>
   
<h3> <p>A distribuidora de insumos químicos agrícolas, Agripoli Brasil, está há trinta e cinco anos no
mercado brasileiro, em Cuiabá, estado do Mato Grosso, atuando com fornecedores, produtores
rurais, revendas e cooperativas, na venda de defensivos e fertilizantes. Dos 409 distribuidores/
comerciantes cadastrados pelo Órgão Estadual de Defesa Sanitária Vegetal (OEDSV) do Mato
Grosso, a Agripoli Brasil é a terceira maior distribuidora do estado, representando
aproximadamente 9% do total das vendas nacionais de insumos químicos agrícolas, em 2018.
Nas instalações da empresa, o setor de Tecnologia da Informação e Comunicação (TIC) é
denominado de Núcleo de Tecnologia da Informação (NTI). O NIT apoia, integra e flexibiliza as
atividades operacionais e estratégias de todos os níveis funcionais da empresa. É constituído por
uma equipe de profissionais responsáveis pelo suporte de toda infraestrutura tecnológica de rede e
pelo sistema de Business Intelligence (BI), implantado recentemente, que é mantido em quatro
servidores locais e sob contingência de réplica contínua em ambiente datacenter Tier 3
terceirizado, com contratos firmados em nível de serviço para recuperação e ajuste, no padrão
vinte e quatro horas por dia e sete dias por semana.
O projeto do BI despendeu um longo período de desenvolvimento, pois a empresa mantinha sistemas
legados, sistemas de informação e sistemas de gestão em diversos bancos de dados e em demais
fontes de armazenamento. No BI, a arquitetura do Data Warehouse é do tipo global centralizada com
implementação bottom-up dos Data Marts.
Os Data Marts de marketing, financeiro, compra e venda constantemente estão sendo
incrementados com novas funcionalidades (fatos) e manipulados com as ferramentas On-line
Analytical Processing (OLAP) e de Data Mining, diante das necessidades dos usuários analistas e
estratégicos. </p></h3>
</br>
</br>
<h2>3. Papel do aluno e sua participação na resolução do problema.</h2>

<h3> <p>Você, como profissional de TI, e gestor da informação da Agripoli Brasil, precisa atender uma
solicitação do diretor de vendas da empresa, para projetar duas novas funcionalidades do Data Mart
de vendas, sendo:
1. Vendas realizadas pelos representantes para os produtores rurais por localização e período.
2. Vendas realizadas pelos vendedores para os revendedores por localização e período.
Considere algumas regras de negócio dos bancos de dados transacionais:
• Quanto aos produtos: um produto possui nome; descrição, tipo do produto (defensivos ou
fertilizantes); categoria (exemplo correspondente ao tipo defensivo: herbicidas, fungicidas,
inseticidas, acaricidas etc); marca (exemplo: Syngenta, Bayer, Basf, Dow AgroSciences,
Monsanto, DuPont etc); quantidade; preço de custo; preço de venda; e desconto. Cada
produto é adquirido diretamente de um fornecedor (indústria química fabricante), que
caracteriza uma marca, sendo que o mesmo fornecedor pode fornecer vários produtos.
• Quanto aos produtores rurais: mantida por Inscrição Estadual (IE); nome; CPF do produtor;
CNPJ (apenas para os estados que exigem, como, por exemplo, estado de São Paulo); dados
da localização da propriedade; data de habilitação; situação; CNAE; telefones e demais dados
de contatos. Um produtor rural pode realizar várias compras de defensivos e/ ou fertilizantes
da distribuidora, via pedido, emitido por um representante (vendedor externo que visita
periodicamente os produtores). Cada representante atende vários produtores rurais por
região/ estado.
• Quanto as revendas: mantida por CNPJ; Inscrição Estadual (IE); razão social; nome fantasia;
endereço completo; situação; CNAE; telefones e demais dados de contatos. Uma revenda
pode realizar várias compras de defensivos e/ ou fertilizantes da distribuidora, via pedido,
emitido por um vendedor interno da distribuidora. Cada representante atende vários
produtores rurais.
• Quanto as cooperativas: mantida por CNPJ; Inscrição Estadual (IE); nome; endereço completo;
situação; CNAE; telefones e demais dados de contatos. Uma cooperativa pode realizar várias
compras de defensivos e/ ou fertilizantes da distribuidora, via pedido, emitido por um
representante da distribuidora. Cada representante atende várias cooperativas região/
estado. Os cooperados são produtores rurais do tipo pessoa física.
A partir das regras definidas e dos dados descritos, elabore:
a. O modelo Entidade Relacionamento (ER) conceitual para melhor compreensão do contexto,
representando o Diagrama Entidade-Relacionamento (DER).
b. O Esquema Estrela correspondente ao fato “vendas realizadas pelos representantes para os
produtores rurais por localização e período”.
c. O Esquema Floco de Neve correspondente ao fato “vendas realizadas pelos vendedores para
os revendedores por localização e período”.
Para resolver este desafio profissional, você deverá ler com atenção o conteúdo da disciplina,
disponível no ambiente virtual e aprofundar os estudos mediante leituras complementares sobre
projeto de banco de dados. </p></h3>
<h4>Leitura sugerida, disponível na biblioteca virtual:
HEUSER, Alberto, C. Projeto de Banco de Dados. 6. ed. São Paulo: Bookman, 2009</h4>
