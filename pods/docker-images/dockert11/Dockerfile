FROM    centos:7
RUN     useradd -u 2000 surendra
WORKDIR /home/surendra
USER    2000
COPY    run.sh .
CMD     ["sh", "run.sh"]