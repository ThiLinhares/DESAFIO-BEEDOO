## User Stories para formulário de inclusão de cursos

**US01: Cadastrar Novo Curso**

Como administrador, quero cadastrar um novo curso com informações completas e válidas, incluindo título, descrição, imagem de capa, datas de início e término, e tipo do curso, para que ele fique disponível na plataforma.

**Critérios de Aceite:**

* O sistema deve permitir o cadastro de um novo curso com:
    * Título (entre 5 e 100 caracteres)
    * Descrição (entre 10 e 500 caracteres)
    * URL válida para a imagem de capa
    * Datas de início e término válidas (data de término posterior à data de início)
    * Tipo de curso
* O sistema deve impedir o cadastro de um novo curso com nome já existente, exibindo uma mensagem de erro.
* O sistema deve validar os campos do formulário e exibir mensagens de erro específicas para cada campo inválido ou obrigatório não preenchido.
* Após o cadastro bem-sucedido, o curso deve ser criado e o administrador deve ser redirecionado para a página de detalhes do curso.

--

**US02: Definir Título do Curso**

Como administrador, quero inserir um título válido para o curso, que seja informativo, siga os padrões da plataforma (entre 5 e 100 caracteres) e utilize apenas caracteres permitidos (letras, números e espaços), para garantir a qualidade dos dados na plataforma.

**Critérios de Aceite:**

* O sistema deve aceitar títulos com no mínimo 5 e no máximo 100 caracteres.
* O sistema deve permitir apenas a utilização de letras, números e espaços no título.
* O sistema deve exibir mensagens de erro caso o título seja muito curto, muito longo ou contenha caracteres inválidos.

--

**US03: Descrever o Curso**

Como administrador, quero inserir uma descrição completa e dentro dos limites de caracteres (entre 10 e 500 caracteres) para o curso, a fim de fornecer informações detalhadas aos usuários da plataforma sobre o conteúdo do curso.

**Critérios de Aceite:**

* O sistema deve aceitar descrições com no mínimo 10 e no máximo 500 caracteres.
* O sistema deve exibir mensagens de erro caso a descrição seja muito curta ou muito longa.

--

**US04: Inserir Imagem de Capa**

Como administrador, quero inserir uma URL válida para a imagem de capa do curso, a fim de tornar a página do curso mais visualmente atrativa e informativa para os usuários.

**Critérios de Aceite:**

* O sistema deve exibir uma prévia da imagem a partir da URL inserida, caso a URL seja válida.
* O sistema deve exibir uma mensagem de erro caso a URL seja inválida.
* O sistema deve exibir uma imagem padrão caso a imagem da URL inserida não seja encontrada.

--

**US05: Definir a Data do Curso**

Como administrador, quero definir datas de início e término válidas para o curso, a fim de informar aos usuários o período de disponibilidade do curso.

**Critérios de Aceite:**

* O sistema deve aceitar datas de início e término futuras à data atual.
* O sistema deve garantir que a data de término seja posterior à data de início.
* O sistema deve exibir mensagens de erro caso as datas inseridas sejam inválidas.

--

**US06: Escolher o Tipo do Curso**

Como administrador, quero selecionar um tipo de curso existente para o novo curso, a fim de categorizá-lo corretamente na plataforma e facilitar a navegação e busca dos usuários por cursos específicos.

**Critérios de Aceite:**

* O sistema deve fornecer uma lista de tipos de cursos existentes para seleção.
* O sistema deve permitir a seleção de apenas um tipo de curso por vez.
* O sistema deve exibir uma mensagem de erro caso nenhum tipo de curso seja selecionado. 
