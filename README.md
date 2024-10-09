# ubuntu


# Configurar Teclado ABNT2 pt-BR
Os comandos consideram que o repositório foi clonado e você está na raiz no projeto

Execute o comando:
```
cp -rf  keyboard-abnt2-pt-br.txt  /etc/default/keyboard
```

# Configurar IP 192.168.4.220
Os comandos consideram que o repositório foi clonado e você está na raiz no projeto

Execute o comando:
```
cp -rf config-ip-192.168.4.220.yaml /etc/netplan/50-cloud-init.yaml

netplan try

netplan apply
```

# Configurar IP 192.168.4.224
Os comandos consideram que o repositório foi clonado e você está na raiz no projeto

Execute o comando:
```
cp -rf config-ip-192.168.4.224.yaml /etc/netplan/50-cloud-init.yaml

netplan try

netplan apply
```
