start:
	g++ *.cpp -lmysqlclient -Wno-write-strings -fPIC -shared -o ../openspy/modules/peerchat.so  -I.. ../common/*.cpp ../common/*.c
debug:
	g++ *.cpp -lmysqlclient -Wno-write-strings -fPIC -ggdb -Wstack-protector -fstack-protector-all -shared -o ../openspy/modules/peerchat.so -I.. ../common/*.cpp ../common/*.c
