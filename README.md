

# reproducibility-tutorial    
    1  cd scratch
    2  git clone https://github.com/KarenMcGinnis/profile.git
    3  wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
    4  bash Miniconda3-latest-Linux-x86_64.sh -b -p /opt/conda
    5  ln -s /opt/conda/pkgs/*/bin/* /bin
    6  ln -s /opt/conda/pkgs/*/lib/* /usr/lib
    7  /opt/conda/bin/conda install -c conda-forge -y jupyterlab=1.2.3
    8  /opt/conda/bin/conda install -c conda-forge -y nodejs=10.13.0
    9  /opt/conda/bin/pip install bash_kernel
   10  /opt/conda/bin/pip install ipykernel
   11  /opt/conda/bin/python3 -m bash_kernel.install
   12  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'
   13  /opt/conda/bin/conda search -c bioconda snakemake
   14  /opt/conda/bin/conda install -c bioconda -c conda-forge -y snakemake=5.8.1
   15  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'profile
   16  #/opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'/opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'
   17  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'
   18  df-h
   19  df -h
   20  ls
   21  mkdir reproducibility-tutorial
   22  ls
   23  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'
   24  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'
   25  ls reproducibility-tutorial
   26  /opt/conda/bin/conda search -c bioconda snakemake
   27  /opt/conda/bin/conda install -c bioconda -c conda-forge -y snakemake=5.8.1
   28  ln -s /opt/conda/bin/* /bin
   29  ln -s /opt/conda/lib/* /usr/lib
   30  snakemake --version
   31  sudo apt-get update
   32  sudo apt-get install -y 
   33  apt-transport-https \
   34  ca-certificates \
   35  ca-certificates \
   36  sudo apt-get install -y 
   37  apt-transport-https \
   38  ca-certificates \
   39  curl \
   40  gnupg-agent \
   41  software-properties-common
   42  curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
   43  sudo apt-get install -y 
   44  apt-transport-https \
   45  ca-certificates \
   46  curl \
   47  gnupg-agent \
   48  software-properties-common
   49   sudo apt-get update
   50  sudo apt-get install -y 
   51  apt-transport-https \
   52  ca-certificates \
   53  curl \
   54  gnupg-agent \
   55  software-properties-common
   56  sudo apt-get install -y apt-transport-https 
   57  sudo apt -get install -y\ca-certificates
   58  sudo apt-get install -y ca-certificates
   59  sudo apt -get install -y curl
   60  sudo apt -get install -y curl
   61  sudo apt-get install -y curl
   62  sudo apt-get install -y gnupg-agent
   63  sudo apt-get install -y software-properties-common
   64  cp reproducibility-tutorial/untitled.ipynb
   65  curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
   66  sudo add-apt-repository 
   67   "deb [arch=amd64] https://download.docker.com/linux/ubuntu \
   68   $(lsb_release -cs) \
   69   stable"
   70  history
   71  history >>README.markdown
   72  nano readme.markdown
   73  git clone https://karenmcginnis.github.io/profile/
   74  git status
   75  git clone https://github.com/KarenMcGinnis/reproducibility-tutorial.git
   76  wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
   77  bash Miniconda3-latest-Linux-x86_64.sh -b -p /opt/conda
   78  ln -s /opt/conda/pkgs/*/bin/* /bin
   79  ln -s /opt/conda/pkgs/*/lib/* /usr/lib
   80  /opt/conda/bin/conda install -c conda-forge -y jupyterlab=1.2.3
   81  /opt/conda/bin/conda install -c conda-forge -y nodejs=10.13.0
   82  /opt/conda/bin/pip install bash_kernel
   83  /opt/conda/bin/pip install ipykernel
   84  /opt/conda/bin/python3 -m bash_kernel.install
   85  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'
   86  /opt/conda/bin/conda install -c bioconda -c conda-forge -y snakemake=5.8.1
   87  ln -s /opt/conda/bin/* /bin
   88  ln -s /opt/conda/lib/* /usr/lib
   89  snakemake --version
   90  sudo apt-get update
   91  sudo apt-get install –y apt-transport-https 
   92  sudo apt-get install –y ca-certificates 
   93  sudo apt-get install –y curl 
   94  sudo apt-get install –y gnupg-agent
   95  sudo apt-get install –y software-properties-common
   96  curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
   97  sudo add-apt-repository 
   98   "deb [arch=amd64] https://download.docker.com/linux/ubuntu \
   99   $(lsb_release -cs) \
  100   stable"
  101  git clone https://github.com/KarenMcGinnis/reproducibility-tutorial.git
  102  iinit
  103  chown -R YOURCYVERSEUSERNAME /scratch/reproducibility-tutorial/
  104  chown -R YOURCYVERSEUSERNAME /scratch/reproducibility-tutorial/chown -R YOURCYVERSEUSERNAME /scratch/reproducibility-tutorial/
  105  chown -R karenmcginnis /scratch/reproducibility-tutorial/
  106  ls
  107  scp ~/Downloads/SraRunTable.txt karenmcginnis@ 128.196.142.4:/scratch/reproducibility-tutorial/
  108  scp ~/Downloads/SraRunTable.txt karenmcginnis@ 128.196.142.4:/scratch/reproducibility-tutorial/
  109  scp ~/Downloads/SraRunTable.txt karenmcginnis@128.196.142.4:/scratch/reproducibility-tutorial/
  110  scp ~/Downloads/SraRunTable.txt karenmcginnis@128.196.142.4:/scratch/reproducibility-tutorial/
  111  scp D:\Users\mcginnis\SraRunTable.txt karenmcginnis@128.196.142.4:/scratch/reproducibility-tutorial/
  112  head D:\Users\mcginnis\
  113  scp D:\Users\mcginnis\downloads\SraRunTable.txt karenmcginnis@128.196.142.4:/scratch/reproducibility-tutorial/
  114  scp \Users\mcginnis\downloads\SraRunTable.txt karenmcginnis@128.196.142.4:/scratch/reproducibility-tutorial/
  115  head D:
  116  nano SRAroundtable.txt
  117  scp \Users\mcginnis\downloads\SraRunTable.txt karenmcginnis@128.196.142.4:/scratch/reproducibility-tutorial/
  118  cd scratch
  119  ls
  120  cd reproducibility-tutorial/
  121  nano SRAroundtable.txt
  122  cut -f1 SRAroundtable.txt -d ,
  123  git clone https://github.com/KarenMcGinnis/reproducibility-tutorial.git
  124  /opt/conda/bin/conda search -c bioconda snakemake
  125  /opt/conda/bin/conda install -c bioconda -c conda-forge -y snakemake=5.8.1
  126  ln -s /opt/conda/* /bin
  127  ln-s /opt/conda/bin/* /bin
  128  ln -s /opt/conda/bin/* /bin
  129  ln -s /opt/conda/lib/* /usr/lib
  130  snakemake --version
  131  sudo apt-get update
  132  sudo ap-get install -y apt-transport-https ca-certificates curl gnupg-agent software-properties-common
  133  sudo apt-get install -y apt-transport-https ca-certificates curl gnupg-agent software-properties-common
  134  curl -fsSL https://download.docker.com/linux/ubuntu 
  135  curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
  136  sudo add-apt-repository  "deb [arch=amd64] https://download.docker.com/linux/ubuntu \

 $(lsb_release -cs) \

 stable"
  137  sudo apt-get update
  138  sudo apt-get install -y docker-ce docker-ce-cli containerd.io
  139  docker run hello-world
  140  cd /scratch/reproducibility-tutorial/
  141  git clone https://github.com/KarenMcGinnis/reproducibility-tutorial.git
  142  history >>README.md
  143  nano README.md
  144  nano README.md
  145  git status
  146  git add experiment/
  147  conda search jupyter lab
  148  /opt/conda/bin/conda install -c conda-forge -y jupyterlab=1.2.3
  149  /opt/conda/bin/conda install -c conda-forge -y nodejs=10.13.0
  150  /opt/conda/bin/pip install bash_kernel
  151  /opt/conda/bin/pip install ipykernel
  152  /opt/conda/bin/python3 -m bash_kernel.install
  153  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'
  154  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token= --NotebookApp.password= --notebook-dir=/scratch/reproducibility-tutorial/
  155  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=128.196.142.18 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'
  156  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=128.196.142.18--NotebookApp.token= --NotebookApp.password= --notebook-dir=/scratch/reproducibility-tutorial/
  157  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=128.196.142.18--NotebookApp.token= --NotebookApp.Ih8pwords!= --notebook-dir=/scratch/reproducibility-tutorial/
  158  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=128.196.142.18NotebookApp.token='' --NotebookApp.Ih8pwords!='' --notebook-dir='/scratch/reproducibility-tutorial/'
  159  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=128.196.142.18  --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'
  160  cd /scratch/reproducibility-tutorial/
  161  cd scratch
  162  cd reproducibility-tutorial
  163  ls
  164  git push
  165  git push
  166  git push
  167  git push
  168  history >>README.md
    1  cd scratch
    2  git clone https://github.com/KarenMcGinnis/profile.git
    3  wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
    4  bash Miniconda3-latest-Linux-x86_64.sh -b -p /opt/conda
    5  ln -s /opt/conda/pkgs/*/bin/* /bin
    6  ln -s /opt/conda/pkgs/*/lib/* /usr/lib
    7  /opt/conda/bin/conda install -c conda-forge -y jupyterlab=1.2.3
    8  /opt/conda/bin/conda install -c conda-forge -y nodejs=10.13.0
    9  /opt/conda/bin/pip install bash_kernel
   10  /opt/conda/bin/pip install ipykernel
   11  /opt/conda/bin/python3 -m bash_kernel.install
   12  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'
   13  /opt/conda/bin/conda search -c bioconda snakemake
   14  /opt/conda/bin/conda install -c bioconda -c conda-forge -y snakemake=5.8.1
   15  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'profile
   16  #/opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'/opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'
   17  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'
   18  df-h
   19  df -h
   20  ls
   21  mkdir reproducibility-tutorial
   22  ls
   23  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'
   24  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'
   25  ls reproducibility-tutorial
   26  /opt/conda/bin/conda search -c bioconda snakemake
   27  /opt/conda/bin/conda install -c bioconda -c conda-forge -y snakemake=5.8.1
   28  ln -s /opt/conda/bin/* /bin
   29  ln -s /opt/conda/lib/* /usr/lib
   30  snakemake --version
   31  sudo apt-get update
   32  sudo apt-get install -y 
   33  apt-transport-https \
   34  ca-certificates \
   35  ca-certificates \
   36  sudo apt-get install -y 
   37  apt-transport-https \
   38  ca-certificates \
   39  curl \
   40  gnupg-agent \
   41  software-properties-common
   42  curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
   43  sudo apt-get install -y 
   44  apt-transport-https \
   45  ca-certificates \
   46  curl \
   47  gnupg-agent \
   48  software-properties-common
   49   sudo apt-get update
   50  sudo apt-get install -y 
   51  apt-transport-https \
   52  ca-certificates \
   53  curl \
   54  gnupg-agent \
   55  software-properties-common
   56  sudo apt-get install -y apt-transport-https 
   57  sudo apt -get install -y\ca-certificates
   58  sudo apt-get install -y ca-certificates
   59  sudo apt -get install -y curl
   60  sudo apt -get install -y curl
   61  sudo apt-get install -y curl
   62  sudo apt-get install -y gnupg-agent
   63  sudo apt-get install -y software-properties-common
   64  cp reproducibility-tutorial/untitled.ipynb
   65  curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
   66  sudo add-apt-repository 
   67   "deb [arch=amd64] https://download.docker.com/linux/ubuntu \
   68   $(lsb_release -cs) \
   69   stable"
   70  history
   71  history >>README.markdown
   72  nano readme.markdown
   73  git clone https://karenmcginnis.github.io/profile/
   74  git status
   75  git clone https://github.com/KarenMcGinnis/reproducibility-tutorial.git
   76  wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
   77  bash Miniconda3-latest-Linux-x86_64.sh -b -p /opt/conda
   78  ln -s /opt/conda/pkgs/*/bin/* /bin
   79  ln -s /opt/conda/pkgs/*/lib/* /usr/lib
   80  /opt/conda/bin/conda install -c conda-forge -y jupyterlab=1.2.3
   81  /opt/conda/bin/conda install -c conda-forge -y nodejs=10.13.0
   82  /opt/conda/bin/pip install bash_kernel
   83  /opt/conda/bin/pip install ipykernel
   84  /opt/conda/bin/python3 -m bash_kernel.install
   85  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'
   86  /opt/conda/bin/conda install -c bioconda -c conda-forge -y snakemake=5.8.1
   87  ln -s /opt/conda/bin/* /bin
   88  ln -s /opt/conda/lib/* /usr/lib
   89  snakemake --version
   90  sudo apt-get update
   91  sudo apt-get install –y apt-transport-https 
   92  sudo apt-get install –y ca-certificates 
   93  sudo apt-get install –y curl 
   94  sudo apt-get install –y gnupg-agent
   95  sudo apt-get install –y software-properties-common
   96  curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
   97  sudo add-apt-repository 
   98   "deb [arch=amd64] https://download.docker.com/linux/ubuntu \
   99   $(lsb_release -cs) \
  100   stable"
  101  git clone https://github.com/KarenMcGinnis/reproducibility-tutorial.git
  102  iinit
  103  chown -R YOURCYVERSEUSERNAME /scratch/reproducibility-tutorial/
  104  chown -R YOURCYVERSEUSERNAME /scratch/reproducibility-tutorial/chown -R YOURCYVERSEUSERNAME /scratch/reproducibility-tutorial/
  105  chown -R karenmcginnis /scratch/reproducibility-tutorial/
  106  ls
  107  scp ~/Downloads/SraRunTable.txt karenmcginnis@ 128.196.142.4:/scratch/reproducibility-tutorial/
  108  scp ~/Downloads/SraRunTable.txt karenmcginnis@ 128.196.142.4:/scratch/reproducibility-tutorial/
  109  scp ~/Downloads/SraRunTable.txt karenmcginnis@128.196.142.4:/scratch/reproducibility-tutorial/
  110  scp ~/Downloads/SraRunTable.txt karenmcginnis@128.196.142.4:/scratch/reproducibility-tutorial/
  111  scp D:\Users\mcginnis\SraRunTable.txt karenmcginnis@128.196.142.4:/scratch/reproducibility-tutorial/
  112  head D:\Users\mcginnis\
  113  scp D:\Users\mcginnis\downloads\SraRunTable.txt karenmcginnis@128.196.142.4:/scratch/reproducibility-tutorial/
  114  scp \Users\mcginnis\downloads\SraRunTable.txt karenmcginnis@128.196.142.4:/scratch/reproducibility-tutorial/
  115  head D:
  116  nano SRAroundtable.txt
  117  scp \Users\mcginnis\downloads\SraRunTable.txt karenmcginnis@128.196.142.4:/scratch/reproducibility-tutorial/
  118  cd scratch
  119  ls
  120  cd reproducibility-tutorial/
  121  nano SRAroundtable.txt
  122  cut -f1 SRAroundtable.txt -d ,
  123  git clone https://github.com/KarenMcGinnis/reproducibility-tutorial.git
  124  /opt/conda/bin/conda search -c bioconda snakemake
  125  /opt/conda/bin/conda install -c bioconda -c conda-forge -y snakemake=5.8.1
  126  ln -s /opt/conda/* /bin
  127  ln-s /opt/conda/bin/* /bin
  128  ln -s /opt/conda/bin/* /bin
  129  ln -s /opt/conda/lib/* /usr/lib
  130  snakemake --version
  131  sudo apt-get update
  132  sudo ap-get install -y apt-transport-https ca-certificates curl gnupg-agent software-properties-common
  133  sudo apt-get install -y apt-transport-https ca-certificates curl gnupg-agent software-properties-common
  134  curl -fsSL https://download.docker.com/linux/ubuntu 
  135  curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
  136  sudo add-apt-repository  "deb [arch=amd64] https://download.docker.com/linux/ubuntu \

 $(lsb_release -cs) \

 stable"
  137  sudo apt-get update
  138  sudo apt-get install -y docker-ce docker-ce-cli containerd.io
  139  docker run hello-world
  140  cd /scratch/reproducibility-tutorial/
  141  git clone https://github.com/KarenMcGinnis/reproducibility-tutorial.git
  142  history >>README.md
  143  nano README.md
  144  nano README.md
  145  git status
  146  git add experiment/
  147  conda search jupyter lab
  148  /opt/conda/bin/conda install -c conda-forge -y jupyterlab=1.2.3
  149  /opt/conda/bin/conda install -c conda-forge -y nodejs=10.13.0
  150  /opt/conda/bin/pip install bash_kernel
  151  /opt/conda/bin/pip install ipykernel
  152  /opt/conda/bin/python3 -m bash_kernel.install
  153  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'
  154  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token= --NotebookApp.password= --notebook-dir=/scratch/reproducibility-tutorial/
  155  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=128.196.142.18 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'
  156  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=128.196.142.18--NotebookApp.token= --NotebookApp.password= --notebook-dir=/scratch/reproducibility-tutorial/
  157  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=128.196.142.18--NotebookApp.token= --NotebookApp.Ih8pwords!= --notebook-dir=/scratch/reproducibility-tutorial/
  158  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=128.196.142.18NotebookApp.token='' --NotebookApp.Ih8pwords!='' --notebook-dir='/scratch/reproducibility-tutorial/'
  159  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=128.196.142.18  --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'
  160  cd /scratch/reproducibility-tutorial/
  161  cd scratch
  162  cd reproducibility-tutorial
  163  ls
  164  git push
  165  git push
  166  git push
  167  git push
  168  history >>README.md
  169  git push
  170  nano README.md
  171  git push
  172  git push
  173  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'
  174  cd /scratch/reproducibility-tutorial/
  175  ls
  176  history >>README.md
