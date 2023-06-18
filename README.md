## 1 - Execute o CMD ou o Windows PowerShell como administrador
## 2 - Digite o comando:
    wsl --install -d ubunto
## Editor de texto (VI)
    vi nome.txt //acessa o arquivo
    ins ou ins+shift(Num lock ativado) //modo de escrita
    esc ou ctrl+c //sair do modo de escrita
    shift + :q! //sair do editor
    shift + :wq! //sair do editor e salvar o arquivo
## GCC
     //Baixar
     sudo apt update
     sudo apt install gcc
     //compilar
     gcc nome.cpp -o nome -lstdc++ 
     //Executar
     ./nome

