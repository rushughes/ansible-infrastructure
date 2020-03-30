# running a playbook on a specific host

ansible-playbook -i production.yaml -l _example.domain.com_ site.yaml -bK --check
