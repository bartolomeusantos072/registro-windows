# registro-windows
registro windows
#Abrindo o Regedit
Pressione Windows + R para abrir a caixa de execução.
Digite regedit e pressione Enter.
Comandos Úteis
#Backup do Registro

Antes de fazer alterações, sempre faça um backup: Arquivo > Exportar, escolha um local e um nome.
#Alterar Tempo de Espera do Menu Iniciar

Caminho: HKEY_CURRENT_USER\Control Panel\Desktop
Valor: MenuShowDelay
Mude para 0 para instantaneamente mostrar o menu.
Desativar o Assistente de Atualizações do Windows

Caminho: HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\WindowsUpdate\AU
Crie um novo valor DWORD chamado NoAutoUpdate e defina como 1.
#Aumentar o Número de Conexões TCP

Caminho: HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\Tcpip\Parameters
Crie um novo valor DWORD chamado MaxUserPort e defina um número entre 5000 e 65534.
#Desativar a Tela de Bloqueio

Caminho: HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\Personalization
Crie um novo valor DWORD chamado NoLockScreen e defina como 1.
#Ativar o Modo Escuro

Caminho: HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Themes
Altere o valor AppsUseLightTheme para 0.

# correcoes no window 10:
https://answers.microsoft.com/pt-br/windows/forum/all/melhorar-desempenho-do-computador-com-o-windows-10/2e17a67e-1e9e-4b45-b8bf-415163f602c9

faça download:
https://lira.epac.to/DOCS-TECH/Sistemi%20Operativi/Windows/Microsoft%20Windows%20Registry%20Guide%20-%202nd%20Edition%20(2005).pdf
