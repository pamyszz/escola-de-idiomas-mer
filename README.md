### 📘 README - Modelo Entidade-Relacionamento (MER)
![image](https://github.com/pamyszz/escola-de-idiomas-mer/assets/153380356/4416e4f1-4105-467d-9cd4-94c8eac4797f)

---
Bem-vindo ao guia do Modelo Entidade-Relacionamento (MER) para gestão de cursos e alunos! Este README oferece uma visão clara e objetiva do diagrama fornecido, destacando as principais entidades e seus relacionamentos. Use este documento para entender e navegar pelo sistema de maneira eficiente. 😊✨


### 🔍 Visão Geral

O modelo representa um sistema de gestão acadêmica com foco em alunos, cursos e matrículas. Cada componente é essencial para garantir que a administração de dados seja eficiente e clara.

---

### 🗂️ Entidades e Atributos

1. **Aluno 👨‍🎓👩‍🎓**
   - **Chave Primária (PK)**: `Pk_Id_Aluno`
   - **Atributos**:
     - `Nome_Aluno` 📝
     - `Data_Nascimento` 📅
     - `Endereço` 🏡:
       - `Rua`
       - `Número`
       - `CEP`
     - **Telefone** 📞 (1:N):
       - `Telefone1`
       - `Telefone2`

2. **Curso 📚**
   - **Chave Primária (PK)**: `Pk_Id_Curso`
   - **Atributos**:
     - `Nome_Curso` 📑
     - `Carga_Horária` ⏰
     - `Turno` 🌞🌜
     - `Nível` 📊

3. **Matrícula 🎓**
   - **Chave Primária (PK)**: `Pk_Id_Matricula`
   - **Chaves Estrangeiras (FK)**:
     - `Fk_Id_Aluno` 🔗
     - `Fk_Id_Curso` 🔗
   - Esta entidade faz a ligação entre alunos e cursos, permitindo que um aluno se matricule em um ou mais cursos.

---

### 🔗 Relacionamentos

- **Aluno** e **Matrícula**: Um aluno pode ter várias matrículas (`1:N`).
- **Curso** e **Matrícula**: Um curso pode ter várias matrículas (`1:N`).

---

### 🛠️ Como Utilizar

- Utilize este MER para estruturar a base de dados do sistema de gestão acadêmica.
- As relações entre as entidades ajudam a garantir a integridade referencial e a eficiência no acesso às informações.

---

Espero que este documento tenha sido útil para sua compreensão do sistema. Obrigado por ler! 📖✨

---
