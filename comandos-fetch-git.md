# 🚀 Git -- Comandos para trabalhar com o fecht e gerenciamento de branches

# ⚙️ Configurações de Fetch

------------------------------------------------------------------------

## 🎯 Setar o fetch default para apenas a master

``` bash
git config remote.origin.fetch '+refs/heads/master:refs/remotes/origin/master'
```

------------------------------------------------------------------------

## 🌎 Setar o fetch default para todas as branches (retornar a configuração padrão do git)

``` bash
git config remote.origin.fetch '+refs/heads/*:refs/remotes/origin/*'
```

------------------------------------------------------------------------

# 📥 Fetch de Branch Específica

## 🔹 Efetuar um fetch de uma branch específica

``` bash
git fetch origin NOME COMPLETO DA BRANCH
```

### 📌 Exemplo

``` bash
git fetch origin FIX/ITAU
```
