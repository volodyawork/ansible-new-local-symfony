###Creating new local project on Symfony2 (apache2)

####Environment:
- ansible 2.0.0.2
- Ubuntu 14.04.3 LTS
- Apache/2.4.7 (Ubuntu)
- PHP 5.6.20

#### Manual:

Change in playbook.yml 2 or more parameters:

    - all_projects_dir: "..."
    - project_name: my-super-project
    - ...

Run in console:

    $ ansible-playbook playbook.yml -K