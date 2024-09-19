# Sistema de Gestão das Olimpíadas (SGO)

### Participantes
* [Ana Julia Teixeira Candido](https://github.com/anajuliateixeiracandido)
* [Marcella Ferreira Chaves Costa](https://github.com/marcellafccosta)

---

### Histórias de Usuário para o **Administrador**:

#### US01 - Cadastro de Competições

**Como** administrador do sistema,  
**Eu quero** cadastrar competições com nome da modalidade, data, horário, local e lista de atletas inscritos,  
**Para que** eu possa organizar o cronograma das competições e garantir que cada evento tenha as informações corretas.

**Critérios de aceitação:**
- O sistema deve permitir o cadastro de uma competição, incluindo o nome da modalidade, data, horário, local e atletas.
- O sistema deve validar a disponibilidade do local e evitar conflitos de horário.
- O sistema deve permitir a edição dos dados da competição antes de sua realização.

---

#### US02 - Alocação de Locais

**Como** coordenador do evento,  
**Eu quero** alocar locais para as competições de forma a evitar conflitos de horário,  
**Para que** cada competição tenha seu local reservado sem sobreposição.

**Critérios de aceitação:**
- O sistema deve permitir a alocação de um local para cada competição.
- O sistema deve impedir a reserva de um local para mais de uma competição no mesmo horário.
- O sistema deve sugerir locais disponíveis com base no horário e capacidade.

---

#### US03 - Controle de Resultados

**Como** árbitro ou administrador,  
**Eu quero** registrar os resultados das competições, incluindo os vencedores de ouro, prata e bronze,  
**Para que** os resultados possam ser armazenados e usados para relatórios futuros.

**Critérios de aceitação:**
- O sistema deve permitir o registro de resultados após a conclusão da competição.
- O sistema deve identificar e registrar os vencedores de ouro, prata e bronze.
- O sistema deve permitir a consulta e revisão dos resultados registrados.

---

#### US04 - Geração de Relatórios de Medalhas

**Como** administrador do sistema,  
**Eu quero** gerar relatórios de medalhas conquistadas por país,  
**Para que** eu possa acompanhar o desempenho de cada país nas Olimpíadas.

**Critérios de aceitação:**
- O sistema deve gerar relatórios de medalhas com base nos resultados registrados.
- O relatório deve mostrar o número de medalhas de ouro, prata e bronze de cada país.
- O relatório deve permitir a filtragem por modalidade ou data.

---

### Histórias de Usuário para o **Atleta**:

#### US05 - Inscrição em Competições

**Como** atleta,  
**Eu quero** me inscrever em diferentes competições representando o meu país,  
**Para que** eu possa participar das modalidades nas quais estou apto.

**Critérios de aceitação:**
- O sistema deve permitir que o atleta se inscreva em várias competições.
- O sistema deve restringir a participação do atleta a um país por modalidade.
- O sistema deve permitir a visualização e alteração das inscrições antes do prazo de fechamento.

---

## Diagramas
### Diagrama de Caso de Uso

<div>
 <img src="imagens/Diagrama de Caso de Uso - SGO.png" width="500px" height="500px">
</div>

### Diagrama de Classe

<div>
 <img src="imagens/Diagrama de Classe -SGO.png" width="500px" height="500px">
</div>

### Diagrama de Pacote

<div>
 <img src="imagens/Diagrama de Pacote -SGO.png" width="500px" height="500px">
</div>

### Diagrama de Componente

<div>
 <img src="imagens/Diagrama de Componentes - SGO.png" width="500px" height="500px">
</div>

### Diagrama de Implantação

<div>
 <img src="imagens/Diagrama de Implantação - SGO.png" width="500px" height="500px">
</div>
