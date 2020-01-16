1、安装anaconda 
2、打开终端并进入ForTest目录
3、执行conda env create -f environment.yml
4、执行conda activate pytorch1.1
5、执行python eval_txt.py -N core_coreless_test.txt -A Anno_test -I Image_test -M bestmodel.pt