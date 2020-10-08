## Programação Paralela

Repositório criado durante a matéria de programação paralela.

## pthread

Com o objetivo de criar THREADS, o arquivo Atividade1.cpp utiliza matriz fazendo a soma e a multiplicação de cada célula da mesma em uma thread diferente.

## OpenCL

Diferentemente do arquivo anterior, os arquivos dentro da pasta `dataParallel` são responsáveis por executar um código em openCL. Para isso, é necessário rodar os comandos que seguem para instalação do cmake e do nvidia-opencl-dev.

`$ sudo apt-get install cmake`

`$ sudo apt-get install nvidia-opencl-dev`

Para compilar e executar:

`$ cmake .`
`$ make`

`$ ./dataParallel.nvidia `

