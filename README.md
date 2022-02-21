# comandos_conda

## CREAR AMBIENTE CONDA:
conda create --name test_env python3.9 -y

## PARA ACTIVAR EL AMBIENTE CONDA:
conda activate test_env

## PARA DESACTIVAR EL AMBIENTE CONDA USAR:
conda deactivate

## PARA INSTALAR DEPENDENCIAS:
conda install -c conda-forge -y numpy pandas matplotlib scipy scikit-learn jupyter jupyterlab

## EXPORTAR AMBIENTE CONDA:
conda env export > /ruta/exportacion/test_env.yaml

## IMPORTAR AMBIENTE CONDA:
conda env create -f /ruta/archivo/test_env.yaml
