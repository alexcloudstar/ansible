ln -s "/Users/stefanalexandruromila/Library/Application Support/pipx/venvs/ansible/bin/python" /usr/local/bin/ansible_python
vars:
  ansible_python_interpreter: /usr/local/bin/ansible_python
python3 -m venv ~/ansible_venv
source ~/ansible_venv/bin/activate
pip install ansible

