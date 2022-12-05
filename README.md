# ansible-role-openshift-local

Ansible Role to manage OpenShift Local instance.

## Requirements

None

## Testing

Testing the Ansible Role is achieved through the following areas.

> Linting

The role uses `ansible-lint` to perform linting when you commit code locally using git. You might have 

> Continuous Integration (CI)

- Using VSCode with Docker and Ansible extension to run `ansible-lint` on existing code

> Unit Testing

- Using `ansible-navigator` with an Execution Environment container image to run the [test playbook](./tests/test.yml) against a target environment.

## License

BSD

## Author

John Wadleigh