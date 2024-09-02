# Sobre o projeto

Sou estudante do curso de Ciência da Computação e com o intuito de praticar e aprender mais sobre Análise de Dados iniciei esse projeto pessoal que visa explorar dados a respeito de casos de Síndrome Respiratória Aguda Grave (SRAG) hospitalizados no Brasil. Os dados foram disponibilizados pelo Ministério da Saúde e são referentes ao período de 2021 a julho de 2024 e podem ser acessador através do link: https://dados.gov.br/dados/conjuntos-dados/srag-2021-e-2022 . No mesmo link também está disponível o PDF contido no projeto com as informações que estão dispostas nos arquivos com os dados.

Vale ressaltar que como os arquivos dos dados são muito grandes não consegui fazer o upload deles para o GitHub, tentei fazer o uso do Git LFS mas recebi um e-mail alertando que para extender o uso dessa função eu precisaria comprar um pacote de dados adicionais, então optei por simplesmente disponibilizar o link que consegui os dados.

Para me organizar melhor criei o Excel "Organizando dados.xlsx" que também contem as ingormações das colunas dos CSV, uma descrição e uma marcação se a coluna seria ou não considerada nas análises do projeto (tentei deixar uma breve justificativa do porquê acredito que as colunas em questão não devem ser consideradas).

# Comentários gerais a respeito da organização dos dados

As datas serão desconsideradas dado a quantia de informações faltantes bem como a importância dos dados (nesse projeto daremos mais importância para se determinado evento aconteceu, não para quando aconteceu). Com exceção das datas referente as doses das vacinas do COVID-19 (inclusas as de reforço) para conseguirmos analisar a quantidade de pessoas que recebeu cada dose

Também estarei desconsiderando informações pessoais dos médicos e pacientes (bem como nome, documentos, endereços, telefones e etc).

Informações como descrições de resultados de exames serão também desconsideradas devido ao número de dados e a profundidade que os dados serão explorados, acredito que considerar essas informações possa ser alvo de estudo de projetos futuros.

Todas as linhas que receberiam valores como "Outros, especifique" ou algum outro semelhante foram generalizadas como "Outros" para as análises, além disso, valors que eram nulos foram substituídos para "Não preenchido".
