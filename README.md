# Molecule Examples 

The following directories contain examples of using Molecule with Ansible playbooks:

> __create_file_playbook__
>
> __httpd_playbook__
>
> __two-vms__

In the roles directory are additional examples of how to use Molecule to test Ansible roles. 
When testing roles, ensure to either:

> __web__
>
> __motd__

When testing roles, ensure to either set your environment variable __ANSIBLE_COLLECTIONS_PATH__ to include the path where your collection resides, or specify the collection path in __ansible.yml__.

For an example of setting the collection path, refer to the 
__create_file_playbook/extensions__ directory.

Please see the __README.md__ file under each directory for instructions on creating the virtual Python environment and running the tests.

## Acknowledgments

This repository is inspired/influenced by:
> [Ansible for DevOps -Jeff Geerling](https://www.ansiblefordevops.com/).
>
> [Jacob Hunt's molecule-workshop](https://github.com/rhjhunt/molecule-workshop).
>
> [Christopher Snapp](https://github.com/snapp/template-ansible-collection), template ansible collection.

> [!WARNING]
>
> This code is NOT supported by Red Hat and may not work as expected.
>
> Red Hat does not guarantee its correctness, reliability, or performance.
>
> Use at your own risk!
