------------------------------------------------------------------------------------------------------------------

#@title **INSTALL >> SAGE + ECDSA + BITCOIN + algorithm LLL**

!apt-get update
!sudo apt update
!pip3 install utils
!pip3 install ecdsa
!pip3 install bitcoin
!pip3 install base58
!pip2 install utils
!pip2 install ecdsa
!pip2 install bitcoin
!pip2 install base58
!sudo apt install python-gmpy2
!yes '' | sudo env DEBIAN_FRONTEND=noninteractive apt-get -y -o DPkg::options::="--force-confdef" -o DPkg::options::="--force-confold" install sagemath


------------------------------------------------------------------------------------------------------------------


#@title **Checking the installation SAGE**


!sage -v


------------------------------------------------------------------------------------------------------------------


#@title **Running a script**


!chmod +x lattice.sh
!sed -i -e 's/\r$//' lattice.sh

!./lattice.sh 08d917f0fee48b0d765006fa52d62dd3d704563200f2817046973e3bf6d11f1f 15N1KY5ohztgCXtEe13BbGRk85x2FPgW8E



------------------------------------------------------------------------------------------------------------------


#@title **Clear Data Base**

!rm *.txt
!rm *.csv
!rm *.json



------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------