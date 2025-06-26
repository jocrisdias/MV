# MV
Criar uma máquina virtual.
Dentro do Azure selecione página inicial, depois máquinas virtuais e em seguida +criar.
Preencha as informações na aba básico, tais como:
Detalhes da instância
Nome da máquina virtual: myVM
Região: (Canada) Cananda Central
Opções de disponibilidade: Zona de disponibilidade
Zona de disponibilidade: Zona 2
Tipo de segurança: Computadores virtuais de inicialização confiável
Imagem: Windows Server 2022 Datacente: Azure Edition - X64 Gen2
Tamanho: Standard_E2s_v3 - 2 vcpus, 16 GiB memória (US$ 0,02554/hora)
Em Conta de administrador, forneça um nome de usuário, como azureuser e uma senha. A senha deve ter no mínimo 12 caracteres e atender a requisitos de complexidade definidos.
Nome de usuário: j*******as
Senha:************
Confirmar senha:************
Em Regras de porta de entrada, escolha Permitir portas selecionadas e, em seguida, selecione RDP (3389) e HTTP (80) na lista suspensa.
Deixe os padrões restantes e, em seguida, selecione o botão Revisar + criar na parte inferior da página.
Aguarde um tempo.
Após a execução da validação, selecione o botão Criar na parte inferior da página.
Após a conclusão da implantação, selecione Ir para o recurso.
Com isso a máquina virtual está criada.




