Passo a Passo para Corrigir erro de Path do Golang no terminal Git Bash:
Certifique-se de que as variáveis de ambiente GOPATH e GOMODCACHE estejam configuradas corretamente.  

Abrir o Painel de Controle do Sistema:

Clique com o botão direito em "Este PC" ou "Computador" na área de trabalho ou no explorador de arquivos.

Selecione "Propriedades" e depois "Configurações avançadas do sistema".

Abrir Variáveis de Ambiente:

Na aba "Avançado", clique em "Variáveis de Ambiente".
Verificar GOPATH:

Verifique se há uma variável de ambiente chamada GOPATH. Se existir, certifique-se de que seu valor é um caminho absoluto, como C:\Users\Seu-Nome\go

Se você precisa configurar o GOMODCACHE manualmente, você pode fazer isso adicionando as variáveis de ambiente no seu perfil do Git Bash.

Abra o Git Bash e edite seu arquivo de configuração ~/.bashrc

bash 
nano ~/.bashrc

Adicionar Variáveis:


Adicione ou ajuste as variáveis GOPATH e GOMODCACHE para que sejam caminhos absolutos. Por exemplo:

bash
export GOPATH=/c/Users/YourUsername/go
export GOMODCACHE=$GOPATH/pkg/mod
Substitua YourUsername pelo nome do seu usuário no Windows.

Recarregue o arquvio

Para aplicar as mudanças, execute:

bash
source ~/.bashrc

Verificar o Caminho do Cache de Módulos

Agora manin(a)
Crie um modulo pra gente testar isso

bash
mkdir mymodule
cd mymodule
go mod init mymodule

Vamos adicionar codigo agora

bash
echo 'package main\nimport "fmt"\nfunc main() { fmt.Println("Hello, world!") }' > main.go

Executee o code:
bash
go run main.go































