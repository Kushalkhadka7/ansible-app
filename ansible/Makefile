.PHONY: test

yaml-lint:
	@yamllint .

syntax-check:
	@ansible-playbook main.yml --syntax-check

lint:
	@ansible-lint main.yml

init-role:
	@molecule init role abc.testrole

test:
	@molecule test