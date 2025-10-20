# Projeto XPeriência – Testes Sprint 4

Bem-vindo ao repositório do projeto XPeriência. Aqui estão documentados os testes manuais e de automação realizados para a Sprint 4.

**Integrantes do grupo:**
- Guilherme Doretto Sobreiro 	 | RM: 99674
- Guilherme Fazito Ziolli Sordili  | RM: 550539
- Raí Gumieri dos Santos     	 | RM: 98287

---

## Parte A – Testes Manuais (Azure Boards)

> **Link de acesso ao Azure Boards:** [Clique aqui para acessar](https://dev.azure.com/XPeriencia/Challenge%20-%20XPeriencia/_workitems/recentlyupdated/)

Os testes manuais foram planejados e registrados no **Azure Boards**. Cada Test Case cobre as funcionalidades principais do aplicativo: cadastro, login, acesso aos cursos gratuitos e tela de suporte.

### Test Cases
1. **TC01 – Cadastro de Usuário**  
   - **Descrição:** Valida se um usuário consegue criar uma conta com sucesso.  
   - **Dados de Entrada:** Nome, E-mail, Senha, Confirmação de Senha.  
   - **Dados de Saída Esperados:** Mensagem de sucesso "Cadastro realizado com sucesso".  
   - **Procedimento de Teste:**  
     1. Abrir o aplicativo.  
     2. Preencher os campos de cadastro.  
     3. Clicar no botão de confirmação.  
     4. Verificar se a mensagem de sucesso aparece.  

2. **TC02 – Login de Usuário**  
   - **Descrição:** Valida o login com a conta cadastrada.  
   - **Dados de Entrada:** E-mail e senha do usuário cadastrado.  
   - **Dados de Saída Esperados:** Acesso à tela inicial do app com cursos gratuitos.  
   - **Procedimento de Teste:**  
     1. Abrir o aplicativo.  
     2. Preencher os campos de login.  
     3. Clicar em "Entrar".  
     4. Verificar se o usuário é direcionado para a tela inicial.

3. **TC03 – Acesso aos Cursos Gratuitos**  
   - **Descrição:** Valida se o usuário consegue acessar os cursos gratuitos disponíveis.  
   - **Dados de Entrada:** Login realizado com sucesso.  
   - **Dados de Saída Esperados:** Listagem de cursos gratuitos.  
   - **Procedimento de Teste:**  
     1. Acessar a tela inicial após login.  
     2. Selecionar um curso gratuito.  
     3. Verificar se os capítulos estão disponíveis para navegação.

4. **TC04 – Tela de Suporte**  
   - **Descrição:** Valida se o usuário consegue acessar a tela de suporte e visualizar informações de contato.  
   - **Dados de Entrada:** Login realizado com sucesso.  
   - **Dados de Saída Esperados:** Tela de suporte com e-mail, telefone e celular visíveis.  
   - **Procedimento de Teste:**  
     1. Acessar a barra de navegação.  
     2. Selecionar a opção "Suporte".  
     3. Verificar se todas as informações de contato estão visíveis.


---

## Parte B – Testes Automatizados (Selenium IDE)

Para validar o fluxo principal do aplicativo, foram gravados **4 testes automatizados** utilizando o **Selenium IDE**, com a funcionalidade Record & Playback:

### Vídeos de Testes Automatizados
1. **TA01 – Cadastro de Usuário**
2. **TA02 – Login de Usuário** 
3. **TA03 – Acesso aos Cursos Gratuitos** 
4. **TA04 – Tela de Suporte** 

**Todos os vídeos estão hospedados neste repositório, na pasta `Evidencias`.**

**É possível acessar os vídeos no Youtube, no formato shorts. Links:**
> **Link do Cadastro de Usuário:** [Clique aqui para acessar o vídeo](https://youtube.com/shorts/rTB4TmZ6qR8?feature=share)

> **Link do Login de Usuário:** [Clique aqui para acessar o vídeo](https://youtube.com/shorts/Ks_oTIXFhWs?feature=share)

> **Link de Acesso aos Cursos:** [Clique aqui para acessar o vídeo](https://youtube.com/shorts/j0otPxC6dAs?feature=share)

> **Link de Acesso ao Suporte:** [Clique aqui para acessar o vídeo](https://youtube.com/shorts/ynmf-5tCdvg?feature=share)
---

## Observações

- Branch utilizada: `develop`  
- Todos os testes foram planejados de acordo com o plano de release e tarefas realizadas nas sprints anteriores.  
- Os dados utilizados nos testes foram predefinidos e controlados.  

---
