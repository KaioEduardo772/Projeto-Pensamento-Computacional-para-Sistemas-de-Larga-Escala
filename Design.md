# Pensamento Computacional Aplicado

**Decomposição:**
Os alunos farão acesso a uma ferramenta web de troca de mensagens, a IA recebe a pergunta do usuário, se for acadêmica consulta o regimento interno para responder a pergunta, se for técnica consulta manual das funcionalidades e fornece um tutorial da resolução do problema dentro da Área do Aluno, caso o aluno não consiga resolver o seu problema com a IA ele será fornecida as vias de contato oficiais para uma conversa com os atendentes.

**Reconhecimento de Padrões:**
- Chat bots personalizados para empprezas
- Ignorar contexto não relacionado com a UDF
  
**Abstração:**

    Pseudocódio
    
    Inicia Chat Bot{

    	Envia para o usuário uma mensagem, explicando regras de uso do chat e suas capacidades.
    	
    	Recebe a entrada do usuário e interpreta.
    
    	Se cabe no contexto da faculdade {
    
    		Se Duvida acadêmica{ 
    
    			Consulta o regimento interno e responde a pergunta.
    			Se Encontra{ a resposta fornece a informação.}
    			Se Não Encontra{ a resposta pede por especificação.}
    		}
    
    		Se Duvida técnica {
    
    			Consulta o Manual de Funcionalidade da Área do Aluno.
    			Se Encontra{ o tutorial passo a passo para a resolução do problema dentro da Área do Aluno.}
    			Se Não Encontra{ a resposta pede por especificação.}
    
    		}
      }
