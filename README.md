# Setup ubuntu workstation via ansible


1) Update packages

    ```sh
    sudo apt update
    sudo apt upgrade
    sudo apt autoremove
    ```

2) Install packages

    ```sh
    sudo apt install ansible git
    ```

3) Clone git repo

    ```sh
    git clone
    ```

4) Execute

    ```sh
    ansible-playbook local.yml --ask-become-pass
    ```
