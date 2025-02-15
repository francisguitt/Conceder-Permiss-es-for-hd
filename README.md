# Conceder-Permiss-es-for-hd


O método que usamos é chamado de "Assumir Propriedade e Conceder Permissões". Ele é usado para recuperar o controle de arquivos ou unidades que pertenciam a outro usuário ou sistema operacional.

📌 Por que esse problema acontece?
Quando um HD externo era usado em outro computador (como um notebook), os arquivos podem estar protegidos por permissões do antigo sistema. Isso significa que, mesmo sendo administrador no seu PC atual, você não tem direito de acessar ou modificar os arquivos, porque o "dono" deles era o outro sistema.

📌 O que fizemos para resolver?
Abrimos o Prompt como Administrador → Para ter permissões elevadas.
Usamos takeown → Para assumir a propriedade dos arquivos.
Alteramos as permissões (icacls) → Para garantir que seu usuário possa ler, modificar e excluir os arquivos.
Formatamos o HD (se necessário) → Para apagar tudo e criar uma nova estrutura limpa.
📌 Para que esse método serve?
✅ Recuperar arquivos protegidos de um HD ou pendrive.
✅ Excluir ou formatar um HD externo usado em outro computador.
✅ Corrigir erros de "Acesso Negado" ao tentar abrir pastas ou arquivos.
✅ Restaurar permissões quando um sistema corrompido impede o acesso.

Agora você tem controle total sobre o HD e pode usá-lo normalmente. 🚀
