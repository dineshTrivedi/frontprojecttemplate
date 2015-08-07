Nessa pasta ira conter os hooks do git:
- precommit: hook que executara jshint e scss-lint antes do commit
- pre-commit-msg: Hook que adiciona uma mensagem a todo commit dizendo qual branch o commit foi realizado

Possuira, tambem, um build.py que sera responsavel por adicionar hash como query string para todo script importado que for necessario, como: scripts js, css e outros. O hash sera definido na hora da build, provavelmente sera o timestamp.