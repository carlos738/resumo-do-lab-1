# resumo-do-lab-1
# CRIANDO UMA MÁQUINA VIRTUAL NA MICROSOFT AZURE

# 1º Passo
Acesse o portal da Azure e faça login na sua conta.

# 2º PASSO
Após o acesso use a barra de pesquisas e digite Virtual Machines

# 3º PASSO
Clique em Add,e depois clique em Virtual Machine
# 4º PASSO
Selecione sua Subscription.Em seguida, em Resource Group,clique em Create New.No campo Name, escolha o de sua preferência,depois clique em OK.
Neste passo você tem diversas escolhas :
VMs Linux, Windows,Conjuntos de dimensionamento flexíveis.

    O que é necessário considerar antes de criar uma máquina virtual?
    Partes de uma VM e como elas são cobradas
    Disponibilidade
    Tamanhos e preços

Aplica-se a:  VMs Linux , VMs Windows , Conjuntos de dimensionamento flexíveis

As VMs (máquinas virtuais) do Azure são um dos vários tipos de recursos de computação sob demanda escalonáveis oferecidos pelo Azure. Normalmente, você escolhe uma máquina virtual quando precisa de mais controle sobre o ambiente de computação do que as outras opções oferecem.

# Alguns exemplos de VMs do Azure
Desenvolvimento e teste => oferece maneira rápida e fácil de criar um computador com configurações específicas.
Aplicativos na nuvem => como a demanda por seu aplicativo pode variar, pode fazer sentido, em termos econômicos, executá-lo em uma máquina virtual no Azure. Você paga por máquinas virtuais extras quando precisa delas e as desliga quando não são mais necessárias.
Datacenter estendido => as máquinas virtuais em uma rede virtual do Azure pode ser fácilmente conectada a rede de sua organização.

Porém se deve ter algumas considerações ao se criar uma máquina virtual:

    Os nomes de seus recursos;
    O local onde os recursos são armazenados;
    O tamanho da máquina virtual;
    O número máximo de máquinas virtuais que podem ser criadas;
    O sistema operacional que a máquina; virtual executará;
    A configuração da máquina virtual depois; que ela for iniciada;
    Os recursos relacionados que a máquina; virtual precisa.
após algumas explicações vamos para o :
# 5º PASSO 
Nesta seção você deve acessar a seção Instance details, virtual machine name insira o nome desejado e selecione sua Region, escolha a imagem desejada ,
e Create Virtual Machine.
# 6º PASSO
Na seção size , selecione a quantidade de memória e o preço.
# 7º PASSO
Na seção Administrator account, Authentication type, selecione a opção SSH public key. Chegando em Username, defina o de sua preferência. Em SSH public key source, mantenha a opção Generate new key pair selecionada. Para concluir essa etapa, em Key pair name, escolha o nome de sua preferência.
# 8º PASSO
Em Inbound port rules, Allow selected ports, mantenha a porta SSH que você deseja usar , selecione a , depois clique em Review + Create.
# 10º PASSO
Você também pode gerar chaves SSH , para isto você deve clicar em Generate new key pair, clicar em Download private key and create resource.E será gerada uma chave SSH.
# 11º PASSO
Após alguns instantes, temos a informação de que a implementação da máquina virtual foi concluída com sucesso. Sensacional!

Agora. clique em Go to resource.
# 12º PASSO 
Depois de acessar as informações do recurso tcbcusapp01, em Public IP address, clique no ícone destacado para copiar o IP público para a área de transferência.

Para ter acesso via SSH à máquina virtual criada você pode utilizar o gitbash tanto no Linux ,Windows ou Mac. E assi você poderá acessar sua máquina virtual da MICROSOFT AZURE.

## CONCLUSÃO 
A crição de máquinas virtuais é uma boa idéia te oferecem vários tipos de serviços de acordo com suas necessidades e seguindo todos os passos acima e tomando todos os devidos cuidados você
pode usar e usufruir de todos os recursos e segurança disponíveis nas nuvens.