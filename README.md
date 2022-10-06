# GIT-FLOW

- pra criar uma feature é necessario estar na develop
- se der algo errado na branch de release, resolve o problema nela
- quando for criar hot fix é bom estar na branch master/main

## Some git-flow commands
```bash
  # create git flow
  git flow init
  # create a new feature
  git flow feature start <feature name>
  # finalizar uma feature já criada
  git flow feature finish <feature name>
  # faz puch da branch para o github, pro time mecher nela
  git flow feature public <feature name>
  # criar release
  git flow release start <release name(exmaple 1.0)>
  # finalizar uma release
  git flow release finish <release name>
  # criar um hotfix (criar ela estando na master/main)
  git flow hotfix start <hotfix name(exmaple 1.1)>
  # finalizar hotfix
  git flow hotfix finish <hotfix name(exmaple 1.1)>
```
