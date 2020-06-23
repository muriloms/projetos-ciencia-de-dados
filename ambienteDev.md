# Preparar ambiente para desevolvimento
## Anaconda
- Download Anaconda:

https://www.anaconda.com/products/individual#Downloads
- Passo a passo para instalar: 

https://www.digitalocean.com/community/tutorials/how-to-install-anaconda-on-ubuntu-18-04-quickstart-pt


## Editor de texto
- Sublime text 3:

https://www.sublimetext.com/docs/3/linux_repositories.html#apt

- VS Code:

https://code.visualstudio.com/docs/setup/linux


# Preparar ambiente virtual
atualizar
```
conda update conda
conda update anaconda
conda update --all
```
criar ambiente
```
conda create -n projeto python==3.7.2 numpy==1.16.1 scipy
```
ativar ambiente
```
conda active projeto
```
desativar ambiente
```
conda deactive projeto
```
