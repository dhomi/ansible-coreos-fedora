# Installeer services op techlab servers

## via ansible

installeer eerst voor jezelf de ansible-playbook in je machine.
De wachtwoorden zijn vergrendeld

creeer een '.vault_password' file met daarin onze vault wachtoord

ansible-playbook -i inventory ngnix.yml --vault-password-file ./vault_file --ask-vault-pass
