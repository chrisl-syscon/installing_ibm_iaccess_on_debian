# Installing the IBM iAccess package on Linux Debian (11)
Instructions for how to install the IBM iAccess package on a Linux Debian system

Install the IBM IAccess ODBC packages repository and package per https://ibmi-oss-docs.readthedocs.io/en/latest/odbc/installation.html
curl https://public.dhe.ibm.com/software/ibmi/products/odbc/debs/dists/1.1.0/ibmi-acs-1.1.0.list | sudo tee /etc/apt/sources.list.d/ibmi-acs-1.1.0.list
apt update
apt install ibm-iaccess

Get the latest iAccess client solutions Linux App Package from:
https://www.ibm.com/resources/mrs/assets/DownloadList?source=swg-ia&lang=en_US
You will need an IBM account

On the linux machine unzip:
unzip ./IBMiAccess_v1r1_LinuxAP.zip

cd x86_64
dpkg -i ibm-iaccess-1.1.0.28-1.0.amd64.deb


see also: https://kadler.io/blog/2022-05-20-odbc-repos/

Documentation for package:
https://www.ibm.com/docs/en/ssw_ibm_i_72/rzatv/rzatvpdf.pdf
https://iwm.dhe.ibm.com/sdfdl/v2/regs2/sharee2/iacs-java/v1r1/Xa.2/Xb.Fjx4e5cjaz3A9ZmH2xINCxcOX5DKJh2Nl6e235yn7n0/Xc.iacs-java/v1r1/GettingStarted_en.html/Xd./Xf.lPr.D1vk/Xg.12934808/Xi.swg-ia/XY.regsrvs/XZ.VyUAr6jWydbADYONFjKjp67K1Cx248d1/XX.text/html/GettingStarted_en.html
http://www.web400.com/downloads/ACS/RunIBMiAccessClientDataXfers.pdf
