# Arch Linux Install

Esse é um script de instalação do Arch Linux.

### Antes de usar:

- Essa é uma configuração MINHA, então pode não ser boa para você.
- LEIA o script antes de executa-lo.
- NÃO me responsabilizo por danos.
- Fique a vontade para editar o script ao seu gosto/uso.

### Configuração:

Uso UEFI/EFI e [BTRFS](https://wiki.archlinux.org/title/btrfs) como filesystem com snapshots, você pode não gostar, então recomendo a edição do script.

sda1 - ESP

sda2 - Swap 4GB

sda3 - /

### Download/Execução:

- ATENÇÃO - LEIA O SCRIPT ANTES DE EXECUTA-LO.

- Esse script roda fora do chroot, assim que bootar a archiso execute esses comandos:

  ```sh
  loadkeys br-abnt2
  curl https://raw.githubusercontent.com/frannks/arch-install/main/arch-install.sh |bash
  ```

  

### Contatos:

[Telegram](https://t.me/FranklinTech)

[Email](mailto:fraank@riseup.net)
