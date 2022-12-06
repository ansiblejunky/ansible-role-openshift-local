# ansible-role-openshift-local

Ansible Role to manage OpenShift Local instance.

## Requirements

None

## Testing

The test playbook uses extra variable `mode` to allow easily testing each of the task files. An example of runing the `configure` mode:

```shell
ansible-playbook tests/test.yml -i tests/inventory -c local -e mode=configure
```

## License

BSD

## Author

John Wadleigh
