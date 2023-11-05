FROM ubuntu:18.04
# CMD [ "sleep", "3", "", "" ]
# CMD [ "EXECUTABLE", "ARGUMENT", "ARGUMENT", "ARGUMENT" ]
# CMD sleep 3
# docker run ubuntu-sleeper sleep 1 // cmd kodu override edilir - ubuntu:18.04 son satir => CMD [ "/bin/bash" ]
ENTRYPOINT [ "sleep" ]
# docker run ubuntu-sleeper 1 // sadece arguman verilir
# docker run ubuntu-sleeper // parametre verilmezse => sleep: missing operand (error)
CMD [ "3" ] 
# default value verilir ve artik 'docker run ubuntu-sleeper' parametresiz olarak calisabilir