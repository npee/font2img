# 폰트 파일(ttf)을 이미지(png)로 바꾸는 예제
## 사용된 패키지
- python 3.7.5
- os
- numpy 1.17.3
- PIL 6.2.1
- tqdm 4.41.1

## 내용
- 폰트파일 내에서 조합가능한 모든 한글(Unicode)에 대하여 이미지 추출하여 파일로 저장한다
- Unicode별 폴더 생성 후 code에 맞는 순서의 한글을 이미지로 만들어서 저장(폰트파일당 11172회)

## 사용한 환경에 설치된 모든 패키지(conda list)
Name                      Version                   Build    Channel
_tflow_select             2.3.0                       mkl
absl-py                   0.8.1                    py37_0    conda-forge
astor                     0.7.1                      py_0    conda-forge
blas                      1.0                         mkl
ca-certificates           2019.11.28           hecc5488_0    conda-forge
certifi                   2019.11.28               py37_0    conda-forge
cycler                    0.10.0                     py_2    conda-forge
freetype                  2.10.0               h563cfd7_1    conda-forge
gast                      0.2.2                      py_0    conda-forge
google-pasta              0.1.8                      py_0    conda-forge
grpcio                    1.23.0           py37h3db2c7e_0    conda-forge
h5py                      2.10.0   nompi_py37h422b98e_101    conda-forge
hdf5                      1.10.5      nompi_ha405e13_1104    conda-forge
icc_rt                    2019.0.0             h0cc432a_1
icu                       64.2                 he025d50_1    conda-forge
intel-openmp              2019.4                      245
jpeg                      9c                hfa6e2cd_1001    conda-forge
keras-applications        1.0.8                      py_1    conda-forge
keras-preprocessing       1.1.0                      py_0    conda-forge
kiwisolver                1.1.0            py37he980bc4_0    conda-forge
libblas                   3.8.0                    14_mkl    conda-forge
libcblas                  3.8.0                    14_mkl    conda-forge
libclang                  9.0.0        default_hf44288c_4    conda-forge
liblapack                 3.8.0                    14_mkl    conda-forge
liblapacke                3.8.0                    14_mkl    conda-forge
libmklml                  2019.0.5                      0
libopencv                 4.1.2                    py37_2    conda-forge
libpng                    1.6.37               h7602738_0    conda-forge
libprotobuf               3.11.2               h1a1b453_0    conda-forge
libtiff                   4.1.0                h21b02b4_1    conda-forge
libwebp                   1.0.2                hfa6e2cd_4    conda-forge
lz4-c                     1.8.3             he025d50_1001    conda-forge
m2w64-gcc-libgfortran     5.3.0                         6
m2w64-gcc-libs            5.3.0                         7
m2w64-gcc-libs-core       5.3.0                         7
m2w64-gmp                 6.1.0                         2
m2w64-libwinpthread-git   5.0.0.4634.697f757            2
markdown                  3.1.1                      py_0    conda-forge
matplotlib                3.1.2                    py37_1    conda-forge
matplotlib-base           3.1.2            py37h2981e6d_1    conda-forge
mkl                       2019.4                      245
mkl-service               2.3.0            py37hfa6e2cd_0    conda-forge
msys2-conda-epoch         20160418                      1
numpy                     1.17.3           py37hc71023c_0    conda-forge
olefile                   0.46                     py37_0    anaconda
opencv                    4.1.2                    py37_2    conda-forge
openssl                   1.1.1d               hfa6e2cd_0    conda-forge
opt_einsum                3.1.0                      py_0    conda-forge
pillow                    6.2.1            py37hdc69c19_0    anaconda
pip                       19.3.1                   py37_0
protobuf                  3.11.2           py37he025d50_0    conda-forge
py-opencv                 4.1.2            py37h5ca1d4c_2    conda-forge
pyparsing                 2.4.6                      py_0    conda-forge
pyqt                      5.12.3           py37h6538335_1    conda-forge
pyqt5-sip                 4.19.18                  pypi_0    pypi
pyqtwebengine             5.12.1                   pypi_0    pypi
pyreadline                2.1                   py37_1001    conda-forge
python                    3.7.5                h8c8aaf0_0
python-dateutil           2.8.1                      py_0    conda-forge
qt                        5.12.5               h7ef1ec2_0    conda-forge
scipy                     1.3.1            py37h29ff71c_0    conda-forge
setuptools                42.0.2                   py37_0
six                       1.13.0                   py37_0    conda-forge
sqlite                    3.30.1               he774522_0
tensorboard               1.15.0                   py37_0    conda-forge
tensorflow                1.15.0       mkl_py37h3789bd0_0
tensorflow-base           1.15.0       mkl_py37h190a33d_0
tensorflow-estimator      1.15.1             pyh2649769_0
termcolor                 1.1.0                      py_2    conda-forge
tk                        8.6.8                hfa6e2cd_0    anaconda
tornado                   6.0.3            py37hfa6e2cd_0    conda-forge
tqdm                      4.41.1                     py_0    conda-forge
vc                        14.1                 h0510ff6_4
vs2015_runtime            14.16.27012          hf0eaf9b_1
werkzeug                  0.16.0                     py_0    conda-forge
wheel                     0.33.6                   py37_0
wincertstore              0.2                      py37_0
wrapt                     1.11.2           py37hfa6e2cd_0    conda-forge
xz                        5.2.4             h2fa13f4_1001    conda-forge
zlib                      1.2.11            h2fa13f4_1006    conda-forge
zstd                      1.4.4                hd8a0e53_1    conda-forge
