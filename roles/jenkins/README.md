Role Name
=========

Role para fazer as operações vinculadas ao Jenkins

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

address: Endereço para onde o Jenkins está em execução, lembrando que se o Ansible estiver fora da rede do Jenkins, o endereço deverá ser publico
port: Porta que o serviço do Jenkins está escutando
job: O Job que o artefato deverá ser recuperado
system_adm: A pasta do sistema ADM
system_venta: A pasta do sistema Venta
system_venta_client: A pasta do sistema Venta Client

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

RJ Consultores

Author Information
------------------

Email: eduardo@rjconsultores.com.br
